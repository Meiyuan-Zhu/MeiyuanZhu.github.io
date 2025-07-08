---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div id="about"></div>

# Welcome to Meiyuan Zhu's Academic Website 🎉

Hello! I’m a 2nd year Software Engineering undergrad at Nanjing University. My research interests lie in Visual–Language Agents, Embodied AI and Multimodal LLMs. My goal is to build AI agents that can seamlessly understand, reason, and act across both physical and digital environments.

Currently I’m a student Research Assistant at [XLANG Lab](https://xlang.ai/) (as part of the [HKU NLP Group](https://hkunlp.github.io/)) with [Prof. Tao Yu](https://taoyds.github.io/). Before that, I had the honor of collaborating with [Prof. Hongyu Kuang](https://software.nju.edu.cn/khy/index.html) at Nanjing University on large-scale language understanding and generation research.

---

<div id="education"></div>

## Education

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <img src="/images/NJU-logo.jpeg" alt="Nanjing University Logo" style="width: 80px; height: 80px; margin-right: 20px; flex-shrink: 0;">
  <div>
    <h3 style="margin: 0 0 5px 0; font-size: 1.4em;">Nanjing University</h3>
    <p style="margin: 0 0 5px 0; color: #666; font-size: 1em;">2023.09 - 2027.07 (Expected)</p>
    <p style="margin: 0 0 5px 0; font-weight: bold; font-size: 1.1em;">B.E. in Software Engineering</p>
    <p style="margin: 0; color: #666;">GPA: 92.6/100  (4.63/5.00)</p>
  </div>
</div>

<div id="publications"></div>

## Publications
<p><em>Publications will be added as I progress in my academic journey. 💪</em></p>

---

<div id="projects"></div>

## Projects

### LLM-Enhanced Prompt Design for Sentiment Analysis on SE Texts
GitHub: [https://github.com/Meiyuan-Zhu/SA4SE-NJU2025](https://github.com/Meiyuan-Zhu/SA4SE-NJU2025)

In this paper, we propose a paper-insight-enhanced prompting approach that utilizes the insights digested from SA4SE-related papers to guide ChatGPT toward better performance in this task.

### Forexseek Website
Github: [https://github.com/Meiyuan-Zhu/2025-HuaQiFrontend](https://github.com/Meiyuan-Zhu/2025-HuaQiFrontend)

[View website](http://118.178.184.189/#/homepage)

### "Tomato" Bookstore Website
Github: [https://github.com/bbyuan/Tomato-BookStore-Frontend](https://github.com/bbyuan/Tomato-BookStore-Frontend)

---

<div id="awards"></div>

## Selected Awards

- **National Grand Prize, Citi Cup Financial Innovation Competition, 2025**   
<em>Top 1 team nationwide, $10,000<em>

- **Nantional Scholarship, 2024**   
<em>Top 0.2% nationwide, the highest honor for undergraduates in China, ¥10,000 <em>

- **First Prize, EL Programming Design Competition, Nanjing University**   
<em>Top 2 teams in NJU, ¥3,000 <em>

- **Outstanding Student Leader， 2023， 2024**   


---

<div id="acknowledgement"></div>

## Acknowledgement

This website uses the website design and template by [academicpages](https://github.com/academicpages/academicpages.github.io)

---

<style>
/* Remove top margin from main content */
#main {
  margin-top: 0.5em !important;
}

/* Remove top margin from first heading */
h1:first-of-type {
  margin-top: 0 !important;
  padding-top: 0 !important;
}

/* Smooth scrolling for anchor links */
html {
  scroll-behavior: smooth;
}

/* Add some spacing for anchor targets to account for fixed header */
div[id] {
  padding-top: 90px;
  margin-top: -90px;
}

/* Override the about div to have no top spacing */
div[id="about"] {
  padding-top: 0 !important;
  margin-top: 0 !important;
}

/* Section styling */
h2 {
  border-bottom: 2px solid #f1f1f1;
  padding-bottom: 10px;
  margin-top: 60px;
}

hr {
  margin: 40px 0;
  border: none;
  border-top: 1px solid #e1e1e1;
}

/* Contact section improvements */
#contact + h2 + p {
  margin-bottom: 20px;
}

/* Responsive adjustments for mobile */
@media (max-width: 768px) {
  div[id] {
    padding-top: 70px;
    margin-top: -70px;
  }
  
  h2 {
    margin-top: 40px;
  }
}
</style>

<script>
// Smooth scrolling for navigation links
document.addEventListener('DOMContentLoaded', function() {
  // Get all navigation links that start with #
  const navLinks = document.querySelectorAll('a[href^="#"]');
  
  navLinks.forEach(link => {
    link.addEventListener('click', function(e) {
      e.preventDefault();
      const targetId = this.getAttribute('href').substring(1);
      const targetElement = document.getElementById(targetId);
      
      if (targetElement) {
        // Get the masthead height for proper offset calculation
        const masthead = document.querySelector('.masthead');
        const mastheadHeight = masthead ? masthead.offsetHeight : 70;
        // Add a small buffer to ensure the title is clearly at the top
        const offset = mastheadHeight + 20;
        
        const targetPosition = targetElement.offsetTop - offset;
        
        window.scrollTo({
          top: targetPosition,
          behavior: 'smooth'
        });
      }
    });
  });
});
</script>
