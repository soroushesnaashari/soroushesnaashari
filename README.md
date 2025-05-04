<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Mohammad Soroush Esnaashari</title>
  <!-- 1) Import a nice serif font -->
  <link
    href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&display=swap"
    rel="stylesheet"
  />
  <style>
    /* —————————————————————————————————————————
       Fancy animated gradient for your name
       ————————————————————————————————————————— */
    .fancy-name {
      font-family: 'Playfair Display', serif;
      font-size: 2.5rem;
      text-align: center;
      background: linear-gradient(
        45deg,
        #ff7e5f,
        #feb47b,
        #86a8e7,
        #91eae4
      );
      background-size: 300% 300%;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
      animation: gradientShift 5s ease infinite;
      display: inline-block;
      margin: 1rem 0;
    }
    @keyframes gradientShift {
      0%   { background-position: 0% 50%; }
      50%  { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    /* —————————————————————————————————————————
       Center everything
       ————————————————————————————————————————— */
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
      padding: 2rem;
      max-width: 800px;
      margin: auto;
    }
    .center { text-align: center; }
    .badges a { margin: 0 4px; display: inline-block; vertical-align: middle; }
    hr { border: none; border-top: 1px solid #eee; margin: 2rem 0; }
  </style>
</head>
<body>

  <!-- Your Name -->
  <p class="center">
    <strong class="fancy-name">Mohammad Soroush Esnaashari</strong>
  </p>

  <br>

  <!-- Subtitle -->
  <p class="center">
    <span style="font-size:16.5px; font-weight:normal;">
      &lt; Operations Research, AI, Machine Learning, Deep Learning, Data Science and Industrial Engineering /&gt;
    </span>
  </p>

  <br>

  <!-- Social Badges -->
  <p class="center badges">
    <a href="https://soroushesnaashari.github.io"        target="_blank">
      <img alt="Website"
           src="https://img.shields.io/badge/-Website-2d2d2d?style=flat-square&logo=githubpages&logoColor=white">
    </a>
    <a href="https://www.linkedin.com/in/soroushesnaashari" target="_blank">
      <img alt="LinkedIn"
           src="https://custom-icon-badges.demolab.com/badge/-LinkedIn-2d2d2d?style=flat-square&logo=linkedin-white&logoColor=white">
    </a>
    <a href="https://x.com/srshesn"                      target="_blank">
      <img alt="X"
           src="https://img.shields.io/badge/-Twitter-2d2d2d?style=flat-square&logo=X&logoColor=white">
    </a>
    <a href="https://github.com/soroushesnaashari"       target="_blank">
      <img alt="GitHub"
           src="https://img.shields.io/badge/-GitHub-2d2d2d?style=flat-square&logo=github&logoColor=white">
    </a>
    <a href="https://www.kaggle.com/soroushesnaashari"    target="_blank">
      <img alt="Kaggle"
           src="https://img.shields.io/badge/-Kaggle-2d2d2d?style=flat-square&logo=kaggle&logoColor=white">
    </a>
  </p>

  <hr>

  <!-- Skills & Expertise -->
  <h3>🛠️ Skills &amp; Expertise</h3>
  <ul>
    <li><strong>Programming Languages</strong>: Python</li>
    <li><strong>Libraries/Frameworks</strong>: TensorFlow, Keras, PyTorch, Scikit‑learn</li>
    <li><strong>Data Science Tools</strong>: Pandas, NumPy, Matplotlib, Seaborn</li>
    <li><strong>Other Tools</strong>: Primavera, Microsoft Project, Excel, data visualization tools</li>
  </ul>

  <hr>

  <!-- Projects -->
  <h3>💻 Selected Projects</h3>
  <p>Here are some of my notable projects (and more on my <a href="https://www.kaggle.com/soroushesnaashari" target="_blank">Kaggle</a>):</p>
  <ul>
    <li>
      <strong>Customer Behavior Analysis</strong>: An unsupervised learning project analyzing customer data.
      <a href="https://github.com/soroushesnaashari/Customer-Clustering" target="_blank">Repo</a>
    </li>
    <li>
      <strong>Google Stock Price Forecasting</strong>: LSTM models in TensorFlow &amp; PyTorch.
      <a href="https://github.com/soroushesnaashari/Google-Stock-Price-with-LSTM-using-TensorFlow" target="_blank">TF Repo</a> ·
      <a href="https://github.com/soroushesnaashari/Google-Stock-Price-with-LSTM-using-PyTorch" target="_blank">PT Repo</a>
    </li>
    <li>
      <strong>Rice Images Classification</strong>: CNN models for 5 rice varieties (TF &amp; PyTorch).
      <a href="https://github.com/soroushesnaashari/Rice-Images-Classification-with-CNN-using-TensorFlow" target="_blank">TF Repo</a> ·
      <a href="https://github.com/soroushesnaashari/Rice-Images-Classification-with-CNN-using-PyTorch" target="_blank">PT Repo</a>
    </li>
  </ul>

  <hr>

  <!-- Blog Posts -->
  <h3>✍️ Blog Posts</h3>
  <ul>
    <li>
      <a href="https://medium.com/towards-artificial-intelligence/data-scaling-101-standardscaler-vs-minmaxscaler-e8f78d77283f" target="_blank">
        Data Scaling 101: StandardScaler vs MinMaxScaler
      </a>
    </li>
    <li>
      <a href="https://medium.com/datadriveninvestor/data-scaling-102-beyond-the-basics-exploring-robustscaler-maxabsscaler-and-other-scaling-methods-383dd2921f69" target="_blank">
        Data Scaling 102: Beyond the Basics, Exploring RobustScaler, MaxAbsScaler and Other Scaling Methods
      </a>
    </li>
  </ul>

</body>
</html>
