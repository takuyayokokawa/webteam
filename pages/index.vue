<template>
  <article>
    <div class="all">

      <Logo />

    <div class="backgrounds">
      <div class="section1">
      </div>
      <div class="section2">
      </div>

      <h1 class="name">Publicity and Creation</br>Web team</br></h1>

      <div class="links">
        <div class="About">
          <a href="/about"><p>About</p></a>
        </div>
        <div class="Schedule">
          <a href="/Schedule"><p>Schedule</p></a>
        </div>
        <div class="Member">
          <a href="/Member"><p>Member</p></a>
        </div>
      </div>
    </div>

    

    </div>
  </article>
</template>

<script>
  import Logo from '~/components/Logo'
  export default{
    components: Logo
  }

</script>

<style>
  * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
          font-family: "游ゴシック体", "Yu Gothic", YuGothic, "ヒラギノ角ゴ Pro", "Hiragino Kaku Gothic Pro", "メイリオ", "Meiryo", "sans-serif";
      }

      a{
        text-decoration: none;
        color: black;
      }

      .backgrounds{
          width: 100%;
          height: 100vh;
          display: flex; 
      }
      
      .section1{
          width: 32.5%;
          height: auto;
          background-color: #F7EF99;
      }

      .section2{
          width: 67.5%;
          height: auto;
          background-color: #ABE188;
      }

      .name{
          position: absolute;
          font-size: 45px;
          top: 30%;
          left: 12%;
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
        .links{
           display: block;
           left: 45%;
        } 

        .About,.Schedule,.Member{
        width: auto;
        height: auto;
        border: solid;
        padding: 2px 8px;
        margin:20px 20px ;
        font-size: 25px;
        text-align: center;
      }
        
      }
</style>
