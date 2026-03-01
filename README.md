<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Epistemic Feed - Knowledge for a Better Tomorrow</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
        font-family:'Poppins', sans-serif;
    }

    body{
        background:#0f0f0f;
        color:white;
    }

    header{
        background:#111;
        padding:20px 10%;
        display:flex;
        justify-content:space-between;
        align-items:center;
    }

    header h1{
        color:#ffcc00;
        font-size:28px;
    }

    nav a{
        color:white;
        text-decoration:none;
        margin-left:20px;
        font-weight:500;
        transition:0.3s;
    }

    nav a:hover{
        color:#ffcc00;
    }

    .hero{
        padding:80px 10%;
        text-align:center;
        background:linear-gradient(to right, #000000, #1a1a1a);
    }

    .hero h2{
        font-size:40px;
        margin-bottom:20px;
        color:#ffcc00;
    }

    .hero p{
        font-size:18px;
        max-width:700px;
        margin:auto;
        line-height:1.6;
    }

    .btn{
        display:inline-block;
        margin-top:30px;
        padding:12px 30px;
        background:#ff0000;
        color:white;
        text-decoration:none;
        border-radius:30px;
        font-weight:600;
        transition:0.3s;
    }

    .btn:hover{
        background:#cc0000;
    }

    .section{
        padding:60px 10%;
        text-align:center;
    }

    .section h3{
        font-size:30px;
        margin-bottom:30px;
        color:#ffcc00;
    }

    .cards{
        display:grid;
        grid-template-columns:repeat(auto-fit, minmax(250px, 1fr));
        gap:20px;
    }

    .card{
        background:#1a1a1a;
        padding:30px;
        border-radius:10px;
        transition:0.3s;
    }

    .card:hover{
        transform:translateY(-10px);
        background:#222;
    }

    footer{
        background:#111;
        text-align:center;
        padding:20px;
        margin-top:40px;
        font-size:14px;
        color:#aaa;
    }

    @media(max-width:768px){
        .hero h2{
            font-size:28px;
        }
    }
</style>
</head>

<body>

<header>
    <h1>Epistemic Feed</h1>
    <nav>
        <a href="#about">About</a>
        <a href="#topics">Topics</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Knowledge for a Better Tomorrow 🚀</h2>
    <p>
        Exploring mind-blowing facts, What If scenarios, science mysteries, 
        and the future of technology. Boost your curiosity every day!
    </p>
    <a href="https://www.youtube.com/@EpistemicFeed" target="_blank" class="btn">
        Subscribe on YouTube
    </a>
</section>

<section id="about" class="section">
    <h3>About The Channel</h3>
    <p>
        Welcome to Epistemic Feed! We explore amazing facts, science, space,
        mysteries, and powerful "What If" scenarios that make you think deeper.
        Our mission is to increase curiosity and help you learn something new every day.
    </p>
</section>

<section id="topics" class="section">
    <h3>What You’ll Find Here</h3>
    <div class="cards">
        <div class="card">
            <h4>Amazing Facts</h4>
            <p>Mind-blowing and interesting facts that expand your knowledge.</p>
        </div>
        <div class="card">
            <h4>Science & Space</h4>
            <p>Discover the universe, AI, and the future of technology.</p>
        </div>
        <div class="card">
            <h4>Mysteries</h4>
            <p>Unsolved mysteries and fascinating unknown stories.</p>
        </div>
    </div>
</section>

<section id="contact" class="section">
    <h3>Contact</h3>
    <p>Business Email: theindian850@gmail.com</p>
    <p>Instagram: @epistemic_feed</p>
</section>

<footer>
    © 2026 Epistemic Feed | Made with Passion for Knowledge
</footer>

</body>
</html>
