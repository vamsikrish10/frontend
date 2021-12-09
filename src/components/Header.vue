<template>
<div>
    <h1> {{siteName}} </h1>
    <h4> {{authorName}} </h4>
</div>
</template>

<script>

export default{
    name: 'Header',
    props:{
        siteName: String,
        authorName:String
    }
}

</script>

<style scoped>

div{
    text-align: center;
    background-color: rgb(218, 189, 255);
}

</style>