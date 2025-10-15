# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio | MD. SHAMIM HOSSAIN</title>

  <style>
    body {
      font-family: "Poppins", Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom right, #f5f7fa, #c3cfe2);
      color: #333;
      line-height: 1.6;
    }

    header {
      text-align: center;
      background: linear-gradient(135deg, #0077b6, #00b4d8);
      color: white;
      padding: 50px 20px;
      border-bottom-left-radius: 50px;
      border-bottom-right-radius: 50px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    .profile-pic {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 5px solid white;
      object-fit: cover;
      box-shadow: 0 0 15px rgba(255, 255, 255, 0.5);
    }

    .tagline {
      font-size: 18px;
      font-style: italic;
      margin-top: 10px;
    }

    section {
      background: white;
      margin: 40px auto;
      padding: 30px;
      max-width: 800px;
      border-radius: 20px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    }

    h2 {
      color: #0077b6;
      border-bottom: 3px solid #00b4d8;
      padding-bottom: 5px;
      text-align: left;
    }

    a {
      color: #0077b6;
      text-decoration: none;
      font-weight: bold;
    }

    a:hover {
      color: #023e8a;
      text-decoration: underline;
    }

    .links {
      margin-top: 10px;
      text-align: center;
      line-height: 2;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li {
      margin: 10px 0;
      font-size: 18px;
    }

    .project-item {
      text-align: center;
    }

    .btn {
      display: inline-block;
      background: #0077b6;
      color: white;
      padding: 8px 15px;
      border-radius: 8px;
      text-decoration: none;
      transition: background 0.3s;
    }

    .btn:hover {
      background: #023e8a;
    }

    .skill-list {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
    }

    .skill-list span {
      background: #00b4d8;
      color: white;
      padding: 8px 15px;
      border-radius: 25px;
      font-weight: bold;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
      transition: transform 0.2s;
    }

    .skill-list span:hover {
      transform: scale(1.1);
      background: #0096c7;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #0077b6;
      color: white;
      margin-top: 50px;
      border-top-left-radius: 50px;
      border-top-right-radius: 50px;
    }
  </style>
</head>

<body>
  <header>
    <img src="SK.jpg" alt="Shamim Khan" class="profile-pic">
    <h1>MD. SHAMIM HOSSAIN</h1>
    <p class="tagline">Aspiring Competitive Programmer | ICT Student | Tech Enthusiast</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>
      Hi, my name is <b>Md. Shamim Hossain</b>. I am pursuing my B.Sc. in
      <b>Information and Communication Technology</b> at
      <b>Chandpur Science and Technology University</b>, Bangladesh.
    </p>
    <p>
      My passion is to become an excellent <b>competitive programmer</b>. I have solved over
      <b>1000+ algorithmic problems</b> on various online judges.
    </p>
    <div class="links">
      🌐
      <a href="https://www.facebook.com/shamimkhan1981">Facebook</a> |
      <a href="https://github.com/khanshamim8134">GitHub</a> |
      <a href="https://codeforces.com/profile/khanshamim8134">Codeforces</a> |
      <a href="https://judge.beecrowd.com/en/profile/853555">Beecrowd</a> |
      <a href="https://toph.co/u/shamimkhanuser.8061">Toph</a> |
      <a href="https://www.hackerrank.com/profile/khanshamim8134">HackerRank</a><br><br>
      📞 WhatsApp: 01723355140 | 📧 Email: khanshamim8134@gmail.com
    </div>
  </section>

  <section>
    <h2>Education</h2>
    <ul>
      <li><b>HSC:</b> Science – Darsana Govt. College</li>
      <li><b>B.Sc.:</b> Information & Communication Technology – CSTU</li>
    </ul>
  </section>

  <section>
    <h2>Experiences & Achievements</h2>
    <ul>
      <li>🏆 Champion – ICT-CSTU Programming Contest</li>
      <li>🥈 1st Runner-up – CSTU CPC IUPC 2025</li>
      <li>🏅 5th Place – BAIUST IUPC 2025</li>
      <li>🎯 ICPC Asia Dhaka Regional (BUBT-2023) – Honorable Mention</li>
      <li>💡 BUET, CUET, IUT, PU, CU, AUST IUPC Participation (2023–2025)</li>
      <li>🎓 53rd Place – 8th DRMC Tech Carnival 2025 (Preli)</li>
      <li>🤖 5th International Robotic Olympiad 2025</li>
      <li>✅ Completed 47+ Online Contests (Proof in GitHub)</li>
    </ul>
  </section>

  <section>
    <h2>Projects</h2>
    <div class="project-item">
      <h3>🎹 PIANO</h3>
      <p>A simple web-based piano application.</p>
      <a href="https://github.com/khanshamim8134/PIANO" class="btn" target="_blank">View Project</a>
    </div>
  </section>

  <section>
    <h2>Skills</h2>
    <div class="skill-list">
      <span>Python</span>
      <span>Java</span>
      <span>C/C++</span>
      <span>HTML & CSS</span>
      <span>Algorithms</span>
      <span>Data Structures</span>
    </div>
  </section>

  <footer>
    <p>© 2025 Md. Shamim Hossain | Made with ❤️ and HTML</p>
  </footer>
</body>
</html>
