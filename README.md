<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Maithili Kadukar | Portfolio</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
/* ===== GLOBAL ===== */
body {
    margin: 0;
    font-family: "Poppins", sans-serif;
    text-align: center;
    color: #2e285f;
    background: linear-gradient(140deg, #f3e9ff, #ece4ff, #f7efff);
    overflow-x: hidden;
    animation: bgMove 10s infinite alternate ease-in-out;
}

@keyframes bgMove {
    0% {background-position: left;}
    100% {background-position: right;}
}

/* ===== CONTAINER ===== */
.container {
    width: 85%;
    margin: auto;
    padding: 25px;
    animation: fadeIn 1.2s ease-in-out;
}

@keyframes fadeIn {
    from {opacity: 0; transform: translateY(15px);}
    to {opacity: 1; transform: translateY(0);}
}

/* ===== HEADING ===== */
h1 {
    font-size: 38px;
    font-weight: 700;
    background: linear-gradient(90deg, #6f36ff, #b38cff);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

.typing {
    margin-bottom: 18px;
    font-size: 18px;
    overflow: hidden;
    white-space: nowrap;
    border-right: 2px solid #8f5fff;
    animation: type 4s steps(35) infinite alternate, blink .7s infinite;
    color: #5a497d;
}

@keyframes type {
    0% {width: 0;}
    100% {width: 300px;}
}

@keyframes blink {
    50% {border-color: transparent;}
}

/* ===== CARD ===== */
.card {
    margin: 25px 0;
    padding: 25px;
    background: rgba(255,255,255,0.45);
    border-radius: 20px;
    backdrop-filter: blur(15px);
    border: 1px solid rgba(255,255,255,0.6);
    animation: slideIn .8s ease;
    transition: .4s;
    box-shadow: 0px 8px 22px rgba(128,77,255,0.15);
}

.card:hover {
    transform: translateY(-6px) scale(1.03);
    box-shadow: 0px 12px 26px rgba(128,77,255,0.25);
}

/* ===== TAGS ===== */
.card span {
    display: inline-block;
    margin: 6px;
    padding: 10px 18px;
    border-radius: 24px;
    background: linear-gradient(90deg, #d6c3ff, #eee7ff);
    font-weight: 500;
    font-size: 14px;
    transition: .3s;
}

.card span:hover {
    transform: scale(1.12);
    background: linear-gradient(90deg, #9b63ff, #b788ff);
    color: #fff;
}

/* ===== BUTTON ===== */
.btn {
    padding: 13px 30px;
    display: inline-block;
    background: linear-gradient(90deg, #7d47ff, #b085ff);
    border-radius: 30px;
    color: #fff;
    text-decoration: none;
    font-size: 15px;
    font-weight: 600;
    transition: .35s;
    box-shadow: 0px 0px 12px rgba(140,100,255,0.25);
}

.btn:hover {
    transform: scale(1.08);
    box-shadow: 0px 0px 16px rgba(96,47,255,0.45);
}

/* Footer */
footer {
    margin-top: 10px;
    font-size: 13px;
    color: #7c6d9b;
    animation: fadeInUp 1.2s ease;
}

@keyframes fadeInUp {
    0% {opacity:0; transform:translateY(10px);}
    100% {opacity:1; transform:translateY(0);}
}
</style>

</head>
<body>

<div class="container">
    <h1>Hello, I'm <span>Maithili Vijay Kadukar</span> 💜</h1>
    <div class="typing">BCA Student | Developer | AI Enthusiast 👩‍💻</div>
<div
    <div class="card skills">
        <h2>✨ Skills</h2>
        <span>Python</span><span>C</span><span>C++</span><span>MySQL</span>
        <span>HTML</span><span>CSS</span>
        <span>AI/ML Basics</span><span>Numpy</span><span>Pandas</span>
        <span>Model Building</span><span>Data Preprocessing</span>
        <span>Supervised & Unsupervised ML</span>
    </div>
<div
    <div class="card projects">
        <h2>🚀 Projects</h2>
        <span>MediChat (Python, HTML, CSS)</span><br><br>
        <span>Restaurant Billing System (C & Python)</span>
    </div>
<div
    <div class="card certificate">
        <h2>🎓 Certifications</h2>
        <span>Web Development (Corizo)</span>
        <span>C++ (MKCL)</span>
    </div>
<div
    <div class="card contact">
        <h2>📬 Contact</h2>
        <p><b>GitHub:</b> maithilikadukar</p>
        <p><b>Email:</b> <a href="maithlikadukar@gmail.com">maithlikadukar@gmail.com</a></p>
        <a href="https://github.com/maithilikadukar" target="_blank" class="btn">Visit My GitHub</a>
    </div>
</div>

<footer>Made with 💖 & Passion — Maithili</footer>

</body>
</html>


