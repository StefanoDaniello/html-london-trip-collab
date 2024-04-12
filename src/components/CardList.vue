<template>
    <div class="container">
        <div class="row">
            <div class="col-3 my-2" v-for="(coktail, index) in coktail_list" :key="index" >
                <div class="card" >
            <img :src="coktail.strDrinkThumb" class="card-img-top" :alt="coktail.strDrink">
            <div class="card-body">
                <h5 class="card-title">{{ coktail.strDrink }}</h5>
            </div>
        </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'CardList',
       
        data() {
            return {
                coktail_list:[
                    {
                    "strDrink": "110 in the shade",
                    "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/xxyywq1454511117.jpg",
                    "idDrink": "15423"
                    },
                    {
                    "strDrink": "151 Florida Bushwacker",
                    "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/rvwrvv1468877323.jpg",
                    "idDrink": "14588"
                    },
                    {
                    "strDrink": "155 Belmont",
                    "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/yqvvqs1475667388.jpg",
                    "idDrink": "15346"
                    },
                    {
                    "strDrink": "24k nightmare",
                    "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/yyrwty1468877498.jpg",
                    "idDrink": "17060"
                    },
                    {
                    "strDrink": "252",
                    "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/rtpxqw1468877562.jpg",
                    "idDrink": "15288"
                    },
                    {
                    "strDrink": "3 Wise Men",
                    "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/wxqpyw1468877677.jpg",
                    "idDrink": "13899"
                    },
                    {
                    "strDrink": "3-Mile Long Island Iced Tea",
                    "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/rrtssw1472668972.jpg",
                    "idDrink": "15300"
                    },
                    {
                    "strDrink": "410 Gone",
                    "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/xtuyqv1472669026.jpg",
                    "idDrink": "13581"
                    },
                    {
                    "strDrink": "50/50",
                    "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/wwpyvr1461919316.jpg",
                    "idDrink": "14598"
                    },
                    {
                    "strDrink": "501 Blue",
                    "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/ywxwqs1461867097.jpg",
                    "idDrink": "17105"
                    },
                    {
                    "strDrink": "57 Chevy with a White License Plate",
                    "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/qyyvtu1468878544.jpg",
                    "idDrink": "14029"
                    },
                    {
                    "strDrink": "69 Special",
                    "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/vqyxqx1472669095.jpg",
                    "idDrink": "13940"
                    },
                ],
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>