<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Dharavath Nani | Electronics & Communication Engineer | ESP32 & IoT Portfolio</title>

<meta name="description"
content="Dharavath Nani | Electronics & Communication Engineer portfolio featuring ESP32, IoT, embedded systems, sensors, robotics, electronics projects and ECE experiments.">

<meta name="keywords"
content="Dharavath Nani, Electronics Communication Engineer, ECE Engineer, ESP32, IoT, Embedded Systems, Electronics Projects, Sensor Projects, Arduino, Robotics, Communication Engineering">

<meta name="author" content="Dharavath Nani">
<meta name="robots" content="index, follow, max-image-preview:large">
<meta name="googlebot" content="index, follow">

<meta name="theme-color" content="#07111f">

<!-- CHANGE THIS AFTER PUBLISHING -->
<link rel="canonical"
href="https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/">

<!-- Open Graph -->
<meta property="og:type" content="website">
<meta property="og:title"
content="Dharavath Nani | Electronics & Communication Engineer">
<meta property="og:description"
content="ECE portfolio featuring ESP32, IoT, embedded systems, sensors, robotics and electronics experiments.">
<meta property="og:url"
content="https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/">
<meta property="og:site_name"
content="Dharavath Nani ECE Portfolio">

<!-- Twitter -->
<meta name="twitter:card" content="summary">
<meta name="twitter:title"
content="Dharavath Nani | Electronics & Communication Engineer">
<meta name="twitter:description"
content="ECE portfolio featuring ESP32, IoT, embedded systems, sensors, robotics and electronics experiments.">

<!-- Person Schema -->
<script type="application/ld+json">
{
  "@context":"https://schema.org",
  "@type":"Person",
  "name":"Dharavath Nani",
  "jobTitle":"Electronics & Communication Engineer",
  "email":"mailto:dharavathnani01@email.com",
  "url":"https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/",
  "sameAs":[
    "https://www.linkedin.com/in/dharavath-durga-prasad-10546442b/"
  ],
  "knowsAbout":[
    "Electronics and Communication Engineering",
    "ESP32",
    "IoT",
    "Embedded Systems",
    "Sensors",
    "Robotics",
    "Arduino",
    "Communication Systems",
    "Circuit Design",
    "Python",
    "C",
    "C++"
  ]
}
</script>

<style>

:root{
    --bg:#07111f;
    --bg2:#0b1830;
    --card:rgba(13,29,52,.78);
    --text:#edf6ff;
    --muted:#9fb4cc;
    --accent:#38bdf8;
    --accent2:#8b5cf6;
    --line:rgba(148,163,184,.18);
    --shadow:0 20px 60px rgba(0,0,0,.28);
}

*{
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    margin:0;
    font-family:Inter,Segoe UI,Arial,sans-serif;
    background:
    radial-gradient(circle at 15% 10%,rgba(56,189,248,.14),transparent 30%),
    radial-gradient(circle at 85% 20%,rgba(139,92,246,.15),transparent 30%),
    var(--bg);
    color:var(--text);
    line-height:1.6;
}

body:before{
    content:"";
    position:fixed;
    inset:0;
    pointer-events:none;
    opacity:.22;
    background-image:
    linear-gradient(rgba(56,189,248,.08) 1px,transparent 1px),
    linear-gradient(90deg,rgba(56,189,248,.08) 1px,transparent 1px);
    background-size:50px 50px;
}

a{
    color:inherit;
    text-decoration:none;
}

.container{
    width:min(1120px,92%);
    margin:auto;
}

nav{
    position:fixed;
    top:0;
    left:0;
    right:0;
    z-index:50;
    background:rgba(7,17,31,.85);
    backdrop-filter:blur(16px);
    border-bottom:1px solid var(--line);
}

.navbar{
    height:72px;
    display:flex;
    align-items:center;
    justify-content:space-between;
}

.logo{
    font-size:1.25rem;
    font-weight:800;
}

.logo span{
    color:var(--accent);
}

.navlinks{
    display:flex;
    gap:20px;
    font-size:.9rem;
    color:var(--muted);
}

.navlinks a:hover{
    color:var(--accent);
}

.menu{
    display:none;
    background:none;
    border:0;
    color:white;
    font-size:1.6rem;
}

.hero{
    min-height:100vh;
    display:grid;
    place-items:center;
    padding:120px 0 70px;
}

.hero-grid{
    display:grid;
    grid-template-columns:1.2fr .8fr;
    gap:60px;
    align-items:center;
}

.badge{
    display:inline-flex;
    gap:8px;
    align-items:center;
    padding:8px 13px;
    border:1px solid rgba(56,189,248,.3);
    border-radius:999px;
    background:rgba(56,189,248,.08);
    color:#bcecff;
    font-size:.85rem;
}

.badge i{
    width:8px;
    height:8px;
    border-radius:50%;
    background:#22c55e;
    box-shadow:0 0 14px #22c55e;
}

h1{
    font-size:clamp(2.7rem,6vw,5.4rem);
    line-height:1.02;
    margin:20px 0;
    letter-spacing:-3px;
}

