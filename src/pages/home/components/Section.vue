<template>
  <section>

    <div class="sousuo">
      <img src="../../../assets/image/logo.png" alt="">
      <div>
        <form action="" method="GET">
          <div class="form_search">
            <input type="search" name="search" required placeholder="请输入关键字"><label for="">搜索</label>
          </div>
        </form>
        <div class="search_history">
          <ul>
            <li><a href=""> 咖啡</a></li>
            <li><a href="">Iphone6s</a> </li>
            <li><a href="">新鲜美食</a> </li>
            <li><a href="">蛋糕</a> </li>
            <li><a href="">日用品</a> </li>
            <li><a href="">连衣裙</a> </li>

          </ul>
        </div>
      </div>
      <div class="shop_car">
        <span> 购物车</span>
      </div>
    </div>
    <!-- -------------------------------------------------------------- -->
    <div class="all_douct">
      <p>全部商品分类</p>
      <ul>
        <li><a href="">首页</a></li>
        <li><a href="">自营超市</a></li>
        <li><a href="">1号团</a></li>
        <li><a href="">1号超市</a></li>
        <li><a href="">女装</a></li>
        <li><a href="">美妆</a></li>
        <li><a href="">1号海购</a></li>
        <li><a href="">团购</a></li>
      </ul>
      <div class="pohone_buy">
        <div>
          <img src="../../../assets/image/s_tel.png" alt="">
        </div>
        <span> 手机下单惊喜多！</span>
      </div>
    </div>
    <!-- -------------------------------------------------------------------- -->
    <div class="caidan">
      <div class="caidan_liebiao">
        <ul>
          <li class="li-1 li">
            <span></span>
            <a href="">进口食品、生鲜</a>
            <span class="span1"></span>
          </li>
          <li class="li-2 li">
            <span></span>
            <a href="">进口食品、生鲜</a>
            <span class="span1"></span>
          </li>
          <li class="li-3 li">
            <span></span>
            <a href="">进口食品、生鲜</a>
            <span class="span1"></span>
          </li>
          <li class="li-4 li">
            <span></span>
            <a href="">进口食品、生鲜</a>
            <span class="span1"></span>
          </li>
          <li class="li-5 li">
            <span></span>
            <a href="">进口食品、生鲜</a>
            <span class="span1"></span>
          </li>
          <li class="li-6 li">
            <span></span>
            <a href="">进口食品、生鲜</a>
            <span class="span1"></span>
          </li>
          <li class="li-7 li">
            <span></span>
            <a href="">进口食品、生鲜</a>
            <span class="span1"></span>
          </li>
          <li class="li-8 li">
            <span></span>
            <a href="">进口食品、生鲜</a>
            <span class="span1"></span>
          </li>
          <li class="li-9 li">
            <span></span>
            <a href="">进口食品、生鲜</a>
            <span class="span1"></span>
          </li>
          <li class="li-10 li">
            <span></span>
            <a href="">进口食品、生鲜</a>
            <span class="span1"></span>
          </li>
        </ul>
      </div>
      <div class="caidan_tupian">
        <swiper :options="swiperOptions">
          <swiper-slide><img class="swiper-img" src="../../../assets/image/ban1.jpg" alt=""></swiper-slide>
          <swiper-slide><img class="swiper-img" src="../../../assets/image/ban1.jpg" alt=""></swiper-slide>
          <swiper-slide><img class="swiper-img" src="../../../assets/image/ban1.jpg" alt=""></swiper-slide>
          <div class="swiper-pagination" slot="pagination"></div>
        </swiper>
      </div>
      <div class="caidan_zixun">
        <div class="caidan_zixun_kuaixun">
          <ul>
            <li>
              <a href="">

                <div>
                  <h4>快讯</h4>
                  <span class="caidan_zixun_kuaixun_span2">更多></span>

                </div>
              </a>
            </li>

            <li>
              <a href="">
                <h4>【特惠】</h4>
                <span>掏一轮明月&nbsp;表无尽惦念</span>
              </a>
            </li>
            <li>
              <a href="">
                <h4>【公告】</h4>
                <span>掏一轮明月&nbsp;表无尽惦念</span>
              </a>
            </li>
            <li>
              <a href="">
                <h4>【特惠】</h4>
                <span>掏一轮明月&nbsp;表无尽惦念</span>
              </a>
            </li>
            <li>
              <a href="">
                <h4>【公告】</h4>
                <span>掏一轮明月&nbsp;表无尽惦念</span>
              </a>
            </li>
            <li>
              <a href="">
                <h4>【特惠】</h4>
                <span>掏一轮明月&nbsp;表无尽惦念</span>
              </a>
            </li>
          </ul>
        </div>

        <div class="caidan_zixun_kuaixun">
          <ul>
            <li>
              <a href="">
                <div>
                  <h4>一号钱包</h4>
                </div>
              </a>
            </li>
            <li>
              <a href="">
                <div>
                  <p>收益日结</p>
                  <img src="../../../assets/image/oneAD.jpg" alt="">
                </div>
              </a>
            </li>

          </ul>
        </div>

      </div>
    </div>
    <!-- ------------------------------------------------------ -->
    <div class="hot">
      <div class="hot_first hot1">
        <img src="../../../assets/image/l_img.jpg" alt="">
        <div>
          <span>￥53</span><span>26r</span>
        </div>

      </div>
      <div class="hot_first">
        <img src="../../../assets/image/hot1.jpg" alt="">
        <p>德国进口</p>
        <p>全职纯牛奶</p>
        <div>
          <span>￥53</span><span>26r</span>
        </div>

      </div>
      <div class="hot_first">
        <img src="../../../assets/image/hot2.jpg" alt="">
        <p>德国进口</p>
        <p>全职纯牛奶</p>
        <div>
          <span>￥53</span><span>26r</span>
        </div>
      </div>
      <div class="hot_first">
        <img src="../../../assets/image/hot3.jpg" alt="">
        <p>德国进口</p>
        <p>全职纯牛奶</p>
        <div>
          <span>￥53</span><span>26r</span>
        </div>
      </div>
      <div class="hot_first">
        <img src="../../../assets/image/hot4.jpg" alt="">
        <p>德国进口</p>
        <p>全职纯牛奶</p>
        <div>
          <span>￥53</span>
          <span>26r</span>
        </div>
      </div>
    </div>
    <div class="img">

      <img src="../../../assets/image/mban_2.jpg" alt="">
    </div>
    <div class="first_F">
      <div class="first_F_jinkou_shengxian">
        <div class="first_F_jinkou_shengxian_title">
          <img src="../../../assets/image/floor.png" alt="">
          <span>1F</span>
          <p>进口·生鲜</p>
        </div>
        <ul>
          <li>
            <a href=" ">进口咖啡</a>
          </li>
          <li>
            <a href=" ">进口酒</a>
          </li>
          <li>
            <a href=" ">进口母婴</a>
          </li>
          <li>
            <a href=" ">新鲜蔬菜</a>
          </li>
          <li>
            <a href=" ">新鲜水果</a>
          </li>
        </ul>
      </div>
      <div class="first_F_jinkou_shengxian_xiangxi ">
        <div class="first_F_jinkou_shengxian_xiangxi_img ">

          <img src="../../../assets/image/fre_r.jpg" alt=" ">
          <ul>

            <li class="first_F_jinkou_shengxian_xiangxi_img_li ">
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
            </li>
            <li>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
            </li>
            <li>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
            </li>
            <li>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
            </li>
          </ul>
        </div>

        <div class="first_F_jinkou_shengxian_xiangxi_shangpin ">
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_1.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_2.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_3.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_4.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_5.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_6.jpg" alt=" ">
          </div>
        </div>
        <div class="first_F_jinkou_shengxian_xiangxi_shangpin_rightimg ">
          <img src="../../../assets/image/fre_b1.jpg" alt=" ">
          <img src="../../../assets/image/fre_b2.jpg" alt=" ">
        </div>
      </div>
    </div>
    <!-- ----------------------------------------------------------- -->
    <div class="first_F">
      <div class="first_F_jinkou_shengxian">
        <div class="first_F_jinkou_shengxian_title">
          <img src="../../../assets/image/floor.png" alt="">
          <span>2F</span>
          <p>进口·生鲜</p>
        </div>
        <ul>
          <li>
            <a href=" ">护法</a>
          </li>
          <li>
            <a href=" ">面膜</a>
          </li>
          <li>
            <a href=" ">洗面奶</a>
          </li>
          <li>
            <a href=" ">香水</a>
          </li>
          <li>
            <a href=" ">沐浴露</a>
          </li>
        </ul>
      </div>
      <div class="first_F_jinkou_shengxian_xiangxi ">
        <div class="first_F_jinkou_shengxian_xiangxi_img ">

          <img src="../../../assets/image/fre_r.jpg" alt=" ">
          <ul>

            <li class="first_F_jinkou_shengxian_xiangxi_img_li ">
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
            </li>
            <li>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
            </li>
            <li>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
            </li>
            <li>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
            </li>
          </ul>
        </div>

        <div class="first_F_jinkou_shengxian_xiangxi_shangpin ">
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/fre_3.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_4.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_5.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_4.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_5.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_6.jpg" alt=" ">
          </div>
        </div>
        <div class="first_F_jinkou_shengxian_xiangxi_shangpin_rightimg ">
          <img src="../../../assets/image/fre_b1.jpg" alt=" ">
          <img src="../../../assets/image/fre_b2.jpg" alt=" ">
        </div>
      </div>
    </div>
    <!-- ---------------------------------------------------------- -->
    <div class="img">

      <img src="../../../assets/image/mban_2.jpg" alt="">
    </div>
    <!-- ---------------------------------------------------------- -->
    <div class="first_F">
      <div class="first_F_jinkou_shengxian">
        <div class="first_F_jinkou_shengxian_title">
          <img src="../../../assets/image/floor.png" alt="">
          <span>3F</span>
          <p>进口·生鲜</p>
        </div>
        <ul>
          <li>
            <a href=" ">营养品</a>
          </li>
          <li>
            <a href=" ">孕妈背带裤</a>
          </li>
          <li>
            <a href=" ">儿童玩具</a>
          </li>
          <li>
            <a href=" ">婴儿床</a>
          </li>
          <li>
            <a href=" ">喂奶器</a>
          </li>
        </ul>
      </div>
      <div class="first_F_jinkou_shengxian_xiangxi ">
        <div class="first_F_jinkou_shengxian_xiangxi_img ">

          <img src="../../../assets/image/fre_r.jpg" alt=" ">
          <ul>

            <li class="first_F_jinkou_shengxian_xiangxi_img_li ">
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
            </li>
            <li>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
            </li>
            <li>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
            </li>
            <li>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
              <a href="# ">进口水果</a>
            </li>
          </ul>
        </div>

        <div class="first_F_jinkou_shengxian_xiangxi_shangpin ">
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/fre_3.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_4.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_5.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_4.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_5.jpg" alt=" ">
          </div>
          <div class="first_F_jinkou_shengxian_xiangxi_shangpin_list ">
            <p>美宝莲粉饼</p>
            <p>￥300</p>
            <img src="../../../assets/image/make_6.jpg" alt=" ">
          </div>
        </div>
        <div class="first_F_jinkou_shengxian_xiangxi_shangpin_rightimg ">
          <img src="../../../assets/image/fre_b1.jpg" alt=" ">
          <img src="../../../assets/image/fre_b2.jpg" alt=" ">
        </div>
      </div>
    </div>
    <!-- -------------------------------------------------------------------------- -->
    <div class="baozhang">
      <div class="baozhang_bz">
        <div class="baozhang_bz_yuan">
          <img src="../../../assets/image/b1.png" alt="">
        </div>
        <p>正品保障</p>
        <p>正品行货 放心购买</p>
      </div>
      <div class="baozhang_bz">
        <div class="baozhang_bz_yuan">
          <img src="../../../assets/image/b2.png" alt="">
        </div>
        <p>正品保障</p>
        <p>正品行货 放心购买</p>
      </div>

      <div class="baozhang_bz">
        <div class="baozhang_bz_yuan">
          <img src="../../../assets/image/b3.png" alt="">
        </div>
        <p>正品保障</p>
        <p>正品行货 放心购买</p>
      </div>

      <div class="baozhang_bz">
        <div class="baozhang_bz_yuan">
          <img src="../../../assets/image/b4.png" alt="">
        </div>
        <p>正品保障</p>
        <p>正品行货 放心购买</p>
      </div>
    </div>
    <!-- ------------------------------------------------------ -->
    <div class="contact">
      <div class="contact_dl">
        <ul>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
        </ul>

        <ul>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
        </ul>

        <ul>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
        </ul>
        <ul>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
        </ul>
        <ul>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
          <li>
            <a href="">新手上路</a>
          </li>
        </ul>

      </div>

      <div class="code">
        <div class="erweima">
          <img src="../../../assets/image/er.gif" alt="">
          <img src="../../../assets/image/ss.png" alt="">
        </div>

        <div class="wb_wx">
          <div>
            <img src="../../../assets/image/wbf.png" alt="">
            <p>新浪微博</p>
          </div>
          <div>
            <img src="../../../assets/image/wxf.png" alt="">
            <p>微信</p>
          </div>

          <p>服务热线:</p>
          <p class="p_number">4008208820</p>

        </div>

      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HomeSection',
  data () {
    return {
      swiperOptions: {
        pagination: '.swiper-pagination'
      }
    }
  }
}
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
}

