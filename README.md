<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Yuvatha Creations</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: linear-gradient(135deg, #000000, #1a1a1a);
    color: white;
}

/* Header */
header {
    text-align: center;
    padding: 40px 20px;
    background: radial-gradient(circle, #ff4500, #000);
}

header h1 {
    font-size: 42px;
    margin: 0;
    letter-spacing: 2px;
}

header p {
    color: #ffcc00;
    margin-top: 10px;
}

/* Tabs */
.tabs {
    display: flex;
    justify-content: center;
    background: #111;
}

.tabs button {
    background: none;
    border: none;
    color: white;
    padding: 15px 30px;
    cursor: pointer;
    font-size: 16px;
    transition: 0.3s;
}

.tabs button:hover,
.tabs button.active {
    background: #ff4500;
}

/* Content */
.content {
    display: none;
    padding: 30px;
    max-width: 1000px;
    margin: auto;
}

.content.active {
    display: block;
}

/* Cards */
.card {
    background: #1f1f1f;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 10px;
    box-shadow: 0 0 15px rgba(255,69,0,0.3);
}

/* Portfolio list */
ul {
    list-style: none;
    padding: 0;
}

ul li {
    padding: 10px 0;
    border-bottom: 1px solid #333;
}

/* YouTube section */
.video {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.video a {
    color: #ffcc00;
    text-decoration: none;
    font-weight: bold;
}

.video a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background: #000;
    color: #aaa;
    font-size: 14px;
}
</style>
</head>

<body>

<header>
    <h1>🔥 YUVATHA CREATIONS 🔥</h1>
    <p>Dynamics 365 CRM Developer| Editor | Designer | Dreamer</p>
</header>

<div class="tabs">
    <button class="tabBtn active" onclick="openTab('portfolio')">My Portfolio</button>
    <button class="tabBtn" onclick="openTab('youtube')">YouTube Channel</button>
</div>

<!-- Portfolio Tab -->
<div id="portfolio" class="content active">
    <div class="card">
        <h2>👤 About Me</h2>
        <p>
            Microsoft Dynamics 365 & Power Platform Developer with 4+ years of industry experience 🚀

I specialize in Dynamics 365 CE, Power Automate, and Microsoft Power Platform, building smart CRM solutions that streamline business processes and boost efficiency.
On this channel, I share: 📘 Practical learning on Dynamics 365 & Power Platform

🎓 Career guidance for students & working professionals
📸 My passion for photography & creativity
💡 Real-world insights from industry experience

<b>🚀 Coming soon:</b>

I’ll be sharing how the software industry actually works today, what beginners should prepare for entry-level jobs, which domains are booming, and how to plan long-term career growth based on your skills.
Everything here is created purely out of passion ♾️❣️🤞 — to teach, guide, and inspire others.
If my content helps you grow, please support me guys 😊
Let’s learn, build, and grow together 💙
        </p>
    </div>

    <div class="card">
        <h2>🛠 Skills</h2>
        <ul>
            <li>🎬 Video Editing (Premiere Pro / After Effects)</li>
            <li>🎨 Graphic Design</li>
            <li>🔥 YouTube Content Creation</li>
            <li>💻 HTML & CSS Basics</li>
        </ul>
    </div>

    <div class="card">
        <h2>🏆 Projects</h2>
        <ul>
            <li>Short Film Edits</li>
            <li>YouTube Intro Animations</li>
            <li>Reels & Shorts Editing</li>
        </ul>
    </div>
</div>

<!-- YouTube Tab -->
<div id="youtube" class="content">
    <div class="card">
        <h2>▶️ My YouTube Channel</h2>
        <p>Watch my latest creative works below 👇</p>
    </div>

    <div class="card video">
        <span>🔥 Cinematic Intro Video</span>
        <a href="https://www.youtube.com/watch?v=YOUR_VIDEO_ID" target="_blank">Watch Now</a>
    </div>

    <div class="card video">
        <span>💥 Motivational Edit</span>
        <a href="https://www.youtube.com/watch?v=YOUR_VIDEO_ID" target="_blank">Watch Now</a>
    </div>

    <div class="card video">
        <span>🎥 Short Film Trailer</span>
        <a href="https://www.youtube.com/watch?v=YOUR_VIDEO_ID" target="_blank">Watch Now</a>
    </div>
</div>

<footer>
    © 2026 Yuvatha Creations | All Rights Reserved
</footer>

<script>
function openTab(tabName) {
    let contents = document.querySelectorAll(".content");
    let buttons = document.querySelectorAll(".tabBtn");

    contents.forEach(c => c.classList.remove("active"));
    buttons.forEach(b => b.classList.remove("active"));

    document.getElementById(tabName).classList.add("active");
    event.currentTarget.classList.add("active");
}
</script>

</body>
</html>
