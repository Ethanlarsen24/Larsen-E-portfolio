# Larsen-E-portfolio
E-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ethan Larsen – E‑Portfolio</title>
<link rel="preconnect" href="[fonts.googleapis.com](https://fonts.googleapis.com)">
<link href="[fonts.googleapis.com](https://fonts.googleapis.com/css2?family=Oswald:wght@300;400;500;700&family=Inter:wght@300;400;500;700&display=swap)" rel="stylesheet">
<script src="[kit.fontawesome.com](https://kit.fontawesome.com/2d3b0a4d95.js)" crossorigin="anonymous"></script>

<style>
    body {
        margin: 0;
        background-color: #0b0d23;
        color: #f5f5f5;
        font-family: 'Inter', sans-serif;
        scroll-behavior: smooth;
    }

    /* NAVBAR */
    nav {
        width: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 25px 80px;
        background-color: #0b0d23;
        font-weight: 500;
        position: relative;
    }

    nav a {
        color: #f5f5f5;
        text-decoration: none;
        margin-left: 40px;
        font-size: 15px;
        letter-spacing: 1px;
    }

    nav a:hover {
        color: #d4af37;
    }

    .brand {
        font-size: 20px;
        font-weight: 700;
        letter-spacing: 3px;
    }

    /* SECTION WRAPPER */
    section {
        padding: 120px 140px;
        max-width: 1200px;
        margin: auto;
    }

    h1 {
        font-family: 'Oswald', sans-serif;
        font-size: 110px;
        margin: 0;
        line-height: 0.9;
        text-transform: uppercase;
    }

    h2 {
        font-size: 38px;
        margin-top: 0;
        font-family: 'Oswald', sans-serif;
        letter-spacing: 1px;
        color: #d4af37;
        text-transform: uppercase;
    }

    .gold { color: #d4af37; }

    /* HOME IMAGE LAYOUT */
    .home-images {
        position: relative;
        width: 480px;
        height: 520px;
    }

    .img-frame {
        position: absolute;
        border: 4px solid #d4af37;
        width: 260px;
        height: auto;
        background-color: #111326;
    }

    .img-main {
        top: 40px;
        left: 80px;
        width: 260px;
    }

    .img-1 {
        top: -20px;
        left: -20px;
        width: 220px;
    }

    .img-2 {
        bottom: -20px;
        right: -30px;
        width: 230px;
    }

    img {
        width: 100%;
        height: auto;
        display: block;
    }

    /* FOOTER */
    footer {
        text-align: center;
        padding: 40px;
        background-color: #0b0d23;
        border-top: 1px solid #26283c;
    }

    footer a {
        color: #d4af37;
        margin: 0 15px;
        font-size: 25px;
    }

    footer p {
        margin-top: 20px;
        font-size: 14px;
        letter-spacing: 1px;
    }
</style>
</head>

<body>

<!-- NAVIGATION -->
<nav>
    <div class="brand">EL</div>
    <div>
        <a href="#home">HOME</a>
        <a href="#identity">IDENTITY</a>
        <a href="#vision">VISION</a>
        <a href="#resume">RESUME & RESOURCES</a>
        <a href="#reflections">REFLECTIONS</a>
    </div>
</nav>

<!-- HOME SECTION -->
<section id="home" style="display:flex; justify-content:space-between; align-items:center;">
    <div style="max-width:500px;">
        <p class="gold" style="letter-spacing:4px;">MARKETING & SPORT MANAGEMENT</p>
        <h1>Ethan<br>Larsen</h1>
        <p style="font-style:italic; margin-top:10px;">Athlete • Leader • Sales & Marketing Professional</p>

        <p style="margin-top:25px; line-height:1.6;">
            Marketing graduate with a minor in Sport Management from St. Francis Xavier University. 
            Varsity soccer captain, two‑time AUS Champion, and relationship‑focused professional 
            who understands how to market himself as the **sport product** while tailoring his image, message, 
            and value to the **sport consumer** — employers seeking performance, communication, and leadership.
        </p>

        <a href="#identity" style="
            display:inline-block; 
            margin-top:25px;
            background-color:#d4af37;
            padding:14px 28px;
            color:#0b0d23;
            font-weight:700;
            letter-spacing:1px;
            text-decoration:none;
        ">EXPLORE MY STORY →</a>

        <div style="margin-top:40px; display:flex; gap:60px;">
            <div><h3 class="gold">4</h3><p>Years Varsity</p></div>
            <div><h3 class="gold">2×</h3><p>AUS Champion</p></div>
            <div><h3 class="gold">$1,250</h3><p>Raised for Charity</p></div>
        </div>
    </div>

    <div class="home-images">
        <div class="img-frame img-1"><img src="speaking.jpg"></div>
        <div class="img-frame img-main"><img src="headshot.jpg"></div>
        <div class="img-frame img-2"><img src="soccer.jpg"></div>
    </div>
</section>

<!-- IDENTITY SECTION -->
<section id="identity">
    <h2>Identity</h2>

    <p style="line-height:1.6;">
        This page reflects my personal brand and what differentiates me in the sport and business landscape. 
        These qualities form the **brand pillars** I market to future employers.
    </p>

    <h3 class="gold">Strengths & Achievements</h3>
    <ul>
        <li>Captain of StFX AUS Soccer — leading through trust, communication, and example.</li>
        <li>Two‑time AUS Champion — competitive mindset and resilience.</li>
        <li>Built sponsorship relationships that delivered measurable value.</li>
        <li>Executed events and campaigns that strengthened community engagement.</li>
    </ul>

    <h3 class="gold">Top 5 CliftonStrengths</h3>

    <p><strong>Relator:</strong> I build genuine, high‑trust relationships — a key part of my personal brand positioning.</p>
    <p><strong>Achiever:</strong> I thrive in performance‑driven environments and take pride in consistent results.</p>
    <p><strong>Competition:</strong> I’m motivated by high standards and pushing to be the best in any environment.</p>
    <p><strong>Communication:</strong> I connect ideas to people effectively — essential for marketing, sales, and leadership.</p>
    <p><strong>Responsibility:</strong> I deliver on commitments, reinforcing reliability and brand credibility.</p>

    <h3 class="gold">Vision Board</h3>
    <img src="visionboard.jpg" style="width:60%; border:4px solid #d4af37; margin-top:20px;">
</section>

<!-- VISION SECTION -->
<section id="vision">
    <h2>Vision</h2>

    <p>This section demonstrates how I apply **long‑term planning, segmentation, and brand strategy** to my life and career path.</p>

    <h3 class="gold">8 Squares of Vision</h3>

    <ul>
        <li><strong>Current Position:</strong> Marketing graduate, varsity athlete, preparing for a sales and marketing career.</li>
        <li><strong>Strengths:</strong> Leadership, communication, relationship‑building, competitiveness.</li>
        <li><strong>Resources:</strong> Support system, athletic discipline, professional network, education.</li>
        <li><strong>Next Steps:</strong> Secure a full‑time role, expand network, develop hands‑on skills.</li>
        <li><strong>1‑Year Vision:</strong> Entry‑level role, financial independence, continued involvement in sport.</li>
        <li><strong>5‑Year Vision:</strong> Career advancement, leadership responsibility, new experiences.</li>
        <li><strong>10‑Year Vision:</strong> Financial stability, balanced lifestyle, continued personal growth.</li>
        <li><strong>Championship Life:</strong> Long‑term success defined by purpose, balance, and fulfillment.</li>
    </ul>

    <h3 class="gold">Passion to Paycheque</h3>
    <p>
        I believe passion drives long‑term performance. Using segmentation logic, I target roles that align 
        with what motivates me most — relationship‑building, competition, and creating value through people.
        This drives not just income, but sustainable satisfaction.
    </p>
</section>

<!-- RESUME SECTION -->
<section id="resume">
    <h2>Resume & Resources</h2>

    <p>Below is a summary of my professional experience, demonstrating **brand credibility**, **sponsorship value**, and **consumer engagement**.</p>

    <h3 class="gold">Support Squad</h3>
    <ul>
        <li>Coaches who shaped my leadership and discipline.</li>
        <li>Professors who developed my marketing and strategic thinking.</li>
        <li>Professional contacts from sponsorship outreach and community work.</li>
        <li>Family, friends, and teammates who provide personal support.</li>
    </ul>

    <h3 class="gold">Resume</h3>
    <a href="YOUR_RESUME_LINK_HERE" style="color:#d4af37;">Click here to view my resume</a>

    <h3 class="gold">Experience Highlights</h3>
    <ul>
        <li><strong>StFX Soccer Captain:</strong> Leadership, accountability, championship‑level culture building.</li>
        <li><strong>Stick It For Motionball:</strong> Event organizer, fundraiser, sponsorship outreach ($1,250 raised).</li>
        <li><strong>Impact X Marketing Project:</strong> Built a winning social media strategy with real consumer focus.</li>
        <li><strong>Client‑Facing Roles:</strong> Communication, relationship‑building, customer experience.</li>
    </ul>
</section>

<!-- REFLECTIONS SECTION -->
<section id="reflections">
    <h2>Reflections</h2>

    <p>
        My reflections connect my experiences to **sport marketing theories** such as positioning, branding, consumer behavior, 
        and leadership identity. They demonstrate who I am as the “product” entering the workforce.
    </p>

    <p>
        Through university and varsity athletics, I learned the value of balance, accountability, and performance. 
        Working long hours taught me discipline, but I learned that sustainable success requires balance and well‑being.
    </p>

    <p>
        Respect, communication, and relationship‑building became the foundation of my leadership — aligning directly with 
        what employers look for in the sport industry: consistency, trust, and people‑first impact.
    </p>

    <p>
        Looking ahead, I’m driven to enter roles where I can influence outcomes, create value, and grow within competitive 
        environments. My journey reflects a brand built on purpose, work ethic, and the drive to make a long‑term impact.
    </p>
</section>

<!-- FOOTER -->
<footer>
    <a href="mailto:ethanlarsensoccer@gmail.com"><i class="fas fa-envelope"></i></a>
    <a href="tel:9024832253"><i class="fas fa-phone"></i></a>
    <a href="[instagram.com](https://instagram.com/ethan_larsen78)"><i class="fab fa-instagram"></i></a>
    <a href="[linkedin.com](https://www.linkedin.com/in/ethan-larsen-6b20a6318/)"><i class="fab fa-linkedin"></i></a>
    <p>© 2026 Ethan Larsen</p>
</footer>

</body>
</html>
