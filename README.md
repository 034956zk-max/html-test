<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>ZAID Academy | CIT & DIT Courses</title>
.profile-photo{
    width:150px;
    height:150px;
    object-fit:cover;
    border-radius:50%;
    border:4px solid white;
    display:block;
    margin-bottom:25px;
    box-shadow:0 8px 25px rgba(0,0,0,.3);
}<section class="hero" id="home">

<div class="container hero-content">

<img
    src="zaid.jpg.jpeg"
    alt="ZAID Academy"
    class="profile-photo"
>

<span class="badge">
FREE COMPUTER LEARNING PLATFORM
</span>

<h1>
Learn Computer Skills With ZAID Academy
</h1>

<style>
*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:Arial,Helvetica,sans-serif;
    background:#f4f7fb;
    color:#172033;
    line-height:1.6;
}

a{
    text-decoration:none;
}

.container{
    width:92%;
    max-width:1200px;
    margin:auto;
}

/* NAVBAR */

header{
    position:sticky;
    top:0;
    z-index:1000;
    background:#07111f;
    box-shadow:0 3px 15px rgba(0,0,0,.2);
}

.navbar{
    min-height:70px;
    display:flex;
    align-items:center;
    justify-content:space-between;
}

.logo{
    color:white;
    font-size:25px;
    font-weight:bold;
}

.logo span{
    color:#38bdf8;
}

nav{
    display:flex;
    gap:8px;
}

nav a{
    color:#dbeafe;
    padding:10px 13px;
    border-radius:8px;
}

nav a:hover{
    background:#172554;
}

/* HERO */

.hero{
    background:linear-gradient(135deg,#07111f,#12356b,#2563eb);
    color:white;
    padding:90px 0;
}

.hero-content{
    max-width:850px;
}

.badge{
    display:inline-block;
    padding:7px 14px;
    border:1px solid rgba(255,255,255,.3);
    border-radius:50px;
    background:rgba(255,255,255,.1);
}

.hero h1{
    font-size:clamp(40px,7vw,70px);
    line-height:1.05;
    margin:20px 0;
}

.hero p{
    font-size:19px;
    color:#dbeafe;
    max-width:760px;
}

.buttons{
    display:flex;
    gap:12px;
    flex-wrap:wrap;
    margin-top:25px;
}

.btn{
    display:inline-block;
    padding:12px 20px;
    border:none;
    border-radius:10px;
    font-weight:bold;
    cursor:pointer;
}

.btn-primary{
    background:white;
    color:#1d4ed8;
}

.btn-blue{
    background:#2563eb;
    color:white;
}

.btn-dark{
    background:#07111f;
    color:white;
}

/* GENERAL */

section{
    padding:70px 0;
}

.section-title{
    text-align:center;
    margin-bottom:35px;
}

.section-title h2{
    font-size:35px;
    margin-bottom:8px;
}

.section-title p{
    color:#64748b;
}

/* COURSE CARDS */

.grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:25px;
}

.card{
    background:white;
    border:1px solid #e2e8f0;
    border-radius:18px;
    padding:25px;
    box-shadow:0 8px 30px rgba(15,23,42,.06);
}

.course{
    display:flex;
    gap:20px;
}

.icon{
    min-width:65px;
    height:65px;
    display:grid;
    place-items:center;
    background:#dbeafe;
    border-radius:16px;
    font-size:32px;
}

.card h3{
    margin-bottom:8px;
}

.card p{
    color:#64748b;
    margin-bottom:15px;
}

.tags{
    display:flex;
    flex-wrap:wrap;
    gap:7px;
    margin-bottom:17px;
}

.tag{
    background:#eff6ff;
    color:#1d4ed8;
    padding:5px 10px;
    border-radius:20px;
    font-size:12px;
}

/* FEATURES */

.feature-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:20px;
}

.feature{
    text-align:center;
}

.feature-icon{
    font-size:42px;
    margin-bottom:10px;
}

/* LESSONS */

.lesson-layout{
    display:grid;
    grid-template-columns:310px 1fr;
    gap:25px;
    align-items:start;
}

.lesson-menu{
    position:sticky;
    top:90px;
}

.lesson-button{
    display:block;
    width:100%;
    text-align:left;
    padding:13px;
    margin-bottom:8px;
    border:1px solid #e2e8f0;
    background:white;
    border-radius:10px;
    cursor:pointer;
}

.lesson-button:hover,
.lesson-button.active{
    background:#eff6ff;
    border-color:#60a5fa;
}

