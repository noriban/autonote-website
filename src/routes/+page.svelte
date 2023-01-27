<script>
    import Navbar from '../components/Navbar.svelte'
    import Features from '../components/Features.svelte'
    import Faq from '../components/Faq.svelte'
    import Info from '../components/Info.svelte'
    import FooterComp from '../components/Footer.svelte'
    import '../app.css'
    // import 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css'
</script>

<Navbar />

<main>
    <section>
        <Info />
    </section>
    <section>
        <Features />
    </section>
    <section>
        <Faq />
    </section>
    <section>
        Hi, im james
    </section>
</main>


<FooterComp />