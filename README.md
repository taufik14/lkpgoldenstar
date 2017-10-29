<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Untitled Document</title>
<style>
  @charset "utf-8";
#pembungkus{
	width:960px;
	height:auto;
	margin:auto;

}
body{
	background-image:url(ground-back-background-images-music.jpg);
	background-repeat:no-repeat;
}
#judul{
	color:#FFF;
	text-align:center;
	margin-bottom:80px;
	margin-top:50px;
	text-shadow:4px 4px 11px #00F;

}


#or{
	color:#FFF;
	float:left;
	margin-top:100px;
	text-shadow: 0px 0px 8px #F0F;
}

#box{
	width:300px;;
	height:300px;
	border:10px;
	float:left;
	margin-left:90px;
	margin-right:30px;
	transition: .3s;
	animation-name:putar;
	animation-duration: 3s;
	animation-iteration-count:1;
	animation-play-state:paused;
	opacity:.83;
	
}


@keyframes putar{
	0%{transform:rotateZ(0deg);}
	100%{transform:rotateZ(360deg);}
}

#kotak{
	width:320px;;
	height:250px;
	border:10px;
	float:left;
	margin-left:90px;
	margin-right:30px;
	position:relative;
	right:110px;
	bottom:295px;
	z-index:-3;
	
}
#kotak1{
	width:320px;;
	height:250px;
	border:10px;
	float:left;
	margin-left:90px;
	margin-right:30px;
	position:relative;
	right:110px;
	bottom:295px;
	z-index:-3;
	
}
#box1{
	width:300px;
	height:300px;
	background-image:linear-gradient(#4848FF, #FFF);
	border-radius:160px;
	border:10px solid #F00;
	box-shadow:0px 0px 8px #000;
	transform:rotateZ(45deg);
	transition: .5s;
	position:relative;
	right:10px;
	bottom:10px;
	
	
}
#box1 p{
  text-align:left;
  box-sizing: border-box;
  font-size: 20px;
  transform: rotate(-45deg);
  color:#FFF;
  text-shadow:4px 4px 11px #F00;
}
#box1 img{
	margin-left:83px;
}
#box1 button{
	margin-left:133px;
	background-color:#00F;
	color:#FFF;
	box-shadow:0px 0px 11px #F00;
}
#box:hover #box1{
  border-radius: 0;
}
#box:hover #kotak{
	  border-right:10px solid #00F;
	  border-left:10px solid #00F;
}
#box:hover{
  border: 10px solid #00F;
  animation-play-state:running;
  background-color:#F00;
  
}
#box2{
	width:300px;;
	height:300px;
	border:10px;
	float:left;
	margin-left:30px;
	margin-right:60px;
	transition: .3s;
	animation-name:mutar;
	animation-duration: 3s;
	animation-iteration-count:1;
	animation-play-state:paused;
	opacity:.83;
}

@keyframes mutar{
	0%{transform:rotateZ(0deg);}
	100%{transform:rotateZ(360deg);}
}

#box4{
	width:300px;
	height:300px;
	background-image:linear-gradient(#F00, #FFF);
	border-radius:160px;
	border:10px solid #00F;
	box-shadow:0px 0px 8px #000;
	transform:rotateZ(45deg);
	transition: .5s;
	position:relative;
	right:10px;
	bottom:10px;
	
}
#box4 p{
  text-align:left;
  box-sizing: border-box;
  font-size: 20px;
  transform: rotate(-45deg);
  color:#FFF;
  text-shadow:4px 4px 11px #00F;
}
#box4 img{
	margin-left:83px;
}
#box4 button{
	margin-left:133px;
	background-color:#F00;
	color:#FFF;
	box-shadow:0px 0px 11px #00F;
}

#box2:hover #box4{
  border-radius: 0;
}
#box2:hover #kotak1{
	  border-right:10px solid #F00;
	  border-left:10px solid #F00;
}
#box2:hover{
	animation-play-state:running;
	 border: 10px solid #F00;
	 background-color:#00F;
  
}
</style>
</head>

<body>

<div id="pembungkus" align="center">
<div id="judul">
<h1 class="tracking-in-expand">SELAMAT DATANG DI WEBSITE GOLDEN STAR</h1>
Silahkan Pilih Website Di Bawah ini
</div>
<div id="box">
<div id="box1"><br><p align="left">LKP GOLDEN STAR<p><br><img src="FB_IMG_1431860143726.png" width="173" height="136"><br>
<button>Kunjungi</button>
</div>
<div id="kotak"></div>
</div>
<div id="or">
  <h1 align="center">ATAU</h1>
</div>
<div id="box2">
<div id="box4"><br><p>&nbsp;&nbsp;&nbsp;TK DAN PAUD<p><br><img src="tkpaud.png" width="173" height="136"><br>
<button>Kunjungi</button></div>
<div id="kotak1"></div>
</div>


</div>
</body>
</html>