.lesson-content{
    min-height:500px;
}

.lesson-content h3{
    font-size:30px;
    margin-bottom:20px;
}

.lesson-content h4{
    color:#1d4ed8;
    margin:22px 0 8px;
}

.note{
    background:#eff6ff;
    border-left:5px solid #2563eb;
    padding:15px;
    border-radius:8px;
    margin:18px 0;
}

.practical{
    background:#ecfdf5;
    border-left:5px solid #16a34a;
    padding:15px;
    border-radius:8px;
    margin:18px 0;
}

/* VISUALS */

.visual{
    background:#f8fafc;
    border:1px solid #e2e8f0;
    padding:25px;
    border-radius:15px;
    margin:20px 0;
}

.diagram{
    display:flex;
    justify-content:center;
    align-items:center;
    flex-wrap:wrap;
    gap:10px;
}

.diagram-box{
    min-width:105px;
    padding:17px 10px;
    text-align:center;
    border:2px solid #93c5fd;
    background:white;
    border-radius:13px;
}

.arrow{
    font-size:25px;
    color:#64748b;
}

/* QUIZ */

.quiz{
    background:#f8fafc;
    border:1px solid #e2e8f0;
    padding:20px;
    border-radius:15px;
    margin-top:25px;
}

.option{
    display:block;
    background:white;
    border:1px solid #e2e8f0;
    padding:10px;
    border-radius:8px;
    margin:8px 0;
    cursor:pointer;
}

.option:hover{
    background:#eff6ff;
}

.result{
    margin-top:12px;
    font-weight:bold;
}

/* VIDEO */

.video-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:20px;
}

.video{
    background:#07111f;
    color:white;
    border-radius:18px;
    padding:25px;
}

.video-icon{
    font-size:45px;
    margin-bottom:10px;
}

.video p{
    color:#cbd5e1;
}

/* FAQ */

details{
    background:white;
    border:1px solid #e2e8f0;
    padding:16px;
    border-radius:10px;
    margin:10px 0;
}

summary{
    font-weight:bold;
    cursor:pointer;
}

/* FORM */

form{
    display:grid;
    gap:13px;
}

input,
textarea,
select{
    width:100%;
    padding:13px;
    border:1px solid #cbd5e1;
    border-radius:9px;
    font-size:15px;
}

textarea{
    min-height:130px;
}

.question{
    padding:15px;
    border:1px solid #e2e8f0;
    background:white;
    border-radius:10px;
    margin-bottom:10px;
}

/* FOOTER */

footer{
    background:#07111f;
    color:#cbd5e1;
    padding:45px 0;
    text-align:center;
}

footer h2{
    color:white;
}

/* MOBILE */

@media(max-width:850px){

    nav{
        display:none;
    }

    .grid,
    .lesson-layout,
    .feature-grid,
    .video-grid{
        grid-template-columns:1fr;
    }

    .lesson-menu{
        position:static;
    }

    .hero{
        padding:60px 0;
    }

    .course{
        flex-direction:column;
    }
}

@media(max-width:500px){

    section{
        padding:50px 0;
    }

    .hero h1{
        font-size:43px;
    }

    .buttons .btn{
        width:100%;
        text-align:center;
    }
}
</style>
</head>

<body>

<!-- NAVBAR -->

<header>
<div class="container navbar">

<a href="#home" class="logo">
ZAID <span>Academy</span>
</a>

<nav>
<a href="#home">Home</a>
<a href="#courses">Courses</a>
<a href="#cit">CIT</a>
<a href="#dit">DIT</a>
<a href="#videos">Videos</a>
<a href="#quiz">Quiz</a>
<a href="#questions">Q&A</a>
</nav>

</div>
</header>


<!-- HERO -->

<section class="hero" id="home">

<div class="container hero-content">

<span class="badge">
FREE COMPUTER LEARNING PLATFORM
</span>

<h1>
Learn Computer Skills With ZAID Academy
</h1>

<p>
Complete CIT and DIT learning platform with computer notes,
hardware lessons, software, networking, programming,
web development, quizzes, practical work and video resources.
</p>

<div class="buttons">

<a href="#courses" class="btn btn-primary">
Start Learning
</a>

<a href="#questions" class="btn btn-blue">
Ask a Question
</a>

</div>

</div>

</section>


<!-- COURSES -->

<section id="courses">

<div class="container">

<div class="section-title">
<h2>Our Courses</h2>
<p>Choose your computer course</p>
</div>

<div class="grid">

<div class="card course">

<div class="icon">💻</div>

