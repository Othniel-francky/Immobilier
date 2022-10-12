<template>
    <div class="photo">
        <img src="@/assets/maison-plain-pied-orion.jpeg" alt="">
    </div>

    <div class="pot">
        <h2>Bienvenue chez Immob Immobilier</h2>
        <p>Nous mettons un point d'honneur à réaliser vos rêves</p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Temporibus sunt aperiam deserunt minus amet vitae cum iste quod facere necessitatibus eligendi dicta veritatis nam ea possimus quis, similique vero officia!</p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Adipisci odio magni consequuntur impedit eius cumque exercitationem labore tenetur soluta harum ab dolores quidem ipsa doloremque, explicabo animi eaque odit. Ipsa?
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eaque, incidunt illum. Corrupti, cumque. Minima, assumenda, autem ratione voluptatem sunt ducimus ipsa commodi aliquam nobis repellat, itaque fugiat consequatur? Consequuntur, praesentium?
    </div>
    <div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat nobis in facilis incidunt! Praesentium vitae natus, cum ab modi ea recusandae amet sapiente totam odio voluptatibus reprehenderit architecto alias sequi.</p>
    </div>

    <br><br>
    <div class="wrapper">
            <div class="ecrire">
                <p>Pour tous vos traveaux de construction, Immob vous propose</p>
            </div>
            <div class="espace">
                <div class="elle">
                    <img src="@/assets/metier-macon-btp.jpeg" alt="">
                    <div>
                        <p>
                            Maçon
                        </p>
                    </div>
                </div>
                <div class="elle">
                    <img src="@/assets/metier-plombier.jpeg" alt="">
                    <div>
                        <p>Plombier</p>
                    </div>
                </div>
                <div class="elle">
                    <img src="@/assets/climatisation.jpeg" alt="">
                    <div>
                        <p>Climatisation</p>
                    </div>
                </div>
                <div class="elle">
                    <img src="@/assets/7-Batiment.jpeg" alt="">
                    <div>
                        <p>Menusier</p>
                    </div>
                </div>
            </div>
    </div>
</template>

<script>
export default {
    components:{
    }

}
</script>

<style>
    img{
        width: 100%;
        height: 80vh;
    }
    .ecrire{
        text-align: center;
    }
    .ecrire p{
        padding: 17px;
        text-transform: uppercase;
        font-size: 20px;
    }

    .wrapper{
        height: 350px;
        width: 100%;
        border: 1px solid;
        background: grey;
    }

    .elle img{
        height: 100px;
        width: 150px;

    }
    .elle{
        display: inline-block;
        margin: 50px;
        text-align: center;
    }
    .espace{
        text-align: center;
        padding-bottom: 20px;
    }

    .pot{
        text-align: center;
    }

</style>