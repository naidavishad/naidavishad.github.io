---
layout: default
title: Home
---

<style>
* { box-sizing: border-box; }
.hero-card {
  background: linear-gradient(135deg, #1a1a2e, #16213e);
  color: white; border-radius: 16px;
  padding: 50px 40px; margin-bottom: 30px; text-align: center;
}
.hero-card h1 { font-size: 30px; font-weight: 700; margin-bottom: 8px; }
.hero-card .reg { color: #aaa; font-size: 14px; margin-bottom: 6px; }
.hero-card .badge {
  display: inline-block; background: #e94560;
  color: white; padding: 5px 16px; border-radius: 20px;
  font-size: 13px; margin-top: 10px;
}
.info-grid {
  display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 20px; margin-bottom: 30px;
}
.info-card {
  background: white; border-radius: 12px; padding: 28px;
  box-shadow: 0 3px 15px rgba(0,0,0,0.08);
  border-left: 4px solid #e94560;
}
.info-card h3 { color: #e94560; font-size: 16px; margin-bottom: 12px; }
.info-card p, .info-card li { color: #555; font-size: 14px; line-height: 1.8; }
.info-card ul { padding-left: 18px; }
.nav-cards {
  display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 16px;
}
.nav-card {
  background: white; border-radius: 12px; padding: 24px;
  text-align: center; text-decoration: none; color: #1a1a2e;
  box-shadow: 0 3px 15px rgba(0,0,0,0.08);
  border-top: 4px solid #e94560;
  transition: transform 0.2s;
}
.nav-card:hover { transform: translateY(-4px); color: #e94560; }
.nav-card .icon { font-size: 32px; margin-bottom: 10px; }
.nav-card h3 { font-size: 15px; font-weight: 600; }
</style>

<div class="hero-card">
  <h1>Nahida Wishad Ali Khan</h1>
  <div class="reg">Registration No: 2025-BSCPE-140</div>
  <div class="badge">BS Computer Engineering · Semester 2 · UET Lahore</div>
</div>

<div class="info-grid">
  <div class="info-card">
    <h3>👩💻 Professional Profile</h3>
    <p>Welcome to my official academic portfolio. This platform documents my 8-semester journey in Computer Engineering, focusing on technical excellence and structured learning.</p>
  </div>
  <div class="info-card">
    <h3>🎯 Current Focus</h3>
    <ul>
      <li>Programming Fundamentals</li>
      <li>Database Management Systems</li>
      <li>Technical Stack: C++, MySQL, GitHub, Jekyll</li>
    </ul>
  </div>
  <div class="info-card">
    <h3>🏆 Objective</h3>
    <p>To build a comprehensive repository of academic projects and lab implementations across all 8 semesters of Computer Engineering.</p>
  </div>
</div>

<div class="nav-cards">
  <a href="/about/" class="nav-card"><div class="icon">👤</div><h3>About Me</h3></a>
  <a href="/blog/" class="nav-card"><div class="icon">📖</div><h3>My Story</h3></a>
  <a href="/semester1/" class="nav-card"><div class="icon">📚</div><h3>Semester 1</h3></a>
  <a href="/semester2/" class="nav-card"><div class="icon">🎯</div><h3>Semester 2</h3></a>
</div>
