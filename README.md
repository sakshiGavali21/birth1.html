<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Birthday My Love ❤️</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: black;
      font-family: 'Segoe UI', sans-serif;
      color: white;
      overflow-x: hidden;
      position: relative;
    }

    .confetti {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-image: linear-gradient(to bottom, rgba(0,0,0,0.5), rgba(0,0,0,0.9)), url('10.png');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      opacity: 1;
      z-index: -1;
    }

    .container {
      padding: 20px;
      text-align: center;
      position: relative;
      z-index: 2;
    }

    h1 {
      font-size: 2.4em;
      color: #ff66cc;
      text-shadow: 2px 2px 8px #fff;
      margin: 0.3em 0;
    }

    .gallery-wrapper {
      display: flex;
      justify-content: center;
      align-items: flex-start;
      gap: 40px;
      flex-wrap: wrap;
      margin-top: 30px;
    }

    .gallery-column {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }

    .gallery-column img {
      width: 140px;
      height: 200px;
      object-fit: cover;
      border: 3px solid #fff;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(255, 255, 255, 0.3);
      transition: transform 0.3s ease;
    }

    .gallery-column img:nth-child(odd) {
      transform: rotate(-5deg) translateX(-5px);
    }

    .gallery-column img:nth-child(even) {
      transform: rotate(5deg) translateX(5px);
    }

    .gallery-column img:hover {
      transform: scale(1.05) rotate(0deg) translateX(0);
    }

    .message-plain {
      max-width: 90%;
      font-size: 1.1em;
      line-height: 1.8;
      color: #ffccff;
      margin: 40px auto;
      text-align: center;
      white-space: pre-line;
    }

    .bottom-decor {
      margin-top: 60px;
      display: flex;
      justify-content: center;
      align-items: flex-end;
      gap: 80px;
      flex-wrap: wrap;
    }

    .bottom-decor img {
      height: 180px;
      filter: drop-shadow(2px 4px 6px rgba(0,0,0,0.7));
      transform: scale(1);
      transition: transform 0.5s ease;
    }

    .bottom-decor img:hover {
      transform: scale(1.05);
    }

    .balloon {
      animation: float 5s ease-in-out infinite;
    }

    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
      100% { transform: translateY(0); }
    }

    @media (max-width: 800px) {
      h1 {
        font-size: 1.8em;
      }
      .gallery-wrapper {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <div class="confetti"></div>

  <div class="container">
    <h1>Happy Birthday My Love ❤️</h1>
    <h1>Dnyaneshwar</h1>

    <div class="gallery-wrapper">
      <!-- Left 3 Photos -->
      <div class="gallery-column">
        <img src="2.jpeg" alt="love1" />
        <img src="3.jpeg" alt="love2" />
        <img src="5.jpeg" alt="love3" />
      </div>

      <!-- Message Center Without Box -->
      <div class="message-plain">
        माझ्या हृदयाच्या राजाला, वाढदिवसाच्या लाख लाख शुभेच्छा! <b>Saheb</b> 💕
        तुझं हासणं, तुझं बोलणं, तुझं माझ्यासोबत असणं... हे सगळं मला खूप आवडतं. ❤️
        <b>You’re My Special One Saheb</b>
        तुझ्याशिवाय माझं जीवन अपूर्ण वाटतं आणि तुझ्या प्रेमामुळेच ते पूर्ण झालंय.
        तू माझं स्वप्न आहेस, आणि माझ्या हृदयातली जी जागा तुझ्यासाठी आहे, ती आज, उद्या आणि कायम तुझीच राहील. ✨
        तुझं प्रत्येक स्वप्न पूर्ण होवो, आणि तुला सुख, समाधान, यश आणि अपार प्रेम लाभो. 🎉
        मला आयुष्यभर तुझ्यासोबत राहायचं आहे... माझं संपूर्ण आयुष्य फक्त तुझ्यासोबत घालवायचं आहे.
        मी फक्त तुझीच आहे, आणि तुझीच राहीन. ❤️
        <b>I Love You So Much ❤️</b>
      </div>

      <!-- Right 3 Photos -->
      <div class="gallery-column">
        <img src="6.jpeg" alt="love4" />
        <img src="7.jpeg" alt="love5" />
        <img src="8.jpeg" alt="love6" />
      </div>
    </div>

    <!-- Bottom Cake and Balloons -->
    <div class="bottom-decor">
      <img src="cake.jpg" alt="cake" />
      <img src="ballon.jpg" class="balloon" alt="balloons" />
    </div>
  </div>
</body>
</html>