<div>

<h3>CIT - Certificate in Information Technology</h3>

<p>
Computer fundamentals, hardware, Windows,
MS Office, Internet, networking, cyber safety
and practical computer skills.
</p>

<div class="tags">
<span class="tag">Computer</span>
<span class="tag">Hardware</span>
<span class="tag">Windows</span>
<span class="tag">Office</span>
<span class="tag">Internet</span>
</div>

<a href="#cit" class="btn btn-blue">
Open CIT
</a>

</div>

</div>


<div class="card course">

<div class="icon">🧑‍💻</div>

<div>

<h3>DIT - Diploma in Information Technology</h3>

<p>
Programming, algorithms, HTML, CSS,
JavaScript, databases, SQL, networking
and practical web development.
</p>

<div class="tags">
<span class="tag">Programming</span>
<span class="tag">HTML</span>
<span class="tag">CSS</span>
<span class="tag">Database</span>
</div>

<a href="#dit" class="btn btn-blue">
Open DIT
</a>

</div>

</div>

</div>

</div>

</section>


<!-- FEATURES -->

<section>

<div class="container">

<div class="section-title">
<h2>What You Will Learn</h2>
<p>Learn theory and practical skills together.</p>
</div>

<div class="feature-grid">

<div class="card feature">
<div class="feature-icon">📚</div>
<h3>Complete Notes</h3>
<p>
Simple explanations and important definitions.
</p>
</div>

<div class="card feature">
<div class="feature-icon">🖼️</div>
<h3>Visual Learning</h3>
<p>
Hardware and technology diagrams for easier learning.
</p>
</div>

<div class="card feature">
<div class="feature-icon">📝</div>
<h3>Quizzes</h3>
<p>
Test your knowledge after every lesson.
</p>
</div>

</div>

</div>

</section>


<!-- CIT -->

<section id="cit">

<div class="container">

<div class="section-title">
<h2>📘 CIT Full Course</h2>
<p>Select a lesson.</p>
</div>

<div class="lesson-layout">

<div class="lesson-menu" id="citMenu"></div>

<div class="card lesson-content" id="citContent"></div>

</div>

</div>

</section>


<!-- DIT -->

<section id="dit">

<div class="container">

<div class="section-title">
<h2>📗 DIT Full Course</h2>
<p>Programming, web development and IT skills.</p>
</div>

<div class="lesson-layout">

<div class="lesson-menu" id="ditMenu"></div>

<div class="card lesson-content" id="ditContent"></div>

</div>

</div>

</section>


<!-- VIDEOS -->

<section id="videos">

<div class="container">

<div class="section-title">
<h2>🎥 Video Learning</h2>
<p>Video resources for computer students.</p>
</div>

<div class="video-grid">

<div class="video">

<div class="video-icon">▶️</div>

<h3>Computer Fundamentals</h3>

<p>
Learn computer basics, hardware and software.
</p>

<br>

<a
class="btn btn-primary"
target="_blank"
href="https://www.youtube.com/results?search_query=computer+fundamentals+for+beginners">
Watch Videos
</a>

</div>


<div class="video">

<div class="video-icon">▶️</div>

<h3>MS Office</h3>

<p>
Learn Word, Excel and PowerPoint.
</p>

<br>

<a
class="btn btn-primary"
target="_blank"
href="https://www.youtube.com/results?search_query=MS+Office+beginner+tutorial">
Watch Videos
</a>

</div>


<div class="video">

<div class="video-icon">▶️</div>

<h3>HTML & CSS</h3>

<p>
Learn how to build websites.
</p>

<br>

<a
class="btn btn-primary"
target="_blank"
href="https://www.youtube.com/results?search_query=HTML+CSS+beginner+tutorial">
Watch Videos
</a>

</div>

</div>

</div>

</section>


<!-- QUICK QUIZ -->

<section id="quiz">

<div class="container">

<div class="section-title">

<h2>📝 Computer Quiz</h2>

<p>Test your basic knowledge.</p>

</div>

<div class="card" id="quickQuiz"></div>

</div>

</section>


<!-- QUESTIONS -->

<section id="questions">

<div class="container">

<div class="section-title">

<h2>❓ Ask a Question</h2>

<p>
Students can write their computer questions here.
</p>

</div>

<div class="grid">

<div class="card">

<form id="questionForm">

<input
id="studentName"
type="text"
placeholder="Your Name"
required
>

<select id="course">

<option>CIT</option>
<option>DIT</option>
<option>General</option>

</select>

