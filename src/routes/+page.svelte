<script>
    import Navbar from '../components/Navbar.svelte'
    import Features from '../components/Features.svelte'
    import Faq from '../components/Faq.svelte'
    import Info from '../components/Info.svelte'
    import FooterComp from '../components/Footer.svelte'
    import '../app.css'
</script>

<Navbar />

<main>
    <section id="info">
        <Info />
    </section>
    <section id="features">
        <Features />
    </section>
    <section id="faq">
        <Faq />
    </section>
    <!-- <section>
        Hi, im james
    </section> -->
</main>


<FooterComp />