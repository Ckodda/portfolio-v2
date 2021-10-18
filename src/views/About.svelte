<script>
    import { fly } from "svelte/transition";
    import {Link} from "svelte-routing";
</script>

<section class="relative py-5 md:py-20 w-full">
    <div
        in:fly={{ y: 200, duration: 1000 }}
        class="container flex justify-center items-center  mx-auto h-full"
    >
        <div class="p-2 flex flex-col md:flex-row justify-center gap-10  w-full">
            <h2 class="md:hidden  title text-center shadow-sm">About me</h2>
            <figure class="flex justify-center w-full md:w-1/4 ">
                <img id="photo"
                    class="w-36  md:w-full h-3/4 md:h-full lg:h-3/4 object-cover"
                    src="./src/img/dcb-perfil.png"
                    alt=""
                />
            </figure>
            <div class="w-full md:w-2/5 text-white">
                <h1 class="title hidden md:block">About me</h1>
                <p class="text-2xl sm:text-lg pt-2  mx-10 md:mx-0 md:pt-10 primary-text">
                    Welcome to my portfolio! <br />
                    I'm <span>Daniel Córdova</span>. <br />
                    And i'm 21 years old. <br />
                    I'm fullstack Developer, with experience of 3 years on software
                    develoment
                </p>
                <div class="mx-10 md:mx-0 pt-4">
                    <span class="font-bold text-xl">More</span>
                    <aside class="flex justify-center pt-2 flex-col sm:flex-row md:justify-start items-center gap-4">
                        <a href="#tecnologies" class="sm:btns btns w-full font-semibold">Tecnologies</a>
                        <Link to="/works" class="sm:btns btns w-full font-semibold">Works</Link>
                        <Link to="/contact" class="sm:btns btns w-full font-semibold">Contact</Link>
                    </aside>
                    <div class="w-full mt-4">
                        <a class="btns p-0 m-0 h-full flex gap-2 justify-center" href="#">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4" />
                              </svg>
                            Download CV
                        </a>
                    </div>
                </div>
            </div>
            
        </div>
    </div>
</section>
<section class="w-full py-5 md:py-20 relative z-0">

    <div class="container mx-auto  border-opacity-10 border-t-2">
        <h2 class="title flex gap-5 items-center pt-10 text-xs justify-center" id="tecnologies">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 5l7 7-7 7M5 5l7 7-7 7" />
              </svg>
            Tecnologies
        </h2>
        <article class="border-opacity-10  border-b-2 mt-10 p-5 rounded-lg grid grid-cols-2 lg:grid-cols-5 md:grid-cols-3 items-center justify-items-center gap-10">
            <img class="transition duration-200 ease-linear hover:scale-110 transform w-40" src="https://img.icons8.com/fluency/144/000000/github.png" alt=""/>
            <img  class="transition duration-200 ease-linear hover:scale-110 transform w-40" src="https://img.icons8.com/dusk/128/000000/php-logo.png" alt=""/>
            <img  class="transition duration-200 ease-linear hover:scale-110 transform w-40" src="https://img.icons8.com/color/128/000000/javascript--v1.png"  alt=""/>
            <img  class="transition duration-200 ease-linear hover:scale-110 transform w-40" src="https://img.icons8.com/color/144/000000/css3.png" alt=""/>
            <img  class="transition duration-200 ease-linear hover:scale-110 transform w-40" src="https://img.icons8.com/color/144/000000/mysql-logo.png" alt=""/>
            <img  class="transition duration-200 ease-linear hover:scale-110 transform w-40" src="https://img.icons8.com/doodle/96/000000/svetle.png" alt=""/>
            <img  class="transition duration-200 ease-linear hover:scale-110 transform w-40" src="https://img.icons8.com/color/96/000000/html-5--v1.png" alt=""/>
            <img class="transition duration-200 ease-linear hover:scale-110 transform w-40" src="https://img.icons8.com/color/96/000000/microsoft-sql-server.png" alt=""/>
            <img class="transition duration-200 ease-linear hover:scale-110 transform w-40" src="https://img.icons8.com/color/96/000000/wordpress.png" alt=""/>
        </article>
    </div>

</section>
<style>
    figure {
        transition: all 0.5s;
    }
    figure:hover {
        transform: translateY(-0.5em);
    }
    #photo{
        box-shadow: 0px 0px 15px 5px rgba(0, 0, 0, 0.2);
    }
    article img{
        transition: all 0.5s;
    }
    article img:hover{
        filter: drop-shadow(0em 0em  0.5em #ccc);
    }
</style>
