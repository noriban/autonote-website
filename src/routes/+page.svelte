<script>
    import Navbar from '../components/Navbar.svelte'
    import Info from '../components/Info.svelte'
    import FooterComp from '../components/Footer.svelte'
    import Features from '../components/Features.svelte'
    import FAQ from '../components/Faq.svelte'

</script>

<Navbar/>

<main>
    <section>
        <Info />
    </section>
    <section class="sections">
        <Features />
    </section>
    <section class="sections">
         <FAQ />
    </section>
    <section class="sections">
        Tu będzie ekran downloadu
    </section>
</main>
<FooterComp />