<textarea
id="questionText"
placeholder="Write your question..."
required
></textarea>

<button class="btn btn-blue">
Submit Question
</button>

</form>

<br>

<small>
This GitHub version stores questions in the browser only.
A shared online Q&A database requires a backend/database.
</small>

</div>


<div class="card">

<h3>Recent Questions</h3>

<div id="questionList"></div>

</div>

</div>

</div>

</section>


<!-- FAQ -->

<section>

<div class="container">

<div class="section-title">
<h2>Frequently Asked Questions</h2>
</div>

<details>

<summary>
What is CIT?
</summary>

<p>
CIT means Certificate in Information Technology.
It focuses on practical computer and office skills.
</p>

</details>


<details>

<summary>
What is DIT?
</summary>

<p>
DIT means Diploma in Information Technology.
It can include programming, databases,
web development, networking and practical projects.
</p>

</details>


<details>

<summary>
Can ZAID Academy run on GitHub Pages?
</summary>

<p>
Yes. This website uses HTML, CSS and JavaScript,
so it can run as a static GitHub Pages website.
</p>

</details>


<details>

<summary>
Can students ask questions?
</summary>

<p>
Yes, this version has a question form.
For a shared question system where every student
can see the same questions, a database/backend
will need to be added later.
</p>

</details>

</div>

</section>


<!-- FOOTER -->

<footer>

<div class="container">

<h2>ZAID Academy</h2>

<p>
Learn • Practice • Build
</p>

<p>
CIT & DIT Computer Education
</p>

</div>

</footer>


<script>

/* =========================
   CIT LESSON DATA
========================= */

