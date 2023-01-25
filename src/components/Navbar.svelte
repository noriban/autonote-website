<script>
    import logo from '../assets/logo.png'
</script>
<style>
    nav {
        border: inset;
        margin: auto;
        position: relative;
    /* border: 1px solid red; */
    /* margin-bottom: 0.3em;
    margin-top: 0.3em; */
    height: 20%;
    width: 60em;
    border-radius: 5em;
    place-self: center;
    place-content: center;
    align-items: center;
    text-align: center;
}
nav img {
    margin: 0;
    width: 3em;
    height: auto;
    border-radius: 1.4em;
}
nav ul {
    /* border: 1px solid green; */
    /* padding: 1em; */
    margin: 0.5em auto;
    padding: 0;
    align-items: center;
    place-content: center;
    display: flex;
    justify-content: space-evenly;
    border-radius: 15px;
}
nav ul a{
    /* border: 1px solid red; */
    width: 8em;
    height: 2em;
    margin: auto;
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
    /* position: relative; */
    /* display: inline-block; */
    position: relative;
    width: 4%;
    margin: auto 0.1em;
    text-align: left;
}
nav ul a:first-child:hover{
    color: inherit;
    background-color: inherit;
}
nav ul a:last-child{
    width: auto;
    position: relative;
    margin: auto 0.5em;
    justify-content: space-evenly;
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
    transition: 0.15s;
    border-radius: 15px;
}
</style>
<nav>
    <ul>
        <a href="/">
            <li>
                <img src="{logo}" alt="logo.png">
            </li>
        </a>
        <a href="/">
            <li>Home</li>
        </a><a href="#features">
            <li>Features</li>
        </a><a href="#faq">
            <li>FAQ</li>
        </a>
        <a href="/">
            <li>test</li>
        </a>
        <a href="https://github.com/noriban/AutoNote">
            <li>Source</li>
        </a>
        <a href="https://github.com/noriban/AutoNote/releases/latest">
            <li>Try now</li>
        </a>
    </ul>
</nav>