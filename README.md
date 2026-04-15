# dio-card8
디오르나인 안양역 모바일 명함 
<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>Dio.L9 - 이동규 부장</title>

<meta property="og:title" content="이동규 부장 · 평촌 디오르나인 안양역 분양 상담">
<meta property="og:description" content="오늘 계약·오늘 입주, 안양역 더블 초역세권 디오르나인 상담은 이동규 부장에게 문의하세요.">
<meta property="og:url" content="https://cyh1931-boop.github.io/dio-card8/">
<meta property="og:type" content="website">

<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+KR:wght@300;400;600&family=Noto+Sans+KR:wght@300;400;500;700&display=swap" rel="stylesheet">

<style>
  *{box-sizing:border-box;margin:0;padding:0;}
  :root{
    --gold:#b8965a;--gold-light:#d4b07a;--dark:#1a1a1a;
    --card-bg:#fffdf9;--pink-border:#e8c5cb;
  }
  body{
    background:#f0ece4;font-family:'Noto Sans KR',sans-serif;
    min-height:100vh;display:flex;flex-direction:column;
    align-items:center;padding-bottom:40px;
  }
  .banner{
    width:100%;background:#1a1a1a;color:#f5f0e8;
    padding:20px 20px 0;position:relative;overflow:hidden;
  }
  .banner::before{
    content:'';position:absolute;top:0;left:0;right:0;height:3px;
    background:linear-gradient(90deg,#b8965a,#d4b07a,#b8965a);
  }
  .brand-logo{
    font-family:'Noto Serif KR',serif;font-size:22px;
    font-weight:600;color:#d4b07a;letter-spacing:1px;
  }
  .brand-sub{
    font-size:9px;color:rgba(245,240,232,0.45);
    letter-spacing:2px;text-transform:uppercase;
  }
  .msg-box{
    margin-top:16px;background:rgba(255,255,255,0.05);
    border:1px solid rgba(184,150,90,0.2);border-radius:12px;
    padding:14px 16px;font-size:12.5px;line-height:1.7;
    color:rgba(245,240,232,0.9);
  }
  .msg-box strong{color:#d4b07a;}
  .card-wrap{
    width:calc(100% - 32px);max-width:400px;
    margin:12px 16px 0;
  }
  .card{
    background:var(--card-bg);border-radius:16px;
    border:2px solid var(--pink-border);
    box-shadow:0 8px 32px rgba(0,0,0,0.18);
    overflow:hidden;
  }
  .card-inner{padding:24px 24px 20px;position:relative;}
  .card-logo{
    position:absolute;top:20px;right:20px;text-align:right;
  }
  .card-logo-main{
    font-family:'Noto Serif KR',serif;font-size:20px;
    font-weight:600;color:#1a1a1a;
  }
  .card-logo-sub{
    font-size:8px;color:#aaa;letter-spacing:1.5px;
    text-transform:uppercase;
  }
  .name-block{margin-top:46px;margin-bottom:12px;}
  .name-kr{
    font-family:'Noto Serif KR',serif;font-size:26px;
    font-weight:600;color:#1a1a1a;letter-spacing:4px;
  }
  .name-rank{font-size:12px;color:#888;margin-left:10px;}
  .divider{
    height:1px;background:linear-gradient(to right,#e8c5cb,transparent);
    margin-bottom:12px;
  }
  .contact-row{
    display:flex;align-items:center;gap:10px;
    font-size:13px;
  }
  .contact-icon{
    width:28px;height:28px;background:#1a1a1a;border-radius:7px;
    display:flex;align-items:center;justify-content:center;
  }
  .contact-icon svg{width:13px;height:13px;fill:#d4b07a;}
  .contact-label{font-size:9px;color:#bbb;text-transform:uppercase;}
  .contact-value a{color:#1a1a1a;text-decoration:none;font-weight:500;}

  .card-footer{
    display:flex;align-items:center;justify-content:space-between;
    padding:12px 24px 16px;border-top:1px solid #e8c5cb;
    background:rgba(232,197,203,0.1);
  }
  .addr-text{font-size:10.5px;color:#888;line-height:1.5;padding-right:12px;}
  .on-logo{
    width:44px;height:44px;border-radius:50%;background:#1a1a1a;
    display:flex;align-items:center;justify-content:center;
    font-family:'Noto Serif KR',serif;font-size:15px;
    font-weight:700;color:#fff;
  }
  .btn-wrap{
    width:calc(100% - 32px);max-width:400px;
    margin:14px 16px 0;display:grid;
    grid-template-columns:1fr 1fr;gap:10px;
  }
  .btn{
    display:flex;align-items:center;justify-content:center;
    gap:8px;padding:12px 10px;border-radius:12px;
    font-size:13px;font-weight:500;text-decoration:none;
    border:none;cursor:pointer;transition:.15s ease;
  }
  .btn:active{transform:scale(.97);opacity:.85;}
  .btn svg{width:16px;height:16px;}
  .btn-call{background:#1a1a1a;color:#f5f0e8;}
  .btn-call svg{fill:#d4b07a;}
  .btn-web{background:#b8965a;color:#fff;}
  .btn-web svg{fill:#fff;}
  .btn-sms{
    grid-column:1/-1;background:#f5f0e8;color:#1a1a1a;
    border:1px solid #e0d5c5;font-size:12px;
  }
  .btn-sms svg{fill:#b8965a;}
  .cta{
    width:calc(100% - 32px);max-width:400px;
    margin:12px 16px 0;padding:16px 18px;
    border-radius:14px;
    background:linear-gradient(135deg,#1a1a1a,#2d2416);
    display:flex;align-items:center;justify-content:space-between;
    font-size:13px;color:rgba(245,240,232,0.8);
  }
  .cta strong{display:block;font-size:15px;color:#d4b07a;margin-bottom:2px;}
  .cta-btn{
    background:#b8965a;color:#fff;border:none;border-radius:10px;
    padding:9px 14px;font-size:12px;font-weight:600;
    text-decoration:none;white-space:nowrap;
  }
</style>
</head>
<body>

<div class="banner">
  <div class="brand-logo">Dio.L9</div>
  <div class="brand-sub">Luxury Limited House</div>
  <div class="msg-box">
    <p>✅ <strong>오늘 계약, 오늘 입주 가능</strong><br>안양 기입주 아파트, 실입주·투자 모두 가능한 기회입니다.</p>
  </div>
</div>

<div class="card-wrap">
  <div class="card">
    <div class="card-inner">
      <div class="card-logo">
        <div class="card-logo-main">Dio.L9</div>
        <div class="card-logo-sub">Luxury Limited House</div>
      </div>

      <div class="name-block">
        <span class="name-kr">이 동 규</span>
        <span class="name-rank">부장</span>
      </div>
      <div class="divider"></div>

      <div class="contact-row">
        <div class="contact-icon">
          <svg viewBox="0 0 24 24"><path d="M6.62 10.79a15.05 15.05 0 0 0 6.59 6.59l2.2-2.2a1 1 0 0 1 1.01-.24c1.12.37 2.33.57 3.58.57a1 1 0 0 1 1 1V20a1 1 0 0 1-1 1C9.61 21 3 14.39 3 6a1 1 0 0 1 1-1h3.5a1 1 0 0 1 1 1c0 1.25.2 2.45.57 3.57a1 1 0 0 1-.45 1.22z"/></svg>
        </div>
        <div>
          <div class="contact-label">Mobile</div>
          <div class="contact-value"><a href="tel:01052844662">010-5284-4662</a></div>
        </div>
      </div>
    </div>

    <div class="card-footer">
      <div class="addr-text">경기도 안양시 만안구 안양로 243<br>(1BL 3층 홍보관)</div>
      <div class="on-logo">ON</div>
    </div>
  </div>
</div>

<div class="btn-wrap">
  <a class="btn btn-call" href="tel:01052844662">
    <svg viewBox="0 0 24 24"><path d="M6.62 10.79a15.05 15.05 0 0 0 6.59 6.59l2.2-2.2a1 1 0 0 1 1.01-.24c1.12.37 2.33.57 3.58.57a1 1 0 0 1 1 1V20a1 1 0 0 1-1 1C9.61 21 3 14.39 3 6a1 1 0 0 1 1-1h3.5a1 1 0 0 1 1 1c0 1.25.2 2.45.57 3.57a1 1 0 0 1-.45 1.22z"/></svg>
    전화연결
  </a>
  <a class="btn btn-web" href="https://cyh1931.creatorlink.net/" target="_blank" rel="noopener noreferrer">
    <svg viewBox="0 0 24 24"><path d="M12 2a10 10 0 1 0 0 20A10 10 0 0 0 12 2zm-1 17.93V18a1 1 0 0 0-1-1H8a3 3 0 0 1-3-3v-1l4 4v1c0 .34.03.67.07 1zm6.32-2.06l-1.32-1.32a1 1 0 0 0-.71-.29H13v-2a1 1 0 0 0-1-1H9v-2h2a1 1 0 0 0 1-1V7h2a2 2 0 0 1 2 2v1.5l2 2a8 8 0 0 1-1.68 3.37z"/></svg>
    홈페이지
  </a>
  <a class="btn btn-sms" href="sms:01052844662">
    <svg viewBox="0 0 24 24"><path d="M20 2H4a2 2 0 0 0-2 2v18l4-4h14a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2z"/></svg>
    문자보내기
  </a>
</div>

<div class="cta">
  <div>
    <strong>방문 예약 상담</strong>
    전화 또는 문자로 예약 후 방문해 주세요
  </div>
  <a class="cta-btn" href="tel:01052844662">예약 전화</a>
</div>

</body>
</html>
