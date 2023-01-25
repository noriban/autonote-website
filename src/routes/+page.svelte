<script>
    import logo from '../assets/logo.png'
</script>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Adlam+Unjoined:wght@400;500;600&display=swap');
body {
    font-family: 'Noto Sans Adlam Unjoined', sans-serif;
    padding: 0;
    margin: 0;
    /* background-color: gray; */
}
nav {
    /* border: 1px solid red; */
    margin-bottom: 0.3em;
    margin-top: 0.3em;
    border: 0.1em solid gray;
    height: 20%;
    width: 70%;
    border-radius: 5em;
    left: 15%;
    position: relative;
    place-content: center;
    align-items: center;
}
nav img {
    width: 2.5em;
    height: 2.5em;
    border-radius: 1.5em;
}
nav ul {
    border: 1px solid green;
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
    border: 1px solid red;
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
    width: auto;
    position: relative;
    place-items: left;
}
nav ul a:last-child{
    right: 0;
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
section {
    border: 1px dotted coral;
    display: grid;
    place-items: center;
    align-content: center;
    min-height: 100vh;
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
