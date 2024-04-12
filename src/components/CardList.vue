<template>
    <div class="container">
        <div class="row">
            <div class="col-3" v-for="(coktail, index) in coktail_list" :key="index" >
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
                    strDrink: "110 in the shade",
                    strDrinkThumb: "https://www.thecocktaildb.com/images/media/drink/xxyywq1454511117.jpg",
                    idDrink: "15423"
                    },
                    {
                    strDrink: "151 Florida Bushwacker",
                    strDrinkThumb: "https://www.thecocktaildb.com/images/media/drink/rvwrvv1468877323.jpg",
                    idDrink: "14588"
                    },
                    {
                    strDrink: "110 in the shade",
                    strDrinkThumb: "https://www.thecocktaildb.com/images/media/drink/xxyywq1454511117.jpg",
                    idDrink: "15423"
                    },
                    {
                    strDrink: "151 Florida Bushwacker",
                    strDrinkThumb: "https://www.thecocktaildb.com/images/media/drink/rvwrvv1468877323.jpg",
                    idDrink: "14588"
                    }, 
                    {
                    strDrink: "110 in the shade",
                    strDrinkThumb: "https://www.thecocktaildb.com/images/media/drink/xxyywq1454511117.jpg",
                    idDrink: "15423"
                    },
                    {
                    strDrink: "151 Florida Bushwacker",
                    strDrinkThumb: "https://www.thecocktaildb.com/images/media/drink/rvwrvv1468877323.jpg",
                    idDrink: "14588"
                    },
                    {
                    strDrink: "151 Florida Bushwacker",
                    strDrinkThumb: "https://www.thecocktaildb.com/images/media/drink/rvwrvv1468877323.jpg",
                    idDrink: "14588"
                    },{
                    strDrink: "151 Florida Bushwacker",
                    strDrinkThumb: "https://www.thecocktaildb.com/images/media/drink/rvwrvv1468877323.jpg",
                    idDrink: "14588"
                    },
                ],
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>