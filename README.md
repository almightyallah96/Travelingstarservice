<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Traveling Star Service</title>

  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #f7f7f7;
      color: #222;
    }

    header {
      background: url("hero.jpg") center/cover no-repeat;
      padding: 80px 20px;
      text-align: center;
      color: white;
    }

    header h1 {
      margin: 0;
      font-size: 40px;
      text-shadow: 0 0 10px rgba(0,0,0,0.5);
    }

    header p {
      font-size: 18px;
      text-shadow: 0 0 10px rgba(0,0,0,0.4);
    }

    .section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
      background: white;
      margin-top: 25px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    h2 {
      margin-top: 0;
      color: #1a1a1a;
      border-left: 6px solid #1a1a1a;
      padding-left: 10px;
    }

    .image-box {
      width: 100%;
      border-radius: 10px;
      margin-top: 15px;
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      margin-top: 20px;
    }

    .gallery img {
      width: 48%;
      border-radius: 10px;
      box-shadow: 0 0 8px rgba(0,0,0,0.2);
    }

    ul {
      padding-left: 20px;
      line-height: 1.8;
    }

    .btn {
      display: block;
      width: 100%;
      text-align: center;
      padding: 15px;
      background: #1a1a1a;
      color: white;
      text-decoration: none;
      font-size: 18px;
      border-radius: 8px;
      margin-top: 20px;
    }

    .btn:hover {
      background: #333;
    }

    .footer {
      text-align: center;
      padding: 20px;
      color: #444;
    }

  </style>

</head>
<body>

<header>
  <h1>Traveling Star Service</h1>
  <p>Your trusted transportation provider in Rocky Mount, NC</p>
</header>

<div class="section">
  <h2>🚖 Our Services</h2>
  <img src="services.jpg" class="image-box" alt="Transportation services image">

  <ul>
    <li>Local transportation</li>
    <li>Out-of-town trips</li>
    <li>Airport rides</li>
    <li>On-demand pickups</li>
    <li>Scheduled appointments</li>
  </ul>
</div>

<div class="section">
  <h2>🚗 Our Vehicles</h2>
  <p>Your comfort and safety are our top priority.</p>

  <div class="gallery">
    <img src="vehicle1.jpg" alt="Vehicle image 1">
    <img src="vehicle2.jpg" alt="Vehicle image 2">
  </div>
</div>

<div class="section">
  <h2>📞 Contact & Booking</h2>
  <p><strong>Phone:</strong> 252-969-2444</p>
  <p><strong>Location:</strong> Rocky Mount, North Carolina</p>
  <a class="btn" href="tel:2529692444">📞 Call Now to Book a Ride</a>
</div>

<div class="section">
  <h2>📝 Booking Request Form</h2>
  <p>Submit your ride request below. We will contact you shortly.</p>

  <form action="https://formsubmit.co/YOUR_EMAIL_HERE" method="POST">
    <input type="hidden" name="_captcha" value="false">

    <p><strong>Your Name</strong></p>
    <input type="text" name="Name" required style="width:100%; padding:10px;">

    <p><strong>Phone Number</strong></p>
    <input type="text" name="Phone" required style="width:100%; padding:10px;">

    <p><strong>Pick-Up Location</strong></p>
    <input type="text" name="Pickup" required style="width:100%; padding:10px;">

    <p><strong>Drop-Off Location</strong></p>
    <input type="text" name="Dropoff" required style="width:100%; padding:10px;">

    <p><strong>Date & Time</strong></p>
    <input type="text" name="Datetime" required style="width:100%; padding:10px;">

    <button type="submit" class="btn">Submit Ride Request</button>
  </form>
</div>

<div class="footer">
  <p>© Traveling Star Service — All Rights Reserved</p>
</div>

</body>
</html>
