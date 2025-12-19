<!DOCTYPE html><html lang="zh-Hant">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>一起美甲吧✨</title>
<style>
:root{
  --green1:#c4dbaa;
  --green2:#90a677;
  --bg:#f6f7f4;
}
*{box-sizing:border-box;font-family:"Noto Sans TC",sans-serif;}
body{margin:0;background:var(--bg);color:#333;}
header{position:sticky;top:0;z-index:10;background:var(--green1);}
nav{display:flex;overflow-x:auto;white-space:nowrap;}
nav a{flex:0 0 auto;padding:14px 18px;color:#2f3b2f;text-decoration:none;font-size:14px;}
nav a:hover{background:var(--green2);color:#fff;}
section{padding:24px;max-width:900px;margin:auto;}
.card{background:#fff;border-radius:16px;padding:20px;margin-bottom:20px;}
h1,h2{margin-top:0;color:#4b5f4b;}
button{background:var(--green2);color:#fff;border:none;border-radius:20px;padding:10px 16px;cursor:pointer;}
button.disabled{background:#ccc;cursor:not-allowed;}
input,select,textarea{width:100%;padding:8px;margin:6px 0;border-radius:10px;border:1px solid #ccc;}
.notice{background:#eef3ea;border-left:6px solid var(--green2);padding:12px;border-radius:10px;}
.price-table div{margin:6px 0;}
.hidden{display:none;}
</style>
</head>
<body>
<header>
  <nav>
    <a href="#home">首頁</a>
    <a href="#rule">預約須知</a>
    <a href="#book">我要預約</a>
    <a href="#price">價目表</a>
    <a href="#news">優惠活動</a>
    <a href="#member">我的會員</a>
    <a href="#admin" onclick="return adminEnter()">管理後台</a>
  </nav>
</header><section id="home">
  <div class="card">
    <h1>一起美甲吧✨</h1>
    <p>溫柔・簡約・莫蘭迪綠系美甲空間</p>
    <p>
      IG：<a href="https://instagram.com" target="_blank">前往 IG</a><br/>
      官方 LINE：<a href="https://line.me/R/ti/p/~" target="_blank">加入 LINE</a>
    </p>
  </div>
</section><section id="book">
  <div class="card">
    <h2>我要預約</
