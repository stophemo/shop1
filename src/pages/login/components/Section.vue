<template>
  <section>
        <div class="login_content">
            <div class="login_content_right">
                <img src="../../../assets/image/loadimg.jpg" alt="">
            </div>
            <div class="login_content_left">
                <form action="">
                    <div class="login_content_left_title">
                        <span>1号店用户登录</span><span>注册帐号</span>
                    </div>
                    <div class="username">
                        <img src="../../../assets/image/userHead.png" alt="">
                        <input type="text" name="" id="" placeholder="用户名/手机号/邮箱">
                    </div>
                    <div class="username">
                        <img src="../../../assets/image/lock.png" alt="">
                        <input type="text" name="" id="" placeholder="密码">
                    </div>

                </form>
                <div class="auto_login">
                    <div><input type="checkbox"> <span>自动登录</span></div>
                    <div>忘记密码</div>
                </div>
                <div>
                    <button @click="ToHome">登录</button>
                </div>
                <p>更多合作网站登录</p>
                <div class="login_more">
                    <div class="login_more_log">
                        <img src="../../../assets/image/qqt.png" alt="">
                        <img src="../../../assets/image/wbt.png" alt="">
                        <img src="../../../assets/image/wxt.png" alt="">
                        <img src="../../../assets/image/zhit.png" alt="">
                    </div>
                    <div>
                        <p>更多合作网站</p>
                        <img src="../../../assets/image/turnb.png" alt="">
                    </div>
                </div>

            </div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'LoginSection',
  methods: {
    ToHome () {
      this.$router.push('/home')
    }
  }
}
</script>

<style scoped>
section {
    padding: 100px 0;
}

.login_content {
    display: flex;
    justify-content: space-around;
}

.username {
    border: 1px solid rgb(175, 174, 174);
    display: flex;
    align-items: center;
    padding: 5px;
}

form input {
    width: 230px;
    height: 40px;
    border: none;
    outline: none;
    padding: 0 10px;
}

form {
    display: flex;
    flex-flow: column;
    justify-content: space-evenly;
    height: 200px;
}

.login_content_left_title {
    display: flex;
    justify-content: space-between;
}

form span:nth-of-type(1) {
    font-size: 14px;
    color: black;
    font-weight: bold;
}

form span:nth-of-type(2) {
    color: blue;
}

.auto_login {
    display: flex;
    justify-content: space-between;
}

button {
    width: 100%;
    height: 50px;
    color: white;
    background: #FF3C3C;
    border: noneF;
}

.login_content_left {
    height: 400px;
    /* border: 1px solid red; */
    display: flex;
    flex-flow: column;
    justify-content: space-evenly;
}

.login_more {
    display: flex;
    justify-content: space-between;
}

.login_more_log img {
    height: auto;
    width: 10%;
    margin-left: 5px;
}

.login_more div:nth-child(2) {
    display: flex;
}

.login_more div:nth-child(2) img {
    align-self: flex-start;
    margin-top: 5px;
}
</style>
