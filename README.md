<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Account & Data Deletion Request</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to bottom, skyblue, lightgreen, orange);
      color: #000;
    }

    .container {
      max-width: 600px;
      margin: 50px auto;
      background-color: #ffffffcc;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }

    h1 {
      text-align: center;
      color: #000;
      font-size: 26px;
      font-weight: bold;
      margin-bottom: 20px;
    }

    form label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 16px;
    }

    form button {
      width: 100%;
      padding: 12px;
      background-color: #007acc;
      color: #fff;
      border: none;
      border-radius: 6px;
      font-size: 18px;
      cursor: pointer;
    }

    form button:hover {
      background-color: #005999;
    }

    .footer {
      text-align: center;
      padding: 20px;
      background-color: #007acc;
      color: white;
      margin-top: 40px;
    }

    .note {
      font-size: 15px;
      background: #fff3cd;
      border: 1px solid #ffeeba;
      padding: 10px;
      border-radius: 6px;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Earn to by Ads – Account & Data Deletion Request</h1>

    <div class="note">
      Please fill out the form below to request deletion of your account. We will verify the information and process it within <strong>7 working days</strong>.
    </div>

    <form action="mailto:helpsearntoads@gmail.com" method="post" enctype="text/plain">
      <label for="email">Registered Email ID:</label>
      <input type="email" id="email" name="Email" required />

      <label for="accountId">Account ID (if applicable):</label>
      <input type="text" id="accountId" name="Account ID" />

      <label for="reason">Reason for Deletion (optional):</label>
      <textarea id="reason" name="Reason" rows="4" placeholder="Enter your reason..."></textarea>

      <button type="submit">Submit Request</button>
    </form>
  </div>

  <div class="footer">
    © 2025 Earn to by Ads – All Rights Reserved
  </div>

</body>
</html>
