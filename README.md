<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>MANAVI BALWANT DAHAT - Resume</title>
    <style>
    body {  
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: white;
    }
    .container { 
      display: flex;
      max-width: 1100px;
      margin: 30px auto;
      background: white;
      box-shadow: 0 0 15px rgba(61, 51, 51, 0.1);
    }
    .left { 
      width: 30%;
      background: rgb(2, 2, 84);
      color: white;
      padding: 30px 20px;
      text-align: center;
    }
    .left img { 
      width: 120px;
      height: 120px;
      border-radius: 50%;
      margin-bottom: 15px;
      object-fit: cover;
    }
    .left h2 { margin: 10px 0; } 
    .left ul {
      list-style: none;
      padding: 0;
      font-size: 14px;
    }
    .left ul li { 
      margin-bottom: 8px;
    }
    .right { 
      width: 70%;
      padding: 30px;
      color: #333;
    }
    .right h1 { 
      font-size: 28px;
      margin: 0;
    }
    .right h3 { 
      color: #00695c;
      margin-top: 20px;
    }
    .right ul { 
      padding-left: 20px;
    }
    .skills, .languages { 
      text-align: left;
      margin-top: 20px;
    }
    .bar { 
      background: #ddd;
      border-radius: 20px;
      overflow: hidden;
      margin: 5px 0;
    }
    .bar-fill { 
      height: 10px;
      background: #009688;
    }
    .buttons { 
      text-align: center;
      margin: 20px 0;
    }
    .buttons button { 
      margin: 8px;
      padding: 10px 16px;
      border: none;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }
    .download { background: #55b8ac; } 
    .whatsapp { background: #10a647; }
    .twitter { background: #1076b6; }
    .linkedin { background: #246eb7; }
    </style>
    </head>
    <body><!-- Share & Download Buttons -->
        <div class="buttons"><button class="download" onclick="downloadResume()">Download Resume</button>
            <button class="whatsapp" onclick="shareWhatsApp()">WhatsApp</button>
            <button class="twitter" onclick="shareTwitter()">Twitter</button>
            <button class="linkedin" onclick="shareLinkedIn()">LinkedIn</button>
        </div>
    <div class="container">  
        <div class="left"><img src="C:\Users\User\OneDrive\ドキュメント\WhatsApp Image 2025-04-01 at 01.34.26_a1cacd48.jpg" alt="Profile Image">
            <h2>MANAVI BALWANT DAHAT</h2>
            <p>STUDENT</p>
            <h4>Contact</h4>
            <ul>
                <li>7558362553</li>
                <li>manavidahat@gmail.com</li>
                <li>neri puunarvasan salod (hirpur) wardha</li>
            </ul>
            <h4>Skills</h4>
            <div class="skills">
                <p>Generate AI</p>
                <div class="bar"><div class="bar-fill" style="width: 40%"></div></div>
                <p>web development</p>
                <div class="bar"><div class="bar-fill" style="width: 75%"></div></div>
            </div>
            <h4>Languages</h4>
            <div class="languages">
                <p>HTML</p>
                <div class="bar"><div class="bar-fill" style="width: 95%"></div></div>
                <p>C++</p>
                <div class="bar"><div class="bar-fill" style="width: 50%"></div></div>
                <p>PYTHON</p>
                <div class="bar"><div class="bar-fill" style="width: 60%"></div></div>
                <p>JAVA</p>
                <div class="bar"><div class="bar-fill" style="width: 30%"></div></div>
            </div>
        </div>
        <div class="right"><h1>MANAVI BALWANT DAHAT</h1>
            <h3>Career Objective</h3>
            <p>A highly driven and ambitious second-year Electronics and Telecommunication (EXTC) student with a minor in Data Science, passionate about technology, 
                innovation, and impact-driven problem-solving. With a strong foundation in programming (Python, C) and web development, coupled with practical experience 
                in creative writing, and freelancing.Eager to continuously grow through real-world projects, startup ventures, and certifications
                aspire to leverage my technical, analytical,and creative skills to contribute meaningfully to cutting-edge tech solutions while pursuing financial 
                independence and personal excellence.Currently building tech-based startups and committed to excelling in both academics and industry.
            </p>
            <h3>Education</h3>
            <ul>
                <li><strong>B.Tech – EXTC</strong> – P.R. Pote College, 2023–2027 – CGPA: 7.65</li>
                <li><strong>HSC</strong> – Zila parilsad College of arts and science – 69%</li>
                <li><strong>SSC</strong> – alphonsa sr.sec.school – 61.8%</li>
            </ul>
            <h3>Certifications / Internships</h3>
            <ul>
                <li>Content Writing Internship – In-Amigos Foundation</li>
            </ul>
            <h3>Examinations</h3>
            <ul>
                <li>JEE Score: 59</li>
                <li>CET Score: 55</li>
            </ul>
            <h3>References</h3>
            <p><strong>MANAVI BALWANT DAHAT</strong> – Phone: 7558362553</p>
        </div>
    </div><!-- JavaScript for sharing and downloading -->
    <script>
    const resumeURL = window.location.href;
    function shareWhatsApp() {
        window.open(`https://wa.me/?text=Check out this resume: 
        ${encodeURIComponent(resumeURL)}`, '_blank');
    }
    function shareTwitter() {
      window.open(`https://twitter.com/intent/tweet?text=Check out this 
      resume&url=${encodeURIComponent(resumeURL)}`, '_blank');
    }
    function shareLinkedIn() {
      window.open('https://www.linkedin.com/sharing/share-offsite/?url=${encodeURIComponent(resumeURL)}', '_blank'); 
    }
    function downloadResume() {
      window.print();
    }  
    </script>
    </body>
</html># resume-website
