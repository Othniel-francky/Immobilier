<template>
    <nav class="navbar">
        <h1>Immob</h1>
        <div class="nav-link">
            <ul>
                <li><router-link to="/vente">Vente</router-link></li>
                <li><a href="#">Location</a></li>
                <li><a href="#">Biens vendus</a></li>
                <li><a href="#">Gestion</a></li>
                <li><a href="#">Agence</a></li>
                <li><a href="#">Contact</a></li>
            </ul>

        </div>

    </nav>
</template>

<script>

</script>

<style scoped>
    *{
        margin: 0;
        padding: 0;
    }
    h1{
        font-size: 45px;
        font-weight: bold;
        color: #444;
    }
    .navbar{
        padding: 40px;
        display: flex;
        justify-content: space-between;
        width: 100%;
        box-sizing: border-box;
        align-items: center;
        position: absolute;
    }
    .navbar .nav-link ul{
        display: flex;
    }
    .navbar .nav-link ul li{
        margin: 0 25px;
        font-weight: 400;
    }
    ul li {
        list-style-type: none;
        
    }
    li a{
        text-decoration: none;
    }

</style>