<template>
  <div class="home">
    <section>
      <div id="top-wrapper">
        <p>ようこそ</p>
      </div>
    </section>

    <section>
      <div id="about-wrapper">
        このサイトについて
      </div>
    </section>

    <section>
      <div id="profile-wrapper">
        初めてプログラミングに触れたのが、小学生の頃でした。
      </div>
    </section>

    <section>
      <div id="works-wrapper">
        改装中カード式モーダル表示
      </div>
    </section>

    <section>
      <div id="skill-wrapper">
        学んだことがあるものを含め自分の見解で数値化したグラフを用意
      </div>
    </section>

    <section>
      <div id="history-wrapper">
        2012年初めてHTMLに触れる
      </div>
    </section>

    <section>
      <div id="contact-wrapper">

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
  .section {
    min-height: 100vh;
    width: 100%;
  }
  div#top-wrapper{
    background: #e3f6f5;
    height: calc(100vh - 60px);
  }
</style>
