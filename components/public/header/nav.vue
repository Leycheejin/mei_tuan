<template>
  <div class="m-nav">
    <ul class="nav">
      <li class="list">
        <nuxt-link to="/order">我的美团</nuxt-link>
        <dl>
          <dd><nuxt-link to="./order">我的订单</nuxt-link></dd>
          <dd><nuxt-link to="./order">我的收藏</nuxt-link></dd>
          <dd><nuxt-link to="./order">抵用券</nuxt-link></dd>
          <dd><nuxt-link to="./order">账户设置</nuxt-link></dd>
        </dl>
      </li>
      <li>
        <nuxt-link to="/order">手机APP</nuxt-link>
      </li>
      <li class="list bd">
        <nuxt-link to="/order">商家中心</nuxt-link>
        <dl>
          <dd><nuxt-link to="./order">登录商家中心</nuxt-link></dd>
          <dd><nuxt-link to="./order">美团智能收银</nuxt-link></dd>
          <dd><nuxt-link to="./order">我想合作</nuxt-link></dd>
          <dd><nuxt-link to="./order">手机免费开店</nuxt-link></dd>
          <dd><nuxt-link to="./order">餐饮代理商招募</nuxt-link></dd>
          <dd><nuxt-link to="./order">商家申请开票</nuxt-link></dd>
          <dd><nuxt-link to="./order">免费合作美团排队</nuxt-link></dd>
        </dl>
      </li>
      <li class="list meituan-rules">
        <nuxt-link to="/order">美团规则</nuxt-link>
        <dl>
          <dd><nuxt-link to="./order">规则中心</nuxt-link></dd>
          <dd><nuxt-link to="./order">规则目录</nuxt-link></dd>
          <dd><nuxt-link to="./order">规则评议院</nuxt-link></dd>
        </dl>
      </li>
      <li class="list site">
        <nuxt-link to="/order">网站导航</nuxt-link>
        <ul class="subContainer">
          <li class="hotel">
            <h5>酒店旅游</h5>
            <div class="wrapper">
              <dl>
                <dd>国际机票</dd>
                <dd>国际机票</dd>
                <dd>国际机票</dd>
                <dd>国际机票</dd>
                <dd>国际机票</dd>
              </dl>
              <dl>
                <dd>火车票</dd>
                <dd>火车票</dd>
                <dd>火车票</dd>
                <dd>火车票</dd>
              </dl>
              <dl>
                <dd>樟果民宿</dd>
                <dd>樟果民宿</dd>
                <dd>樟果民宿</dd>
                <dd>樟果民宿</dd>
              </dl>
            </div>
          </li>
          <li class="food">
            <h5>吃美食</h5>
            <div class="wrapper">
              <dl>
                <dd>烤鱼</dd>
                <dd>烤鱼</dd>
                <dd>烤鱼</dd>
              </dl>
              <dl>
                <dd>特色美食</dd>
                <dd>特色美食</dd>
                <dd>特色美食</dd>
                <dd>特色美食</dd>
              </dl>
            </div>
          </li>
          <li class="movie">
            <h5>看电影</h5>
            <div class="wrapper">
              <dl>
                <dd>热映电影</dd>
                <dd>热映电影</dd>
                <dd>热映电影</dd>
                <dd>热映电影</dd>
                <dd>热映电影</dd>
              </dl>
            </div>
          </li>
          <li class="app">
            <h5>手机应用</h5>
            <div class="wrapper">
              <dl>
                <dd>
                  <a href="#">
                    <img
                      src="//s0.meituan.net/bs/fe-web-meituan/2d53095/img/appicons/meituan.png"
                      title="美团app"
                      alt="美团app"
                    />
                  </a>
                </dd>
                <dd>
                  <a href="#">
                    <img
                      src="//s1.meituan.net/bs/fe-web-meituan/404d350/img/appicons/waimai.png"
                      title="外卖app"
                      alt="外卖app"
                    />
                  </a>
                </dd>
                <dd>
                  <a href="#">
                    <img
                      src="//s0.meituan.net/bs/fe-web-meituan/404d350/img/appicons/zhenguo.png"
                      title="榛果app"
                      alt="榛果app"
                    />
                  </a>
                </dd>
                <dd>
                  <a href="#">
                    <img
                      src="//s1.meituan.net/bs/fe-web-meituan/404d350/img/appicons/dianping.png"
                      title="点评app"
                      alt="点评app"
                    />
                  </a>
                </dd>
                <dd>
                  <a href="#">
                    <img
                      src="//s1.meituan.net/bs/fe-web-meituan/404d350/img/appicons/maoyan.png"
                      title="猫眼app"
                      alt="猫眼app"
                    />
                  </a>
                </dd>
              </dl>
            </div>
          </li>
        </ul>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Nav'
}
</script>

<style lang="scss" scoped></style>
