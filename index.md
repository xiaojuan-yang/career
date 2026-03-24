---
layout: null
---

<head>
    <meta charset="UTF-8">
    <title>Grace X. Yang</title>
    <style>
        /* 页面居中控制 */
        body { 
            font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; 
            line-height: 1.6; 
            color: #333; 
            max-width: 800px; /* 限制宽度 */
            margin: 60px auto; /* 自动居中 */
            padding: 0 40px; 
            background-color: #fff; 
        }
        
        /* 个人信息栏：照片在左，文字在右 */
        .profile-container { 
            display: flex; 
            align-items: center; 
            gap: 40px; 
            margin-bottom: 40px; 
        }
        .profile-img { 
            width: 180px; 
            height: 180px; 
            border-radius: 50%; 
            object-fit: cover; 
            flex-shrink: 0;
        }
        .profile-text h1 { margin: 0 0 10px 0; font-size: 2.2em; }
        .profile-text p { margin: 5px 0; font-size: 1.1em; color: #555; }
        
        /* 导航栏 */
        .nav { 
            border-top: 1px solid #eee; 
            border-bottom: 1px solid #eee; 
            padding: 15px 0; 
            margin-bottom: 30px; 
            text-align: center; /* 导航居中 */
        }
        .nav a { 
            margin: 0 15px; 
            font-weight: 500; 
            text-decoration: none; 
            color: #444; 
        }
        
        /* 社交链接 */
        .social-links { margin-top: 15px; }
        .social-links a { 
            margin-right: 15px; 
            text-decoration: none; 
            color: #0056b3; 
            font-size: 0.95em;
        }

        h3 { border-bottom: 1px solid #f0f0f0; padding-bottom: 8px; margin-top: 40px; }
    </style>
</head>

<div class="profile-container">
    <img src="assets/avatar.jpeg" class="profile-img">
    <div class="profile-text">
        <h1>Grace X. Yang</h1>
        <p><strong>Ph.D. Candidate in International Relations</strong></p>
        <p>Freie Universität Berlin</p>
        <p><strong>Interdisciplinary Consultant</strong></p>
        <p>Digital Policy & Market Strategy</p>
        
        <div class="social-links">
            <a href="mailto:Graceyang_pro@outlook.com">Email</a>
            <a href="https://www.linkedin.com/in/xiaojuan-yang/">LinkedIn</a>
            <a href="https://github.com/xiaojuan-yang">GitHub</a>
            <a href="https://scholar.google.com/">Google Scholar</a>
        </div>
    </div>
</div>

<div class="nav">
    <a href="index.html">About</a>
    <a href="research.html">Research</a>
    <a href="experience.html">Consultancy</a>
    <a href="wenshe.html">Wenshe</a>
</div>

<h3>About Me</h3>
<p>I am an interdisciplinary researcher and consultant bridging the gap between global political thoery and practice. My work explores the intersection of digital technology, state sovereignty, and political strategies.</p>

<p>As a researcher, I employ computational social science methods to unpack political discourses. As a consultant, I translate theoretical insights into actionable intelligence for digital trade, market entry, and strategic communication.</p>

<h3>Core Expertise</h3>
<ul>
    <li><strong>Academic:</strong> Global Governance, Sino-Russian Relations, Great Power Competition.</li>
    <li><strong>Technical:</strong> NLP Pipeline Development, Large-scale Textual Analysis, Python, SQL.</li>
    <li><strong>Consulting:</strong> Cross-border Market Strategy, Digital Trade Auditing, Multi-language Content Operations.</li>
</ul>


<p style="text-align: center; color: #999; font-size: 0.8em; margin-top: 50px;">
    &copy; 2026 Grace X. Yang. Expected PhD Completion: April 2026.
</p>