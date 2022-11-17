<nav>
    <h1>AS</h1>
    <ul>
        <li><a href="/">01 Home</a></li>
        <li><a href="/about">02 About</a></li>
        <li><a href="/project">03 Projects</a></li>
        <li><a href="/contact">04 Contact Me</a></li>
    </ul>
</nav>

<style>
    nav{
        width: 100vw;
        height: 80px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 3rem;
        padding: 0 9rem;
    }
    ul{
        list-style: none;
        display: flex;
        align-items: center;
        width: 40vw;
        justify-content: space-between;
    }
    ul li a{
        text-decoration: none;
        color: white;
        font-family: 'Montserrat';
        font-weight: var(--fw-400);
        font-size: 1.25rem;
    }
    nav h1{
        font-family: 'Plaster';
        font-size: 3rem;
        color: white;
    }
    @media screen and (max-width: 414px){
        nav{
            padding: 0 2.5rem;
        }
        nav ul{
            display: none;
        }
        
    }
</style>
