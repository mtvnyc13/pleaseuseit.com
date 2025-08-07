<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>pleaseuseit.com</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');
  body {
    margin: 0;
    height: 100vh;
    background: #121212;
    color: #eee;
    font-family: 'Montserrat', sans-serif;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  h1 {
    font-size: 3rem;
    margin: 0 0 10px 0;
    animation: glow 2s ease-in-out infinite alternate;
  }
  p {
    font-size: 1.25rem;
    margin: 0 0 40px 0;
    color: #bbb;
  }
  @keyframes glow {
    from {
      text-shadow: 0 0 5px #00ff99, 0 0 10px #00ff99;
      color: #00ff99;
    }
    to {
      text-shadow: 0 0 20px #00ff99, 0 0 30px #00ff99;
      color: #00cc77;
    }
  }
  .social-links {
    display: flex;
    gap: 30px;
    justify-content: center;
  }
  .social-links a {
    display: inline-flex;
    transition: transform 0.3s ease, filter 0.3s ease;
  }
  .social-links a svg {
    width: 32px;
    height: 32px;
    fill: #00ff99;
    filter: drop-shadow(0 0 3px #00ff99);
    transition: fill 0.3s ease, filter 0.3s ease;
  }
  .social-links a:hover svg {
    fill: #00cc77;
    filter: drop-shadow(0 0 8px #00cc77);
    transform: scale(1.2);
  }
</style>
</head>
<body>

<h1>pleaseuseit.com</h1>
<p>Site is under construction 🚧<br />Stay tuned!</p>

<div class="social-links">
  <a href="https://www.facebook.com/mikhail.timofeev.3726/" target="_blank" rel="noopener" aria-label="Facebook" title="Facebook">
    <svg width="24" height="24" fill="#00ff99" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <path d="M22.675 0H1.325C.593 0 0 .593 0 1.326v21.348C0 23.407.593 24 1.325 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.098 2.794.142v3.24l-1.918.001c-1.504 0-1.796.715-1.796 1.763v2.31h3.588l-.467 3.622h-3.12V24h6.116C23.407 24 24 23.407 24 22.674V1.326C24 .593 23.407 0 22.675 0z"/>
    </svg>
  </a>
  <a href="https://t.me/yourtelegram" target="_blank" rel="noopener" aria-label="Telegram" title="Telegram">
    <svg width="24" height="24" fill="#00ff99" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <path d="M9.04 16.27l-.38 5.32c.54 0 .77-.23 1.05-.5l2.52-2.4 5.22 3.82c.96.53 1.65.25 1.9-.88l3.44-16.1c.3-1.38-.5-1.94-1.4-1.6L2.9 10.44c-1.34.52-1.33 1.26-.23 1.62l5.92 1.85 13.74-8.63c.65-.35 1.24-.16.75.22"/>
    </svg>
  </a>
  <a href="mailto:mikhailtimoff@gmail.com" aria-label="Email" title="Email">
    <svg width="24" height="24" fill="#00ff99" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zM4 8l8 5 8-5v-2l-8 5-8-5v2z"/>
    </svg>
  </a>
</div>

</body>
</html>