section {
  width: 1200px;
  margin: 0 auto;
}

.sousuo {
  padding: 20px;
  display: flex;
  align-items: center;
}

.sousuo form {
  height: 60px;
  line-height: 60px;
  margin-left: 150px;
}

.sousuo form input {
  border: 2px solid red;
  width: 430px;
  padding: 10px 10px 10px 10px;
  line-height: 3px;
  outline: none;
}

.sousuo form label {
  padding: 10.5px 20px;
  border: 1px solid red;
  background: red;
  color: white;
}

.shop_car {
  display: flex;
  padding: 5px 30px 5px 50px;
  border: 1px solid rgb(209, 205, 205);
  margin-left: 150px;
  background: #F6F6F6;
  background-image: url(../../../assets/image/car.png);
  background-repeat: no-repeat;
  background-position: 20px 10px;
}

.search_history {
  margin-left: 150px;
}

.search_history ul {
  display: flex;
}

.search_history ul li {
  padding: 0px 5px;
}

.all_douct {
  width: 1200px;
  /* border: 1px solid red; */
  margin: 0 auto;
  display: flex;
}

.all_douct ul {
  display: flex;
  padding: 10px 10px;
}

.all_douct li {
  font-size: 14px;
  margin: 0px 10px;
  font-weight: bold;
}

