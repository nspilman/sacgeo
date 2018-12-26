<template>
    <div id = 'title' class = 'text-center'>
        <h1>{{titleString}}</h1>
    </div>
</template>
<script>
export default {
    data(){
        return{
            titleString: 'SACRED GEOMETRY',
            h1s:''

        }},
        created(){
            this.h1s = 'yooooo'
        }
    }
    
</script>
<style scoped>
@import 'https://fonts.googleapis.com/css?family=Dosis';
h1{
    color:white;
    font-family: 'Dosis', sans-serif;
    font-size:20vw;
}

</style>