const CIT = [

{
title:"1. Computer Fundamentals",

notes:`
A computer is an electronic machine that accepts input,
processes data, stores information and produces output.

The basic computer cycle is:

Input → Processing → Output → Storage

Hardware means physical parts of a computer that you can touch.

Examples:
• CPU
• RAM
• Keyboard
• Mouse
• Monitor
• Motherboard
• HDD
• SSD

Software means programs and instructions used by the computer.

Examples:
• Windows
• Microsoft Word
• Web browsers
• Media players

Important terms:

Data = raw facts.

Information = processed and meaningful data.

CPU = Central Processing Unit.

RAM = Random Access Memory.

Storage = long-term data storage.
`,

visual:[
"⌨️ Input",
"→",
"⚙️ Processing",
"→",
"🖥️ Output",
"→",
"💾 Storage"
],

practical:`
Find five computer components around you.
Write their names and explain what each one does.
`,

quiz:{
question:"Which component mainly processes instructions?",
options:[
"Monitor",
"CPU",
"Keyboard",
"Printer"
],
answer:1
}

},


{
title:"2. Motherboard, CPU and RAM",

notes:`
The motherboard is the main circuit board of a computer.

It connects important components together.

The CPU executes instructions and performs calculations.

RAM is temporary working memory.

RAM is used by programs while they are running.

When power is removed, normal RAM loses its temporary contents.

Common ports include:

USB
HDMI
Ethernet
Audio
Display ports
`,

visual:[
"🧩 Motherboard",
"→",
"🧠 CPU",
"→",
"⚡ RAM",
"→",
"🔌 Ports"
],

practical:`
Look at a computer safely and identify USB,
audio, display and network ports if available.
`,

quiz:{
question:"Which component is the main circuit board?",
options:[
"RAM",
"Motherboard",
"Mouse",
"Printer"
],
answer:1
}

},


{
title:"3. Input and Output Devices",

notes:`
Input devices send information to a computer.

Examples:

Keyboard
Mouse
Microphone
Scanner
Webcam

Output devices present information from a computer.

Examples:

Monitor
Printer
Speakers
Projector

A touchscreen can work as both input and output.
`,

visual:[
"⌨️ Keyboard",
"🖱️ Mouse",
"🎤 Microphone",
"→",
"🖥️ Monitor",
"🖨️ Printer"
],

practical:`
Create two lists in your notebook.

Input Devices:
Write at least five.

Output Devices:
Write at least five.
`,

quiz:{
question:"Which is an input device?",
options:[
"Printer",
"Monitor",
"Mouse",
"Speaker"
],
answer:2
}

},


{
title:"4. Storage - HDD, SSD and USB",

notes:`
Storage keeps data after the computer is turned off.

HDD means Hard Disk Drive.

HDD uses magnetic disks.

SSD means Solid State Drive.

SSD uses flash memory and normally provides faster access.

USB flash drives are portable storage devices.

Common capacity units:

KB
MB
GB
TB
`,

visual:[
"💻 Computer",
"→",
"💽 HDD",
"⚡ SSD",
"🔑 USB"
],

practical:`
Open File Explorer → This PC.

Check how much storage is available on your computer.
`,

quiz:{
question:"Which storage device normally has no spinning disk?",
options:[
"HDD",
"SSD",
"DVD",
"Floppy Disk"
],
answer:1
}

},


{
title:"5. Operating System and Windows",

notes:`
An operating system manages computer hardware
and provides an environment for applications.

Examples:

Windows
Linux
macOS
Android
iOS

Windows includes:

Desktop
Start Menu
Taskbar
File Explorer
Settings
Recycle Bin

Good file management means using clear names
and organized folders.
`,

visual:[
"👤 User",
"↕",
"🪟 Operating System",
"↕",
"💻 Hardware"
],

practical:`
Create these folders:

Documents
Pictures
Projects
Backup

Then place files into the correct folders.
`,

quiz:{
question:"What does an operating system do?",
options:[
"Only prints documents",
"Manages hardware and software",
"Only plays music",
"Only browses websites"
],
answer:1
}

},


{
title:"6. Microsoft Word",

notes:`
Microsoft Word is a word-processing application.

It can be used for:

Letters
Reports
Assignments
CVs
Notes
Tables
Documents

Important skills include:

Typing
Formatting
Headings
Bold
Italic
Underline
Lists
Tables
Images
Page setup
`,

visual:[
"📄 Document",
"→",
"✏️ Text",
"→",
"🔤 Formatting",
"→",
"🖼️ Images"
],

practical:`
Create a one-page student profile.

Include:

Name
Education
Skills
Hobbies
A small table
`,

quiz:{
question:"Which feature organizes information into rows and columns?",
options:[
"Table",
"Wallpaper",
"Taskbar",
"Recycle Bin"
],
answer:0
}

},


{
title:"7. Microsoft Excel",

notes:`
Excel is a spreadsheet application.

A spreadsheet contains rows and columns.

The intersection is called a cell.

Formulas normally start with =

Example:

=SUM(B2:B6)

Useful functions include:

SUM
AVERAGE
MIN
MAX
COUNT

Excel can be used for marks,
budgets and data analysis.
`,

visual:[
"📊 Rows",
"→",
"▦ Cells",
"→",
"=SUM(B2:B6)"
],

practical:`
Create a marks sheet for five subjects.

Calculate:

Total
Average
Highest mark
Lowest mark
`,

quiz:{
question:"Which symbol normally starts an Excel formula?",
options:[
"#",
"=",
"@",
"&"
],
answer:1
}

},


{
title:"8. Microsoft PowerPoint",

notes:`
PowerPoint is used to create presentations.

A good presentation normally has:

Title
Introduction
Main Points
Examples
Conclusion

Use short points instead of very large paragraphs.

Use readable text and relevant images.
`,

visual:[
"🖥️ Slide 1",
"→",
"🖥️ Slide 2",
"→",
"🖥️ Slide 3"
],

practical:`
Create five slides about:

Computer Hardware

Use one main topic on each slide.
`,

quiz:{
question:"What should a good presentation avoid?",
options:[
"Clear headings",
"Relevant images",
"Huge paragraphs",
"Short points"
],
answer:2
}

},


{
title:"9. Internet, Browser and Email",

notes:`
The Internet is a global network of connected devices.

A web browser is software used to access websites.

Examples include browsers such as Edge and Chrome.

Search engines help users find information.

Email can be used to send messages and files.

Never open suspicious links or unexpected attachments.
`,

visual:[
"💻 Device",
"→",
"🌐 Internet",
"→",
"🔎 Website"
],

practical:`
Search for a computer topic using a search engine.

Compare information from two educational sources.
`,

quiz:{
question:"Which software is used to open websites?",
options:[
"Browser",
"Calculator",
"Paint",
"File Compressor"
],
answer:0
}

},


{
title:"10. Networking Basics",

notes:`
A computer network connects devices so they can communicate.

LAN means Local Area Network.

WAN means Wide Area Network.

Wi-Fi provides wireless networking.

An IP address identifies a device/interface
on a network.

A router can connect networks and direct traffic.
`,

visual:[
"💻 PC",
"↘",
"📡 Router",
"↙",
"📱 Phone"
],

practical:`
Draw a home network containing:

Router
Computer 1
Computer 2
Phone
`,

quiz:{
question:"What does LAN normally mean?",
options:[
"Local Area Network",
"Large Application Network",
"Local Application Name",
"Long Access Node"
],
answer:0
}

},


{
title:"11. Cyber Safety",

notes:`
Cyber safety means protecting devices,
accounts and personal information.

Important practices:

Use strong passwords.

Do not share passwords.

Use multi-factor authentication when available.

Keep software updated.

Avoid suspicious links.

Do not download unknown files.

Phishing is a deceptive attempt to obtain
information by pretending to be trustworthy.
`,

visual:[
"🔐 Password",
"+",
"📱 Verification",
"+",
"🛡️ Updates",
"=",
"🔒 Safer Account"
],

practical:`
Create a personal security checklist.

Include:

Strong passwords
MFA
Updates
Backups
Suspicious-link awareness
`,

quiz:{
question:"What is phishing?",
options:[
"A monitor",
"A deceptive attempt to steal information",
"A storage device",
"A keyboard shortcut"
],
answer:1
}

},


{
title:"12. Typing, Files and Folders",

notes:`
Typing accurately improves computer productivity.

Useful keyboard shortcuts:

Ctrl + C = Copy

Ctrl + V = Paste

Ctrl + X = Cut

Ctrl + Z = Undo

Ctrl + S = Save

Ctrl + A = Select All

Alt + Tab = Switch applications

Good file management means using organized folders
and meaningful file names.
`,

visual:[
"⌨️ Typing",
"→",
"📁 Folders",
"→",
"📄 Files",
"→",
"💾 Backup"
],

practical:`
Create a folder called:

ZAID-Academy-Project

Inside it create:

Notes
Images
Documents
Backup
`,

quiz:{
question:"Which shortcut normally saves a document?",
options:[
"Ctrl + S",
"Ctrl + P",
"Ctrl + X",
"Ctrl + F"
],
answer:0
}

}

];


