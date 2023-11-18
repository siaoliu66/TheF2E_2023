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
    <div class="sevices" id="Sevices">
      <div class="div">
        <div class="text">
        <p class="title">
        您的聲音, 我們的行動!
      </p>
      <p class="content">
        親愛的鄉親，每一位市民的意見都是我們社區前進的原動力。無論大小事，我都誠摯希望聽到您的建議。分享您的想法，一同為我們的未來
      <br/>打造更美好！
      </p>
      </div>
      <div class="form">
        <div class="form_wrap">
          <label for="name">您的姓名</label>
          <input type="text" name="name" id="name">
        </div>  
        <div class="form_wrap">
          <label for="name">您的Email</label>
          <input type="text" name="mail" id="mail" placeholder="Email及手機可擇一填寫">
        </div>
        <div class="form_wrap">
          <label for="name">您的手機</label>
          <input type="text" name="phone" id="phone" placeholder="Email及手機可擇一填寫">
        </div>
        <div class="form_wrap feedback">
          <label for="name">您的建言</label>
          <textarea name="feedback" id="feedback" cols="30" rows="10" placeholder="請填寫1000字內文字..."></textarea>
        </div>  
        <input type="submit" value="送出意見" class="send">
      </div>
      </div>
      
      
    </div>
  </div>
  <footermenu />
</template>


