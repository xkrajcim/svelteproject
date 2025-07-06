
<header>
    <a class="main-logo" href="/"><svg width="150" height="150" viewBox="0 0 120 120" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M23.2996 59.5084H49.4329M67.6947 59.5084H49.4329M49.4329 59.5084V35.894H73.677M49.4329 65.4908V83.4377H76.1959" stroke="black" stroke-width="5"/>
        <path class="logo-outline" d="M24.0556 36.8386C25.6639 34.3292 27.565 31.9531 29.7591 29.7591C46.1946 13.3236 72.8418 13.3236 89.2772 29.7591C105.713 46.1946 105.713 72.8418 89.2772 89.2773C72.8418 105.713 46.1946 105.713 29.7591 89.2773C27.3767 86.8949 25.3396 84.2979 23.6479 81.5486" stroke="black" stroke-width="5"/>
        </svg>
    </a>
        
    <nav>
        <a href="/aboutme">about me</a>
        <a href="/portfolio">portfolio</a>
        <a href="/contact">contact</a>
    </nav>
</header>

<slot/>

<style>

    header{
        position: absolute;
        top:0;
        left:0;
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        padding: 50px 0 150px 70px;
    }

    .main-logo svg{
        transition: 0.5s ease;
    }

    .main-logo:hover svg{
        transform: rotate(90deg);
        
    }

    nav{
        display: flex;
        flex-direction: column;
        padding-left: 20px;
    }

    nav a{
        text-decoration: none;
        font-size: 36px;
        font-weight: 500;
        letter-spacing: 1px;
        margin-bottom: 15px;
        color: rgba(0, 0, 0, 0.7);
        transition: 0.5s ease;
    }

    nav a::before{
        content: '';
        background-color: #000;
        width: 0px;
        height: 2px;
        display: inline-block;
        margin-right: 25px;
        margin-left: -25px;
        transform: translateY(-10px);
        transition: 0.5s ease;
        position: relative;
    }

    nav a:hover{
        color: #000;
    }

    nav a:hover::before{
        width: 75px;
    }
</style>