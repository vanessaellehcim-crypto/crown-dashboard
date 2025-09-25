# crown-dashboard
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Crown Dashboard - ShelterKey</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Welcome to ShelterKey</h1>
    <p>Your donations help support veterans and those in need.</p>
  </header>

  <section class="banner">
    <h2>Crown Notice & ShelterKey Program</h2>
    <p>Join our mission to protect and provide for our community.</p>
  </section>

  <section class="donate">
    <a class="donate-button" href="https://www.paypal.com/donate?hosted_button_id=YOUR_BUTTON_ID" target="_blank">
      Donate Now
    </a>
  </section>
</body>
</html>
/* General Body Styling */
body {
  font-family: 'Arial', sans-serif;
  background-color: #f0f2f5;
  margin: 0;
  padding: 0;
  text-align: center;
}

/* Header Styling */
header {
  background-color: #0070BA;
  color: #fff;
  padding: 30px 0;
  font-size: 28px;
  font-weight: bold;
}

/* Banner Section */
.banner {
  background-color: #e6f7ff;
  padding: 20px 0;
  margin-bottom: 20px;
}

/* Donate Button Styling */
.donate-button {
  display: inline-block;
  background: linear-gradient(90deg, #FFD700, #FFA500);
  color: #111;
  padding: 14px 24px;
  border-radius: 8px;
  text-decoration: none;
  font-size: 18px;
  font-weight: bold;
  margin-top: 15px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.3);
  transition: all 0.3s ease;
}

.donate-button:hover {
  background: linear-gradient(90deg, #FFA500, #FFD700);
  transform: scale(1.05);
}

