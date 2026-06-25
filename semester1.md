---
layout: default
title: Semester 1
permalink: /semester1/
---

<style>
.sem-hero {
  background: linear-gradient(135deg, #1a1a2e, #16213e);
  color: white; border-radius: 16px;
  padding: 40px; text-align: center; margin-bottom: 30px;
}
.sem-hero h1 { font-size: 28px; margin-bottom: 8px; }
.sem-hero p { color: #aaa; font-size: 14px; }
.back-btn {
  display: inline-block; margin-bottom: 24px;
  background: #e94560; color: white;
  padding: 8px 20px; border-radius: 20px;
  text-decoration: none; font-size: 13px;
}
.section-card {
  background: white; border-radius: 12px; padding: 30px;
  margin-bottom: 24px; box-shadow: 0 3px 15px rgba(0,0,0,0.08);
}
.section-card h2 {
  color: #e94560; font-size: 20px; margin-bottom: 16px;
  border-bottom: 2px solid #f4f6f9; padding-bottom: 10px;
}
.subjects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  margin-top: 15px;
}
.subject-card {
  position: relative;
  background: #ffffff;
  border-radius: 16px;
  padding: 24px 20px;
  text-align: left;
  border: 1px solid #eaeaea;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.03);
  transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  overflow: hidden;
}
.subject-card::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 4px;
  height: 100%;
  background: #e94560;
  transition: width 0.2s ease;
}
.subject-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 12px 24px rgba(233, 69, 96, 0.1);
  border-color: rgba(233, 69, 96, 0.2);
}
.subject-card:hover::before {
  width: 6px;
}
.subject-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 12px;
}
.subject-card .icon {
  font-size: 32px;
  background: #fff0f2;
  width: 48px;
  height: 48px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 12px;
}
.subject-type-header {
  font-size: 16px;
  font-weight: 700;
  color: #1a1a2e;
  margin: 25px 0 15px 0;
  display: flex;
  align-items: center;
  gap: 8px;
  border-left: 4px solid #e94560;
  padding-left: 10px;
}
.subject-type-header:first-of-type {
  margin-top: 10px;
}
.subject-card .name {
  font-size: 15px;
  font-weight: 700;
  color: #1a1a2e;
  line-height: 1.4;
  margin-bottom: 6px;
}
.subject-card .teacher {
  font-size: 13px;
  color: #777;
  display: flex;
  align-items: center;
  gap: 6px;
}
.subject-card .teacher::before {
  content: "👨‍🏫";
  font-size: 12px;
}
.story-card {
  background: white; border-radius: 12px; padding: 24px;
  margin-bottom: 14px; box-shadow: 0 3px 15px rgba(0,0,0,0.08);
  border-left: 4px solid #e94560;
}
.story-card h3 { color: #1a1a2e; font-size: 16px; margin-bottom: 10px; }
.story-card li { color: #555; font-size: 14px; line-height: 1.9; }
.posts-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 16px;
  margin-top: 15px;
}
.post-card {
  display: block;
  background: #f9f9f9;
  border-radius: 8px;
  padding: 18px;
  text-decoration: none;
  border-left: 4px solid #e94560;
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
  transition: transform 0.2s, background-color 0.2s;
}
.post-card:hover {
  transform: translateY(-2px);
  background: #fef6f8;
}
.post-title {
  font-size: 14px;
  font-weight: 600;
  color: #1a1a2e;
  margin-bottom: 8px;
}
.post-meta {
  font-size: 11px;
  color: #888;
  display: flex;
  justify-content: space-between;
}
</style>

<a href="/blog/" class="back-btn">← Back to My Story</a>

<div class="sem-hero">
  <h1>📚 Semester 1</h1>
  <p>My first semester at UET Lahore · BS Computer Engineering</p>
</div>

<div class="section-card">
  <h2>📖 About This Semester</h2>
  <p style="color:#555; font-size:14px; line-height:1.9;">My first semester was where everything began. Coming in with no prior computer science background, I had to learn fast. From adapting to the engineering culture of UET Lahore to writing my first lines of code in Programming Fundamentals, every week brought new challenges and new lessons. This semester built the foundation of who I am as an engineering student.</p>
</div>

<div class="section-card">
  <h2>📋 Subjects & Teachers</h2>
  <div class="subjects-grid">
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">💻</div>
        <span class="type-badge theory">Theory</span>
      </div>
      <div class="name">Programming Fundamentals</div>
      <div class="teacher">Dr. Bilal Ahmad</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">📐</div>
        <span class="type-badge theory">Theory</span>
      </div>
      <div class="name">Calculus</div>
      <div class="teacher">Mam Arshi</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">🧮</div>
        <span class="type-badge theory">Theory</span>
      </div>
      <div class="name">Discrete Mathematics</div>
      <div class="teacher">Sir Abdullah Bilal</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">🖥️</div>
        <span class="type-badge theory">Theory</span>
      </div>
      <div class="name">AICT</div>
      <div class="teacher">Mam Asia</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">⚛️</div>
        <span class="type-badge theory">Theory</span>
      </div>
      <div class="name">Applied Physics</div>
      <div class="teacher">Mam Nosheen</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">📖</div>
        <span class="type-badge theory">Theory</span>
      </div>
      <div class="name">Fahm-e-Quran</div>
      <div class="teacher">Dr. Aslam</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">🔬</div>
        <span class="type-badge lab">Lab</span>
      </div>
      <div class="name">Lab - PF</div>
      <div class="teacher">Dr. Bilal</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">💾</div>
        <span class="type-badge lab">Lab</span>
      </div>
      <div class="name">Lab - AICT</div>
      <div class="teacher">Mam Asia</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">🧪</div>
        <span class="type-badge lab">Lab</span>
      </div>
      <div class="name">Lab - Physics</div>
      <div class="teacher">Mam Sherish</div>
    </div>
  </div>
</div>

<div class="section-card">
  <h2>📝 Posts</h2>
  <p style="color:#888; font-size:13px; margin-bottom:15px;">A collection of my posts and reflections for this semester.</p>
  <div class="posts-grid">
    {% assign semester_posts = site.posts | where: "category", "semester1" | sort: "date" %}
    {% if semester_posts.size > 0 %}
      {% for post in semester_posts %}
        <a href="{{ post.url | relative_url }}" class="post-card">
          <div class="post-title">{{ post.title }}</div>
          <div class="post-meta">
            <span class="post-date">📅 {{ post.date | date: "%b %d, %Y" }}</span>
            {% if post.read_time %}
              <span class="post-readtime">⏱️ {{ post.read_time }}</span>
            {% endif %}
          </div>
        </a>
      {% endfor %}
    {% else %}
      <p style="color:#777; font-size:14px; font-style:italic;">No posts added yet for this semester. They will appear here once published.</p>
    {% endif %}
  </div>
</div>

<div class="section-card">
  <h2>📝 My Semester 1 Story</h2>

  <div class="story-card">
    <h3>🏛️ The Beginning: Pressure & Expectations</h3>
    <ul>
      <li><strong>Post-FSC Stress:</strong> Navigating intense societal and parental pressure during university admissions.</li>
      <li><strong>Achievement of UET Lahore:</strong> The pride of joining one of Pakistan's top engineering institutions.</li>
      <li><strong>Reality Check:</strong> Realizing that admission was only the start of a much bigger challenge.</li>
    </ul>
  </div>

  <div class="story-card">
    <h3>💻 Programming Fundamentals: The Real Start</h3>
    <ul>
      <li><strong>Foundation of Learning:</strong> Introduction to coding and development of logical thinking with Dr. Bilal Ahmad.</li>
      <li><strong>Expression Gap:</strong> Understanding concepts in the lab but struggling in theoretical exams.</li>
      <li><strong>Performance Imbalance:</strong> Identifying the gap between practical skills and written results.</li>
    </ul>
  </div>

  <div class="story-card">
    <h3>⏳ Managing Academic Pressure</h3>
    <ul>
      <li><strong>Heavy Workload:</strong> Simultaneously handling assignments, quizzes, and projects.</li>
      <li><strong>Strategic Planning:</strong> Developing time management skills to stay ahead.</li>
      <li><strong>Mental Strength:</strong> Building resilience to stay focused during challenging situations.</li>
    </ul>
  </div>
</div>
