---
permalink: /
title: "Welcome to Learning English with Michael Sipper"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Learning English with Michael Sipper</title>
  <style>
    :root{
      --bg:#f7f9fb;
      --card:#ffffff;
      --muted:#6c757d;
      --accent:#2f80ed;
      --accent-dark:#2468c9;
      --border:#e6eef9;
      --maxw:1100px;
      --radius:10px;
      --pad:20px;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }

    html,body{height:100%;}
    body{
      margin:0;
      min-height:100%;
      background:var(--bg);
      color:#222;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.55;
      padding:40px 16px;
      display:flex;
      justify-content:center;
    }

    .container{
      width:100%;
      max-width:var(--maxw);
    }

    header{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:16px;
      margin-bottom:28px;
    }

    .brand {
      display:flex;
      flex-direction:column;
      gap:4px;
    }

    .brand h1{
      margin:0;
      font-size:1.35rem;
      color:#213547;
      letter-spacing:0.1px;
    }

    .brand p{
      margin:0;
      font-size:0.95rem;
      color:var(--muted);
    }

    nav{
      display:flex;
      gap:12px;
      align-items:center;
      flex-wrap:wrap;
    }

    nav a{
      text-decoration:none;
      color:var(--accent);
      padding:8px 12px;
      border-radius:8px;
      font-weight:600;
    }

    nav a:hover{
      background:linear-gradient(180deg,var(--border),transparent);
      color:var(--accent-dark);
    }

    main{
      background:linear-gradient(180deg, rgba(255,255,255,0.9), rgba(255,255,255,0.95));
      border:1px solid var(--border);
      border-radius:var(--radius);
      padding:var(--pad);
      box-shadow:0 6px 18px rgba(46,61,73,0.06);
    }

    .hero{
      display:grid;
      grid-template-columns:1fr 320px;
      gap:24px;
      align-items:start;
    }

    @media (max-width:860px){
      .hero{grid-template-columns:1fr;}
      nav{justify-content:flex-start;}
    }

    .lead{
      margin:0 0 8px 0;
      color:#17202a;
      font-size:1.02rem;
    }

    .lead strong{color:#0f1720;}

    .summary{
      margin:0 0 18px 0;
      color:var(--muted);
    }

    .cards{
      display:flex;
      flex-direction:column;
      gap:12px;
    }

    .card{
      background:var(--card);
      border-radius:8px;
      padding:14px;
      border:1px solid #eef4fb;
    }

    .card h3{
      margin:0 0 6px 0;
      font-size:1rem;
      color:#213547;
    }

    .card p{
      margin:0;
      color:var(--muted);
      font-size:0.95rem;
    }

    .links{
      margin-top:16px;
      display:flex;
      flex-direction:column;
      gap:8px;
    }

    .links a{
      color:var(--accent);
      text-decoration:none;
      font-weight:600;
    }

    .links a:hover{text-decoration:underline;}

    aside.sticky{
      position:relative;
      top:0;
    }

    .cta{
      display:flex;
      gap:10px;
      margin-top:16px;
    }

    .btn{
      display:inline-block;
      padding:10px 14px;
      border-radius:8px;
      text-decoration:none;
      font-weight:600;
      border:1px solid transparent;
    }

    .btn-primary{
      background:var(--accent);
      color:white;
      border-color:var(--accent-dark);
    }

    .btn-outline{
      background:transparent;
      color:var(--accent);
      border-color:var(--border);
    }

    footer{
      margin-top:22px;
      font-size:0.9rem;
      color:var(--muted);
      display:flex;
      justify-content:space-between;
      align-items:center;
      gap:12px;
      flex-wrap:wrap;
    }

    .meta small{color:var(--muted);}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <h1>Learning English with Michael Sipper</h1>
        <p>Free, comprehensive resources for students, faculty, and community members</p>
      </div>

      <nav aria-label="Primary">
        <a href="#resources">Resources</a>
        <a href="#conversation-clubs">Conversation Clubs</a>
        <a href="#library">Resource Library</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <section class="hero" aria-labelledby="welcome-heading">
        <div>
          <h2 id="welcome-heading" class="lead">Welcome to Learning English with Michael Sipper</h2>
          <p class="summary">
            A free, comprehensive platform designed to support students, faculty, and community members on their English language journey.
            Whether you are preparing for academic success, professional advancement, or improving everyday communication, you will find curated materials,
            structured learning paths, and community-led conversation practice here.
          </p>

          <div class="cards" id="resources" aria-label="Primary resources">
            <div class="card">
              <h3>Who this site serves</h3>
              <p>
                International students adapting to academic English, faculty seeking teaching resources, professionals improving workplace communication,
                and community members learning English for daily life.
              </p>
            </div>

            <div class="card" id="conversation-clubs">
              <h3>Conversation Clubs & Practice</h3>
              <p>Weekly moderated conversation sessions designed to build fluency and confidence. Join a group that matches your proficiency and objectives.</p>
              <div class="links">
                <a href="conversation-club-schedule.html">Conversation Club Schedule</a>
                <a href="signup-conversation.html">Sign up for a session</a>
              </div>
            </div>

            <div class="card" id="library">
              <h3>Resource Library</h3>
              <p>Curated lesson plans, grammar worksheets, listening modules, and test preparation materials organized by proficiency (A1–C2).</p>
              <div class="links">
                <a href="EnglishHub.html">English Learning Materials (full page)</a>
                <a href="downloads/">Download Center (PDFs)</a>
                <a href="test-prep/">TOEFL / IELTS Preparation</a>
              </div>
            </div>

            <div class="card" id="about">
              <h3>Program Approach</h3>
              <p>
                The program emphasizes communicative practice, academic English for university success, and community engagement. Materials are usable
                in classroom settings or for independent study.
              </p>
            </div>
          </div>
        </div>

        <aside class="sticky" aria-label="Quick links and contact">
          <div class="card">
            <h3>Quick Links</h3>
            <div class="links">
              <a href="README.md">Main README</a>
              <a href="EnglishHub.html">English Hub (full resource page)</a>
              <a href="vocabulary/">Vocabulary Lists (Anki-ready)</a>
              <a href="pronunciation/">Pronunciation & Listening</a>
              <a href="placement-test.html">Placement Assessment</a>
            </div>

            <div class="cta" style="margin-top:12px;">
              <a class="btn btn-primary" href="resources@university.edu" onclick="location.href='mailto:resources@university.edu'">Contact</a>
              <a class="btn btn-outline" href="schedule.html">Book Consultation</a>
            </div>
          </div>

          <div class="card" style="margin-top:12px;">
            <h3>Getting Started</h3>
            <p style="margin:0;">If you are unsure of your level, take the placement assessment and begin with the recommended learning path.</p>
            <div class="links" style="margin-top:10px;">
              <a href="placement-test.html">Take placement assessment</a>
              <a href="learning-paths.html">View learning paths</a>
            </div>
          </div>
        </aside>
      </section>

      <footer>
        <div class="meta"><small>© 2025 Michael Sipper — Learning English hub</small></div>
        <div><small>Last updated: November 2, 2025</small></div>
      </footer>
    </main>
  </div>
</body>
</html>


