## Hi there 👋
<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Odmagicalworld</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #d1c4e9, #b39ddb);
            color: #333;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }
        header {
            background-color: #7e57c2;
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            animation: slideDown 1s ease forwards;
        }
        .logo {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        nav {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            background-color: #9575cd;
            padding: 12px 0;
            animation: fadeIn 2s ease forwards;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ffd54f;
        }
        .hero {
            text-align: center;
            padding: 60px 20px;
            animation: fadeInUp 2s ease forwards;
        }
        .hero h1 {
            font-size: 40px;
            margin-bottom: 20px;
            color: #512da8;
        }
        .hero p {
            font-size: 18px;
        }
        .section {
            padding: 50px 20px;
            max-width: 1100px;
            margin: auto;
            animation: fadeIn 2s ease forwards;
        }
        .section h2 {
            font-size: 30px;
            text-align: center;
            margin-bottom: 20px;
            color: #5e35b1;
        }
        .section p {
            font-size: 17px;
            line-height: 1.7;
            text-align: center;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 20px;
            margin-top: 25px;
        }
        .gallery img {
            width: 100%;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
            transition: transform 0.3s;
        }
        .gallery img:hover {
            transform: scale(1.07);
        }
        footer {
            background-color: #7e57c2;
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 50px;
            animation: fadeIn 2s ease forwards;
        }
        video {
            width: 100%;
            max-width: 600px;
            height: auto;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
        @keyframes fadeInUp {
            0% { opacity: 0; transform: translateY(30px); }
            100% { opacity: 1; transform: translateY(0); }
        }
        @keyframes slideDown {
            0% { transform: translateY(-100%); }
            100% { transform: translateY(0); }
        }
        @media (max-width: 600px) {
            .hero h1 {
                font-size: 28px;
            }
            .hero p, .section p {
                font-size: 15px;
            }
            nav {
                flex-direction: column;
                align-items: center;
            }
            .section h2 {
                font-size: 22px;
            }
            .logo {
                width: 70px;
                height: 70px;
            }
        }
    </style>
</head>
<body>
<header>
    <img src="https://cdn-icons-png.flaticon.com/512/10216/10216876.png" alt="OD MAGICAL WORLD Logo" class="logo">
    <h1>OD MAGICAL WORLD</h1>
    <p>Welcome to the world of art, fantasy & AI animations!</p>
</header>
<nav>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#animations">AI Animations</a>
    <a href="#aiDesigns">AI Designs</a>
    <a href="#contact">Contact</a>
</nav>
<section class="hero">
    <h1>Explore the Magic</h1>
    <p>Discover art, AI animations and fantasy stories crafted with love.</p>
</section>
<section class="section" id="about">
    <h2>About OD MAGICAL WORLD</h2>
    <p>OD MAGICAL WORLD is a space where creativity, art and technology come together. From AI-generated artwork to whimsical animations, we bring fantasy to life.</p>
</section>
<section class="section" id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
        <img src="https://placekitten.com/400/300" alt="Artwork 1">
        <img src="https://placekitten.com/401/300" alt="Artwork 2">
        <img src="https://placekitten.com/402/300" alt="Artwork 3">
        <img src="https://placekitten.com/403/300" alt="Artwork 4">
    </div>
</section>
<section class="section" id="animations">
    <h2>AI Animations</h2>
    <p>Experience stunning AI-generated animations that bring fantasy to life. Watch a glimpse below:</p>
    <div style="text-align:center;">
        <video controls autoplay muted loop>
            <source src="https://cdn.pixabay.com/vimeo/123181720/ai-animation-1080p.mp4?width=1280&hash=fb1d68933ec741d4e3767a7d8b73420c740f5cf2" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</section>
<section class="section" id="aiDesigns">
    <h2>AI Picture & Design Showcase</h2>
    <div class="gallery">
        <img src="https://cdn.pixabay.com/photo/2023/03/24/12/15/ai-7875015_1280.jpg" alt="AI Design 1">
        <img src="https://cdn.pixabay.com/photo/2023/04/02/09/25/ai-7894403_1280.jpg" alt="AI Design 2">
        <img src="https://cdn.pixabay.com/photo/2024/02/15/13/20/artificial-intelligence-8575881_1280.jpg" alt="AI Design 3">
        <img src="https://cdn.pixabay.com/photo/2024/01/08/08/34/ai-art-8492514_1280.jpg" alt="AI Design 4">
    </div>
    <h3 style="text-align:center; margin-top:30px;">More AI Animation Samples</h3>
    <div style="text-align:center;">
        <video controls autoplay muted loop style="margin-top: 20px;">
            <source src="https://cdn.pixabay.com/vimeo/933081442/ai-brain-153763.mp4?width=1280&hash=4cb7470a9a203212f6aee14cfe560ef376d2657b" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</section>
<section class="section" id="contact">
    <h2>Contact</h2>
    <p>Email: contact@odmagicalworld.com</p>
    <p>Follow us on Instagram: @odmagicalworld</p>
</section>
<footer>
    &copy; 2025 OD MAGICAL WORLD. All rights reserved.
</footer>
</body>
</html>
<!--
**ODMAGAICALWORLD/Odmagaicalworld** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
