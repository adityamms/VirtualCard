<template>
    <div style="display: flex;justify-content: center;align-items: center;" id="Dataku">

        <div style="width: 90%;height:1400px;border: 1px solid black;background-color: white;position: relative;top: -20px;box-shadow: 2px 2px 4px green;padding: 15px;">
            <div style="display: flex; gap: 10px;">       
                <h1> <img src="./icons/phone-call.png" alt="" style="width: 30px;height: 30px; border-radius: 50%;border: 1px solid green;padding: 2px;position: relative;top: 6px;" /> Contact</h1>
            </div>
            <ul>
                <li>name
                    <div><h2>your name</h2></div>
                </li>
                <li>phone
                    <div><h2>phone number </h2></div>
                </li>
                <li>tel
                    <div><h2>telephone number</h2></div>
                </li>
                <li>company
                    <div><h2>your company</h2></div>
                </li>
            </ul>
            <div style="display: grid;gap: 30px;position: relative;top: 50px;">
            <div style="border: .5px solid black;padding-left: 20px;"
            ><h1 style="margin: 0px;"><img src="./icons/info.png" alt="" style="width: 30px;height: 30px;" /> sumary</h1>
            <p>A brief description abaout you and your skill<br>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate dolorem, quidem tempore non autem culpa saepe aliquam nostrum consequuntur neque. Expedita quibusdam molestias magnam omnis nobis labore animi, blanditiis nesciunt.
            </p>
            
            </div>
            <div style="border: .5px solid black;padding-left: 20px;"
            ><h1 style="margin: 0px;"><img src="./icons/placeholder.png" alt="" style="width: 30px;height: 30px;" /> address</h1>
            <p>your address<br><br>
                <button>show on map</button>
                
            </p>
        
            </div>
        </div>
        
        <ul style="position: relative;top: 100px;display: grid;gap: 0px;align-items: center;" id="soscial">
            <li style="border-bottom: none;"><p> <img src="./icons/facebook.png" alt="" /> facebook</p></li>
            <li style="border-bottom: none;"><p> <img src="./icons/twitter.png" alt="" /> twitter</p></li>
            <li style="border-bottom: none;"><p> <img src="./icons/instagram.png" alt="" /> instagram</p></li>
            <li><p> <img src="./icons/linkedin.png" alt="" /> linkdin</p></li>
            
        </ul>
        
        <div style="position: relative;top: 150px;border: 1px solid black;display: grid;justify-content: center;align-items: center;text-align: center;">
           <div> <img src="./icons/world-wide-web.png" alt="" style="height: 30px;width: 30px;"/> </div><h3>www.yourwebsite.com</h3>
        </div>
        
  </div>
</div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    #Dataku{
        ul{
            list-style: none;
            margin: 0%;
            display: grid;
            gap: 30px;
            padding: 5px;
        }

        li{
            border-bottom: 1px solid black;
                text-transform: capitalize;
        }
        h2{
            margin: 5px 0px;
        }
    }

    #carouselExampleSlidesOnly{
        img{
            width: 50%;
            height: 300px;
        }
    }

    #soscial{
        li{
            border: 1px solid black;
            height: 50px;
            padding-left: 5px;
            display: flex;
            align-items: center;
            
        }
        img{
            width: 30px;
            height: 30px;
           
        }
        p{
            position: relative;
            top: 10px;
        }
    }
</style>