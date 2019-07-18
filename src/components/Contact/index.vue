<template>
    <div id = "contact">
        <div class= "contactWrapper">
            <h2>
                Contact
            </h2>
            <h4>
                aj_alvarez91@yahoo.com
            </h4>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

#contact {

  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  background-image:url('https://media0.giphy.com/media/GU60SXeRvBnTG/giphy.gif?cid=790b76115d0be56371494e6c55555709&rid=giphy.gif');
  background-repeat: no-repeat;
  background-position: 50%,50%;
  background-size: 80%;
  background-attachment: fixed;
  background-color:black;
  height: 100vh;
  width:100%;
  display:flex;
  align-items:center;
  justify-content: center;
  flex-direction: column;
}

.contactWrapper{
        padding:3vw;
    margin:15vw;
    background-color:rgba(255,234,0,.8);
    border-radius: 2em;
}

h2{
    color:white;
}
</style>
