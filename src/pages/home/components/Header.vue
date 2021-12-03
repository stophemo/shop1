<template>
  <header>
    <div class="index">
      <span>送货至：四川</span>
      <ul>
        <li><a href="">你好，请登录</a> </li>
        <li><a href="">免费注册</a> </li>
        <li>|</li>
        <li><a href="">我的订单</a> </li>
        <li>|</li>
        <li><a href="">收藏夹</a> </li>
        <li><a href="">客户服务</a> </li>
        <li><a href="">网站导航</a> </li>
        <li>|</li>
        <li><a href="">关注我们</a> </li>
        <li></li>
        <li></li>
        <li><a href="">手机版</a></li>
        <li></li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style>
* {
    margin: 0;
    padding: 0;
}

.index {
    padding: 5px;
    width: 1200px;
    margin: 0 auto;
    background: linear-gradient(to bottom, #D4D4D4, #F5F5F5);
    display: flex;
    justify-content: space-between;
}

.index span {
    padding: 0 20px;
}

.index ul {
    display: flex;
    justify-content: flex-end;
    margin-right: 20px;
}

.index ul li {
    padding: 0 5px;
}

.index ul li:nth-child(2) a {
    color: #ff4e00;
}

.index ul li:nth-child(11) {
    background-image: url(../../../assets/image/sh1.png);
    background-repeat: no-repeat;
    background-position: 0 3px;
    width: 20px;
    padding: 0 2px;
}

.index ul li:nth-child(12) {
    background-image: url(../../../assets/image/sh2.png);
    background-repeat: no-repeat;
    background-position: 0px 6px;
    width: 20px;
}

.index ul li:nth-child(14) {
    background-image: url(../../../assets/image/s_tel.png);
    background-repeat: no-repeat;
    background-position: 0px 5px;
    width: 20px;
}

</style>
