<template>
     <div class="footer">
      <!-- 品质保障，私人定制等-->
<div id="foot_box">
  <div class="icon1 lf">
    <img :src="`${imgBUI}img/footer/icon1.png`" alt="" />

    <h3>品质保障</h3>
  </div>
  <div class="icon2 lf">
    <img :src="`${imgBUI}img/footer/icon2.png`" alt="" />

    <h3>私人定制</h3>
  </div>
  <div class="icon3 lf">
    <img :src="`${imgBUI}img/footer/icon3.png`" alt="" />

    <h3>学员特供</h3>
  </div>
  <div class="icon4 lf">
    <img :src="`${imgBUI}img/footer/icon4.png`" alt="" />

    <h3>专属特权</h3>
  </div>
</div>
<!-- 页面底部-->
<div class="foot_bj">
  <div id="foot">
    <div class="lf">
      <p class="footer1">
        <img
          :src="`${imgBUI}img/footer/logo.png`"
          alt=""
          class="footLogo"
        />
      </p>
      <p class="footer2">
        <img
          :src="`${imgBUI}img/footer/footerFont.png`"
          alt=""
        />
      </p>
    </div>
    <div class="foot_left lf">
      <ul>
        <li>
          <a href="#"><h3>买家帮助</h3></a>
        </li>
        <li><a href="#">新手指南</a></li>
        <li><a href="#">服务保障</a></li>
        <li><a href="#">常见问题</a></li>
      </ul>
      <ul>
        <li>
          <a href="#"><h3>商家帮助</h3></a>
        </li>
        <li><a href="#">商家入驻</a></li>
        <li><a href="#">商家后台</a></li>
      </ul>
      <ul>
        <li>
          <a href="#"><h3>关于我们</h3></a>
        </li>
        <li><a href="#">关于阿甲</a></li>
        <li><a href="#">联系我们</a></li>
        <li>
          <img :src="`${imgBUI}img/footer/wechat.png`" alt="" />
          <img
            :src="`${imgBUI}img/footer/sinablog.png`"
            alt=""
          />
        </li>
      </ul>
    </div>
    <div class="service">
      <p>阿甲商城客户端</p>
      <img :src="`${imgBUI}img/footer/ios.png`" class="lf" />
      <img
        :src="`${imgBUI}img/footer/android.png`"
        alt=""
        class="lf"
      />
    </div>
    <div class="download">
      <img :src="`${imgBUI}img/footer/erweima.png`" />
    </div>
    <!-- 页面底部-备案号 #footer -->
    <div class="record">
      &copy;2017 阿甲集团有限公司 版权所有 京ICP证09002163号
    </div>
  </div>
</div>

    </div>
</template>

<script>
import { mapState } from 'vuex'
    export default {
        computed:{
            ...mapState(['imgBUI'])
        }
    }
</script>

<style lang="scss" scoped>

</style>