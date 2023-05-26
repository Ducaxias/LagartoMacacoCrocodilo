<template>
    <header>
        <nav>
            <h1 href="#!" class="logo">Clovis</h1>
            <ul class="navlinks">
                <RouterLink to="/" class="link">Inicio</RouterLink>
                <li class="link"><a href="#Galeria">Galeria</a></li>
                <li class="link"><a href="#Exposições">Exposições</a></li>
                <li class="link"><a href="#Workshops">Workshops</a></li>
                <RouterLink to="/Login" class="link">Login</RouterLink>
            </ul>
        </nav>
    </header>

</template>

<script>
    export default{
        name: "Navbar"
    }
</script>

<style>
.logo{
    font-size: 35px;
}

.link, .link a{
    color: var(--corprimaria);
    font-size: 18px;
    transition: .3s;
    letter-spacing: 3px;
}

header{
    width: 100%;
    height: 70px;
    position: fixed;
    padding: 10px;
    background-color: #fff;
    border-bottom: 2px solid #000;
}

nav{
    display: flex;
    flex-direction: row;
    gap: 53%;
    width: auto;
    align-items: center;
}

ul{
    gap: 20px;
    width: auto;
    padding: 5px;
    display: flex;
    flex-direction: row;
}
</style>
