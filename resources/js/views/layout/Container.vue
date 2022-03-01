<template>
    <img class="img4" src="https://i.ibb.co/bvFqWrw/googleplay.png" alt="googleplay" border="0">
    <img class="img3" src="https://i.ibb.co/NrYp40Y/appstore.png" alt="appstore" border="0">
    <img class="img2" src="https://i.ibb.co/wCyQcFw/logo-white.png" alt="logo-white" border="0">
    <img class="img1" src="https://i.ibb.co/3m0rZXj/Group-1-1.png" alt="Group-1-1" >
    <div class="login">
        <h2 class="txt">Sign UP</h2>
        <form class="form">
            <my-input type="text" placeholder="email"></my-input>
            <my-input type="text" placeholder="password"></my-input>
        </form>
    </div>
</template>

<script>
import MyButton from "../../components/UI/MyButton";
import MyInput from "../../components/UI/MyInput";
export default {
    name: "Container",
    components: {
        MyInput,
        MyButton
    },
}
</script>

<style scoped lang="scss">
.txt{
    font-size: 34px;
    margin-left: 139px;

    padding-top: 19px;
}
.img4{
    position: relative;
    height: 49px;
    width: 179.7525722457067px;
    left: 1018px;
    top: 240px;
    border-radius: 0px;

}
.img3{
    position: relative;
    height: 50.03773498535156px;
    width: 178px;
    left: 595px;
    top: 240px;
    border-radius: 0px;

}
.img2{
    position: relative;
    top:-300px;
    left: 287px;
}
.img1{
    position: relative;
    left: -145px;
    top: 238px;
}
.login {
    position: relative;
    left: 775px;
    top: -314px;
    width: 420px;
    height: 385px;
    background-color: #ECF0F3;
    border-radius: 30px;
}
.form input {
   border-radius: 20px;
    width: 343px;
    height: 51px;
    margin-left: 35px;
    margin-top: 50px;
}

</style>