/* =========================
   DIT LESSON DATA
========================= */

const DIT = [

{
title:"1. Programming Fundamentals",

notes:`
Programming is the process of creating instructions
that a computer can execute.

An algorithm is a step-by-step method
for solving a problem.

Important programming concepts include:

Variables
Data Types
Operators
Conditions
Loops
Functions

A programmer should understand the problem,
design a solution, write code and test it.
`,

visual:[
"Problem",
"→",
"Algorithm",
"→",
"Code",
"→",
"Test"
],

practical:`
Write an algorithm for finding the larger
of two numbers.
`,

quiz:{
question:"What is an algorithm?",
options:[
"A monitor",
"A step-by-step solution method",
"A keyboard",
"A file type"
],
answer:1
}

},


{
title:"2. HTML and CSS",

notes:`
HTML provides the structure of a web page.

Common HTML elements include:

Headings
Paragraphs
Links
Images
Lists
Buttons
Sections

CSS controls the appearance of a web page.

CSS can change:

Colors
Fonts
Spacing
Borders
Layouts
Responsive design
`,

visual:[
"HTML",
"+",
"CSS",
"=",
"🌐 Website"
],

practical:`
Create a page containing:

Heading
Paragraph
Image
Link
Three cards

Then style it with CSS.
`,

quiz:{
question:"What is mainly used to style HTML?",
options:[
"CSS",
"SQL",
"RAM",
"FTP"
],
answer:0
}

},


{
title:"3. JavaScript",

notes:`
JavaScript adds behavior and interactivity
to websites.

JavaScript can:

Respond to clicks
Change page content
Validate forms
Perform calculations
Create interactive features

Important concepts:

Variables
Functions
Arrays
Objects
Conditions
Loops
DOM
`,

visual:[
"User Click",
"→",
"JavaScript",
"→",
"DOM",
"→",
"Page Update"
],

practical:`
Create a button that changes a paragraph
from "Hello" to "Welcome to ZAID Academy".
`,

quiz:{
question:"What is JavaScript commonly used for?",
options:[
"Website interactivity",
"Replacing RAM",
"Printing only",
"Charging laptops"
],
answer:0
}

},


{
title:"4. Database and SQL",

notes:`
A database stores organized information.

Relational databases normally use tables.

A table contains:

Rows
Columns

SQL is used to work with database information.

Important SQL commands include:

SELECT
INSERT
UPDATE
DELETE

A primary key can uniquely identify a record.
`,

visual:[
"Application",
"→",
"SQL",
"→",
"Database",
"→",
"Tables"
],

practical:`
Design a Student table containing:

ID
Name
Course
Marks
`,

quiz:{
question:"Which SQL command retrieves data?",
options:[
"SELECT",
"PRINT",
"OPEN",
"READFILE"
],
answer:0
}

},


{
title:"5. Networking and TCP/IP",

notes:`
Computer networking allows systems to communicate.

TCP/IP is a family of networking protocols.

IP handles addressing and routing.

TCP provides reliable and ordered delivery
for applications that need it.

DNS translates domain names into IP addresses.

Other concepts include:

Routers
Switches
Servers
Clients
Ports
Protocols
`,

visual:[
"Client",
"→",
"Router",
"→",
"Internet",
"→",
"Server"
],

practical:`
Draw the path from your computer
to a website server.
`,

quiz:{
question:"What is DNS commonly used for?",
options:[
"Translating domain names to IP addresses",
"Printing",
"Editing photos",
"Formatting disks"
],
answer:0
}

},


{
title:"6. Software Development",

notes:`
Software development includes:

Planning
Design
Implementation
Testing
Deployment
Maintenance

Version control helps developers track changes.

Git is a version-control system.

GitHub is a platform for hosting and collaborating
on repositories.

Good projects need documentation and testing.
`,

visual:[
"Plan",
"→",
"Build",
"→",
"Test",
"→",
"Deploy",
"→",
"Maintain"
],

practical:`
Create a project plan containing:

Goal
Features
Files
Testing
Future improvements
`,

quiz:{
question:"What is version control useful for?",
options:[
"Tracking code changes",
"Increasing brightness",
"Printing",
"Charging a laptop"
],
answer:0
}

},


{
title:"7. Data Structures",

notes:`
Data structures organize data for efficient use.

Arrays store ordered collections.

Stacks normally follow:

LIFO
Last In First Out

Queues normally follow:

FIFO
First In First Out

Choosing a suitable data structure
can make a program easier and more efficient.
`,

visual:[
"Data",
"→",
"Structure",
"→",
"Algorithm",
"→",
"Result"
],

practical:`
Give one real-life example of a stack
and one example of a queue.
`,

quiz:{
question:"Which principle does a queue normally follow?",
options:[
"LIFO",
"FIFO",
"Random",
"None"
],
answer:1
}

},


{
title:"8. DIT Practical Web Project",

notes:`
Final practical project:

Build a student learning website.

Recommended sections:

Home
Courses
Lessons
Notes
Visual Learning
Quiz
Videos
Questions
Footer

Use:

HTML for structure
CSS for design
JavaScript for interactions

Test the website on mobile and desktop.
`,

visual:[
"HTML",
"+",
"CSS",
"+",
"JavaScript",
"=",
"🚀 Web Project"
],

practical:`
Build a small ZAID Academy website
with three lessons, a quiz and a question form.

Publish it using GitHub Pages.
`,

quiz:{
question:"Which technologies are used in this project?",
options:[
"HTML, CSS and JavaScript",
"Word, Excel and PowerPoint",
"CPU, RAM and HDD",
"SQL, HDMI and USB"
],
answer:0
}

}

];


