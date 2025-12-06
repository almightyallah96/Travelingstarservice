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

    /* LOGO */
    .logo-box {
      width: 100%;
      text-align: center;
      padding: 20px 0;
      background: #ffffff;
    }

    .logo-box img {
      width: 160px;
      border-radius: 8px;
    }

    /* HEADER */
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

    /* SECTIONS */
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

    /* REVIEWS */
    .review {
      background: #f2f2f2;
      padding: 15px;
      border-radius: 8px;
      margin-bottom: 15px;
      border-left: 5px solid #1a1a1a;
    }

    /* BUTTON */
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

    /* FOOTER */
    .footer {
      text-align: center;
      padding: 20px;
      color: #444;
    }

  </style>

</head>
<body>

<!-- LOGO -->
<div class="logo-box">
  <img src="logo.png" alt="Traveling Star Service Logo">
</div>

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
  <h2>⭐ Customer Reviews</h2>

  <div class="review">
    “Fast, reliable, and excellent service! Highly recommended.”  
    <br><strong>– Maria J.</strong>
  </div>

  <div class="review">
    “Picked me up on time for my airport trip. Very professional.”  
    <br><strong>– David R.</strong>
  </div>

  <div class="review">
    “Clean vehicle, friendly driver. I will book again.”  
    <br><strong>– Jasmine P.</strong>
  </div>
</div>

<div class="section">
  <h2>📍 Service Area</h2>
  <p>We proudly serve Rocky Mount, NC and surrounding areas.</p>

  <iframe 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3223.27099823777!2d-77.7964!3d35.9382!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89ae7e8a8c9a8c27%3A0x5894651c3c5bbd7b!2sRocky%20Mount%2C%20NC!5e0!3m2!1sen!2sus!4v0000000000"
    width="100%" height="300" style="border:0; border-radius:10px;" allowfullscreen="" loading="lazy">
  </iframe>
</div>

<div class="section">
  <h2>📞 Contact & Booking</h2>
  <p><strong>Phone:</strong> 252-969-2444</p>
  <p><strong>Location:</strong> Rocky Mount, North Carolina</p>
  <a class="btn" href="tel:2529692444">📞 Call Now to Book a Ride</a>
</div>

<div class="footer">
  <p>© Traveling Star Service — All Rights Reserved</p>
</div>

</body>
</html>
