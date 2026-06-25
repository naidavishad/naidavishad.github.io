---
layout: default
title: Semester 2
permalink: /semester2/
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
  <h1>🎯 Semester 2</h1>
  <p>My second semester at UET Lahore · BS Computer Engineering</p>
</div>

<div class="section-card">
  <h2>📖 About This Semester</h2>
  <p style="color:#555; font-size:14px; line-height:1.9;">Semester 2 brought a completely new set of challenges — digital logic, OOP, and online learning. It was also the semester where hostel life truly tested my independence and resilience. The introduction of MySQL and Database Systems opened my eyes to how data powers real-world systems.</p>
</div>

<div class="section-card">
  <h2>📋 Subjects & Teachers</h2>
  <div class="subject-type-header">📘 Theory Courses</div>
  <div class="subjects-grid">
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">🗄️</div>
      </div>
      <div class="name">Database</div>
      <div class="teacher">Dr. Bilal</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">⚡</div>
      </div>
      <div class="name">Digital Logic Design</div>
      <div class="teacher">Sir Abdullah Bilal</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">📐</div>
      </div>
      <div class="name">Calculus</div>
      <div class="teacher">Mam Arshi</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">🗣️</div>
      </div>
      <div class="name">Communication Skills</div>
      <div class="teacher">Mam Saira</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">📊</div>
      </div>
      <div class="name">Applied Statistics</div>
      <div class="teacher">Sir Fazal Haq</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">🧩</div>
      </div>
      <div class="name">OOP</div>
      <div class="teacher">Dr. Akram</div>
    </div>
  </div>

  <div class="subject-type-header">🧪 Practical Labs</div>
  <div class="subjects-grid">
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">🖥️</div>
      </div>
      <div class="name">OOP Lab</div>
      <div class="teacher">Mam Rimsha Chaudhry</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">💾</div>
      </div>
      <div class="name">Database Lab</div>
      <div class="teacher">Dr. Bilal</div>
    </div>
    <div class="subject-card">
      <div class="subject-header">
        <div class="icon">🔧</div>
      </div>
      <div class="name">DLD Lab</div>
      <div class="teacher">Sir Abdullah Bilal</div>
    </div>
  </div>
</div>

<div class="section-card">
  <h2>📝 Posts</h2>
  <p style="color:#888; font-size:13px; margin-bottom:15px;">A collection of my posts and reflections for this semester.</p>
  <div class="posts-grid">
    {% assign semester_posts = site.posts | where: "category", "semester2" | sort: "date" %}
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
      <p style="color:#777; font-size:14px; font-style:italic;">No journals or posts added yet for this semester. They will appear here once published.</p>
    {% endif %}
  </div>
</div>

<div class="section-card">
  <h2>📝 My Semester 2 Story</h2>


  <div class="story-card">
    <h3>🌐 Online Learning Challenges</h3>
    <ul>
      <li><strong>Shift to Online Mode:</strong> Adapting to virtual education due to national circumstances.</li>
      <li><strong>Learning Barriers:</strong> Overcoming connectivity issues and lack of physical campus environment.</li>
      <li><strong>Comparison:</strong> Physical classrooms provide better focus and learning outcomes.</li>
    </ul>
  </div>

  <div class="story-card">
    <h3>🏠 Hostel Life: Journey of Independence</h3>
    <ul>
      <li><strong>Living Away from Home:</strong> Learning to manage life independently without family support.</li>
      <li><strong>Real-Life Challenges:</strong> Adjusting to diverse people and limited facilities.</li>
      <li><strong>Personal Growth & Faith:</strong> Developing resilience, patience, and self-reliance through struggle.</li>
    </ul>
  </div>

</div>
