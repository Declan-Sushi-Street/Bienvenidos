/* 
   Declan Sushi & Food - Stylesheet
   Designed for GitHub Pages Deployment
*/

@import url('https://fonts.googleapis.com/css2?family=Shojumaru&family=Montserrat:wght@300;400;600;700;800;900&display=swap');

:root {
  --declan-red: #D32F2F;
  --declan-dark-red: #9A0007;
  --declan-gold: #FFD700;
  --declan-bg: #0D0D0D;
  --declan-card: #171717;
  --declan-border: #2A2A2A;
}

body {
  background-color: var(--declan-bg);
  color: #FFFFFF;
  font-family: 'Montserrat', sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.font-shojumaru {
  font-family: 'Shojumaru', cursive, sans-serif;
}

/* Background Patterns */
.seigaiha-bg {
  background-color: var(--declan-bg);
  background-image: radial-gradient(var(--declan-red) 0.75px, transparent 0.75px), radial-gradient(var(--declan-red) 0.75px, var(--declan-bg) 0.75px);
  background-size: 30px 30px;
  background-position: 0 0, 15px 15px;
}

/* Custom Scrollbars */
::-webkit-scrollbar {
  width: 8px;
  height: 6px;
}

::-webkit-scrollbar-track {
  background: var(--declan-bg);
}

::-webkit-scrollbar-thumb {
  background: var(--declan-red);
  border-radius: 4px;
}

::-webkit-scrollbar-thumb:hover {
  background: var(--declan-dark-red);
}