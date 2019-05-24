# Canon<!DOCTYPE html>
<html lang="KR" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link href="https://fonts.googleapis.com/css?family=Noto+Sans+KR" rel="stylesheet">
    <title></title>
    <style>
    body, h1 {margin: 0px;}
    #scene{height: 800px; overflow: hidden; background-size: cover;
    background-attachment: fixed; }
      .one{background-image: url(images/index_07.png);}
      .two{background-image: url(images/index_08.png);}
      .three{background-image: url(images/index_09.png);}
      #scene h1{position: relative; left: 50%; top: 50%; transform: translateX(-50%) translateY(-50%); text-align: center;}
/*--푸터적용--*/
footer{
  height: 100px; background-color: rgba(0, 0, 0,0.2);}
.footer{position: relative; left: 50%; top: 50%; transform: translateX(-50%) translateY(-50%);
   text-align: center; font-family: 'Noto Sans KR', sans-serif;
 font-size: 0.9rem; font-weight: 100; color: gray;}

 /*--네비게이션 처리--*/
.wrap{
  position: fixed;
  display: block;
  border: 0px solid red;
  height: 100px;
  width: 100%;
  background-color: white;
  z-index: 10;
}
.logo{
  border: 0px solid blue;
  display: inline-block;
  margin-left: 240px;
}
.nav{border: 0px solid green; position:fixed; right: 240px; top: 35px; display:inline-block;
      font-family: 'Noto Sans KR', sans-serif;
  font-size: 0.9rem; font-weight: 600; color: gray;}

    .space{margin-left: 3rem}
    a,a:link :visited :active {text-decoration: none; color: gray;}

    a:hover{color: red; }

    </style>
  </head>
  <body>
    <nav class="wrap">
      <div class="logo">
        <a href="index.html"><img src="images/index_02.png">
      </div>
      <div class="nav">
       <a href="p01.html">EF-S 35mm F2.8 Macro IS STM</a><span class="space"></span>
       <a href="p02.html">EF-S 18-55mm F4-5.6 IS STM</a><span class="space"></span>
       <a href="p03.html">EF 70-300mm F4-5.6 IS II USM</a>
      </div>
    </nav>
    <section id="scene" class="one">
<h1><img src="images/t01.png"></h1>
    </section>
    <section id="scene" class="two">
      <h1><img src="images/t01.png"></h1></section>
    <section id="scene" class="three">
    <h1><img src="images/t01.png"></h1></section>
    <footer><div class="footer">Copyright 2019 Canon korean Consumer Imaging. ALL right reserved. </div>
    </footer>
  </body>
</html>
