
    @keyframes gradient {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .text-box {
      width: 200px;
      height: 100px;
      background: linear-gradient(to right, #ff00cc, #3333ff);
      background-size: 200% 100%;
      border-radius: 10px;
      animation: gradient 3s infinite;
      text-align: center;
      color: white;
      font-size: 24px;
      line-height: 100px;
    }
  <div class="text-box">
    Hello World
  </div>
