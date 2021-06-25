<template>
  <div class="home">
    <section class="section_top">
      <div class="top-wrapper">
        <h1 class="top_title">
          Shimamu<br>
          Library
        </h1>
        <div class="palette_wrapper">
          <div class="palette">
            <div class="palette_whole">

            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section_about">
      <div class="about-wrapper">
        <h1 class="about_title">このサイトについて</h1>
        <p>Takuyaのポートフォリオサイトです。<br>
        少しでも参考になればと思い作りました。<br>
        最後までお楽しみください。</p>
      </div>
    </section>

    <section class="section_profile">
      <div class="profile-wrapper">
        幼い頃から千葉県で育ちました。<br>
        初めてプログラミングに触れたのが、小学生の頃。<br>
        たまたま遊んでいた大学生の方からHTMLと軽いCSSを学びました。<br>
        そこから学業の傍ら趣味として、Wordpressなど触れ、
        プログラミングを更に学びたいと思いました。
      </div>
    </section>

    <!-- <section>
      <div id="works-wrapper">
        改装中カード式モーダル表示
      </div>
    </section> -->

    <section class="section_skill">
      <div class="skill-wrapper">
        学んだことがあるものを含め自分の見解で数値化したグラフを用意
      </div>
    </section>

    <section class="section_history">
      <div class="history-wrapper">
        2012年初めてHTMLに触れる
      </div>
    </section>

    <section class="section_contact">
      <div class="contact-wrapper">
        興味持っていただいた方など、何かありましたら連絡お願いします。
        <form></form>
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  
}
</script>

<style lang="scss" scoped>
  section {
    min-height: 100vh;
    width: 100%;
  }
  .top-wrapper{
    background: #e3f6f5;
    height: calc(100vh - 60px);
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }
  .top_title{
    font-size: 50px;
    // color: ;
  }
  .palette{
    border-radius: 90% 10% 80% 20% / 41% 6% 95% 59% ;
    width: 300px;
    height: 300px;
    background-color: #faae66;
    position: relative;
  }
  .palette_whole{
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #e3f6f5;
    position: absolute;
    bottom: 20px;
    left: 70px;
  }
  .about-wrapper{
    background: #fffffe;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
  }
  .profile-wrapper{
    background: #e3f6f5;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
  }
  .works-wrapper {
    background: #fffffe;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
  }
  .skill-wrapper {
    background: #e3f6f5;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
  }
  .history-wrapper {
    background: #fffffe;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
  }
  .contact-wrapper {
    background: #e3f6f5;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
  }
</style>