/* =========================
   LESSON SYSTEM
========================= */

function loadLessons(data,menuID,contentID,prefix){

const menu=document.getElementById(menuID);

menu.innerHTML="";

data.forEach((lesson,index)=>{

const button=document.createElement("button");

button.className="lesson-button";

button.innerText=lesson.title;

button.onclick=function(){

document
.querySelectorAll("#"+menuID+" .lesson-button")
.forEach(btn=>btn.classList.remove("active"));

button.classList.add("active");

showLesson(data,index,contentID,prefix);

};

menu.appendChild(button);

});

menu.children[0].classList.add("active");

showLesson(data,0,contentID,prefix);

}


function showLesson(data,index,contentID,prefix){

const lesson=data[index];

const content=document.getElementById(contentID);

content.innerHTML=`

<h3>${lesson.title}</h3>

<h4>📚 Lesson Notes</h4>

<div>
${lesson.notes.replace(/\n/g,"<br>")}
</div>

<div class="visual">

<h4>🖼️ Visual Learning</h4>

<div class="diagram">

${lesson.visual.map(item=>{

if(item==="→"){

return `<div class="arrow">→</div>`;

}

return `<div class="diagram-box">${item}</div>`;

}).join("")}

</div>

</div>


<div class="practical">

<strong>🧪 Practical Work</strong>

<br><br>

${lesson.practical}

</div>


<div class="quiz">

<h4>📝 Lesson Quiz</h4>

<p>
<strong>${lesson.quiz.question}</strong>
</p>

${lesson.quiz.options.map((option,i)=>`

<label class="option">

<input
type="radio"
name="${prefix}${index}"
value="${i}"
>

${option}

</label>

`).join("")}

<button
class="btn btn-blue"
onclick="checkLesson('${prefix}',${index})">

Check Answer

</button>

<div
class="result"
id="${prefix}result${index}">
</div>

</div>

`;

}


