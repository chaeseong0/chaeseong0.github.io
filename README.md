<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ELITE 강남</title>
  <link href="https://fonts.googleapis.com/css2?family=Pretendard:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    *{box-sizing:border-box}
    body{margin:0;font-family:'Pretendard',sans-serif;background:#0b0b0c;color:#fff}
     .hero h1{
  font-size:64px;
  letter-spacing:8px;
  color:#d4af37;
  text-shadow:0 0 20px rgba(212,175,55,0.4);
}
    .hero{
      height:420px;
      background:url('https://images.unsplash.com/photo-1519677100203-a0e668c92439?q=80&w=1600&auto=format&fit=crop') center/cover no-repeat;
      display:flex;align-items:center;justify-content:center;
      position:relative;
    }
    .hero::after{content:'';position:absolute;inset:0;background:rgba(0,0,0,0.65)}
    .hero-content{position:relative;text-align:center}
    .hero h1{font-size:56px;letter-spacing:6px;margin:0;color:#d4af37}
    .hero p{margin-top:10px;color:#ccc}

    .container{max-width:900px;margin:-30px auto 40px;padding:20px}

    .card{background:#141416;border-radius:16px;padding:24px;margin-bottom:20px;box-shadow:0 10px 30px rgba(0,0,0,0.4);border:1px solid rgba(255,255,255,0.05)}

    h2{margin:0 0 15px 0;font-weight:600}
    .price{margin:6px 0;color:#ddd}
    hr{border:none;border-top:1px solid #333;margin:12px 0}

    .info p{margin:6px 0;color:#bbb}

    .btn{display:block;width:100%;padding:16px;margin-top:12px;text-align:center;border-radius:10px;text-decoration:none;font-weight:600;transition:0.2s}

    .kakao{background:#FEE500;color:#000}
    .wechat{background:#1AAD19}

    .btn:hover{opacity:0.85}

    .footer{text-align:center;color:#666;font-size:12px;margin-top:30px}
  </style>
</head>
<body>

  <div class="hero">
    <div class="hero-content">
      <h1>ELITE</h1>
      <p>강남 프리미엄 나이트 서비스</p>
    </div>
  </div>

  <div class="container">

    <div class="card">
      <h2>0부 (21시 이전)</h2>
      <div class="price">주대 10</div>
      <div class="price">룸티 5</div>
      <div class="price">TC 12</div>
      <hr>
      <div class="price">1인 27</div>
      <div class="price">2인 39</div>
      <div class="price">3인 51</div>
    </div>

    <div class="card">
      <h2>1부 (21시 이후)</h2>
      <div class="price">주대 12</div>
      <div class="price">룸티 5</div>
      <div class="price">TC 12</div>
      <hr>
      <div class="price">1인 29</div>
      <div class="price">2인 41</div>
      <div class="price">3인 53</div>
    </div>

    <div class="card info">
      <h2>안내</h2>
      <p>✔ 고급 맞춤 서비스 제공</p>
      <p>✔ 24시간 예약 가능</p>
      <p>✔ 철저한 프라이버시 보장</p>
    </div>

  
    <a href="https://open.kakao.com/o/[여기에코드](https://open.kakao.com/o/sQwTbRli)" target="_blank" class="btn kakao">
      카카오톡 문의
    </a>


    <a href="#" onclick="alert('WeChat ID: YOUR_WECHAT_ID')" class="btn wechat">
      위챗 문의
    </a>

    <!-- <a href="https://너의QR페이지주소" target="_blank" class="btn wechat">위챗 문의</a> -->

    <div class="footer">
      © ELITE
    </div>

  </div>

</body>
</html>
 
