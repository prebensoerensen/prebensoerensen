<svg xmlns="http://www.w3.org/2000/svg" width="400" height="200">
  <style>
    .button {
      fill: #3498db;
      rx: 20; /* Rounded corners */
      ry: 20;
      transition: fill 0.3s ease, transform 0.2s ease;
      box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.3);
    }
    .button:hover {
      fill: #e74c3c;
      transform: translateY(-5px);
    }
    .button-text {
      font-family: 'Arial', sans-serif;
      font-size: 24px;
      fill: white;
      transition: fill 0.3s ease;
    }
    .button-text:hover {
      fill: #ecf0f1;
    }
  </style>

  <!-- Button Background -->
  <rect x="50" y="50" width="300" height="100" class="button" />

  <!-- Button Text -->
  <text x="200" y="120" text-anchor="middle" class="button-text">Hover Over Me!</text>

  <!-- Button Shadow (Enhances 3D Effect) -->
  <rect x="55" y="55" width="290" height="90" fill="none" stroke="rgba(0, 0, 0, 0.1)" stroke-width="5" rx="20" ry="20"/>
</svg>
