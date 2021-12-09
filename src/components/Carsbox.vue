<template>
    
     <div class="Carsbox">
         
        <div v-for="car in cars" :key="car.id" >
                
                <Car :car="car"/>
        </div>

     </div>

</template>

<script>

import Car from "./Car.vue"
export default{

    name: 'Carsbox',
    components: {
        Car
    },
    props: {
        cars: JSON
    }

}

</script>


<style>

.Carsbox{

    background-color: rgb(224, 250, 164);
    padding: 1em;
    color: gray;
}
</style>