.all_douct p {
  padding: 10px 10px 10px 30px;
  background-color: red;
  width: 140px;
  height: 25px;
  color: white;
  font-size: 16px;
}

.all_douct ul li:nth-child(1) a {
  color: red;
}

.all_douct ul li:nth-child(2) a {
  color: red;
}

.pohone_buy {
  /* border: 1px solid red; */
  margin-left: 250px;
  display: flex;
  flex-flow: row nowrap;
  align-items: center;
}

.pohone_buy div img {
  vertical-align: middle;
}

.pohone_buy span {
  font-size: 12px;
  margin-left: 10px;
}

.caidan {
  width: 1200px;
  margin: 0 auto;
  display: flex;
}

.caidan_liebiao {
  width: 180px;
  background-color: #B01D1D;
}

.caidan_liebiao ul a {
  color: white;
}

.caidan_liebiao ul li {
  padding: 5px 0px;
}

.li-1 span {
  display: inline-block;
  /* margin-right: 10px; */
  height: 24px;
  width: 30px;
  vertical-align: middle;
  background-image: url(../../../assets/image/nav1.png);
  background-repeat: no-repeat;
  background-position: 8px 2px;
}

.li-2 span {
  display: inline-block;
  /* margin-right: 10px; */
  height: 24px;
  width: 30px;
  vertical-align: middle;
  background-image: url(../../../assets/image/nav2.png);
  background-repeat: no-repeat;
  background-position: 8px 2px;
}

