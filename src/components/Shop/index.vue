<template>
    <div id = "shop">
        <h2>SHOP </h2>
        <a href ="https://teespring.com/stores/sac-geo-store">
            <img class = "tshirt" src = "https://vangogh.teespring.com/v3/image/zBGOzTrfnWUaeY__Fv-CBeWHfTw/480/560.jpg"/>
        </a>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

#shop {

  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-image:url('https://i.giphy.com/media/RdKPvP2TAFjZfLFZlZ/source.gif');
  background-repeat: no-repeat;
  background-position: 50%,50%;
  background-attachment: fixed;
  background-color:black;
  height: 100vh;
  width:100%;
  display:flex;
  align-items:center;
  justify-content: center;
  flex-direction: column;
}

.tshirt{
    height:20vw;
    width:20vw;
}

h2{
    color:white;
}

</style>
