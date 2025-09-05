# Portofolio-HALMAHERA
Repository untuk portofolio aplikasi mobile. Dapat diakses publik.
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Master — Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg: #0b0e13;
      --text: #f5f7fb;
      --muted: #cfd6e4;
      --accent: #00c7ff;
      --accent-2: #2dd4bf;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:"Poppins", system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial;
      color:var(--text);
      background:var(--bg);
      overflow-x:hidden;
    }
    section{padding:80px 20px; max-width:1100px; margin:auto}
    h2{font-size:32px; margin-bottom:20px; text-align:center}
    p{line-height:1.6; color:var(--muted)}

    /* NAVBAR */
    header{
      position:fixed; inset-inline:0; top:0;
      z-index:50;
      background:linear-gradient(to bottom, rgba(0,0,0,.75), rgba(0,0,0,0));
      backdrop-filter:saturate(140%) blur(2px);
    }
    .nav{
      max-width:1100px; margin:auto; padding:18px 22px;
      display:flex; align-items:center; justify-content:space-between;
    }
    .brand{font-weight:800; letter-spacing:.08em; font-size:22px}
    .nav ul{list-style:none; margin:0; padding:0; display:flex; gap:26px; align-items:center}
    .nav a{
      text-decoration:none; color:var(--muted); font-weight:600; font-size:14px; letter-spacing:.08em;
    }
    .nav a:hover{color:var(--text)}
    .nav .active{position:relative; color:var(--text)}
    .nav .active::after{
      content:""; position:absolute; left:0; right:0; bottom:-8px; height:2px; background:var(--text);
    }

        
}

; position:absolute; inset:0; z-index:-1;
      background:radial-gradient(70% 60% at 50% 40%, rgba(0,0,0,0) 0%, rgba(0,0,0,.25) 50%, rgba(0,0,0,.6) 100%);
    }
