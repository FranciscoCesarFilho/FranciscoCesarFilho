<!DOCTYPE html>
<html lang="pt-br">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>César Filho - Desenvolvedor de IA</title>
   <style>
       body {
           font-family: Arial, sans-serif;
           max-width: 1200px;
           margin: 0 auto;
           padding: 20px;
           background-color: #0d1117;
           color: #c9d1d9;
       }

       h1 {
           color: #58a6ff;
           font-size: 24px;
           margin-bottom: 20px;
       }

       .description {
           color: #8b949e;
           font-size: 16px;
           line-height: 1.6;
           margin-bottom: 25px;
           max-width: 800px;
       }

       .highlight {
           color: #58a6ff;
           font-weight: bold;
       }

       .tech-icons {
           display: inline-block;
           background-color: #161b22;
           padding: 20px;
           border-radius: 8px;
           margin: 20px 0;
       }

       .tech-icons img {
           margin: 0 5px;
           transition: transform 0.3s ease;
       }

       .tech-icons img:hover {
           transform: scale(1.2);
       }

       .divider {
           border-top: 1px solid #30363d;
           margin: 20px 0;
       }

       .social-links {
           display: flex;
           gap: 10px;
           flex-wrap: wrap;
       }

       .social-links a {
           text-decoration: none;
           transition: opacity 0.3s ease;
       }

       .social-links a:hover {
           opacity: 0.8;
       }
   </style>
</head>
<body>
   <h1>👋 Olá! Eu sou César Filho</h1>
   
   <div class="description">
       Desenvolvedor especializado em tecnologia e expert em <span class="highlight">Inteligência Artificial</span>. 
       Transformo ideias em soluções inovadoras usando IA, Machine Learning e Deep Learning. 
       Além de criar projetos incríveis, compartilho conhecimento e experiências sobre tecnologia 
       em minhas redes sociais. Vamos juntos explorar o futuro da tecnologia! 🚀
   </div>

   <div class="tech-icons">
       <img align="center" alt="César-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
       <img align="center" alt="César-Ts" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
       <img align="center" alt="César-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
       <img align="center" alt="César-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
       <img align="center" alt="César-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
       <img align="center" alt="César-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
       <img align="center" alt="César-Csharp" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg">
   </div>

   <div class="divider"></div>

   <div class="social-links">
       <a href="https://www.youtube.com/@DreamMetaA.I" target="_blank">
           <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube">
       </a>
       <a href="https://www.instagram.com/cesarfilhotech/" target="_blank">
           <img src="https://img.shields.io/badge/-Instagram-%233b45d9?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
       </a>
       <a href="https://www.facebook.com/profile.php?id=100021988306846" target="_blank">
           <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">
       </a>
       <a href="https://x.com/cesarfilhotech" target="_blank">
           <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
       </a>
   </div>

   <script>
       document.querySelectorAll('.tech-icons img').forEach(icon => {
           icon.addEventListener('mouseover', function() {
               this.style.transform = 'scale(1.2)';
           });
           icon.addEventListener('mouseout', function() {
               this.style.transform = 'scale(1)';
           });
       });
   </script>
</body>
</html>