.li-3 span {
  display: inline-block;
  /* margin-right: 10px; */
  height: 24px;
  width: 30px;
  vertical-align: middle;
  background-image: url(../../../assets/image/nav3.png);
  background-repeat: no-repeat;
  background-position: 6px 2px;
}

.li-4 span {
  display: inline-block;
  /* margin-right: 10px; */
  height: 24px;
  width: 30px;
  vertical-align: middle;
  background-image: url(../../../assets/image/nav4.png);
  background-repeat: no-repeat;
  background-position: 6px 2px;
}

.li-5 span {
  display: inline-block;
  /* margin-right: 10px; */
  height: 24px;
  width: 30px;
  vertical-align: middle;
  background-image: url(../../../assets/image/nav5.png);
  background-repeat: no-repeat;
  background-position: 10px 2px;
}

.li-6 span {
  display: inline-block;
  /* margin-right: 10px; */
  height: 24px;
  width: 30px;
  vertical-align: middle;
  background-image: url(../../../assets/image/nav6.png);
  background-repeat: no-repeat;
  background-position: 6px 2px;
}

.li-7 span {
  display: inline-block;
  /* margin-right: 10px; */
  height: 24px;
  width: 30px;
  vertical-align: middle;
  background-image: url(../../../assets/image/nav7.png);
  background-repeat: no-repeat;
  background-position: 6px 2px;
}

