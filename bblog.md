---
layout: page
title: My Engineering Story
permalink: /blog/
---

<h2 style="color: #001f3f; border-bottom: 3px solid #4b0082; padding-bottom: 10px;">SEMESTER 1 & 2: THE ACADEMIC ROADMAP</h2>

**Student ID:** 2025-BSCPE-140

### 1. Semester 1: The Transition (Foundation)
The initial shift from college to university life and the first encounter with engineering logic.

### 2. Computing Fundamentals (Sem 1)
Introduction to algorithms and the basics of hardware-software interaction.

### 3. Applied Sciences in Engineering
Reflecting on the role of Physics and Mathematics in building a strong engineering base.

### 4. Semester 1 Reflection
Key lessons learned and skills developed during the first six months.

### 5. Entering Semester 2: New Goals
Setting higher targets for GPA and shifting focus toward core programming languages.

### 6. Programming Fundamentals (Current)
Building deep logic in C++ and exploring professional coding standards.

### 7. Database & MySQL Management
Practical implementation of datasets to manage large-scale academic records.

### 8. Digital Logic Design (Sem 2)
The study of logic gates and sequential circuits that define modern computing.

### 9. Version Control (GitHub Integration)
Utilizing professional tools to host and manage this 8-semester documentation.

### 10. Future Vision (Road to Semester 8)
How these two semesters have prepared me for the upcoming advanced engineering modules.

---
### Technical Logs & Weekly Posts
{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url }}) - {{ post.date | date_to_string }}
{% endfor %}
