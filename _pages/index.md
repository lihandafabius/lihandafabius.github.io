---
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
excerpt: >
  <style>
    .intro-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 40px;
      padding: 60px 40px 20px;
      align-items: center;
      justify-items: center;
      color: white;
    }
    .intro-image img {
      width: 100%;
      max-width: 360px;
      border-radius: 20px;
      object-fit: cover;
      border: 6px solid #00FF00;
      box-shadow: 0 8px 25px rgba(0,0,0,0.6);
    }
    .intro-text {
      max-width: 600px;
      text-align: center;
    }
    .intro-text h1 {
      font-size: 2em;
      font-weight: 700;
      margin-bottom: 15px;
      color: #00FF00;
    }
    .intro-text p {
      font-size: 1.1em;
      line-height: 1.6em;
      margin-bottom: 25px;
      color: #e0e0e0;
    }
    .button-group {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
      margin-top: 20px;
    }
    .button-group a {
      padding: 10px 20px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }
    .cv-btn { background-color: #00FF00; color: black; }
    .linkedin-btn { background-color: #0077B5; color: white; }
    .github-btn { background-color: #333; color: white; }
  </style>

  <div class="intro-container">
    <!-- Profile Image -->
    <div class="intro-image">
      <img src="/assets/images/WhatsApp Image 2025-04-07 at 14.26.08.jpeg" alt="Profile Picture">
    </div>

    <!-- Text Content -->
    <div class="intro-text">
      <h1>Cybersecurity | Data Analytics | Secure Web Dev</h1>
      <p>
        Enthusiastic about protecting digital ecosystems and extracting meaningful insights from data. 
        I bring a fusion of cybersecurity awareness, programming knowledge, and analytical thinking 
        to build solutions that are both impactful and secure.
      </p>

      <!-- Typing SVG -->
      <img 
        src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&pause=1000&color=00FF00&width=600&lines=Cybersecurity+%7C+Data+Science+%7C+Python+Web+Development;Passionate+about+Securing+the+Digital+World;Analyzing+Data+for+Meaningful+Insights;Building+Scalable+and+Secure+Web+Applications" 
        alt="Typing SVG" 
        style="max-width: 100%; height: auto; margin-bottom: 20px;">

      <!-- Buttons -->
      <div class="button-group">
        <a href="/assets/Fabius_Lihanda_CV.pdf" download class="cv-btn">📄 Download CV</a>
        <a href="https://www.linkedin.com/in/your-linkedin-username" target="_blank" class="linkedin-btn">🔗 LinkedIn</a>
        <a href="https://github.com/your-github-username" target="_blank" class="github-btn">💻 GitHub</a>
      </div>
    </div>
  </div>

permalink: /

feature_row:
  - title: "🎓 Education"
    excerpt: >
      **BSc. in Computer Science**  
      Egerton University (2020–2025)  
      Focus: Cybersecurity, Cloud Computing, and Data Analytics.
    icon: "fas fa-graduation-cap"
    align: left

  - title: "🛠 Skills"
    excerpt: >
      - Python, Flask, Django  
      - SQL, Power BI, Pandas  
      - Web Security, Wireshark, Burp Suite  
      - HTML, CSS, Git & GitHub
    icon: "fas fa-tools"
    align: left

  - title: "📚 Certifications"
    excerpt: >
      - Google Cybersecurity Certificate  
      - Cisco CCNA & Cybersecurity Essentials  
      - AWS re/Start Program  
      - Active in Bug Bounty Platforms
    icon: "fas fa-certificate"
    align: left

  - title: "💡 Interests"
    excerpt: >
      Threat Intelligence, Open Source, Digital Forensics  
      Machine Learning, Community Volunteering
    icon: "fas fa-lightbulb"
    align: left
---

Welcome to my portfolio! Explore my projects, blog posts, and journey in tech.

{% include feature_row %}
