<script>
    import { fade } from "svelte/transition";
    import Carousel from "svelte-carousel";
</script>

<section class="w-full py-5 md:py-20">
    <div in:fade={{ duration: 500 }} class="container mx-auto">
        <h1 class="title text-center">My Dev's works</h1>

        <article class="w-full py-10">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-3">
                <div class=" p-10">
                    <h3 class="text-2xl primary-text">Neon Led Store</h3>
                    <p class="mt-4 text-lg secondary-text">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Aliquam, natus! Iusto provident fuga est odio veniam
                        nisi. Suscipit quisquam ipsum odit nesciunt? Fugit,
                        error ullam eius nobis exercitationem officia ut. Fugit
                        aliquam facere eum dicta, laboriosam aut nostrum
                        molestiae cumque perspiciatis voluptatem consequuntur
                        dolore mollitia ad accusamus saepe, quaerat vitae iure
                        reiciendis debitis optio est voluptas! Facere iure atque
                        tempora?
                    </p>
                </div>
                <div class="p-10 flex flex-col gap-3 ">
                    <div class="">
                        <Carousel autoplay autoplayDuration={2000}>
                            <img
                                src="./src/img/works/nls/1.png"
                                class="w-full rounded-lg"
                                alt=""
                            />
                            <img
                                src="./src/img/works/nls/2.png"
                                class="w-full rounded-lg"
                                alt=""
                            />
                            <img
                                src="./src/img/works/nls/3.png"
                                class="w-full rounded-lg"
                                alt=""
                            />
                        </Carousel>
                        <!--</1-><img src="./src/img/works/work1.png" class="w-full rounded-lg" alt="">-->
                    </div>
                    <div class="flex gap-4 justify-center">
                        <a href="#" class="btns flex gap-3 items-center">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                class="h-6 w-6"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                                />
                            </svg>
                            VIEW WEB
                        </a>
                        <a href="#" class="btns flex gap-3 items-center">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                class="h-6 w-6"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
                                />
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"
                                />
                            </svg>
                            VIEW REPOSITORY
                        </a>
                    </div>
                </div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-3">
                <div class=" p-10">
                    <h3 class="text-2xl primary-text">Digimedia</h3>
                    <p class="mt-4 text-lg secondary-text">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Aliquam, natus! Iusto provident fuga est odio veniam
                        nisi. Suscipit quisquam ipsum odit nesciunt? Fugit,
                        error ullam eius nobis exercitationem officia ut. Fugit
                        aliquam facere eum dicta, laboriosam aut nostrum
                        molestiae cumque perspiciatis voluptatem consequuntur
                        dolore mollitia ad accusamus saepe, quaerat vitae iure
                        reiciendis debitis optio est voluptas! Facere iure atque
                        tempora?
                    </p>
                </div>
                <div class="p-10 flex flex-col gap-3 ">
                    <div class="">
                        <Carousel autoplay autoplayDuration={2000}>
                            <img
                                src="./src/img/works/digimedia/1.png"
                                class="w-full rounded-lg"
                                alt=""
                            />
                            <img
                                src="./src/img/works/digimedia/2.png"
                                class="w-full rounded-lg"
                                alt=""
                            />
                            <img
                                src="./src/img/works/digimedia/3.png"
                                class="w-full rounded-lg"
                                alt=""
                            />
                        </Carousel>
                        <!--</1-><img src="./src/img/works/work1.png" class="w-full rounded-lg" alt="">-->
                    </div>
                    <div class="flex gap-4 justify-center">
                        <a href="#" class="btns flex gap-3 items-center">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                class="h-6 w-6"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                                />
                            </svg>
                            VIEW WEB
                        </a>
                        <a href="#" class="btns flex gap-3 items-center">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                class="h-6 w-6"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
                                />
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"
                                />
                            </svg>
                            VIEW REPOSITORY
                        </a>
                    </div>
                </div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-3">
                <div class=" p-10">
                    <h3 class="text-2xl primary-text">Shopping web</h3>
                    <p class="mt-4 text-lg secondary-text">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Aliquam, natus! Iusto provident fuga est odio veniam
                        nisi. Suscipit quisquam ipsum odit nesciunt? Fugit,
                        error ullam eius nobis exercitationem officia ut. Fugit
                        aliquam facere eum dicta, laboriosam aut nostrum
                        molestiae cumque perspiciatis voluptatem consequuntur
                        dolore mollitia ad accusamus saepe, quaerat vitae iure
                        reiciendis debitis optio est voluptas! Facere iure atque
                        tempora?
                    </p>
                </div>
                <div class="p-10 flex flex-col gap-3 ">
                    <div class="">
                        <Carousel autoplay autoplayDuration={2000}>
                            <img
                                src="./src/img/works/vc/1.png"
                                class="w-full rounded-lg"
                                alt=""
                            />
                            <img
                                src="./src/img/works/vc/2.png"
                                class="w-full rounded-lg"
                                alt=""
                            />
                            <img
                                src="./src/img/works/vc/3.png"
                                class="w-full rounded-lg"
                                alt=""
                            />
                        </Carousel>
                        <!--</1-><img src="./src/img/works/work1.png" class="w-full rounded-lg" alt="">-->
                    </div>
                    <div class="flex gap-4 justify-center">
                        <a href="#" class="btns flex gap-3 items-center">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                class="h-6 w-6"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                                />
                            </svg>
                            VIEW WEB
                        </a>
                        <a href="#" class="btns flex gap-3 items-center">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                class="h-6 w-6"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
                                />
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"
                                />
                            </svg>
                            VIEW REPOSITORY
                        </a>
                    </div>
                </div>
            </div>
        </article>
    </div>
</section>
<style>
    img{
        max-height: 350px; 
    }
</style>