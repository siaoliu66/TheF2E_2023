<script setup>
import topmenu from './components/menu.vue'
import footermenu from './components/footer.vue'
</script>

<template>
  <topmenu />
  <div class="container">
    <div class="banner" id="banner">
      <img src="./assets/img/banner.png" alt="" class="bgcenter">
      <div class="text-left">
        <img src="./assets/img/text.png" alt="">
        <img src="./assets/img/text2.png" alt="">
      </div>
      <div class="text-right">
        <img src="./assets/img/text3.png" alt="">
      </div>
      <div class="poicey_box">
        <p class="policy_text"><span style="font-size:22px">為毛孩子謀福利！</span><br>推動寵物醫療保障方案</p>
        <a href="javascript:;" class="arrowed">
          <div class="arrow-5"></div>
        </a> 
      </div>
    </div>
    <div class="candidate" id="candidate"></div>
    <div class="news" id="news"></div>
    <div class="policy" id="Policy"></div>
    <div class="donate" id="Donate"></div>
    <div class="sevices" id="Sevices"></div>
  </div>
  <footermenu />
</template>


