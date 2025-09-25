# crown-dashboard 

</head>
<body>
  <header>
    <h1>Welcome to ShelterKey</h1>
  </header>

  <section class="donate">
    <a class="donate-button" href="https://www.paypal.com/donate?hosted_button_id=YOUR_BUTTON_ID" target="_blank">
      Donate Now
    </a>
  </section>
</body>
</html>

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Crown Console - ShelterKey</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Welcome to the Crown Console</h1>
    <p>Manage ShelterKey, view scrolls, and receive donations.</p>
  </header>

  <!-- Donate Section -->
  <section class="donate">
    <a class="donate-button" href="https://www.paypal.com/donate?hosted_button_id=YOUR_BUTTON_ID" target="_blank">
      Donate Now
    </a>
  </section>

  <!-- Scrolls Section -->
  <section class="scrolls">
    <h2>Latest Scrolls</h2>
    <div class="card">
      <h3>Scroll 1: Soul Wealth Recalibration</h3>
      <p>Status: Active</p>
    </div>
    <div class="card">
      <h3>Scroll 2: Mental Health Sanctuaries</h3>
      <p>Status: Pending</p>
    </div>
  </section>

  <!-- Ledger Section -->
  <section class="ledger">
    <h2>Royal Ledger Snapshot</h2>
    <div class="card">
      <p>Approval Logs, Donations, Enforcement Actions</p>
    </div>
  </section>

  <!-- Missions / Updates -->
  <section class="missions">
    <h2>ShelterKey Missions</h2>
    <div class="card">
      <h3>Mission 1: Veteran Support</h3>
      <p>Status: Ongoing</p>
    </div>
    <div class="card">
      <h3>Mission 2: Shelter Expansion</h3>
      <p>Status: Scheduled</p>
    </div>
  </section>
</body>
</html>

/* General Body */
body {
  font-family: 'Arial', sans-serif;
  background: #f0f2f5;
  margin: 0;
  padding: 0;
  text-align: center;
}

/* Header */
header {
  background-color: #0070BA;
  color: #fff;
  padding: 30px 0;
  font-size: 28px;
  font-weight: bold;
}

/* Sections */
section {
  padding: 20px 10px;
  margin-bottom: 20px;
}

/* Donate Button */
.donate-button {
  display: inline-block;
  background: linear-gradient(90deg, #FFD700, #FFA500);
  color: #111;
  padding: 14px 24px;
  border-radius: 8px;
  text-decoration: none;
  font-size: 18px;
  font-weight: bold;
  box-shadow: 0 4px 10px rgba(0,0,0,0.3);
  transition: all 0.3s ease;
}
.donate-button:hover {
  background: linear-gradient(90deg, #FFA500, #FFD700);
  transform: scale(1.05);
}

/* Card Styling for 3D Look */
.card {
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 10px 20px rgba(0,0,0,0.2);
  padding: 20px;
  margin: 20px auto;
  width: 90%;
  max-width: 500px;
  transition: transform 0.3s;
}
.card:hover {
  transform: translateY(-10px);
}
