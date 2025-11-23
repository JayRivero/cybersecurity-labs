<h1>🛡️ Offensive Security Intro — TryHackMe</h1>

<h2>Lab Summary & Notes</h2>

<p>This room introduced the basics of offensive security, focusing on how attackers discover hidden content, enumerate web applications, and think like a penetration tester. This lab helped me build foundational skills such as directory brute forcing, analyzing HTTP responses, and executing simple information-gathering techniques.</p>

<h2>🚀 Overview</h2>

<p>In this lab, I learned how to:</p>
<ul>
    <li>Use Gobuster to enumerate hidden directories and pages</li>
    <li>Understand how wordlists help attackers discover website content</li>
    <li>Interpret HTTP status codes to identify valid pages (e.g., 200 OK)</li>
    <li>Recognize how attackers build a picture of a target before exploiting it</li>
    <li>Think about the difference between pages, directories, and resources</li>
</ul>
<p>This was my first exposure to web enumeration, and it helped me understand why discovering hidden content is such a common first step in penetration testing.</p>
  
<h2>🔧 Tools Used</h2>

<strong>Gobuster</strong>

<p>A command-line tool used for brute-forcing website directories and pages.</p>
  
<h3>The basic workflow:</h3>

<ul>
    <li>Provide a target URL</li>
    <li>Provide a wordlist</li>
    <li>Gobuster tries each word as a potential page or folder</li>
    <li>If the website returns Status: 200, that means the page exists</li>
</ul>

<p>This helped me understand how simple guessing—done at scale—is used to uncover content not linked anywhere on the site.</p>
  
<h2>🧠 What I Did</h2>

<h3>1. Enumerated the website with Gobuster</h3>

<p>I ran Gobuster against the vulnerable site using a wordlist. Gobuster tried each word in the list as a possible path on the website.</p>
  
<h3>2. Interpreted results using HTTP status codes</h3>

<p>Gobuster returned several results with Status: 200, meaning those pages or directories existed. These leads can later be explored manually to find sensitive information or potential vulnerabilities.</p>

<h3>3. Explored discovered pages</h3>

<p>I visited the valid paths in a browser to see what information the “hidden” pages revealed. This replicated the way attackers gather intelligence during reconnaissance.</p>

<h2>📘 Key Takeaways</h2>

<ul>
    <li>Enumeration is essential — attackers don’t guess; they automate.</li>
    <li>Websites often hide sensitive content that can be discovered with brute forcing.</li>
    <li>HTTP status codes matter — understanding them helps determine what’s accessible.</li>
    <li>Wordlists are powerful — they make systematic discovery possible.</li>
    <li>Offensive security starts with information gathering, not exploitation.</li>
</ul>
<p>This room built the foundational mindset needed for future offensive security labs.</p>
  
<h2>📂 Repository Structure</h2>

<p>/TryHackMe/</p>
<p>/Offensive-Security-Intro/</p>
<p>README.md</p>
    
<h2>📝 Next Steps</h2>

<ul>
    <li>Practice enumeration with other tools (e.g., ffuf)</li>
    <li>Continue TryHackMe’s Beginner or Pre-Security paths</li>
    <li>Start building small scripts to automate enumeration tasks</li>
</ul>
