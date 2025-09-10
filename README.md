
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Undangan Outbound Nuansa Pantai</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Pacifico&family=Montserrat:wght@400;700&display=swap');
  body {
    margin: 0; 
    font-family: 'Montserrat', sans-serif;
    background: linear-gradient(180deg, #a4d4f4 0%, #f9fbf2 100%);
    color: #034f84;
    overflow-x: hidden;
  }
  header {
    background: url('https://images.unsplash.com/photo-1507525428034-b723a9ce6890?auto=format&fit=crop&w=1500&q=80') no-repeat center/cover;
    padding: 120px 20px 80px;
    text-align: center;
    color: white;
    text-shadow: 0 2px 7px rgba(0,0,0,0.6);
    opacity: 0;
    animation: fadeSlideDown 1s ease forwards;
  }
  header h1 {
    font-family: 'Pacifico', cursive;
    font-size: 4rem;
    margin: 0 0 15px;
    animation: popIn 1s ease 1s forwards;
    opacity: 0;
  }
  header p {
    font-weight: 600;
    font-size: 1.8rem;
    animation: fadeIn 2s ease 1.2s forwards;
    opacity: 0;
  }
  main {
    max-width: 720px;
    background: rgba(255 255 255 / 0.95);
    margin: -60px auto 40px;
    border-radius: 20px;
    padding: 35px 45px;
    box-shadow: 0 15px 35px rgba(3,79,132,0.25);
    animation: fadeInUp 1s ease 1.5s forwards;
    opacity: 0;
  }.intro {
    font-size: 1.1rem;
    line-height: 1.7;
    margin-bottom: 40px;
    color: #024272;
  }.info-item {
    margin: 25px 0;
    display: flex;
    align-items: flex-start;
    opacity: 0;
    transform: translateX(-50px);
    animation: slideInLeft 0.6s forwards;
  }.info-item:nth-of-type(1) { animation-delay: 1.8s; }.info-item:nth-of-type(2) { animation-delay: 2.1s; }

</style>
</head>
<body>

<header>
  <h1>Petualangan Outbound di Pantai Binalatung</h1>
  <p>Temukan Kesegaran, Kebersamaan, dan Kenangan Tak Terlupakan</p>
</header>

<main>
  <div class="intro">
    Dengan penuh semangat dan rasa syukur, kami mengundang Sahabat semua untuk bergabung dalam kegiatan outbound berkonsep refreshing dan solid team building yang akan diadakan di Pantai eksotis Binalatung. Acara ini dirancang untuk menghadirkan suasana santai, menyenangkan, dan mempererat tali silaturahmi melalui beragam permainan dan kegiatan yang menyatu dengan keindahan alam pantai.
  </div>

  <div class="info-item">
    <svg class="info-icon" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24">
      <path d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
    </svg>
    <div class="info-text">
      <strong>Tanggal</strong>
      Minggu, 14 September 2025
    </div>
  </div>

  <div class="info-item">
    <svg class="info-icon" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24">
      <path d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path>
      <circle cx="15" cy="11" r="3"></circle>
    </svg>
    <div class="info-text">
      <strong>Lokasi</strong>
      <a href="https://maps.app.goo.gl/t7p2FZ4JPdKgNfyLA?g_st=aw" target="_blank" rel="noopener noreferrer">Pantai Binalatung, Tarakan, Kalimantan Utara</a>
    </div>
  </div>

info-item:nth-of-type(3) { animation-delay: 2.4s; }.info-item:nth-of-type(4) { animation-delay: 2.7s; }.info-icon {
    margin-right: 18px;
    flex-shrink: 0;
    stroke: #034f84;
    width: 30px; 
    height: 30px;
    margin-top: 3px;
  }.info-text strong {
    font-weight: 700;
    font-size: 1.15rem;
    display: block;
    margin-bottom: 6px;
    color: #013f66;
  }.info-text a {
    color: #007acc;
    text-decoration: none;
    font-weight: 600;
    transition: all 0.35s ease;
  }.info-text a:hover {
    text-decoration: underline;
    color: #005b99;
  }.agenda {
    background: #e0f2ff;
    border-left: 5px solid #007acc;
    padding: 18px 25px;
    margin-top: 40px;
    border-radius: 8px;
    font-size: 1.2rem;
    color: #034f84;
    font-weight: 700;
    opacity: 0;
    transform: translateY(20px);
    animation: fadeInUp 0.8s forwards;
    animation-delay: 3s;
  }.agenda ul {
    margin: 12px 0 0 20px;
    font-weight: 400;
    font-size: 1rem;
    color: #022f40;
  }.agenda ul li {
    margin-bottom: 8px;
    line-height: 1.4;
  }.closing-note {
    margin-top: 40px;
    font-style: italic;
    color: #05668d;
    font-size: 1.1rem;
    line-height: 1.5;
    opacity: 0;
    animation: fadeInUp 0.8s forwards;
    animation-delay: 3.5s;
  }
  
  footer {
    text-align: center;
    font-size: 0.9rem;
    color: #034f84aa;
    margin-top: 40px;
    padding-bottom: 15px;
  }
  
  @keyframes fadeSlideDown {
    0% {
      opacity: 0;
      transform: translateY(-40px);
    }
    100% {
      opacity: 1;
      transform: translateY(0);
    }
  }
  @keyframes popIn {
    0% {
      opacity: 0;
      transform: scale(0.6);
    }
    100% {
      opacity: 1;
      transform: scale(1);
    }
  }
  @keyframes fadeIn {
    0% {opacity:0;}
    100% {opacity:1;}
  }
  @keyframes fadeInUp {
    0% {
      opacity: 0;
      transform: translateY(40px);
    }
    100% {
      opacity: 1;
      transform: translateY(0);
    }
  }
  @keyframes slideInLeft {
    0% {
      opacity: 0;
      transform: translateX(-50px);
    }
    100% {
      opacity: 1;
      transform: translateX(0);
    }
  }
</style>
</head>
<body>

  <div class="info-item">
    <svg class="info-icon" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24">
      <path d="M12 8v4l3 3"></path>
      <circle cx="12" cy="12" r="10"></circle>
    </svg>
    <div class="info-text">
      <strong>Waktu</strong>
      08:00 s.d selesai
    </div>
  </div>

  <div class="agenda">
    Agenda:
    <ul>
      <li>Refreshing — Nikmati keindahan pantai, laut yang jernih, dan udara segar.</li>
      <li>Team Building — Berbagai permainan seru yang mempererat kekompakan tim.</li>
      <li>Solid — Membangun rasa persaudaraan dan kebersamaan yang berkualitas.</li>
    </ul>
  </div>

  <div class="closing-note">
    Kehadiran Sahabat sangat kami nantikan. Mari bersama-sama menciptakan kenangan indah, menyegarkan pikiran, serta menguatkan tali persaudaraan dalam suasana pantai nan menenangkan. Jangan lewatkan kesempatan emas ini untuk refreshing dan mempererat solidaritas!
  </div>
</main>

<footer>
  &copy; 2025 Outbound Binalatung • Semangat, Ceria, dan Solid Bersama!
</footer>

</body>
</html>
