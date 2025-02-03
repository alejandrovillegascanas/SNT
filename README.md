<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Colombian Flag & Cartoon Farewell</title>
  <style>
    /* Ensure the page takes up the full viewport */
    html, body {
      height: 100%;
      margin: 0;
      padding: 0;
    }
    /* Colombian flag background using a linear gradient:
       - Top 50%: Yellow (#FCD116)
       - Next 25%: Blue (#003893)
       - Bottom 25%: Red (#CE1126)
    */
    body {
      background: linear-gradient(
        to bottom, 
        #FCD116 0%, 
        #FCD116 50%, 
        #003893 50%, 
        #003893 75%, 
        #CE1126 75%, 
        #CE1126 100%
      );
      display: flex;
      align-items: center;
      justify-content: center;
    }
    /* Container for the cartoon character SVG */
    .character-container {
      position: relative;
      width: 400px;
      height: 300px;
    }
  </style>
</head>
<body>
  <div class="character-container">
    <svg width="400" height="300" xmlns="http://www.w3.org/2000/svg">
      <!-- Cartoon Character Face -->
      <circle cx="80" cy="150" r="50" fill="#ffcc99" stroke="#000" stroke-width="2" />
      <!-- Eyes -->
      <circle cx="60" cy="140" r="5" fill="#000" />
      <circle cx="100" cy="140" r="5" fill="#000" />
      <!-- Exaggerated Yelling Mouth -->
      <ellipse cx="80" cy="165" rx="15" ry="10" fill="#e60000" stroke="#000" stroke-width="2" />
      
      <!-- Speech Bubble (a classic investor’s farewell speech) -->
      <rect x="150" y="50" width="220" height="100" rx="15" ry="15" fill="#fff" stroke="#000" stroke-width="2" />
      <!-- Tail connecting the bubble to the character -->
      <polygon points="150,100 130,110 150,110" fill="#fff" stroke="#000" stroke-width="2" />
      <!-- Bold text declaring the final word -->
      <text x="160" y="100" fill="#000" font-family="Arial, sans-serif" font-size="16">
        SCREW THIS, I AM GOING HOME
      </text>
    </svg>
  </div>
</body>
</html>
