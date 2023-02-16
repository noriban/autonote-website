<script>
    import Navbar from '../components/Navbar.svelte'
    import Info from '../components/Info.svelte'
    import FooterComp from '../components/Footer.svelte'
    import Features from '../components/Features.svelte'
    import FAQ from '../components/Faq.svelte'

</script>

<Navbar/>

<main>
    <section class="min-h-screen">
        <Info />
    </section>
    <section>
        <Features />
    </section>
    <section>
        <!-- <Faq/> -->
    </section>
</main>
<FooterComp />