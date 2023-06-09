# team-project
  <style>
    .container {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    
    .grid {
      display: grid;
      grid-template-columns: repeat(8, 1fr);
      grid-template-rows: repeat(4, 1fr);
      gap: 20px;
    }
    
    .card {
      border: 1px solid #ccc;
      border-radius: 4px;
      padding: 10px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      background-color: #fff;
    }
    
    .card img {
      width: 100%;
      height: auto;
    }
    
    .card h3 {
      font-size: 18px;
      margin-top: 10px;
    }
    
    .card p {
      color: #666;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="grid">
      <div class="card">
        <img src="image1.jpg" alt="Зображення 1">
        <h3>Назва карточки 1</h3>
        <p>Опис карточки 1</p>
      </div>
    
      <div class="card">
        <img src="image2.jpg" alt="Зображення 2">
        <h3>Назва карточки 2</h3>
        <p>Опис карточки 2</p>
      </div>
      
      <div class="card">
        <img src="image1.jpg" alt="Зображення 1">
        <h3>Назва карточки 1</h3>
        <p>Опис карточки 1</p>
      </div>
    
      <div class="card">
        <img src="image2.jpg" alt="Зображення 2">
        <h3>Назва карточки 2</h3>
        <p>Опис карточки 2</p>
      </div>

      </div>