<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://kit.fontawesome.com/070428bd88.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="style.css">
    <title>ChatBot | Karamlyy</title>
</head>
<body>
    <section class="msger">
        <header class="msger-header">
          <div class="msger-header-title">
            <img src="robot.png" alt="" srcset="">
            <p>Karamlyy ChatBot</p>
          </div>
        </header>
        <main class="msger-chat">
          <div class="msg left-msg">
            <div
             class="msg-img"
             style="background-image: url(bot.png)"
            ></div>
            <div class="msg-bubble">
              <div class="msg-info">
                <div class="msg-info-name">BOT</div>
                <div class="msg-info-time">12:30</div>
              </div>
              <div class="msg-text">
                Hi, welcome to Karamlyy ChatBot!!<br>
                Go ahead and send me a message. 😄
              </div>
            </div>
          </div>
          <div class="msg right-msg">
            <div
             class="msg-img"
             style="background-image: url(user.png)"
            ></div>
            <div class="msg-bubble">
              <div class="msg-info">
                <div class="msg-info-name">Karamlyy</div>
                <div class="msg-info-time">12:31</div>
              </div>      
              <div class="msg-text">
                You can change your name in JS section!
              </div>
            </div>
          </div>
        </main>
        <form class="msger-inputarea">
          <input type="text" class="msger-input" placeholder="Enter your message...">
          <button type="submit" class="msger-send-btn"><i class="fa fa-paper-plane"></i></button>
        </form>
      </section>
      <script src="main.js"></script>
</body>
</html>
