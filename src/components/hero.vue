<template>
    <div id="bg-avatar" style="background-color: red;width: 100%;height: 150px;z-index: 10;">
        
    </div>
    <div id="nama" style="display: grid;align-items: center;justify-content: center;text-align: center;border-radius: 0 0 20px 20px;background-color: rgb(64,174,163);width: 100%;height: 250px;">
        <div style="position: relative;top: -50px;"><img src="./image/pp.jpg" alt=""></div>
        <div style="position: relative;top: -40px;">
        <h2>your full name</h2>
<p style="position: relative;top: -10px;">your job title</p>
</div>
<ul>
    <li><img src="./icons/phone-call.png" alt=""></li>
    <li><img src="./icons/email.png" alt=""></li>
    <li><img src="./icons/placeholder.png" alt=""></li>
</ul>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

#nama{
    *{
        color:black;
    }
    h2{
       text-transform: capitalize; 
    }
    img{
        border-radius: 50%;
        border: 1px solid black;
        padding: 2px;
        width: 100px;
        height: 100px;
       
    }

    p{
        width: 300px;
    }
    ul{
        list-style: none;
        display: flex;
        gap: 30px;
        position: relative;
        top: -40px;
    }

    ul>li>img{
        width: 40px;
        height: 40px;
        border: none;
    }
    li{
        background-color: white;
        border-radius: 50%;
        width: 60px;
        height: 60px;
        display: flex;
        align-items: center;
        justify-content: center;
        border: 2px solid black;
    }
}

</style>