<template>
    <div id = 'title' class = 'text-center'>
        <h1>{{h1s}}</h1>
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
h1{
    color:white;
}
</style>
