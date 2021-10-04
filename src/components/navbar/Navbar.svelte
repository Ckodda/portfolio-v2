<script>
    import { fly } from "svelte/transition";
    import { Link } from "svelte-routing";
    import IconMenu from "../icons/IconMenu.svelte";
    let showSideMenu = false;
    const toogleMenu = () => {
        showSideMenu = !showSideMenu;
    };
</script>

<header class="w-full text-white relative z-0">
    <div class="container mx-auto relative">
        <nav class="p-3 flex justify-between items-center secondary-text">
            <div>
                <div class="text-3xl ">Daniel</div>
            </div>

            <ul class="hidden md:flex gap-3 justify-center items-center">
                <li class="transform hover:border-white border-b-2 border-gray-900">
                    <Link to="/" class="m-0 p-3 block w-full h-full">About me</Link>
                </li>
                <li class="transform hover:border-white border-b-2 border-gray-900">
                    <Link to="/works" class="m-0 p-3 block w-full h-full">Works</Link>
                </li>
                <li class="transform hover:border-white border-b-2 border-gray-900">
                    <Link to="/contact" class="m-0 p-3 block w-full h-full">Contactme</Link>
                </li>
            </ul>
            
            
        </nav>
    </div>
    
</header>
<div class="absolute z-50 right-2 top-4 block md:hidden">
    <IconMenu {showSideMenu} {toogleMenu} />
</div>
{#if showSideMenu}
        <div
            transition:fly={{ x: 500, duration: 500 }}
            class="bg-black bg-opacity-25 backdrop-filter backdrop-blur-md fixed w-full h-screen top-0 flex items-center justify-center z-10"
        >
            <nav class="w-full secondary-text">
                <ul class="flex flex-col text-center gap-5 text-3xl">
                    <li>
                        <Link on:click="{toogleMenu}" to="/" class="m-0 block w-full h-full">About Me</Link>
                    </li>
                    <li>
                        <Link on:click="{toogleMenu}" to="/works"  class="m-0 block w-full h-full">Works</Link>
                    </li>
                    <li>
                        <Link on:click="{toogleMenu}" to="/contact"  class="m-0 block w-full h-full">Contactme</Link>
                    </li>
                </ul>
            </nav>
            
        </div>
{/if}
