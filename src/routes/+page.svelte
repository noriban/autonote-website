<script>
    import Navbar from '../components/Navbar.svelte'
    import Info from '../components/Info.svelte'
    import FooterComp from '../components/Footer.svelte'
    import Features from '../components/Features.svelte'
    import FAQ from '../components/Faq.svelte'

</script>

<Navbar/>

<main>
    <section class="lg:min-h-screen">
        <Info />
    </section>
    <section class="lg:min-h-screen">
        <Features />
    </section>
    <section class="lg:min-h-screen">
        <!-- <Faq/> -->test
    </section>
</main>
<FooterComp />