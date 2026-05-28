<p align="center">
  <svg width="600" height="200" viewBox="0 0 600 200" xmlns="http://www.w3.org/2000/svg">
    <style>
      .bubble { fill: #64ffda; opacity: 0.3; }
      @keyframes float {
        0% { transform: translateY(0); opacity: 0; }
        50% { opacity: 0.6; }
        100% { transform: translateY(-150px); opacity: 0; }
      }
      .b1 { animation: float 4s infinite ease-in; }
      .b2 { animation: float 6s infinite ease-in 1s; }
      .b3 { animation: float 5s infinite ease-in 2s; }
      .b4 { animation: float 7s infinite ease-in 0.5s; }
    </style>
    <circle class="bubble b1" cx="100" cy="180" r="15" />
    <circle class="bubble b2" cx="250" cy="190" r="25" />
    <circle class="bubble b3" cx="400" cy="180" r="20" />
    <circle class="bubble b4" cx="550" cy="195" r="10" />
  </svg>
</p>
