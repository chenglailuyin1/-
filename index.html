<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="manifest" href="./manifest.json">
  <link rel="apple-touch-icon" sizes="any" href="https://ss284622.stars.ne.jp/header/site.png">
  <meta name="title" content="なんでもさいと">
  <meta name="description" content="どのようなコンテンツもご用意させています">
  <meta name="keywords" content="なんでもさいと,oll,さいと,サイト,なんでもサイト">
  <meta name="robots" content="index, follow">
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta name="revisit-after" content="1 day">
  <meta name="author" content="chenglailuyin">
  <link rel="icon" href="https://ss284622.stars.ne.jp/header/site.png">
  <link rel="shortcut icon" href="https://ss284622.stars.ne.jp/header/site.png">
<meta name="theme-color" media="(prefers-color-scheme: light)" content="#6a11cb"><meta name="theme-color" media="(prefers-color-scheme: dark)" content="#6a11cb"><meta http-equiv="Cache-Control" content="no-cache"><meta name="description" content=""><meta http-equiv="Content-Language" content=""><meta name="google" content="notranslate"><link rel="shortcut icon" href="./src/page/img/favicon.ico">
<title>なんでもさいと</title>
  <style>
    /* 既存のスタイル */
    body {
      display: flex;
      flex-direction: column;
      align-items: center;
      width: 100%;
      margin: 0;
      background: linear-gradient(135deg, #6a11cb, #2575fc);
      color: #fff;
      font-family: sans-serif;
      overflow: hidden; /* ローディング中はスクロールを隠す */
    }
    #p {
      display: none; /* 初期状態では非表示 */
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      width: 100%;
      margin: 0;
    }
    iframe {
      width: 95vw;
      height: 90vh;
      overflow: auto;
      -webkit-overflow-scrolling: touch;
      border: none;
    }
    h1 {
      margin-top: 20px;
      text-align: center;
    }
    #notificationButton {
      padding: 10px 20px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 16px;
      margin-top: 20px;
    }
    #notificationButton:hover {
      background-color: #0056b3;
    }

    /* ローディング画面のスタイル */
    #loading-screen {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(135deg, #6a11cb, #2575fc); /* サイトの背景色に合わせる */
      color: #fff;
      font-size: 24px;
      z-index: 1000; /* 最前面に表示 */
    }

    #loading-screen img {
      width: 100px; /* ローディング画像のサイズ */
      height: auto;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>
  <div id="loading-screen">
    <img src="https://ss284622.stars.ne.jp/header/site.png" alt="ローディング画像">
    <p>なんでもさいと</p>  </div>
  <div id="p">
<a href="mailto:chenglailuyin?subject=お問い合わせ&body=①件名%0D%0A②名前%0D%0A③Tel%0D%0A④内容%0D%0A⑤その他">お問い合わせ</a>
    <a href="https://www.google.co.jp/">google</a>
    <div id="header-container"></div>
    <h1>まだ見ぬ世界とあなたを繋ぐ。<br>ジャンルを超えた、なんでもさいと</h1>
    <section>
      <h1>なんでもあるサイトへようこそ</h1>
      <script async src="https://cse.google.com/cse.js?cx=a0b3ae46ced5541ad"></script>
      <div class="gcse-search"></div>
    </section>
    <button id="notificationButton" onclick="showNotification()">お知らせを受け取る</button>
  </div>
<script>
window.addEventListener('DOMContentLoaded', () => {
  const loadingScreen = document.getElementById('loading-screen');
  const content = document.getElementById('p');

  // ローディング画面を1.5秒後に非表示にし、コンテンツを表示
  setTimeout(() => {
    loadingScreen.style.display = 'none';
    content.style.display = 'flex';
    document.body.style.overflow = 'auto'; // スクロールを許可
  }, 1500);

  fetch('https://ss284622.stars.ne.jp/header/index.php')
    .then(response => response.text())
    .then(html => {
      const headerContainer = document.createElement('div');
      headerContainer.innerHTML = html;
      document.body.insertBefore(headerContainer, content); // ローディング画面より後に挿入

      const header = document.querySelector('header');
      if (header && content) {
        const headerHeight = header.offsetHeight;
        content.style.paddingTop = `${headerHeight}px`;
      }

      const hamburger = document.getElementById('hamburger');
      const menu = document.getElementById('menu');
      const audioControl = document.getElementById('audioControl');
      let bgm;
      let isMuted = true;

      function initAudio() {
        if (!bgm) {
          bgm = new Audio('/header/p.mp3');
          bgm.loop = true;
          bgm.addEventListener('canplaythrough', () => {
            if (!isMuted) {
              bgm.play().catch(error => {
                console.error("自動再生がブロックされました:", error);
                isMuted = true;
                if (audioControl) {
                  audioControl.textContent = "再生";
                }
              });
            }
          });
          if (isMuted) {
            bgm.pause();
          }
        }
      }

      initAudio();

      if (hamburger && menu) {
        hamburger.addEventListener('click', () => {
          menu.style.display = menu.style.display === 'block' ? 'none' : 'block';
        });
      }

      if (audioControl) {
        audioControl.addEventListener('click', () => {
          if (bgm.paused) {
            bgm.play();
            isMuted = false;
            audioControl.textContent = "ミュート";
          } else {
            bgm.pause();
            isMuted = true;
            audioControl.textContent = "再生";
          }
        });
      }

      const goToTopButton = document.createElement('button');
      goToTopButton.innerHTML = '&#x2191;'; /* 上向き矢印のUTF-8コード */
      goToTopButton.style.position = 'fixed';
      goToTopButton.style.right = '20px';
      goToTopButton.style.bottom = '20px';
      goToTopButton.style.width = '40px';
      goToTopButton.style.height = '40px';
      goToTopButton.style.borderRadius = '50%';
      goToTopButton.style.backgroundColor = '#333';
      goToTopButton.style.color = '#fff';
      goToTopButton.style.fontSize = '24px';
      goToTopButton.style.lineHeight = '40px';
      goToTopButton.style.textAlign = 'center';
      goToTopButton.style.border = 'none';
      goToTopButton.style.cursor = 'pointer';
      goToTopButton.addEventListener('click', () => {
        window.scrollTo({ top: 0, behavior: 'smooth' });
      });
      document.body.appendChild(goToTopButton);
    })
    .catch(error => {
      console.error('ヘッダーの読み込みに失敗しました:', error);
    });
});

function showNotification() {
  if (!("Notification" in window)) {
    alert("このブラウザは通知に対応していません。");
    return;
  }

  Notification.requestPermission().then(permission => {
    if (permission === "granted") {
      new Notification("新しいお知らせ", {
        body: "なんでもさいとに新しいコンテンツが追加されました！",
        icon: "https://ss284622.stars.ne.jp/header/site.png"
      });
    } else if (permission === "denied") {
      alert("通知が拒否されました。ブラウザの設定で許可してください。");
    }
  });
}
</script>
</body>
</html>
