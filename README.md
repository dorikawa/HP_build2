# HP_build2

<html>
<head>

<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=EmulateIE10" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<!--ここから上はお決まりの定型文です-->


<!--ここからが表現の書式などを決めるcssという部分-->

<style type="text/css">
 p {
color: #808080;
font-size: 1.5em;
 }
 

 .red {color:#ff0000;}
 .grey {color:#ffffff; background:#999999;}
 .snow {color:#fffafa;}
 .yellow {color:#ff0000; background:#ffff00;}
 .blue {color:#0000ff;}
 .white {color:#ffffff; blinking;}
 .waku {border:2px dotted #99cc66;
　　　　　　line-height: 200%;
　　　　　　padding: 10px;}

 
 main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}
 

/* 点滅 */
.blinking{
	-webkit-animation:blink 1.5s ease-in-out infinite alternate;
    -moz-animation:blink 1.5s ease-in-out infinite alternate;
    animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
    0% {opacity:0;}
    100% {opacity:1;}
}
@-moz-keyframes blink{
    0% {opacity:0;}
    100% {opacity:1;}
}
@keyframes blink{
    0% {opacity:0;}
    100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ*/
	
/*背景を指定する部分*/
body::before {
  content:"";
  display:block;
  position:fixed;
  top:0;
  left:0;
  z-index:-1;
  width:100%;
  height:100vh;
  background:url(https://torokoid.github.io/20210704_Utsunomiya_swim/20210704_002.JPG) center/cover no-repeat; /*fixedをトル！*/
  -webkit-background-size:cover;/*Android4*/
  }
  
a.p:hover {
    position: relative;
    text-decoration: none;
}
a.p span {
    display: none;
    position: relative;
    top: -0.5em;
    left: 2em;
}
a.p:hover span {
    border: none;
    display: block;
    width: 800px;
}   
 

@media	screen and (min-width: 540px),
	screen and (orientation: landscape) {
   p.note { display: none; }
}

</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">

</head>

<body>


<p class="note">
  モバイル端末をお使いの場合は、画面を横向きにすると
  より見やすくご覧頂けます。
</p>

<!--ここ上は、ほぼそのまま使います！-->


<!--QRコードの挿入例-->
<p align="left"> <img src="qr2.png" alt="アクセス用QRコード" width="100">アクセス用QRコード</p>
<p align="right"><marquee direction="left" scrollamount="20" width="30%">(^_^)/~hada</marquee></p>

<!--流れ文字の挿入例-->
<h1><span class="yellow"><marquee behavior="alternate">!!! GithubでHPを作ろう !!!</marquee></span></h1>


<!--ここから下が、本体部分-->
<div style="background-color:rgba(128,255,255,0.8)"> 
<p>HPの作り方を簡単に説明します。<br>HPというのは大まかにいうと以下の２つの事で出来ています。<br>１，インターネットにつながったサーバー<br>
２，サーバー内に記載したHTMLソースコード<br>では、この二つを説明していきます。</p>

<br><p>インターネットにつながったサーバーを立ち上げるのは費用面で事業というレベルになってしまうので、個人ではやりません。<br>幸いGithubという会社がサーバーを無料で使わせてくれています。<br>なぜ無料かというと、この会社はソフトウエア開発者に共同開発の場を提供することが本業で、インターネットサーバーの提供はそのおまけだからです。<br>一般庶民はそのおまけをありがたく使わせてもらうことにします。<br>ほかの手としてはniftyなどのプロバイダーがHP作成ツールを提供してくれたりしていますが、お決まりの書式に当てはめるだけであまり自由度はありません。</p>

    </div> 

<div style="background-color:rgba(255,255,0,0.6)"> 
<p>では、１，のサーバーの確保です。<br>以下のリンクに飛んでGithubのアカウントを作りますが、ドリームかわちメンバーの皆様はこのアカウントをお使いいただいてもかまいません。<br>リンク先のSign inでユーザー：dorikawa, パスワード：doridori2021, で入れます。</p>
<p><a href="https://github.com/">Githubリンクhttps://github.com/</a><br>すでにアカウントをお持ちの場合は、ご自分のアカウントに飛ぶようです。</p>

	</div>
  
<br><br><p>１，の続きですが、Githubのアカウント内にリポジトリ（≒HP）を作ります。</p>
<p><h2>では、新しいリポジトリを作ってみましょう。<br>
以下のようにクリックして、</h2></p>
<a href="https://dorikawa.github.io/HP_build/20210709_006.png" data-lightbox="abc"><img src="https://dorikawa.github.io/HP_build/20210709_006.png" alt="サンプル画像" width="900" /></a>
<p><h2>リポジトリの名前を適当に決めて入力、<br>
下の二箇所にチェックを入れます。最後に一番下の緑のボタンを押して作成完了です。</h2></p>
<a href="https://dorikawa.github.io/HP_build/20210709_002.png" data-lightbox="abc"><img src="https://dorikawa.github.io/HP_build/20210709_002.png" alt="サンプル画像" width="900" /></a>











<br><br><p>おまけ、背景原画</p>
<a href="https://dorikawa.github.io/HP_build/20210704_002.JPG" data-lightbox="abc"><img src="https://dorikawa.github.io/HP_build/20210704_002.JPG" alt="サンプル画像" width="560" /></a>
<br><br><p>おまけ、豆知識、IT関連情報</p>
<h2><a href="https://dorikawa.github.io/HP_build/" target="_blank" rel="noopener noreferrer">QRコードの作り方などIT関連情報へのリンクが新規タブで開きます。</a></h2>
<br><br><p>おまけ、2019年市民大会反省会、暑気払い飲み会</p>
<h2><a href="https://peyng.github.io/dream/" target="_blank" rel="noopener noreferrer">反省会の終盤にお隣の火事で追い出された、いわく付きの記録。</a></h2>

<br><br><br><p>さらにおまけ、瀧田先生の「森のくるまやさん」</p>
<h2><a href="https://tsunakawa-konpou.com/archives/391" target="_blank" rel="noopener noreferrer">手作り感満載のクルマの木製模型、￥300です。</a></h2>

<!--本体はここまで-->


<!--画面に空白地帯を作って、背景が見えるようにしています-->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>



<!-- フッタ -->
<footer>
Copyright 2021/07/15 S.Hada
</footer>

<!--HPにさまざまなJavaScriptを呼び込むための書式-->
<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script>



</body>

</html>