function checkLesson(prefix,index){

const data=prefix==="cit"?CIT:DIT;

const lesson=data[index];

const selected=document.querySelector(
`input[name="${prefix}${index}"]:checked`
);

const result=document.getElementById(
`${prefix}result${index}`
);

if(!selected){

result.innerHTML="⚠️ Please select an answer.";

return;

}

if(Number(selected.value)===lesson.quiz.answer){

result.innerHTML="✅ Correct Answer!";

}else{

result.innerHTML="❌ Incorrect. Try again.";

}

}


/* LOAD CIT AND DIT */

loadLessons(
CIT,
"citMenu",
"citContent",
"cit"
);

loadLessons(
DIT,
"ditMenu",
"ditContent",
"dit"
);


/* =========================
   QUICK QUIZ
========================= */

const quickQuiz=[

{
q:"Which device is used to type text?",
options:["Mouse","Keyboard","Monitor"],
answer:1
},

{
q:"Which memory is temporary?",
options:["RAM","SSD","USB"],
answer:0
},

{
q:"Which language structures a webpage?",
options:["HTML","SQL","BIOS"],
answer:0
},

{
q:"Which language adds website interactivity?",
options:["JavaScript","CSS","RAM"],
answer:0
},

{
q:"What does Ctrl+C normally do?",
options:["Save","Copy","Paste"],
answer:1
}

];


function createQuickQuiz(){

const box=document.getElementById("quickQuiz");

box.innerHTML="";

quickQuiz.forEach((item,index)=>{

const div=document.createElement("div");

div.className="quiz";

div.innerHTML=`

<p>
<strong>
${index+1}. ${item.q}
</strong>
</p>

${item.options.map((option,i)=>`

<label class="option">

<input
type="radio"
name="quick${index}"
value="${i}"
>

${option}

</label>

`).join("")}

`;

box.appendChild(div);

});

const button=document.createElement("button");

button.className="btn btn-blue";

button.innerText="Submit Quiz";

button.onclick=checkQuickQuiz;

box.appendChild(button);

const result=document.createElement("div");

result.className="result";

result.id="quickResult";

box.appendChild(result);

}


function checkQuickQuiz(){

let score=0;

quickQuiz.forEach((question,index)=>{

const selected=document.querySelector(
`input[name="quick${index}"]:checked`
);

if(
selected &&
Number(selected.value)===question.answer
){

score++;

}

});

document.getElementById("quickResult").innerHTML=

`Your Score: ${score} / ${quickQuiz.length}`;

}

createQuickQuiz();


/* =========================
   QUESTIONS
========================= */

const questionForm=
document.getElementById("questionForm");

questionForm.addEventListener(
"submit",
function(event){

event.preventDefault();

const name=
document.getElementById("studentName").value;

const course=
document.getElementById("course").value;

const question=
document.getElementById("questionText").value;

const oldQuestions=
JSON.parse(
localStorage.getItem("zaidQuestions") || "[]"
);

oldQuestions.push({

name:name,

course:course,

question:question,

date:new Date().toLocaleString()

});

localStorage.setItem(
"zaidQuestions",
JSON.stringify(oldQuestions)
);

questionForm.reset();

loadQuestions();

alert("Question saved successfully!");

});


function loadQuestions(){

const box=
document.getElementById("questionList");

const questions=
JSON.parse(
localStorage.getItem("zaidQuestions") || "[]"
);

if(questions.length===0){

box.innerHTML=
"<p>No questions yet.</p>";

return;

}

box.innerHTML=
questions.reverse().map(q=>`

<div class="question">

<strong>
${escapeHTML(q.name)}
</strong>

<span class="tag">
${escapeHTML(q.course)}
</span>

<p>
${escapeHTML(q.question)}
</p>

<small>
${escapeHTML(q.date)}
</small>

</div>

`).join("");

}


function escapeHTML(text){

return String(text).replace(
/[&<>"']/g,
function(character){

const chars={

"&":"&amp;",
"<":"&lt;",
">":"&gt;",
'"':"&quot;",
"'":"&#039;"

};

return chars[character];

});

}

loadQuestions();

</script>

</body>
</html>