.gradient{
    background:linear-gradient(90deg,#fff,var(--accent),#a78bfa);
    -webkit-background-clip:text;
    background-clip:text;
    color:transparent;
}

.hero p{
    font-size:1.1rem;
    color:var(--muted);
    max-width:700px;
}

.buttons{
    display:flex;
    gap:14px;
    flex-wrap:wrap;
    margin-top:28px;
}

.btn{
    padding:13px 20px;
    border-radius:12px;
    border:1px solid var(--line);
    font-weight:700;
    display:inline-flex;
    align-items:center;
    gap:8px;
    transition:.25s;
}

.btn.primary{
    background:linear-gradient(135deg,var(--accent),var(--accent2));
    border:0;
}

.btn:hover{
    transform:translateY(-3px);
    box-shadow:0 12px 30px rgba(56,189,248,.18);
}

/* Circuit */

.circuit{
    height:430px;
    position:relative;
    border:1px solid var(--line);
    border-radius:28px;
    background:linear-gradient(145deg,rgba(15,35,62,.92),rgba(8,20,38,.78));
    box-shadow:var(--shadow);
    overflow:hidden;
}

.circuit:before,
.circuit:after{
    content:"";
    position:absolute;
    border:1px solid rgba(56,189,248,.25);
    border-radius:50%;
}

.circuit:before{
    width:260px;
    height:260px;
    top:80px;
    left:65px;
}

.circuit:after{
    width:170px;
    height:170px;
    top:125px;
    left:110px;
}

.chip{
    position:absolute;
    top:160px;
    left:145px;
    width:110px;
    height:90px;
    border:2px solid var(--accent);
    border-radius:14px;
    display:grid;
    place-items:center;
    background:#09182b;
    box-shadow:0 0 35px rgba(56,189,248,.25);
}

.chip b{
    font-size:1.4rem;
}

.pin{
    position:absolute;
    width:28px;
    height:2px;
    background:var(--accent);
}

.p1{left:117px;top:176px}
.p2{left:117px;top:200px}
.p3{left:117px;top:224px}

.p4{right:117px;top:176px}
.p5{right:117px;top:200px}
.p6{right:117px;top:224px}

.node{
    position:absolute;
    width:10px;
    height:10px;
    border-radius:50%;
    background:var(--accent);
    box-shadow:0 0 18px var(--accent);
}

.n1{top:80px;left:45px}
.n2{top:350px;left:300px}
.n3{top:70px;right:55px}
.n4{bottom:35px;right:85px}

/* Sections */

section{
    padding:90px 0;
}

.section-head{
    margin-bottom:36px;
}

.eyebrow{
    color:var(--accent);
    font-weight:800;
    text-transform:uppercase;
    letter-spacing:2px;
    font-size:.78rem;
}

.section-head h2{
    font-size:2.3rem;
    margin:8px 0;
}

.section-head p{
    color:var(--muted);
    max-width:700px;
}

.card{
    background:var(--card);
    border:1px solid var(--line);
    border-radius:18px;
    padding:25px;
    box-shadow:var(--shadow);
    transition:.25s;
}

.card:hover{
    transform:translateY(-5px);
    border-color:rgba(56,189,248,.35);
}

.about{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:25px;
}

/* Skills */

.skills{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:15px;
}

.skill{
    padding:18px;
    border:1px solid var(--line);
    border-radius:14px;
    background:rgba(255,255,255,.025);
}

.skill strong{
    display:block;
    margin-bottom:6px;
}

.skill span{
    font-size:.86rem;
    color:var(--muted);
}

/* Projects */

.filters{
    display:flex;
    gap:10px;
    flex-wrap:wrap;
    margin-bottom:25px;
}

.filter{
    background:transparent;
    color:var(--muted);
    border:1px solid var(--line);
    padding:9px 14px;
    border-radius:999px;
    cursor:pointer;
}

.filter.active,
.filter:hover{
    color:white;
    border-color:var(--accent);
    background:rgba(56,189,248,.1);
}

.projects{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:18px;
}

.project h3{
    margin:10px 0 7px;
}

.project p{
    color:var(--muted);
    font-size:.92rem;
}

.tags{
    display:flex;
    gap:7px;
    flex-wrap:wrap;
    margin-top:15px;
}

.tag{
    font-size:.72rem;
    color:#bdefff;
    border:1px solid rgba(56,189,248,.22);
    background:rgba(56,189,248,.07);
    padding:5px 8px;
    border-radius:999px;
}

.project small{
    color:var(--accent);
}

/* Experiment Lab */

.lab-note{
    padding:16px 18px;
    border:1px solid rgba(56,189,248,.22);
    border-radius:14px;
    background:rgba(56,189,248,.06);
    color:var(--muted);
    margin-bottom:24px;
}

.experiment-controls{
    display:flex;
    gap:10px;
    margin-bottom:24px;
}

.exp-search{
    width:100%;
    padding:13px 16px;
    border-radius:12px;
    border:1px solid var(--line);
    background:rgba(255,255,255,.04);
    color:white;
    outline:none;
}

.exp-search:focus{
    border-color:var(--accent);
}

.experiments{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:18px;
}

.experiment h3{
    margin:8px 0;
}

.experiment .meta{
    font-size:.8rem;
    color:var(--accent);
    font-weight:700;
}

.exp-details{
    margin-top:16px;
    border-top:1px solid var(--line);
    padding-top:14px;
}

.exp-details summary{
    cursor:pointer;
    color:#bdefff;
    font-weight:700;
}

.exp-details p{
    color:var(--muted);
    font-size:.9rem;
}

.components{
    display:flex;
    gap:7px;
    flex-wrap:wrap;
    margin:10px 0;
}

.component{
    font-size:.72rem;
    padding:5px 8px;
    border:1px solid var(--line);
    border-radius:999px;
    color:var(--muted);
}

.codebox{
    position:relative;
    margin-top:12px;
}

.codebox pre{
    background:#050b14;
    border:1px solid var(--line);
    padding:15px;
    border-radius:12px;
    overflow:auto;
    font-size:.76rem;
    color:#dbeafe;
}

.copybtn{
    position:absolute;
    right:8px;
    top:8px;
    border:1px solid var(--line);
    background:#0d2038;
    color:#bdefff;
    padding:6px 9px;
    border-radius:8px;
    cursor:pointer;
}

/* Timeline */

.timeline{
    border-left:1px solid var(--line);
    padding-left:25px;
    display:grid;
    gap:22px;
}

.timeline .card{
    position:relative;
}

.timeline .card:before{
    content:"";
    position:absolute;
    left:-32px;
    top:27px;
    width:12px;
    height:12px;
    border-radius:50%;
    background:var(--accent);
    box-shadow:0 0 15px rgba(56,189,248,.7);
}

/* Contact */

.contact{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:22px;
}

.contact-item{
    display:flex;
    gap:14px;
    align-items:center;
    padding:17px;
    border:1px solid var(--line);
    border-radius:14px;
}

.icon{
    width:42px;
    height:42px;
    display:grid;
    place-items:center;
    border-radius:12px;
    background:rgba(56,189,248,.1);
}

footer{
    border-top:1px solid var(--line);
    padding:28px 0;
    color:var(--muted);
    text-align:center;
}

/* Animation */

.reveal{
    opacity:0;
    transform:translateY(20px);
    transition:.7s;
}

.reveal.show{
    opacity:1;
    transform:none;
}

/* Mobile */

@media(max-width:850px){

    .hero-grid,
    .about,
    .contact{
        grid-template-columns:1fr;
    }

    .skills{
        grid-template-columns:repeat(2,1fr);
    }

    .projects,
    .experiments{
        grid-template-columns:repeat(2,1fr);
    }

    .navlinks{
        display:none;
    }

    .menu{
        display:block;
    }

    .navlinks.open{
        display:flex;
        position:absolute;
        top:72px;
        left:0;
        right:0;
        background:#07111f;
        padding:20px;
        flex-direction:column;
    }

    .circuit{
        height:350px;
    }
}

@media(max-width:560px){

    h1{
        letter-spacing:-1.5px;
    }

    .skills,
    .projects,
    .experiments{
        grid-template-columns:1fr;
    }

    .hero{
        padding-top:105px;
    }

    .circuit{
        height:310px;
    }

    .chip{
        left:calc(50% - 55px);
    }

}

</style>
</head>

<body>

<!-- NAVIGATION -->

<nav>
<div class="container navbar">

<a class="logo" href="#home">
Dharavath<span>Nani</span>
</a>

<button class="menu"
onclick="document.querySelector('.navlinks').classList.toggle('open')">
☰
</button>

<div class="navlinks">
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#lab">Experiment Lab</a>
<a href="#education">Education</a>
<a href="#contact">Contact</a>
</div>

</div>
</nav>


<!-- HERO -->

<header class="hero" id="home">

<div class="container hero-grid">

<div class="reveal">

<div class="badge">
<i></i>
Electronics & Communication Engineering
</div>

<h1>
Build.<br>
Connect.<br>
<span class="gradient">Innovate.</span>
</h1>

<p>
Hi, I'm <strong>Dharavath Nani</strong> — an Electronics & Communication Engineering enthusiast focused on
<strong>ESP32, IoT, embedded systems, sensors, robotics, electronics and communication technologies</strong>.
</p>

<div class="buttons">

<a class="btn primary" href="#projects">
🚀 Explore Projects
</a>

<a class="btn" href="#lab">
🔬 ECE Experiment Lab
</a>

<a class="btn" href="mailto:dharavathnani01@email.com">
✉ Contact Me
</a>

</div>

</div>


<div class="circuit reveal">

<div class="chip">
<b>ECE</b>
</div>

<span class="pin p1"></span>
<span class="pin p2"></span>
<span class="pin p3"></span>

<span class="pin p4"></span>
<span class="pin p5"></span>
<span class="pin p6"></span>

<span class="node n1"></span>
<span class="node n2"></span>
<span class="node n3"></span>
<span class="node n4"></span>

</div>

</div>

</header>


<!-- ABOUT -->

<section id="about">

<div class="container">

<div class="section-head reveal">

<div class="eyebrow">About</div>

<h2>Engineering with curiosity.</h2>

<p>
A personal portfolio showcasing electronics knowledge,
hands-on projects and practical engineering experiments.
</p>

</div>


<div class="about">

<div class="card reveal">

<h3>👨‍💻 About Dharavath Nani</h3>

<p>
I am Dharavath Nani, an Electronics & Communication Engineering
enthusiast interested in turning ideas into working hardware
and software solutions.
</p>

<p>
My interests include embedded systems, microcontrollers,
IoT, robotics, wireless communication, circuit design
and programming.
</p>

</div>


<div class="card reveal">

<h3>🎯 Areas of Interest</h3>

<p>
Smart devices, sensor-based systems, automation,
connected products, robotics and practical engineering
solutions.
</p>

<div class="tags">

<span class="tag">ESP32</span>
<span class="tag">IoT</span>
<span class="tag">Embedded</span>
<span class="tag">Robotics</span>
<span class="tag">Sensors</span>
<span class="tag">Communication</span>

</div>

</div>

</div>

</div>

</section>


<!-- SKILLS -->

<section id="skills">

<div class="container">

<div class="section-head reveal">

<div class="eyebrow">Technical Skills</div>

<h2>Tools & technologies.</h2>

</div>


<div class="skills">

<div class="skill reveal">
<strong>💻 Programming</strong>
<span>C • C++ • Python • Java • HTML • CSS • JavaScript</span>
</div>

<div class="skill reveal">
<strong>🔌 Electronics</strong>
<span>Analog • Digital • Circuit Design • PCB Basics</span>
</div>

<div class="skill reveal">
<strong>⚙ Embedded Systems</strong>
<span>ESP32 • Arduino • ESP8266 • STM32 • Raspberry Pi</span>
</div>

<div class="skill reveal">
<strong>📡 Communication</strong>
<span>Digital Communication • Wireless • RF • Antennas</span>
</div>

<div class="skill reveal">
<strong>🌐 IoT</strong>
<span>Sensors • MQTT • Wi-Fi • Cloud • Automation</span>
</div>

<div class="skill reveal">
<strong>🤖 Robotics</strong>
<span>Motors • Drivers • Ultrasonic • IR Sensors</span>
</div>

<div class="skill reveal">
<strong>🧪 Simulation</strong>
<span>MATLAB • Proteus • LTspice • KiCad</span>
</div>

<div class="skill reveal">
<strong>🛠 Tools</strong>
<span>Arduino IDE • Git • GitHub • Linux</span>
</div>

</div>

</div>

</section>


<!-- PROJECTS -->

<section id="projects">

<div class="container">

<div class="section-head reveal">

<div class="eyebrow">Projects</div>

<h2>Engineering ideas in action.</h2>

<p>
Project showcase covering embedded systems, IoT,
robotics and electronics.
</p>

</div>


<div class="filters">

<button class="filter active" data-filter="all">
All
</button>

<button class="filter" data-filter="iot">
IoT
</button>

<button class="filter" data-filter="embedded">
Embedded
</button>

<button class="filter" data-filter="robotics">
Robotics
</button>

<button class="filter" data-filter="electronics">
Electronics
</button>

</div>


<div class="projects">


<div class="card project reveal" data-cat="iot">

<small>PROJECT 01</small>

<h3>IoT Smart Home Automation</h3>

<p>
ESP32-based home automation concept for controlling
connected appliances and monitoring sensors.
</p>

<div class="tags">
<span class="tag">ESP32</span>
<span class="tag">IoT</span>
<span class="tag">Sensors</span>
</div>

</div>


<div class="card project reveal" data-cat="embedded">

<small>PROJECT 02</small>

<h3>ESP32 Smart Security System</h3>

<p>
Embedded security prototype using sensors,
alerts and microcontroller control.
</p>

<div class="tags">
<span class="tag">ESP32</span>
<span class="tag">Embedded</span>
<span class="tag">Sensors</span>
</div>

</div>


<div class="card project reveal" data-cat="iot">

<small>PROJECT 03</small>

<h3>IoT Weather Station</h3>

<p>
Temperature and humidity monitoring system
using ESP32 and environmental sensors.
</p>

<div class="tags">
<span class="tag">ESP32</span>
<span class="tag">DHT11</span>
<span class="tag">IoT</span>
</div>

</div>


<div class="card project reveal" data-cat="robotics">

<small>PROJECT 04</small>

<h3>Obstacle Avoiding Robot</h3>

<p>
Autonomous robot that detects obstacles and
changes direction automatically.
</p>

<div class="tags">
<span class="tag">Arduino</span>
<span class="tag">Ultrasonic</span>
<span class="tag">Robotics</span>
</div>

</div>


<div class="card project reveal" data-cat="robotics">

<small>PROJECT 05</small>

<h3>Bluetooth Controlled Robot</h3>

<p>
Wireless robot controlled through a mobile device.
</p>

<div class="tags">
<span class="tag">Bluetooth</span>
<span class="tag">Arduino</span>
<span class="tag">Motors</span>
</div>

</div>


<div class="card project reveal" data-cat="electronics">

<small>PROJECT 06</small>

<h3>Smart Energy Meter</h3>

<p>
Prototype for measuring and monitoring electrical
energy parameters.
</p>

<div class="tags">
<span class="tag">Sensors</span>
<span class="tag">Embedded</span>
<span class="tag">Power</span>
</div>

</div>


<div class="card project reveal" data-cat="electronics">

<small>PROJECT 07</small>

<h3>Automatic Street Light</h3>

<p>
Automatic lighting system based on ambient
light intensity.
</p>

<div class="tags">
<span class="tag">LDR</span>
<span class="tag">Automation</span>
</div>

</div>


<div class="card project reveal" data-cat="electronics">

<small>PROJECT 08</small>

<h3>Fire Detection System</h3>

<p>
Sensor-based fire detection prototype with
visual or audible warning.
</p>

<div class="tags">
<span class="tag">Sensor</span>
<span class="tag">Arduino</span>
<span class="tag">Alarm</span>
</div>

</div>


<div class="card project reveal" data-cat="iot">

<small>PROJECT 09</small>

<h3>Smart Irrigation</h3>

<p>
Soil moisture monitoring concept for automated
plant watering.
</p>

<div class="tags">
<span class="tag">IoT</span>
<span class="tag">Soil Sensor</span>
</div>

</div>


</div>

</div>

</section>


<!-- EXPERIMENT LAB -->

<section id="lab">

<div class="container">

<div class="section-head reveal">

<div class="eyebrow">ECE Experiment Lab</div>

<h2>Build, test & learn.</h2>

<p>
Interactive ESP32 and sensor experiments with
aim, components, wiring, working and starter code.
</p>

</div>


<div class="lab-note reveal">

⚡ <strong>Safety:</strong>
These experiments use low-voltage electronics.
Always verify module voltage levels and wiring before
powering your circuit.

</div>


<div class="experiment-controls">

<input
class="exp-search"
id="expSearch"
placeholder="Search experiments, sensors or components..."
oninput="filterExperiments()">

</div>


<div class="experiments" id="experimentGrid">


<!-- EXPERIMENT 1 -->

<article class="card experiment reveal">

<div class="meta">
EXPERIMENT 01 • ESP32 + DHT11
</div>

<h3>🌡️ Temperature & Humidity Monitor</h3>

<p>
Read temperature and humidity using a DHT11 sensor
connected to an ESP32.
</p>

<div class="components">
<span class="component">ESP32</span>
<span class="component">DHT11</span>
<span class="component">Arduino IDE</span>
</div>

<details class="exp-details">

<summary>
Aim • Wiring • Working • Code
</summary>

<p>
<strong>Aim:</strong>
Interface DHT11 with ESP32 and display readings.
</p>

<p>
<strong>Wiring:</strong>
VCC → 3.3V,
GND → GND,
DATA → GPIO 4.
</p>

<p>
<strong>Working:</strong>
ESP32 requests sensor data and reads temperature
and humidity values.
</p>

<div class="codebox">

<button class="copybtn" onclick="copyCode(this)">
Copy
</button>

<pre><code>#include &lt;DHT.h&gt;

#define DHTPIN 4
#define DHTTYPE DHT11

DHT dht(DHTPIN,DHTTYPE);

void setup(){
  Serial.begin(115200);
  dht.begin();
}

void loop(){

  float temperature =
  dht.readTemperature();

  float humidity =
  dht.readHumidity();

  Serial.print("Temperature: ");
  Serial.println(temperature);

  Serial.print("Humidity: ");
  Serial.println(humidity);

  delay(2000);
}</code></pre>

</div>

</details>

</article>


<!-- EXPERIMENT 2 -->

<article class="card experiment reveal">

<div class="meta">
EXPERIMENT 02 • ESP32 + HC-SR04
</div>

<h3>📏 Ultrasonic Distance Meter</h3>

<p>
Measure distance using ultrasonic pulse timing.
</p>

<div class="components">
<span class="component">ESP32</span>
<span class="component">HC-SR04</span>
<span class="component">ADC/GPIO</span>
</div>

<details class="exp-details">

<summary>
Aim • Wiring • Working • Code
</summary>

<p>
<strong>Aim:</strong>
Measure distance between sensor and object.
</p>

<p>
<strong>Wiring:</strong>
TRIG → GPIO 5,
ECHO → GPIO 18,
GND → GND.
Use appropriate voltage protection on the
echo signal for ESP32.
</p>

<p>
<strong>Working:</strong>
ESP32 measures the time taken by the ultrasonic
pulse to return.
</p>

<div class="codebox">

<button class="copybtn" onclick="copyCode(this)">
Copy
</button>

<pre><code>const int trig = 5;
const int echo = 18;

void setup(){

  Serial.begin(115200);

  pinMode(trig,OUTPUT);
  pinMode(echo,INPUT);
}

void loop(){

  digitalWrite(trig,LOW);
  delayMicroseconds(2);

  digitalWrite(trig,HIGH);
  delayMicroseconds(10);

  digitalWrite(trig,LOW);

  long duration =
  pulseIn(echo,HIGH);

  float distance =
  duration * 0.0343 / 2;

  Serial.println(distance);

  delay(500);
}</code></pre>

</div>

</details>

</article>


<!-- EXPERIMENT 3 -->

<article class="card experiment reveal">

<div class="meta">
EXPERIMENT 03 • ESP32 + LDR
</div>

<h3>💡 Light Intensity Sensor</h3>

<p>
Measure changes in light using an LDR sensor.
</p>

<div class="components">
<span class="component">ESP32</span>
<span class="component">LDR</span>
<span class="component">10K Resistor</span>
</div>

<details class="exp-details">

<summary>
Aim • Wiring • Working • Code
</summary>

<p>
<strong>Aim:</strong>
Read light intensity through an analog input.
</p>

<p>
<strong>Wiring:</strong>
Build an LDR voltage divider and connect
the output to GPIO 34.
</p>

<p>
<strong>Working:</strong>
LDR resistance changes with light,
changing the voltage read by the ESP32 ADC.
</p>

<div class="codebox">

<button class="copybtn" onclick="copyCode(this)">
Copy
</button>

<pre><code>const int ldrPin = 34;

void setup(){

  Serial.begin(115200);

}

void loop(){

  int value =
  analogRead(ldrPin);

  Serial.print("Light: ");
  Serial.println(value);

  delay(500);
}</code></pre>

</div>

</details>

</article>


<!-- EXPERIMENT 4 -->

<article class="card experiment reveal">

<div class="meta">
EXPERIMENT 04 • ESP32 + PIR
</div>

<h3>🚶 Motion Detection</h3>

<p>
Detect movement using a PIR motion sensor.
</p>

<div class="components">
<span class="component">ESP32</span>
<span class="component">PIR</span>
<span class="component">LED</span>
</div>

<details class="exp-details">

<summary>
Aim • Wiring • Working • Code
</summary>

<p>
<strong>Aim:</strong>
Detect movement and control an indicator.
</p>

<p>
<strong>Wiring:</strong>
PIR OUT → GPIO 27.
LED → GPIO 2 through resistor.
</p>

<div class="codebox">

<button class="copybtn" onclick="copyCode(this)">
Copy
</button>

<pre><code>const int pir = 27;
const int led = 2;

void setup(){

  pinMode(pir,INPUT);
  pinMode(led,OUTPUT);

}

void loop(){

  int motion =
  digitalRead(pir);

  digitalWrite(led,motion);

  delay(50);
}</code></pre>

</div>

</details>

</article>


<!-- EXPERIMENT 5 -->

<article class="card experiment reveal">

<div class="meta">
EXPERIMENT 05 • ESP32 + MQ-2
</div>

<h3>🫧 Gas Sensor Monitor</h3>

<p>
Read the analog output of an MQ-2 sensor.
</p>

<div class="components">
<span class="component">ESP32</span>
<span class="component">MQ-2</span>
<span class="component">ADC</span>
</div>

<details class="exp-details">

<summary>
Aim • Working • Code
</summary>

<p>
<strong>Aim:</strong>
Monitor changes in the sensor analog output.
</p>

<p>
<strong>Working:</strong>
The sensor output changes depending on
its sensing environment.
</p>

<p>
This is a learning prototype and should not
be treated as a calibrated safety instrument.
</p>

<div class="codebox">

<button class="copybtn" onclick="copyCode(this)">
Copy
</button>

<pre><code>const int mq2 = 35;

void setup(){

  Serial.begin(115200);

}

void loop(){

  int value =
  analogRead(mq2);

  Serial.print("MQ2: ");
  Serial.println(value);

  delay(500);
}</code></pre>

</div>

</details>

</article>


<!-- EXPERIMENT 6 -->

<article class="card experiment reveal">

<div class="meta">
EXPERIMENT 06 • ESP32 + SOIL SENSOR
</div>

<h3>🌱 Soil Moisture Monitor</h3>

<p>
Monitor soil moisture using an analog sensor.
</p>

<div class="components">
<span class="component">ESP32</span>
<span class="component">Soil Sensor</span>
<span class="component">LED</span>
</div>

<details class="exp-details">

<summary>
Aim • Working • Code
</summary>

<p>
<strong>Aim:</strong>
Determine whether soil is relatively dry or wet.
</p>

<p>
<strong>Working:</strong>
Sensor output changes with soil moisture.
Calibrate the threshold for your particular sensor.
</p>

<div class="codebox">

<button class="copybtn" onclick="copyCode(this)">
Copy
</button>

<pre><code>const int soil = 34;
const int led = 2;

int threshold = 2000;

void setup(){

  pinMode(led,OUTPUT);
  Serial.begin(115200);

}

void loop(){

  int value =
  analogRead(soil);

  digitalWrite(
    led,
    value > threshold
  );

  Serial.println(value);

  delay(500);
}</code></pre>

</div>

</details>

</article>


<!-- EXPERIMENT 7 -->

<article class="card experiment reveal">

<div class="meta">
EXPERIMENT 07 • ESP32 + RELAY
</div>

<h3>🔌 Sensor-Based Relay Control</h3>

<p>
Control a relay from ESP32 digital output.
</p>

<div class="components">
<span class="component">ESP32</span>
<span class="component">Relay</span>
<span class="component">Sensor</span>
</div>

<details class="exp-details">

<summary>
Aim • Working • Code
</summary>

<p>
<strong>Aim:</strong>
Demonstrate digital control of a relay module.
</p>

<p>
<strong>Important:</strong>
Use only correctly rated low-voltage loads
for learning unless you are qualified to work
with mains systems.
</p>

<div class="codebox">

<button class="copybtn" onclick="copyCode(this)">
Copy
</button>

<pre><code>const int relay = 26;

void setup(){

  pinMode(relay,OUTPUT);

  digitalWrite(
    relay,
    LOW
  );

}

void loop(){

  digitalWrite(
    relay,
    HIGH
  );

  delay(2000);

  digitalWrite(
    relay,
    LOW
  );

  delay(2000);
}</code></pre>

</div>

</details>

</article>


<!-- EXPERIMENT 8 -->

<article class="card experiment reveal">

<div class="meta">
EXPERIMENT 08 • ESP32 + OLED
</div>

<h3>🖥️ OLED Sensor Display</h3>

<p>
Display sensor values using an I2C OLED.
</p>

<div class="components">
<span class="component">ESP32</span>
<span class="component">OLED</span>
<span class="component">I2C</span>
</div>

<details class="exp-details">

<summary>
Aim • Wiring • Working • Code
</summary>

<p>
<strong>Aim:</strong>
Learn I2C communication and display data.
</p>

<p>
<strong>Wiring:</strong>
SDA → GPIO 21,
SCL → GPIO 22.
</p>

<div class="codebox">

<button class="copybtn" onclick="copyCode(this)">
Copy
</button>

<pre><code>#include &lt;Wire.h&gt;
#include &lt;Adafruit_GFX.h&gt;
#include &lt;Adafruit_SSD1306.h&gt;

Adafruit_SSD1306 display(
  128,
  64,
  &amp;Wire,
  -1
);

void setup(){

  Wire.begin(21,22);

  display.begin(
    SSD1306_SWITCHCAPVCC,
    0x3C
  );

  display.clearDisplay();

  display.setTextSize(2);
  display.setTextColor(
    SSD1306_WHITE
  );

  display.setCursor(0,0);

  display.println("ECE LAB");

  display.display();
}

void loop(){}</code></pre>

</div>

</details>

</article>


<!-- EXPERIMENT 9 -->

<article class="card experiment reveal">

<div class="meta">
EXPERIMENT 09 • ESP32 + SERVO
</div>

<h3>⚙️ Sensor Controlled Servo</h3>

<p>
Control servo position based on sensor readings.
</p>

<div class="components">
<span class="component">ESP32</span>
<span class="component">Servo</span>
<span class="component">Sensor</span>
</div>

<details class="exp-details">

<summary>
Aim • Working • Code
</summary>

<p>
<strong>Aim:</strong>
Convert an analog sensor value into servo position.
</p>

<div class="codebox">

<button class="copybtn" onclick="copyCode(this)">
Copy
</button>

<pre><code>#include &lt;ESP32Servo.h&gt;

Servo servo;

const int sensor = 34;

void setup(){

  servo.attach(13);

}

void loop(){

  int value =
  analogRead(sensor);

  int angle =
  map(
    value,
    0,
    4095,
    0,
    180
  );

  servo.write(angle);

  delay(30);
}</code></pre>

</div>

</details>

</article>


<!-- EXPERIMENT 10 -->

<article class="card experiment reveal">

<div class="meta">
EXPERIMENT 10 • ESP32 IoT
</div>

<h3>☁️ ESP32 Sensor Web Dashboard</h3>

<p>
Read a sensor and display its value on a
local ESP32 web page.
</p>

<div class="components">
<span class="component">ESP32</span>
<span class="component">Wi-Fi</span>
<span class="component">Sensor</span>
<span class="component">HTML</span>
</div>

<details class="exp-details">

<summary>
Aim • Working • Code
</summary>

<p>
<strong>Aim:</strong>
Combine sensor reading with Wi-Fi connectivity.
</p>

<p>
<strong>Working:</strong>
ESP32 connects to Wi-Fi and serves a simple
web page containing the latest sensor value.
</p>

<div class="codebox">

<button class="copybtn" onclick="copyCode(this)">
Copy
</button>

<pre><code>#include &lt;WiFi.h&gt;

const char* ssid =
"YOUR_WIFI";

const char* password =
"YOUR_PASSWORD";

WiFiServer server(80);

const int sensor = 34;

void setup(){

  Serial.begin(115200);

  WiFi.begin(
    ssid,
    password
  );

  while(
    WiFi.status()
    != WL_CONNECTED
  ){

    delay(300);

  }

  server.begin();
}

void loop(){

  WiFiClient client =
  server.available();

  if(!client)
    return;

  int value =
  analogRead(sensor);

  client.println(
    "HTTP/1.1 200 OK"
  );

  client.println(
    "Content-Type: text/html"
  );

  client.println();

  client.println(
    "&lt;h1&gt;ESP32 Sensor Lab&lt;/h1&gt;"
  );

  client.println(
    "&lt;p&gt;Sensor Value: "
    + String(value)
    + "&lt;/p&gt;"
  );

  client.stop();
}</code></pre>

</div>

</details>

</article>


</div>

</div>

</section>


<!-- EDUCATION -->

<section id="education">

<div class="container">

<div class="section-head reveal">

<div class="eyebrow">
Education & Learning
</div>

<h2>Engineering journey.</h2>

</div>

<div class="timeline">

<div class="card reveal">

<h3>🎓 Electronics & Communication Engineering</h3>

<p>
Building foundations in electronics, communication systems,
embedded systems, digital systems, signals and engineering mathematics.
</p>

</div>

<div class="card reveal">

<h3>📚 Continuous Learning</h3>

<p>
Exploring ESP32, IoT, microcontrollers, programming,
robotics, sensors, PCB design and wireless technologies.
</p>

</div>

</div>

</div>

</section>


<!-- FAQ -->

<section id="faq">

<div class="container">

<div class="section-head reveal">

<div class="eyebrow">FAQ</div>

<h2>ECE Portfolio Questions</h2>

</div>

<div class="about">

<div class="card reveal">

<h3>
What does Dharavath Nani work on?
</h3>

<p>
Dharavath Nani's portfolio focuses on Electronics &
Communication Engineering, ESP32, IoT, embedded systems,
sensors, robotics, circuit design and communication technologies.
</p>

</div>


<div class="card reveal">

<h3>
What is the ECE Experiment Lab?
</h3>

<p>
The ECE Experiment Lab contains ESP32 and sensor experiments
covering temperature, humidity, distance, light, motion,
gas sensing, soil moisture, OLED displays, servo control
and IoT dashboards.
</p>

</div>

</div>

</div>

</section>


<!-- CONTACT -->

<section id="contact">

<div class="container">

<div class="section-head reveal">

<div class="eyebrow">Contact</div>

<h2>Let's connect.</h2>

<p>
Have a project idea, collaboration or engineering opportunity?
Reach out.
</p>

</div>


<div class="contact">

<a
class="contact-item reveal"
href="mailto:dharavathnani01@email.com">

<div class="icon">
✉
</div>

<div>

<strong>Email</strong>

<br>

<span style="color:var(--muted)">
dharavathnani01@email.com
</span>

</div>

</a>


<a
class="contact-item reveal"
href="https://www.linkedin.com/in/dharavath-durga-prasad-10546442b/"
target="_blank"
rel="noopener">

<div class="icon">
in
</div>

<div>

<strong>LinkedIn</strong>

<br>

<span style="color:var(--muted)">
Connect on LinkedIn
</span>

</div>

</a>

</div>

</div>

</section>


<!-- FOOTER -->

<footer>

<div class="container">

© <span id="year"></span>
Dharavath Nani • Electronics & Communication Engineering

</div>

</footer>


<!-- FAQ STRUCTURED DATA -->

<script type="application/ld+json">
{
 "@context":"https://schema.org",
 "@type":"FAQPage",
 "mainEntity":[
 {
  "@type":"Question",
  "name":"What does Dharavath Nani work on?",
  "acceptedAnswer":{
   "@type":"Answer",
   "text":"Dharavath Nani's portfolio focuses on Electronics & Communication Engineering, ESP32, IoT, embedded systems, sensors, robotics, circuit design and communication technologies."
  }
 },
 {
  "@type":"Question",
  "name":"What is the ECE Experiment Lab?",
  "acceptedAnswer":{
   "@type":"Answer",
   "text":"The ECE Experiment Lab contains ESP32 and sensor experiments covering temperature, humidity, distance, light, motion, gas sensing, soil moisture, OLED displays, servo control and IoT dashboards."
  }
 }
 ]
}
</script>


<script>

document.getElementById("year").textContent =
new Date().getFullYear();


/* Scroll animations */

const observer =
new IntersectionObserver(
(entries)=>{
    entries.forEach(entry=>{
        if(entry.isIntersecting){
            entry.target.classList.add("show");
        }
    });
},
{
    threshold:.08
}
);

document
.querySelectorAll(".reveal")
.forEach(element=>{
    observer.observe(element);
});


/* Project filter */

document
.querySelectorAll(".filter")
.forEach(button=>{

button.addEventListener(
"click",
()=>{

document
.querySelectorAll(".filter")
.forEach(b=>{
    b.classList.remove("active");
});

button.classList.add("active");

const filter =
button.dataset.filter;

document
.querySelectorAll(".project")
.forEach(project=>{

if(
filter === "all" ||
project.dataset.cat === filter
){

project.style.display="block";

}else{

project.style.display="none";

}

});

}
);

});


/* Experiment search */

function filterExperiments(){

const query =
document
.getElementById("expSearch")
.value
.toLowerCase();

document
.querySelectorAll(".experiment")
.forEach(card=>{

if(
card.innerText
.toLowerCase()
.includes(query)
){

card.style.display="block";

}else{

card.style.display="none";

}

});

}


/* Copy code */

function copyCode(button){

const code =
button
.parentElement
.querySelector("code")
.innerText;

navigator
.clipboard
.writeText(code)
.then(()=>{

const original =
button.innerText;

button.innerText="Copied!";

setTimeout(()=>{
    button.innerText=original;
},1200);

});

}


/* Mobile menu */

document
.querySelectorAll(".navlinks a")
.forEach(link=>{

link.addEventListener(
"click",
()=>{

document
.querySelector(".navlinks")
.classList.remove("open");

}
);

});

</script>

</body>
</html>
