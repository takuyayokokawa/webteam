<template>
  <article>
    <div class="all">

      <Logo />

    <div class="backgrounds">
      <div class="section1">
          <h1 class="name">Schedule</h1>
      </div>
      <div class="section2">
          <img  class="code" src="~/assets/images/web/Schedule.jpg">
      </div>
      <h1 class="name2">Schedule</h1>
    </div>

    <div class="contents">
        <div class="first">
            <h2>活動スケジュール</h2>
            <p>ここでは新規がチームに配属されてからのWebチームの一年間の活動についてざっくり紹介します。</p>
        </div>

        <div class="second">
            <h2>6~8月</h2>
            <p>Webチームの仕事は何と言っても公式サイトの制作です。その制作が始まる9月頃まではひたすらプログラミングについて勉強していきます。</p>
            <p>プログラミングの勉強にはオンラインのプログラミング学習サービスであるProgateを利用します。</p>
            <p>配属からしばらくは地道な勉強が続きます。でも活動が退屈にならないように皆でzoomで通話をしながら作業したり、練習用のサイトを作成してみたりする予定です！</p>
            <p>こんな状況じゃなかったらレクも沢山行う予定でした…。自粛明けに沢山遊びます。</p>
        </div>

        <div class="third">
            <h2>9~11月</h2>
            <p>秋頃からはいよいよ公式サイトの制作が始まります！</p>
            <p>既存はもちろん、新規も制作に携わります！</p>
            <p>直前期は皆で集まって分からないところを教え合いながら制作を行います。どのチームにも当てはまることだけど、直前期は忙しいけどチームの皆と関わる時間が増えて自然と中が深まります。大変だったけど凄く良い思い出。</p>
            <p>Webチームは早稲田祭当日までには仕事をほとんど終えます。なので当日は他の部署の手伝いをすることが多いです！警備とか案内とか！</p>
            <p></p>
        </div>

        <div class="forth">
            <h2>11~1月</h2>
            <p>早稲田祭が終わった後は引継ぎの時期です。</p>
            <p>既存はチームを引退し、新規だけでの活動が始まります。わくわく。</p>
            <p>早稲田祭後は打ち上げがたくさん！もちろんWebチームでも行います！感動の解散。</p>
        </div>

        <div class="fifth">
            <h2>2~4月</h2>
            <p>2月ごろから新歓の準備が始まります。</p>
            <p>Webチームは運営スタッフの新歓特設サイトの制作を行っていきます。Webチームの新規だけで作るWebサイトになります。大変だったけど今年も何とか作り上げた。</p>
            <p>新歓サイトが完成したあとも度々更新作業を行います。</p>
        </div>

        <div class="footer">
            <h1　class="last">20Webteam</h1>
        </div>

    </div>

    
    
    
    </div>
  </article>
</template>

<script>
  import Logo from '~/components/Logo'
  import footer from '~/components/footer'
  export default{
    components: {Logo,
    footer
    }
  }

</script>

<style>
  * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
          font-family: "游ゴシック体", "Yu Gothic", YuGothic, "ヒラギノ角ゴ Pro", "Hiragino Kaku Gothic Pro", "メイリオ", "Meiryo", "sans-serif";
      }

      .backgrounds{
          width: 100%;
          height: 500px;
          display: flex; 
      }
      
      .section1{
          width: 32.5%;
          height: auto;
          background-color: #F7EF99;
          display: flex;
          justify-content: center;
          align-items: center;
      }

      .section2{
          width: 67.5%;
          height: auto;
          background-color: #ADCAD6;
          display: flex;
          justify-content: center;
          align-items: center;

      }

      .name{
          font-size: 45px;
      }

      .name2{
          display: none;
      }

      .code{
          position: relative;
          width: 70%;
          height: auto;
          
      }

      .contents{
          width: 100%;
          height: auto;
          background-color: #F8F4E3;
          font-family: "游ゴシック";
          text-align: left;
          font-size: 15px;
          font-style: normal;
          padding-top: 100px;
      }

      .first{
          position: relative;
          width: 80%;
          height: auto;
          margin: 0 auto;
          text-align: left;

      }

      .second{
          position: relative;
          width: 80%;
          height: auto;
          margin: 0 auto;
          margin-top: 100px;
          text-align: left;
          
      }

      .site{
          width: 60%;
          height: auto;
      }

      .third{
          position: relative;
          width: 80%;
          height: auto;
          margin: 0 auto;
          margin-top: 100px;
      }

      .forth{
          position: relative;
          width: 80%;
          height: auto;
          margin: 0 auto;
          margin-top: 100px;
      }

      .fifth{
          position: relative;
          width: 80%;
          height: auto;
          margin: 0 auto;
          margin-top: 100px;

      }

      .progate{
          color: black;
          font-size: 25px;
      }
    

      .footer{
          width: 100%;
          height: 200px;
          text-align: center;
          background-color:#F7EF99;
          margin-top: 200px;
          display: flex;
          justify-content: center;
          align-items: center;
      }

      .last{
          font-size: 40px;
          color: black;
      }




      

      .links{
        position:absolute;
        display: flex;
        left: 55%;
        top: 70%;
      }

      .About,.Schedule,.Member{
        width: auto;
        height: auto;
        border: solid;
        padding: 2px 8px;
        margin:20px 20px ;
        font-size: 30px;
        text-align: center;
      }

      @media screen and (max-width: 800px){
        .links{
          left: 35%;
        }
      }

      @media screen and (max-width: 500px) {
        .name{
            display: none;


        }

        .name2{
          display: unset;
          position: absolute;
  top: 50%; /*親要素を起点に上から50%*/
  left: 50%;  /*親要素を起点に左から50%*/
  transform: translateY(-50%) translateX(-50%); /*要素の大きさの半分ずつを戻す*/
  -webkit-transform: translateY(-50%) translateX(-50%);
          font-size: 45px;
        }

        .code{
            display: none;
        }
        
      }
</style>