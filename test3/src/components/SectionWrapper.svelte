<!-- These scripts will have the sectionwrapper receive some props -->
<script>
    // export let + name of prop

    // Number 1 action //////////////////////////////////////////////////////////////////////////////////////////
    // how to receive props
    // export let ___
    export let id;

</script>


<!-- section wrapper with certain styles -->
<!-- dynamic class in {} below-->

<!-- // Number 2 action //////////////// ADD {id} INSIDE <section             > /////////////////////////////////////////// -->
<section {id} class={'min-h-screen flex flex-col px-4'}>

    <!-- occupies as much space as it can (flex flex-col flex-1) -->
    <div class="flex flex-col flex-1 max-w-[1400px] mx-auto w-full">

        <!-- this is the child content that gets wrapped between the opening and closing section wrapping tags -->
        <slot/>
    </div>
</section>