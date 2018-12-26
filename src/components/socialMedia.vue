<template>
    <div id ='socialMedia'>
        <div class = 'icon'>
                <i class="fab fa-instagram"></i>
            </div>
                <div class = 'icon'>
                    <i class="fab fa-youtube"></i>
                </div>
                        <div class = 'icon'>
                            <i class="fab fa-spotify"></i>
                        </div>
        </div>
</template>

<script>
export default {
    
}
</script>
<style scoped>
#socialMedia{
    background-color: white;
    height:8%;
    margin-left: 45%;
    margin-right:45%;
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
