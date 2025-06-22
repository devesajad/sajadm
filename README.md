<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>سجاد محمد مانع | الصفحة التعريفية</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Cairo', sans-serif;
      direction: rtl;
    }

    body {
      background:url('https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?auto=format&fit=crop&w=1500&q=80') no-repeat center center fixed;
      background-size: cover;
      color: #ffffff;
      font-family: 'cairo', sans-serif;
      overflow-x: hidden;
      position: relative;
    }

    .container {
      padding: 3rem 2rem;
      max-width: 900px;
      margin: auto;
      text-align: center;
      animation: fadeIn 2s ease-in-out;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      color: #00ffe7;
      animation: slideIn 1.5s ease;
    }

    h2 {
      font-size: 1.5rem;
      margin-bottom: 1rem;
      color: #ffdf00;
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 1.2rem;
      line-height: 1.7;
    }

    .tag {
      display: inline-block;
      background: #00ffe7;
      color: #000;
      padding: 0.5rem 1rem;
      margin: 0.3rem;
      border-radius: 30px;
      font-weight: bold;
      transition: transform 0.3s ease;
    }

    .tag:hover {
      transform: scale(1.1);
      background: #ffdf00;
      color: #000;
    }

    .quote {
      margin-top: 2rem;
      font-style: italic;
      font-size: 1.2rem;
      color: #ccc;
      animation: pulse 3s infinite;
    }

    .profile-pic {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #00ffe7;
      margin-bottom: 1.5rem;
      animation: fadeIn 2s ease-in-out;
    }

    .social-icons {
      margin-top: 2rem;
    }

    .social-icons a {
      display: inline-block;
      margin: 0 10px;
      color: #ffffff;
      font-size: 1.5rem;
      transition: transform 0.3s ease, color 0.3s ease;
    }

    .social-icons a:hover {
      transform: scale(1.3);
      color: #00ffe7;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(50px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideIn {
      from { opacity: 0; transform: translateX(-100px); }
      to { opacity: 1; transform: translateX(0); }
    }

    @keyframes pulse {
      0%, 100% { opacity: 0.6; }
      50% { opacity: 1; }
    }

    footer {
      margin-top: 3rem;
      font-size: 0.9rem;
      color: #888;
    }
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
>
</head>
<body>
  <div class="container">
    <img src="1.jpg" alt="صورة سجاد" class="profile-pic" />
    <h1>سجاد محمد مانع</h1>
    <h2>طالب تقنيات معلومات | مبرمج ومطور</h2>
    <p>
      أعمل في مجالات تصميم المواقع، تطوير الواجهات، وخبير في صيانة الأجهزة والهواتف الذكية.
      شغوف بتقديم حلول تقنية تسهّل حياة المستخدم وتفتح آفاقاً جديدة في عالم البرمجة.
    </p>
    <div>
      <span class="tag">تصميم</span>
      <span class="tag">تطوير مواقع</span>
      <span class="tag">خبير حاسبات</span>
      <span class="tag">خبير هواتف</span>
    </div>
    <p class="quote">"التقنية ليست فقط مهنة... بل أسلوب حياة"</p>
    <div class="social-icons">
      <a href="https://wa.me/9647727419551" target="_blank" title="واتساب"><i class="fab fa-whatsapp"></i></a>
      <a href="https://t.me/SJ4GG" target="_blank" title="تيليغرام"><i class="fab fa-telegram"></i></a>
      <a href="https://www.instagram.com/sj4g?igsh=MXJlbnV4NHBtMjc3Zg==" target="_blank" title="انستقرام"><i class="fab fa-instagram"></i></a>
      <a href="https://www.facebook.com/share/16JtWNbrZB/?mibextid=wwXIfr" target="_blank" title="فيسبوك"><i class="fab fa-facebook"></i></a>
    </div>
    <footer>
      &copy; 2025 سجاد محمد مانع - جميع الحقوق محفوظة
    </footer>
  </div>
</body>
</html>