.avatar-wrap{width:170px; height:170px; border-radius:50%; padding:8px; background:rgba(255,255,255,.2); backdrop-filter:blur(2px); margin-inline:auto; box-shadow:0 8px 30px rgba(0,0,0,.45)}
    .avatar{width:100%; height:100%; border-radius:50%; object-fit:cover; display:block; border:6px solid rgba(255,255,255,.92)}
    h1{font-size:56px; line-height:1.05; margin:24px 0 6px; font-weight:800}
    .name-accent{color:var(--accent)}
    .subtitle{font-size:20px; color:var(--muted); font-weight:500; min-height:1.6em}
    .typing{border-right:2px solid rgba(255,255,255,.75); white-space:nowrap; overflow:hidden}
    .mouse{
      width:26px; height:42px; border:2px solid rgba(255,255,255,.9); border-radius:14px; margin:42px auto 0; position:relative; opacity:.9;
      animation:float 2.8s ease-in-out infinite;
    }
    .mouse::after{
      content:""; position:absolute; left:50%; transform:translateX(-50%); top:8px; width:4px; height:8px; border-radius:2px; background:rgba(255,255,255,.9);
      animation:wheel 1.4s ease-in-out infinite;
    }
    @keyframes wheel{0%{opacity:1; transform:translate(-50%,0)} 100%{opacity:0; transform:translate(-50%,12px)}}
    @keyframes float{0%,100%{transform:translateY(0)} 50%{transform:translateY(6px)}}

    /* CONTENT SECTIONS */
    .skills-list, .services-list{
      display:grid; grid-template-columns:repeat(auto-fit,minmax(200px,1fr)); gap:20px; margin-top:30px;
    }
    .card{
      background:#11161d; padding:20px; border-radius:12px; text-align:center; box-shadow:0 6px 18px rgba(0,0,0,.4);
    }
    .card h3{margin:10px 0 6px; color:var(--accent)}
    .projects{display:grid; grid-template-columns:repeat(auto-fit,minmax(260px,1fr)); gap:20px; margin-top:30px}
    .projects img{width:100%; border-radius:10px; height:160px; object-fit:cover}

    .contact{display:grid; gap:10px; text-align:center}
    .contact a{color:var(--accent); text-decoration:none; font-weight:600}
    .contact a:hover{text-decoration:underline}

    /* Responsive */
    @media (max-width:720px){
      h1{font-size:38px}
      .avatar-wrap{width:200px; height:200px}
      .subtitle{font-size:18px}
      .nav ul{gap:16px}
      .brand{font-size:18px}
      .nav a{font-size:12px}
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <nav class="nav" aria-label="Primary">
      <div class="brand">M@ster_AL</div>
      <ul>
        <li><a class="active" href="#home">HOME</a></li>
        <li><a href="#about">ABOUT</a></li>
        <li><a href="#services">SERVICES</a></li>
        <li><a href="#works">WORKS</a></li>
        <li><a href="#skills">SKILLS</a></li>
        <li><a href="#contact">CONTACT</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero -->
  <section id="home" class="hero" role="banner">
    <div>
      <div class="avatar-wrap">
        <img class="avatar</a>
        
         profil "https://imgbb.com/<a href=<a href="https://ibb.co.com/SXY2B8ts"><img src<a href="https://ibb.co.com/7tMdpT6s"><img src="https://i.ibb.co.com/7tMdpT6s/IMG-20250905-161605.png" alt="IMG-20250905-161605" border="0"></a></a>
      </div>
      <h1><span>Halma<span class="name-accent">hera</span></h1>
      <p class="subtitle"><span id="typed" class="typing">I'm a Ai Machine specialist & Engineering</span></p>
      <div class="mouse" aria-hidden="true"></div>
    </div>
  </section>

  <!-- About -->
  <section id="about">
    <h2>About Me</h2>
    <p>Saya adalah seorang <strong>Software Engineer</strong> dan <strong>AI Enthusiast</strong> dengan fokus Visi saya adalah membangun produk yang berdampak nyata dan membantu banyak orang melalui teknologi. Misi saya menciptakan aplikasi modern, responsif, dan user-friendly untuk membantu perusahaan dan individu beradaptasi di era digital.</p>
  </section>

  <!-- Services -->
  <section id="services">
    <h2>Services</h2>
    <div class="services-list">
      <div class="card"><h3>Web Development</h3><p>Membangun website modern, responsif, dan cepat.</p></div>
      <div class="card"><h3>AI Solutions</h3><p>Menerapkan Machine Learning & AI untuk bisnis dan riset.</p></div>
      <div class="card"><h3>Mobile Apps</h3><p>Aplikasi Android/iOS dengan tampilan elegan & fungsional.</p></div>
      <div class="card"><h3>Automation</h3><p>Mengotomatisasi workflow dan sistem agar lebih efisien.</p></div>
    </div>
  </section>

  <!-- Works / Projects -->
  <section id="works">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card"><img src="https://picsum.photos/id/1015/400/200" alt="Project 1"><h3>AI Chatbot</h3><p>Chatbot cerdas untuk customer service otomatis.</p></div>
      <div class="card"><img src="https://picsum.photos/id/1024/400/200" alt="Project 2"><h3>E-commerce</h3><p>Platform belanja online dengan payment gateway.</p></div>
      <div class="card"><img src="https://picsum.photos/id/1041/400/200" alt="Project 3"><h3>Task Manager</h3><p>Aplikasi manajemen tugas berbasis web.</p></div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skills-list">
      <div class="card"><h3>Python</h3><p>Machine Learning, Automation, Data Science</p></div>
      <div class="card"><h3>JavaScript</h3><p>Frontend & Backend Development</p></div>
      <div class="card"><h3>HTML/CSS</h3><p>UI/UX Design, Responsive Layout</p></div>
      <div class="card"><h3>Databases</h3><p>MySQL, MongoDB, PostgreSQL</p></div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact</h2>
    <div class="contact">
      <p>Email: <a href="mailto:halmahera@example.com">halmahera@example.com</a></p>
      <p>WhatsApp: <a href="https://wa.me/6281234567890" target="_blank">+62 812-3456-7890</a></p>
      <p>LinkedIn: <a href="https://linkedin.com/in/halmahera" target="_blank">linkedin.com/in/halmahera</a></p>
      <p>GitHub: <a href="https://github.com/halmahera" target="_blank">github.com/halmahera</a></p>
    </div>
  </section>

  <script>
    // Typing Effect
    const roles = ["I'm Software Engineering", "AI & Machine Learning Enthusiast", "Fullstack Web Developer"];
    const el = document.getElementById('typed');
    let r = 0, i = 0, typing = true;
    function tick(){
      const text = roles[r];
      if(typing){
        i++;
        el.textContent = text.slice(0, i);
        if(i === text.length){
          typing = false;
          setTimeout(tick, 1200);
          return;
        }
      }else{
        i--;
        el.textContent = text.slice(0, i);
        if(i === 0){
          typing = true;
          r = (r + 1) % roles.length;
        }
      }
      setTimeout(tick, typing ? 38 : 24);
    }
    tick();
  </script>
</body>
</html>







    © Desain & build by Halmahera 
