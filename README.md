<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>For You ❤️</title>
  <style>
    /* Global Styles */
    body {
      font-family: 'Arial', sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
      transition: background 0.5s;
      overflow-x: hidden;
    }

    /* Page 1 Styles */
    #page1 {
      background-color: #FFD1DC; /* Baby Pink */
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      position: relative;
    }

    .message {
      background-color: rgba(255, 255, 255, 0.8);
      padding: 20px;
      border-radius: 15px;
      max-width: 80%;
      position: relative;
      z-index: 1;
    }

    .flower {
      position: absolute;
      width: 50px;
      opacity: 0.7;
    }

    /* Button Styles */
    .btn {
      background-color: #FF6B8B;
      color: white;
      border: none;
      padding: 12px 25px;
      font-size: 18px;
      border-radius: 50px;
      cursor: pointer;
      margin-top: 20px;
      transition: transform 0.3s;
      z-index: 2;
    }

    .btn:hover {
      transform: scale(1.1);
    }

    /* Page 2 Styles */
    #page2 {
      background-color: #FFD1DC;
      min-height: 100vh;
      display: none;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      position: relative;
    }

    .animated-text {
      animation: fadeIn 2s;
      background-color: rgba(255, 255, 255, 0.8);
      padding: 20px;
      border-radius: 15px;
      max-width: 80%;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    /* Page 3 Styles */
    #page3 {
      background-color: #FFD1DC;
      min-height: 100vh;
      display: none;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .video-container {
      margin: 20px 0;
    }

    .poll {
      background-color: rgba(255, 255, 255, 0.8);
      padding: 20px;
      border-radius: 15px;
      max-width: 80%;
    }

    .poll-option {
      margin: 10px;
      padding: 10px;
      background-color: #FF6B8B;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <!-- Page 1 -->
  <div id="page1">
    <!-- Flowers (randomly positioned) -->
    <img src="https://em-content.zobj.net/thumbs/120/apple/325/rose_1f339.png" class="flower" style="top: 10%; left: 15%;">
    <img src="https://em-content.zobj.net/thumbs/120/apple/325/hibiscus_1f33a.png" class="flower" style="top: 70%; left: 20%;">
    <img src="https://em-content.zobj.net/thumbs/120/apple/325/sunflower_1f33b.png" class="flower" style="top: 30%; right: 10%;">
    <img src="https://em-content.zobj.net/thumbs/120/apple/325/blossom_1f33c.png" class="flower" style="bottom: 20%; right: 15%;">

    <div class="message">
      <p>I know tumne bola ki kuch mat karo tumara mood apne aap accha ho jayega I know<br>But but mujhe thik nahi lgra tha isiliye mene ye ek cheez try ki hai deko😅 sorry</p>
    </div>
    <button class="btn" onclick="showPage2()">Click Here</button>
  </div>

  <!-- Page 2 -->
  <div id="page2">
    <!-- Different Flowers -->
    <img src="https://em-content.zobj.net/thumbs/120/apple/325/cherry-blossom_1f338.png" class="flower" style="top: 5%; left: 5%;">
    <img src="https://em-content.zobj.net/thumbs/120/apple/325/tulip_1f337.png" class="flower" style="top: 80%; left: 10%;">
    <img src="https://em-content.zobj.net/thumbs/120/apple/325/bouquet_1f490.png" class="flower" style="top: 20%; right: 5%;">
    <img src="https://em-content.zobj.net/thumbs/120/apple/325/herb_1f33f.png" class="flower" style="bottom: 10%; right: 10%;">
