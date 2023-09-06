<template>
    <div class="basicinfo">
        <div class="name">刘天泽</div>
<!--         <div class="age">23岁</div> -->
        <!-- photo -->
        <div class="photo">
            <img src="../assets/photos/My2inchPhoto.jpg" alt="" id="myPhoto">
        </div>
        
        <div class="code">
            <div id="codelang">编程语言</div>
            <ul>
                <li>
                    <img src="../assets/codeIconsSVG/html5-logo.svg" alt="">
                    <div class="lang">HTML</div>
                </li>
                <li>
                    <img src="../assets/codeIconsSVG/css-logo.svg" alt="">
                    <div class="lang">CSS</div>
                </li>
                <li>
                    <img src="../assets/gifIcons/javascript.gif" alt="JavaScript">
                    <div class="lang">JavaScript</div>
                </li>
                <li>
                    <img src="../assets/codeIconsSVG/vue-js.svg" alt="">
                    <div class="lang">Vue</div>
                </li>
                <li>
                    <img src="../assets/gifIcons/java-logo.gif" alt="">
                    <div class="lang">Java</div>
                </li>
            </ul>
        </div>
        <div class="contacts">
            <div class="text" id="email">📧 913109138@qq.com</div>
            <div class="text" id="github">💻 githubURL</div>
        </div>

    <div>

    </div>

</div>

    
</template>

<script>
export default {
    name:"MyDetails"
}
</script>

<style>
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    .basicinfo{
        margin: 20px auto;
        width: 300px;
        /* 待改进，现在是写死的参数 */
        height: auto;
/*         border: 1px solid #ddd; */
/*         border-radius: 8px; */
        display: flex;
        flex-direction: column;
    }
    .basicinfo .name{
        font-size: 28px;
        font-weight:bold;
        text-align: center;
        padding:10px 0;
    }
    #codelang{
        font-size: 28px;
        text-align: center;
        padding:10px 0 10px 0;
    }
    .code ul{
        display: flex; 
        flex-wrap: wrap;
        justify-content: space-between;
        /*  */
        align-content: center;
        /* padding:1em; */
        height:auto;
    }
    .code li{
        display: flex;
        flex-wrap: wrap;
        height: 48px;
/*         width: fit-content;
        height:fit-content; */
        margin:5px;
/*         justify-content: space-between; */
/*         align-content: space-between; */
/*         background-color: white; */
    }
    .code li img{
        height:36px;
        width: auto;
    }
    .code li .lang{
        font-size: 16px;
        padding:5px;
       /*  text-align:center; */
    }
/*     .basicinfo h1{

    } */
/*     .basicinfo{
        width: 400px;
        height:auto;
        display: flex;
    } */
    .contacts{
        display: flex;
        align-items:center;
        justify-content: center;

    }
    .contacts .text{

        padding:10px;
        display: flex;

    }
    .photo{
        width: auto;
        height: auto;
        display: flex;
        align-items:center;
        justify-content: center;
    }
    #myPhoto{
        width:200px;
        height:auto
        
    }
</style>