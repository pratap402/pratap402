 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>TU BSC NOTES</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #667eea, #764ba2);
      color: #fff;
      margin: 0;
      padding: 40px 20px;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 40px;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.3);
    }

    .note-list {
      width: 100%;
      max-width: 700px;
    }

    .note {
      background: rgba(255, 255, 255, 0.15);
      border-radius: 10px;
      padding: 20px 25px;
      margin-bottom: 20px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
      backdrop-filter: blur(10px);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .note:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 30px rgba(0,0,0,0.35);
    }

    .note h3 {
      margin-top: 0;
      margin-bottom: 15px;
      color: #fff;
    }

    a.button-link {
      display: inline-block;
      padding: 10px 18px;
      background: #fff;
      color: #764ba2;
      font-weight: 600;
      border-radius: 50px;
      text-decoration: none;
      box-shadow: 0 4px 8px rgba(118,75,162,0.4);
      transition: background 0.3s ease, color 0.3s ease;
    }

    a.button-link:hover {
      background: #5a3786;
      color: #fff;
      box-shadow: 0 6px 15px rgba(90,55,134,0.7);
    }
  </style>
</head>
<body>
  <h1>TU BSC NOTES</h1>
  <div class="note-list">
    <div class="note">
      <h3>Math - Integration Notes</h3>
      <a href="https://drive.google.com/file/d/FILE_ID/view?usp=sharing" target="_blank" class="button-link">View PDF</a>
    </div>
    <div class="note">
      <h3>Physics - Kinematics</h3>
      <a href="https://drive.google.com/file/d/FILE_ID/view?usp=sharing" target="_blank" class="button-link">View PDF</a>
    </div>
    <!-- Add more notes below -->
  </div>
</body>
</html>
