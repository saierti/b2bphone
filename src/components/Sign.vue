// 阳宁  登录界面组件

<template>
    <div class="sign">
        <div class="signlogo"></div>
        <div class="signmessage">
            <div class="username">
                <img src="../assets/userlogo.jpg" alt="">
                <input type="text" placeholder="用户名" >
            </div>
            <div class="password">
                <img src="../assets/userlogo.jpg" alt="">
                <input type="text" placeholder="密码">
            </div>
        </div>
        <div class="signbutton">
            <input type="button" class="normalsign" value="登录">
            <input type="button" class="netsign" value="2018网签登录">
        </div>
    </div>
</template>
<script>
export default {
    data(){
        return {
            logo:{}
        }
    }
}
</script>

<style>
    .signlogo{
        width: 186px;
        height: 61px;
        background-image: url(../assets/yulan.png);
        background-size: cover;
        position: relative;
        left: 50%;
        margin-left: -26%;
        margin-top: 100px;
    }
    .signmessage{
        margin-top: 100px;
    }
    .signmessage input{
        border-style:none;
        border-bottom: 1px solid #707070;
        width: 158px;
        height: 28px;
        margin-left: 5px;
        margin-top: 25px;
        padding-left: 7px;
        font-size: 10px;  
        outline: none; 
    }
    .signmessage -webkit-input-placeholder{
        color:red;
    }
    .signmessage img{
        width: 25px;
        height: 25px;
        vertical-align: middle;
        margin-left: -18px;
    }
    .signbutton{
        margin-top: 80px;
    }
    .signbutton input{
        border-radius: 25px;
        position: relative;
        left: 50%;
        margin-left: -23%;
        text-align:center;
        display: block;
        width: 163px;
        height: 45px;
        border:1px solid #A7D470;
        outline:none;
    }
    .normalsign{
        background: #A7D470;
        color: #ffffff;
    }
    .netsign{
        margin-top: 25px;
        background:none;
        color: #A7D470;
    }
</style>
