# C-Users-faizal-Downloads-java-Companyform.html
online form
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contact HI-TECH</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #05c8e6, #00c3ff, #19d9ff);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .form-container {
      background-color: rgb(255, 255, 255);
      padding: 40px 30px;
      border-radius: 15px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.25);
      width: 100%;
      max-width: 420px;
      animation: fadeIn 1s ease;
    }

    .form-container h2 {
      margin-bottom: 25px;
      color: #2c6460;
      text-align: center;
    }

    .form-group {
      margin-bottom: 20px;
    }

    label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
      color: #444444;
    }

    input, textarea {
      width: 80%;
      padding: 12px;
      border: 2px solid #dddddd;
      border-radius: 8px;
      font-size: 14px;
      transition: all 0.3s ease;
    }

    input:focus, textarea:focus {
      border-color: #645d2c;
      outline: none;
    }

    textarea {
      resize: vertical;
    }

    .btn-submit {
      width: 100%;
      background-color: #be2300;
      color: white;
      padding: 15px;
      font-size: 20px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .btn-submit:hover {
      background-color: #3c1b2b;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(25px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @media (max-width: 500px) {
      .form-container {
        padding: 30px 15px;
      }
    }
  </style>
</head>
<body>

  <div class="form-container">
    <h2>Contact HI-TECH</h2>
    <form>
      <div class="form-group">
        <label for="name">Full Name</label>
        <input type="text" id="name" placeholder="Enter your full name" required>
      </div>

      <div class="form-group">
        <label for="email">Email ID</label>
        <input type="email" id="email" placeholder="yourname@example.com" required>
      </div>

      <div class="form-group">
        <label for="subject">Subject</label>
        <input type="text" id="subject" placeholder="Enter subject" required>
      </div>

      <div class="form-group">
        <label for="feedback">Feedback / Review</label>
        <textarea id="feedback" rows="5" placeholder="Write your feedback or review here..." required></textarea>
      </div>

      <button class="btn-submit" type="submit">Submit</button>
    </form>
  </div>

</body>
</html>
