<script>
    import logo from '../assets/logo.png'
    import css from '../app.css'
</script>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Adlam+Unjoined:wght@400;500;600&display=swap');
body {
    font-family: 'Noto Sans Adlam Unjoined', sans-serif;
    padding: 0;
    margin: 0;
    /* background-color: gray; */
}
/* navbar */
nav {
    /* border: 1px solid red; */
    margin-bottom: 0.3em;
    margin-top: 0.3em;
    border: inset;
    height: 20%;
    width: 70%;
    border-radius: 5em;
    left: 15%;
    position: relative;
    place-content: center;
    align-items: center;
}
nav img {
    width: 2.7em;
    height: 2.7em;
    border-radius: 1.5em;
}
nav ul {
    /* border: 1px solid green; */
    /* padding: 1em; */
    margin: 0.5em;
    align-items: center;
    place-content: center;
    display: flex;
    justify-content: space-evenly;
    border-radius: 15px;
}
/* nav ul a {
    border: 1px solid purple;
    place-content: center;
    align-items: center;
} */
nav ul a{
    /* border: 1px solid red; */
    width: 8em;
    height: 2em;
    margin: 0;
    display: flex;
    text-align: center;
    align-items: center;
    place-content: center;
    border-radius: 10px;
    
    /* display: inline-block; */
    /* height: inherit;
    width: inherit; */
    list-style: none;
}

nav ul a:first-child{
    position: relative;
    right: 10%;
    /* justify-content: start; */
    width: auto;
}
nav ul a:first-child:hover{
    color: inherit;
    background-color: inherit;
}
nav ul a:last-child{
    width: 10%;
    position: relative;
    left: 5%;
    /* justify-content: start; */
} 
nav ul a:visited, nav ul a:link {
    text-decoration: none;
    color: inherit;
}
nav ul a:active {
    border-radius: 10px;
}
nav ul a:hover {
    color: white;
    background-color: black;
    /* animation-duration: 0.15s; */
    transition: 0.15s;
    border-radius: 15px;
}

</style>
<body>
    <nav>
        <ul>
            <a href="/">
                <li>
                    <img src="{logo}" alt="logo.png">
                </li>
            </a>
            <a href="/">
                <li>Home</li>
            </a><a href="/features">
                <li>Features</li>
            </a><a href="/faq">
                <li>FAQ</li>
            </a><a href="https://github.com/noriban/AutoNote">
                <li>Source</li>
            </a>
            <a href="https://github.com/noriban/AutoNote/releases/latest">
                <li>Try now</li>
            </a>
        </ul>
    </nav>
    <section>
        Hi, im james
    </section>
    <section>
        Hi, im james
    </section>
    <section>
        Hi, im james
    </section>
    <section>
        Hi, im james
    </section>
</body>
