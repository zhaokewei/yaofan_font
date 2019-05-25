<template>
    <div>
        <div class="qrcode-block">
            <img class="qrcode" src="../assets/qrcode-wx.jpg" >
            <img class="qrcode" src="../assets/qrcode_zfb.jpg" >
        </div>
        <div class="begimg-block">
            <img class="begimg" src="../assets/beg.jpg">
        </div>
        <div>美女帅哥，行行好，给点饭钱吧！我已经忘记米饭的味道了！</div>
    </div>
</template>

<script>
    export default {
        name: "Home"
    }
</script>

<style scoped>
    .qrcode-block {
        box-shadow: cadetblue 10px 10px 10px 10px;
        width: 60%;
        margin: auto;
    }
    .qrcode {
        width: 30%;
        margin: 5%;
    }
    .begimg-block{
        margin-top: 4%;
    }
    .begimg {
        width: 20%;
        height: 20%;
    }
</style>