<template>
  <article>
    <div class="all">

      <Logo />

    <div class="backgrounds">
      <div class="section1">
          <h1 class="name">About</h1>
      </div>
      <div class="section2">
          <img  class="code" src="~/assets/images/web/About.jpg">
      </div>
      <h1 class="name2">About</h1>
    </div>

    <div class="contents">
        <div class="first">
            <h2>Webチームとは</h2>
            <p>Webチームは広報制作局に所属していて、既存7名・新規5名(予定)で活動していきます!</p>
            <p>早稲田祭運営スタッフにおいて私たちWebチームが担う仕事は外部向けのWebサイトの制作・管理となっています。
            </p>
        </div>

        <div class="second">
            <h3>▼早稲田祭2019公式サイト</h3>
            <a target="_blank" href="https://www.wasedasai.net/"><img class="site" src="~assets/images/web/19official.png"></a>
            </br>
            </br>
            </br>
            </br>
            <h3>▼早稲田祭2020運営スタッフ新歓特設サイト</h3>
            <a target="_blank" href="https://unstashinkan2020.github.io/home/"><img class="site" src="~assets/images/web/20shinkan.png"></a>
        </div>

        <div class="third">
            <p>これらのWebサイトは全てWebチームで一から作成しています</p>
            <p>Webサイトの作成には様々なソフトを使います。</p>
            </br>
            </br>
            <h3>▼VScode</h3>
            <img class="site" src="~/assets/images/web/19code.png">
            <p>このソフトを使ってWebサイトのコードを編集します。何だかかっこいいよね。</p>
            </br>
            </br>
            <h3>▼Adobe XD</h3>
            <img class="site" src="~/assets/images/web/XD.png">
            <p>Adobe XDはWebサイトのデザインを行うソフトです。コードを書く前には必ずデザイン！</p>
        </div>

        <div class="forth">
            <p>そもそもWebサイトを作るにはプログラミングを習得する必要があります。</p>
            <p>Webチームではプログラミングのオンライン学習サービスであるProgateを利用してプログラミングを学習しています。</p>
            <p>無料会員でもプログラミングの基礎が学べるので気になる方は是非。</p>
            </br>
            <h3>▼Progate</h3>
            <a class="progate" target="_blank" href="https://prog-8.com/"><img　class="site" src="~assets/images/web/Progate.png"></a>
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
  export default{
    components: {Logo
    }
  }

</script>

<style>
  * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
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
          background-color: #F56960;
          display: flex;
          justify-content: center;
          align-items: center;

      }

      .name{
          font-family: Bahnschrift;
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
          text-align: center;
          font-size: 15px;
          font-style: normal;
      }

      .first{
          position: relative;
          width: 80%;
          height: auto;
          top: 100px;
          margin: 0 auto;

      }

      .second{
          position: relative;
          width: 80%;
          height: auto;
          top: 100px;
          margin: 0 auto;
          margin-top: 100px;
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
          margin-top: 150px;
      }

      .forth{
          position: relative;
          width: 80%;
          height: auto;
          margin: 0 auto;
          margin-top: 150px;
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
          position: relative;
          font-size: 40px;
          color: black;
          font-family: Bahnschrift;
      }

      h3{
         font-size: 20px; 

      }




      

      .links{
        position:absolute;
        display: flex;
        left: 55%;
        top: 70%;
        font-family: Bahnschrift;
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
          display:unset;
          position: absolute;
          top: 50%; /*親要素を起点に上から50%*/
          left: 50%;  /*親要素を起点に左から50%*/
          transform: translateY(-50%) translateX(-50%); /*要素の大きさの半分ずつを戻す*/
          -webkit-transform: translateY(-50%) translateX(-50%);
          font-family: Bahnschrift;
          font-size: 45px;
        }

        .code{
            display: none;
        }
        
      }
</style>
