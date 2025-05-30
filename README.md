
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Beach Report Promotion</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to bottom, #87ceeb, #ffffff);
      margin: 0;
      padding: 20px;
      color: #03396c;
    }
    header {
      text-align: center;
      margin-bottom: 20px;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 0;
    }
    p {
      font-size: 1.2em;
      max-width: 700px;
      margin: 10px auto 30px auto;
    }
    .content {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      max-width: 900px;
      margin: auto;
      margin-bottom: 40px;
    }
    .video-container {
      flex: 1 1 400px;
      max-width: 400px;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      background-color: #e0f7fa;
    }
    video {
      width: 100%;
      display: block;
    }
    .pictures-container {
      flex: 1 1 400px;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    .pictures-container img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.15);
      display: block;
    }
    .cta {
      text-align: center;
      margin: 40px auto;
      background: #0288d1;
      color: white;
      padding: 30px 20px;
      border-radius: 15px;
      max-width: 600px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.2);
    }
    .cta h2 {
      font-size: 2em;
      margin-bottom: 20px;
    }
    .cta button {
      background: #f9a825;
      border: none;
      color: #03396c;
      font-size: 1.1em;
      padding: 12px 30px;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .cta button:hover {
      background: #fbc02d;
    }
    .contact-details {
      background: #b3e5fc;
      border-radius: 12px;
      padding: 25px 30px;
      max-width: 700px;
      margin: 0 auto 50px auto;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      color: #01579b;
    }
    .contact-details h2 {
      font-size: 1.8em;
      margin-bottom: 15px;
      text-align: center;
    }
    .contact-details p {
      text-align: center;
      margin-bottom: 20px;
      font-style: italic;
      font-size: 1.1em;
    }
    .contact-list {
      list-style: none;
      padding-left: 0;
      font-size: 1.1em;
      max-width: 400px;
      margin: 0 auto;
    }
    .contact-list > li {
      margin-bottom: 15px;
    }
    .contact-list ul {
      list-style: disc inside;
      margin-top: 8px;
    }
    footer {
      text-align: center;
      margin-top: 40px;
      font-style: italic;
      color: #555;
    }

    /* Responsive for smaller screens */
    @media (max-width: 800px) {
      .content {
        flex-direction: column;
        max-width: 100%;
      }
      .video-container, .pictures-container {
        max-width: 100%;
        flex: 1 1 100%;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Welcome to manlayang tariman resort!</h1>
  <p>Your ultimate destination for sun, sand, and serenity. Discover why Paradise Beach is the perfect getaway.</p>
</header>

<video controls width="100%">
  <source src="/storage/emulated/0/Download/MOV_17485742148591529.mp4" type="video/mp4">
</video>

  <div class="pictures-container">
    <img src="/storage/emulated/0/Download/second.jpg" alt="Beach View 1" />
    <img src="/storage/emulated/0/Download/3.jpg" alt="Beach View 2" />
    <img src="/storage/emulated/0/Download/first.jpg" alt="Beach View 3" />
  </div>
</div>

<div class="cta">
  <h2>Book your escape today!</h2>
  <button onclick="alert('Booking feature coming soon!')">Reserve Now</button>
</div>

<div class="section contact-details">
  <h2>Contact Details</h2>
  <p>Find all the information you need before planning your visit.</p>

  <ul class="contact-list">
    <li><strong>Entrance Fee:</strong> ₱50 per person</li>
    <li><strong>Cottage Fee:</strong> 
      <ul>
        <li>Without Overnight: ₱300 - ₱500</li>
        <li>With Overnight: ₱1,000 - ₱2,000</li>
      </ul>
    </li>
    <li><strong>Time:</strong> Open Daily | 6:00 AM – 10:00 PM</li>
    <li><strong>Others:</strong> Parking Available, No Pets Allowed, Free Wi-Fi</li>
  </ul>
</div>

<footer>
  &copy; 2025 tariman Resort - Book your trip today!
</footer>

</body>
</html>
