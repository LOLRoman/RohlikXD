https://lolroman.github.io/RohlikXD/



<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>RohlikXD</title>
  <style>
    body {
      margin: 0;
      padding: 2rem;
      background-color: #121212;
      color: #ffffff;
      font-family: sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      max-width: 720px;
      margin-left: auto;
      margin-right: auto;
    }

    h1 {
      margin-bottom: 2rem;
      font-size: 2rem;
    }

    .columns {
      width: 100%;
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      flex-wrap: wrap;
      margin-bottom: 2rem;
    }

    .left, .right {
      display: flex;
      flex-direction: column;
      gap: 0.8rem;
      min-width: 180px;
    }

    .left {
      animation: slide-left 0.6s ease-out forwards;
      transform: translateX(-100vw);
    }

    .right {
      animation: slide-right 0.6s ease-out forwards;
      transform: translateX(100vw);
    }

    a {
      color: #90caf9;
      text-decoration: none;
      font-size: 1.1rem;
      transition: color 0.2s;
    }

    a:hover {
      color: #ffffff;
    }

    .middle {
      animation: fade-in 0.8s ease-out forwards;
    }

    .search-box {
      margin-bottom: 1rem;
    }

    input[type="text"] {
      padding: 10px;
      font-size: 1rem;
      width: 250px;
      border: none;
      border-radius: 5px;
    }

    input[type="submit"] {
      padding: 10px 15px;
      margin-left: 10px;
      background-color: #90caf9;
      border: none;
      border-radius: 5px;
      color: black;
      font-weight: bold;
      cursor: pointer;
    }

    img {
      margin-top: 1rem;
      max-width: 100%;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 0 10px #00000066;
    }

    @keyframes slide-left {
      to {
        transform: translateX(0);
      }
    }

    @keyframes slide-right {
      to {
        transform: translateX(0);
      }
    }

    @keyframes fade-in {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 768px) {
      .columns {
        flex-direction: column;
        align-items: center;
      }
      .left, .right {
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <strong><h1>RohlikXD</h1></strong>

  <div class="columns">
    <div class="left">
      <a href="https://www.gtgm.cz/" target="_blank">GTGM Web</a>
      <a href="https://gtgm.bakalari.cz/login" target="_blank">GTGM Bakaláři</a>
      <a href="https://moodle4.gtgm.cz/" target="_blank">GTGM Moodle</a>
      <a href="https://chatgpt.com/" target="_blank">ChatGPT</a>
    </div>

    <div class="middle">
      <form class="search-box" action="https://www.google.com/search" method="GET" target="_blank">
        <input type="text" name="q" placeholder="Hledat na Google…" />
        <input type="submit" value="Hledat" />
      </form>
      <img src="https://chromeunboxed.com/wp-content/uploads/2022/03/Chrome-OS-New-Boot-Screen-Feature.jpg" alt="Chrome OS Logo" width="200" />
    </div>

    <div class="right">
      <a href="https://www.google.com/" target="_blank">Google</a>
      <a href="https://mail.google.com/" target="_blank">Gmail</a>
      <a href="https://drive.google.com/" target="_blank">Google Drive</a>
      <a href="https://docs.google.com/" target="_blank">Google Docs</a>
      <a href="https://www.google.com/maps?authuser=0" target="_blank">Google Maps</a>
      <a href="https://calendar.google.com/" target="_blank">Google Kalendář</a>
      <a href="https://classroom.google.com/u/1/?pli=1" target="_blank">Google Classroom</a>
      <a href="https://keep.google.com/" target="_blank">Google Keep</a>
      <a href="https://www.youtube.com/" target="_blank">Youtube</a>
    </div>
  </div>
</body>
</html>
