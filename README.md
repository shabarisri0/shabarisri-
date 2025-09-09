<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shabari sri - Portfolio</title>
  <style>
    /* Basic layout & colors */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f8f8;
      color: #111;
    }
    header {
      background-color: #c8ff33;
      text-align: center;
      padding: 20px;
      color: #000;
      font-size: 24px;
      font-weight: 700;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 10px;
      background-color: #d92b2b;
      padding: 10px;
      flex-wrap: wrap;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      padding: 8px 14px;
      font-weight: bold;
      border-radius: 6px;
    }
    nav a:hover { background: #000; color: #fff; }

    .container {
      width: 90%;
      max-width: 1000px;
      margin: 20px auto;
      padding: 10px;
    }
    .section {
      background: #fff;
      padding: 20px;
      margin: 20px 0;
      border-radius: 10px;
      box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
    }

    .resume a {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 12px;
      background: #d92b2b;
      color: #fff;
      text-decoration: none;
      border-radius: 6px;
    }

    .footer {
      text-align: center;
      padding: 14px 0;
      color: #333;
    }

    /* Responsive video wrapper (keeps 16:9 ratio) */
    .video-wrapper {
      position: relative;
      padding-bottom: 56.25%; /* 16:9 */
      height: 0;
      overflow: hidden;
      border-radius: 10px;
      box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
    }
    .video-wrapper iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: 0;
    }

    @media (max-width: 480px) {
      header { font-size: 20px; }
      .container { padding: 8px; }
    }
  </style>
</head>
<body>

  <header>Shabari sri - Portfolio</header>

  <nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#demo-video">Demo Video</a>
    <a href="#resume">Resume</a>
  </nav>

  <div class="container">

    <div id="about" class="section">
      <h2>About Me</h2>
      <p>I'm a <strong>cyber security</strong> expert and technology enthusiast passionate about helping organizations protect their data. With over 7 years of experience, I stay updated with the latest trends in cybersecurity and online security.</p>
    </div>

    <div id="education" class="section">
      <h2>Education</h2>
      <p><strong>Anna University</strong> - Electrical & Electronics Engineering</p>
    </div>

    <div id="skills" class="section">
      <h2>Skills</h2>
      <ul>
        <li>CyberSecurity</li>
        <li>Internet of Things</li>
        <li>Cloud Computing</li>
        <li>Python</li>
        <li>Java</li>
        <li>Blockchain</li>
        <li>C++</li>
        <li>JavaScript</li>
      </ul>
    </div>

    <div id="projects" class="section">
      <h2>Projects</h2>
      <ul>
        <li><a href="#">AI-Based Alternator Control System</a></li>
        <li><a href="#">Cloud Security IBM</a></li>
        <li><a href="#">IBM Chatbot</a></li>
        <li><a href="#">Chatbot</a></li>
      </ul>
    </div>

    <!-- ====== Demo Video Section (INSERTED) ====== -->
    <div id="demo-video" class="section">
      <h2>Project Demo Video</h2>

      <div class="video-wrapper">
        <!-- Google Drive preview embed link -->
        <iframe
          src="https://drive.google.com/file/d/1QQPqrL1d3fFhMQ9rePR6ceJ6OJgibLWW/preview"
          title="Project Demo Video"
          allow="autoplay; encrypted-media; fullscreen">
        </iframe>
      </div>

      <p style="text-align:center; margin-top:10px;">
        <a href="https://drive.google.com/file/d/1QQPqrL1d3fFhMQ9rePR6ceJ6OJgibLWW/view?usp=drivesdk" target="_blank" rel="noopener">Open the video on Google Drive</a>
      </p>
    </div>
    <!-- ====== End Demo Video Section ====== -->

    <div id="resume" class="section resume">
      <h2>Resume</h2>
      <a href="#">Download CV</a>
    </div>

  </div> <!-- .container -->

  <div class="footer">
    &copy; SHABARI SRI K
  </div>

</body>
</html>
