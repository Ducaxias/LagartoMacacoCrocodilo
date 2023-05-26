<template>
    <header>
        <nav>
            <h1 href="#!" class="logo">Clovis</h1>
            <ul class="navlinks">
                <RouterLink to="/" class="link">Inicio</RouterLink>
                <li class="link"><a href="#">Galeria</a></li>
                <li class="link"><a href="#">Exposições</a></li>
                <li class="link"><a href="#">Projetos</a></li>
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
