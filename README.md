<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Banner</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
    }
    .banner {
      position: relative;
      height: 300px;
      background: linear-gradient(135deg, #6a11cb, #2575fc);
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      font-size: 2.5rem;
      overflow: hidden;
    }
    .banner span {
      position: absolute;
      animation: float 5s infinite linear;
    }
    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
      100% { transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="banner">
    <span>🚀 Welcome to My GitHub!</span>
  </div>
  <script>
    // Optional JS: Change banner text dynamically
    const banner = document.querySelector('.banner span');
    const messages = ["🚀 Welcome!", "💻 Code & Coffee", "✨ Explore Projects"];
    let i = 0;
    setInterval(() => {
      i = (i + 1) % messages.length;
      banner.textContent = messages[i];
    }, 3000);
  </script>
</body>
</html>



<div> 
  <p align="center";color="green">👋 Hi there!</p>
<p align="center">⚡ Electrician by trade</p>
<!-- <img width="300" height="533" alt="Image" src="https://github.com/user-attachments/assets/c938ba26-57a1-4d95-9e16-2d89adc81a3d" /> -->
<p align="center">🎓 Self-taught programmer | 💻 HTML & CSS enthusiast</p>
<p align="center">Currently 🌱 Learning JavaScript</p>
</div>



<!--
**sszn4kevo/sszn4kevo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
