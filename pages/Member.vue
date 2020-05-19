<template>
  <article>
    <div class="all">

      <Logo />

    <div class="backgrounds">
      <div class="section1">
          <h1 class="name">Member</h1>
      </div>
      <div class="section2">
          <img  class="code" src="~/assets/images/web/Member.jpg">
      </div>
      <h1 class="name2">Member</h1>
    </div>

    <div class="contents">
        <div class="first">
            <h2>▼メンバー紹介のサイトです。新規のみんなにもこんなもの作ってもらう予定！</h2>
            </br>
            </br>
            <a href="https://unstashinkan2020.github.io/syokai/">https://unstashinkan2020.github.io/syokai/</a>
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
          background-color: #F7C7DB;
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
          text-align: center;
      }

      a{
        font-size:20px ;
        color: black;

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