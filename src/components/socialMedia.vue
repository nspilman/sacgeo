<template>
<div id='wrapper'>
    <div id ='socialMedia'>
        <a href = "https://www.instagram.com/sac_geo/?hl=en">
            <div class = 'icon'>
                <i class="fab fa-instagram"></i>
            </div>
        </a>
        <a href = "https://www.youtube.com/channel/UCEfvR9o9e5gAt3fPI7_O4xg/">
            <div class = 'icon'>
                <i class="fab fa-youtube"></i>
            </div>
        </a>
        <a href = "https://open.spotify.com/user/21oifm5tgutbg3sad2axb3cua/playlist/7jW9BhOQUurP100QrtuZVP?si=_UCa9vr_QwWXnS4--Af2EA">
            <div class = 'icon'>
                <i class="fab fa-spotify"></i>
            </div>
        </a>
    </div>
</div>
</template>

<script>
export default {
    
}
</script>
<style scoped>
#wrapper{
 display:flex;
    justify-content: center;
    align-items: center;
}

#socialMedia{
    background-color: white;
    height:8%;
    width:40vw;
    margin:0;
    margin-bottom:-8px;
    display:flex;
    justify-content: center;
    align-items: center;
    border-radius: 10px;
}

.fab{
    width:100%;
}

@keyframes glow{
    from{
        box-shadow: 0px 0px 37px -3px rgba(255,234,0,1);
    }

    to{
        box-shadow: 0px 0px 37px 3px rgba(255,234,0,1);
    }
}

.icon{
    width:50px;
    margin:1%;
    font-size:2.5em;
    animation:glow 4s infinite;
}
</style>
