<template>
    <!--div v-if="car.published == false"-->

    <!-- <div :class="car.published ? 'green': 'red' "> -->

    <div>
    
    <h2>{{car.title}}</h2>
    <h3>{{car.year}}</h3>
    <h4>{{car.rating}}</h4>
    <h5> {{car.published}}</h5>


    </div>
</template>

<script>

export default{
    name: 'car',
    props:{
        car : JSON
    }
}
</script>

<style scoped>



h4{
    margin: 2px;
}

div{
    background-color: #f7cc8d;
    color: black;
    padding: 1em;
}

.red{
background-color: orangered !important;

}


</style>