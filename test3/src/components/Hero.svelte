<script>
    import SectionWrapper from "./SectionWrapper.svelte";
    import Header from "./Header.svelte"; 
    

</script>


<!-- now we are going to render everything inside this section wrapper -->

<!-- must import everything first before trying to render -->

<SectionWrapper>
    <Header />




    <!-- this is the main page text -->

    <!-- using a lot of spans-->

    <!-- flex flex-col -->

    <div class="flex flex-col gap-10 flex-1 items-center justify-cetner pb-10 md:pd-14">
        <h2 class="text-5xl sm:text-6xl md:text-7xl lg:text-7xl max-w-[1200px] mx-auto w-full text-center font-semibold">
            <span class="text-indigo-400">
                Design
            </span> Problems <span class="text-slate-600 line-through"> Are Hard</span>
            Just Got <span class="text-indigo-400"> Easier</span>
        </h2>


        <p class="text-xl sm:text-2xl md:text-3xl text-center max-w-[1000px] mx-auto w-full">
            Less thinking & more doing. I'm the designer that can find you the perfect brand identity full of 
            <span class="italic"> history rich, data driven, human oriented designs </span> and much much more.
        </p>





    </div>

</SectionWrapper>
<!-- above is calling the section wrapper to consistently wrap our different sections so they are all styled the same -->
<!-- just do <SectionWrapper> and press enter to import everything -->
    <!-- + just set up the rest in page.svelte and call hero component -->
    <!-- now you are able to type anything inbetween SectionWrapper to display on page.svelte -->