.li-8 span {
  display: inline-block;
  /* margin-right: 10px; */
  height: 24px;
  width: 30px;
  vertical-align: middle;
  background-image: url(../../../assets/image/nav8.png);
  background-repeat: no-repeat;
  background-position: 6px 2px;
}

.li-9 span {
  display: inline-block;
  /* margin-right: 10px; */
  height: 24px;
  width: 30px;
  vertical-align: middle;
  background-image: url(../../../assets/image/nav9.png);
  background-repeat: no-repeat;
  background-position: 8px 2px;
}

.li-10 span {
  display: inline-block;
  /* margin-right: 10px; */
  height: 24px;
  width: 30px;
  vertical-align: middle;
  background-image: url(../../../assets/image/nav10.png);
  background-repeat: no-repeat;
  background-position: 5px 2px;
}

.caidan_liebiao .li .span1 {
  /* border: 1px solid red; */
  background-image: url(../../../assets/image/r_right.png);
  background-repeat: no-repeat;
  vertical-align: middle;
  background-size: 7.5px 14px;
  background-position: 20px 4px;
}
.caidan_tupian {
  width: 740px;
  height: 340px;
  margin-left: 10px;
  margin-top: 10px;
  overflow: hidden;
}
.swiper-wrapper,.swiper-container {
  width: 100%;
  height: 100%;
}

/deep/ .swiper-pagination-bullet-active {
  background: #fff!important;
}

.swiper-img {
  width: 100%;
}

.caidan_tupian {
  position: relative;
}

.caidan_tupian_yuandian {
  position: absolute;
  bottom: 20px;
  left: 350px;
}

