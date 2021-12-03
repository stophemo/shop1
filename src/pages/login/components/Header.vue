<template>
     <header>
        <div class="header_bg">
            <div>
                <img src="../../../assets/image/loginlogo.jpg" alt="">
            </div>
            <div class="header_right">
                <p>您好，欢迎光临1号店</p>
                <p>请登录</p>
                <div class="header_help">
                    <img src="../../../assets/image/runbun.png" alt="">
                    <p>帮助中心</p>
                    <img src="../../../assets/image/turnb.png" alt="">
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
  name: 'LoginHeader'
}
</script>

<style scoped>
* {
    margin: 0;
    padding: 0;
}

.header_bg {
    display: flex;
    padding: 20px;
    border-bottom: 1px solid rgb(177, 175, 175);
    align-items: center;
    justify-content: space-between;
}

.header_bg img {
    height: 100%;
}

.header_bg>div>img {
    margin-left: 50px;
}

.header_right {
    display: flex;
    align-items: center;
    margin-right: 50px;
    width: 330px;
    justify-content: space-evenly;
}

.header_right p:nth-of-type(1) {
    font-size: 16px;
}

.header_right p:nth-of-type(2) {
    color: blue;
}

.header_help {
    width: 110px;
    display: flex;
    border: 1px solid rgb(177, 175, 175);
    align-items: center;
    justify-content: space-evenly;
}
</style>
