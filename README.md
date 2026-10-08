<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>이정화 박사| 리테일 강의</title>
<style>
*{box-sizing:border-box}
body{
  margin:0;
  font-family:"Noto Sans KR",sans-serif;
  background:linear-gradient(145deg,#eef5ff,#fff);
  color:#17365d;
}
.card{
  max-width:480px;
  min-height:100vh;
  margin:auto;
  padding:42px 25px 30px;
  display:flex;
  flex-direction:column;
  justify-content:space-between;
  text-align:center;
}
.top{padding-top:20px}
.badge{
  display:inline-block;
  padding:8px 16px;
  border-radius:30px;
  background:#dceaff;
  font-size:15px;
  font-weight:700;
  margin-bottom:18px;
}
.name{
  font-size:44px;
  font-weight:900;
  letter-spacing:-2px;
  margin:0 0 12px;
}
.intro{
  font-size:20px;
  line-height:1.6;
  font-weight:500;
  margin:0;
}
.highlight{font-weight:800}
.work{margin:35px 0}
.work-title{
  font-size:17px;
  font-weight:800;
  margin-bottom:18px;
}
.items{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:10px;
}
.item{
  background:#fff;
  border:2px solid #d7e5f7;
  border-radius:20px;
  padding:20px 8px;
  font-size:19px;
  font-weight:800;
  box-shadow:0 8px 18px rgba(23,54,93,.08);
  transition:.2s;
}
.item:hover{transform:translateY(-5px)}
.number{
  display:block;
  font-size:14px;
  margin-bottom:8px;
  opacity:.55;
}
.contact{
  display:block;
  width:100%;
  padding:19px;
  border-radius:22px;
  background:#17365d;
  color:#fff;
  text-decoration:none;
  font-size:22px;
  font-weight:800;
  box-shadow:0 10px 22px rgba(23,54,93,.2);
}
.contact span{margin-left:6px}
.contact:active{transform:scale(.97)}
@media(max-width:360px){
  .name{font-size:38px}
  .intro{font-size:18px}
  .item{font-size:17px}
}
</style>
</head>

<body>
<main class="card">

  <section class="top">
    <div class="badge">RETAIL · SERVICE · PEOPLE</div>
    <h1 class="name">이정화</h1>
    <p class="intro">
      리테일 현장에서 배우고 경험한<br>
      <span class="highlight">서비스의 가치를 전합니다.</span>
    </p>
  </section>

  <section class="work">
    <div class="work-title">제가 하는 일 ✦</div>
    <div class="items">
      <div class="item">
        <span class="number">01</span>교육
      </div>
      <div class="item">
        <span class="number">02</span>강의
      </div>
      <div class="item">
        <span class="number">03</span>코칭
      </div>
    </div>
  </section>

  <a class="contact" href="tel:01000000000">
    상담하기 <span>→</span>
  </a>

</main>
</body>
</html>