.caidan_tupian_yuandian span {
  display: inline-block;
  width: 20px;
  height: 20px;
  background: rgb(219, 219, 219);
  border-radius: 50%;
  line-height: 20px;
  text-align: center;
}

.caidan_zixun_kuaixun {
  border: 1px solid rgb(219, 219, 219);
  margin: 0 20px;
}

.caidan_zixun_kuaixun h4 {
  display: inline-block;
}

.caidan_zixun_kuaixun ul li {
  margin: 2px;
}

.caidan_zixun_kuaixun ul li:nth-child(1) h4 {
  font-size: 15px;
}

.caidan_zixun_kuaixun ul li:nth-child(1) {
  border-bottom: 1px solid rgb(219, 219, 219);
}

.caidan_zixun_kuaixun_span2 {
  margin-left: 120px;
}

.caidan_zixun_kuaixun ul li div img {
  margin-top: 2px;
  width: 200px;
  height: 120px;
}

.hot {
  padding: 20px 0;
  width: 1200px;
  display: flex;
  flex-flow: nowrap row;
  justify-content: space-between;
}

.hot_first {
  width: 300px;
  border: 1px solid rgb(202, 199, 199);
  display: flex;
  flex-flow: nowrap column;
  justify-content: center;
  align-items: center;
}

.hot_first p:nth-of-type(1) {
  font-size: 18px;
  font-weight: bold;
}

.hot_first span:nth-of-type(1) {
  font-size: 18px;
  font-weight: bold;
  color: red;
}

.hot_first div span {
  padding: 0px 10px;
}

.hot1 {
  border: none;
}

.img {
  width: 1200px;
}

.first_F {
  padding: 10px 0;
  display: flex;
  flex-flow: column nowrap;
}

.first_F_jinkou_shengxian {
  display: flex;
  flex-flow: row nowrap;
  justify-content: space-between;
}

.first_F_jinkou_shengxian_title {
  display: flex;
  align-items: flex-start;
  vertical-align: middle;
  line-height: 38px;
  position: relative;
}

.first_F_jinkou_shengxian_title p {
  font-size: 15px;
  color: #FF4E00;
  margin-left: 50px;
}

.first_F_jinkou_shengxian ul {
  display: flex;
  flex-flow: row nowrap;
}

.first_F_jinkou_shengxian ul li {
  margin-right: 10px;
}

.first_F_jinkou_shengxian_xiangxi {
  display: flex;
  flex-flow: row nowrap;
  border-top: 2px solid red;
}

.first_F_jinkou_shengxian_xiangxi_img {
  display: flex;
  flex-flow: column nowrap;
}

.first_F_jinkou_shengxian_title span {
  position: absolute;
  left: 6px;
}

.first_F_jinkou_shengxian_xiangxi_img ul li {
  display: flex;
  flex-flow: row nowrap;
  border-bottom: 1px dashed gray;
  border-top: none;
  padding-top: 10px;
  background-color: #E4F7EC;
}

.first_F_jinkou_shengxian_xiangxi_img ul li a {
  margin-left: 20px;
}

.first_F_jinkou_shengxian_xiangxi_img_li {
  padding: 5px 0;
}

.first_F_jinkou_shengxian_xiangxi_shangpin {
  display: grid;
  /* border: 1px solid red; */
  grid-template-columns: 220px 220px 220px;
  grid-template-rows: 220px 220px;
  margin-left: 20px;
}

.first_F_jinkou_shengxian_xiangxi_shangpin_list {
  /* border: 1px solid red; */
  display: flex;
  flex-flow: nowrap column;
  justify-content: center;
  align-items: center;
  border-top: 1px solid rgb(177, 177, 177);
  border-right: 1px solid rgb(177, 177, 177);
}

.first_F_jinkou_shengxian_xiangxi_shangpin_rightimg {
  display: flex;
  flex-flow: column nowrap;
  margin-left: 30px;
}
</style>
