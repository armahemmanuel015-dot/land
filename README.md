<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Thank You!</title>
  <style>
    html, body {
      height: 100%;
      margin: 0;
      font-family: Arial, sans-serif;
    }

    /* Fullscreen background image */
    body {
      background-image: https://ibb.co/5g8FDmPb; /* Replace with your image */
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: white;
    }

    /* Optional: dark overlay to make text readable */
    body::before {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0,0,0,0.4);
      z-index: 0;
    }

    /* Message content */
    .message {
      position: relative;
      z-index: 1; /* above overlay */
      max-width: 600px;
      padding: 20px;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.5rem;
    }
  </style>
</head>
<body>
  <div class="message">
    <h1>Thank You for Your Order!</h1>
    <p>Your payment has been received successfully.<br>We’ll deliver your fresh sausages soon!</p>
  </div>
</body>
</html>
