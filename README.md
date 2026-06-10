<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
  <title>BHUPIN-AD · GitHub Profile README</title>
  <!-- Font Awesome 6 (free icons) -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=Fira+Code:wght@400;500&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: radial-gradient(circle at 10% 30%, #f0f4fa, #e4eaf1);
      font-family: 'Plus Jakarta Sans', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 2rem;
    }

    .readme-card {
      max-width: 1000px;
      width: 100%;
      background: #ffffff;
      border-radius: 2rem;
      box-shadow: 0 25px 45px -12px rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(0, 0, 0, 0.02);
      overflow: hidden;
    }

    .card-header {
      background: #0b1120;
      padding: 1.2rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 1rem;
      border-bottom: 1px solid #1e2a3a;
    }

    .repo-badge {
      display: inline-flex;
      align-items: center;
      gap: 0.6rem;
      background: #1a2538;
      color: #eef2ff;
      padding: 0.4rem 1.2rem;
      border-radius: 40px;
      font-size: 0.85rem;
      font-weight: 500;
      font-family: 'Fira Code', monospace;
    }

    .repo-badge i {
      font-size: 1rem;
      color: #60a5fa;
    }

    .profile-body {
      padding: 2rem 2rem 2rem 2rem;
    }

    .identity {
      display: flex;
      align-items: center;
      gap: 1.2rem;
      flex-wrap: wrap;
      margin-bottom: 1.5rem;
    }

    .avatar-placeholder {
      background: linear-gradient(145deg, #0f2b3d, #071a2b);
      width: 70px;
      height: 70px;
      border-radius: 30px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 2.5rem;
      font-weight: 700;
      color: white;
      box-shadow: 0 12px 18px -8px rgba(0,0,0,0.2);
      font-family: 'Fira Code', monospace;
    }

    .name-title h1 {
      font-size: 2rem;
      font-weight: 800;
      letter-spacing: -0.02em;
      background: linear-gradient(135deg, #0f2b3d, #1e4a76);
      background-clip: text;
      -webkit-background-clip: text;
      color: transparent;
    }

    .name-title .username {
      font-family: 'Fira Code', monospace;
      font-size: 0.85rem;
      color: #4b5563;
      background: #f1f5f9;
      display: inline-block;
      padding: 0.2rem 0.7rem;
      border-radius: 30px;
      margin-top: 6px;
    }

    .role-pills {
      display: flex;
      flex-wrap: wrap;
      gap: 0.7rem;
      margin: 1rem 0 1.2rem 0;
    }

    .pill {
      background: #eef2ff;
      padding: 0.4rem 1.2rem;
      border-radius: 40px;
      font-weight: 600;
      font-size: 0.85rem;
      color: #1e3a8a;
      display: inline-flex;
      align-items: center;
      gap: 8px;
    }

    .bio-block {
      background: #fafcff;
      border-radius: 1.5rem;
      padding: 1.2rem 1.5rem;
      margin: 0.8rem 0 1.8rem 0;
      border: 1px solid #e2edf7;
    }

    .bio-text {
      font-size: 0.98rem;
      line-height: 1.55;
      color: #1e2a41;
      display: flex;
      gap: 12px;
      align-items: flex-start;
    }

    .bio-text i {
      font-size: 1.4rem;
      color: #2c6e9e;
    }

    .contact-strip {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
      background: #ffffff;
      border: 1px solid #e9eef3;
      border-radius: 80px;
      padding: 0.6rem 1.2rem;
      margin: 1.5rem 0;
      box-shadow: 0 4px 8px -6px rgba(0,0,0,0.05);
    }

    .social-links {
      display: flex;
      flex-wrap: wrap;
      gap: 0.8rem;
    }

    .social-link {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      text-decoration: none;
      font-weight: 600;
      font-size: 0.85rem;
      color: #1f2937;
      background: #f8fafc;
      padding: 0.45rem 1rem;
      border-radius: 60px;
      transition: all 0.2s;
      border: 1px solid #e2e8f0;
    }

    .social-link i {
      font-size: 1rem;
    }

    .social-link:hover {
      background: #eef2ff;
      border-color: #cbdff2;
      transform: translateY(-2px);
      color: #0f172a;
    }

    .views-counter {
      background: #eef2ff;
      border-radius: 60px;
      padding: 0.45rem 1rem;
      font-size: 0.85rem;
      font-weight: 500;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      color: #1f3a6b;
    }

    .views-counter i {
      color: #2563eb;
    }

    .tech-wrapper {
      margin: 2rem 0 1.5rem;
    }

    .section-head {
      display: flex;
      align-items: center;
      gap: 12px;
      margin-bottom: 1.2rem;
      border-bottom: 2px solid #eef2ff;
      padding-bottom: 0.5rem;
    }

    .section-head h3 {
      font-size: 1.35rem;
      font-weight: 700;
      color: #0b2b3b;
    }

    .tech-bricks {
      background: #fefefe;
      border-radius: 1.6rem;
      border: 1px solid #eef2f8;
      padding: 1.4rem 1.2rem;
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .tech {
      background: #f1f5f9;
      border-radius: 60px;
      padding: 0.45rem 1.2rem;
      font-size: 0.85rem;
      font-weight: 500;
      font-family: 'Fira Code', monospace;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      transition: all 0.2s;
      color: #1f4662;
      border: 1px solid #e2edf2;
    }

    .tech i {
      font-size: 1rem;
      color: #2c6e9e;
    }

    .tech:hover {
      transform: translateY(-3px);
      background: #e9f0f5;
    }

    .feature-blocks {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      margin: 1.8rem 0 1rem;
    }

    .feature {
      background: #f8fafc;
      border-radius: 1.2rem;
      padding: 0.7rem 1.2rem;
      flex: 1 1 auto;
      display: flex;
      align-items: center;
      gap: 10px;
      border-left: 4px solid #3b82f6;
      font-weight: 500;
    }

    .footer-note {
      margin-top: 1.8rem;
      padding-top: 1rem;
      border-top: 1px dashed #dce5ec;
      display: flex;
      justify-content: space-between;
      font-size: 0.75rem;
      color: #4b6b8f;
      flex-wrap: wrap;
      gap: 0.5rem;
    }

    .edit-hint {
      background: #fef9e3;
      border: 1px solid #fde047;
      border-radius: 12px;
      padding: 0.6rem 1rem;
      margin-top: 1rem;
      font-size: 0.75rem;
      color: #854d0e;
      display: flex;
      align-items: center;
      gap: 10px;
      flex-wrap: wrap;
    }

    @media (max-width: 680px) {
      .profile-body {
        padding: 1.5rem;
      }
      .contact-strip {
        border-radius: 1.5rem;
        flex-direction: column;
        align-items: flex-start;
        gap: 12px;
      }
      .name-title h1 {
        font-size: 1.6rem;
      }
      .avatar-placeholder {
        width: 55px;
        height: 55px;
        font-size: 1.8rem;
      }
    }
  </style>
</head>
<body>
<div class="readme-card">
  <div class="card-header">
    <div class="repo-badge">
      <i class="fab fa-github-alt"></i>
      <span>BHUPIN-AD / README.md</span>
    </div>
    <div class="header-stats">
      <span><i class="far fa-star"></i> builder mindset</span>
    </div>
  </div>

  <div class="profile-body">
    <div class="identity">
      <div class="avatar-placeholder">
        <span>🅱️</span>
      </div>
      <div class="name-title">
        <h1>Bhupin Adhikari</h1>
        <div class="username">
          <i class="fas fa-at"></i> BHUPIN-AD
        </div>
      </div>
    </div>

    <div class="role-pills">
      <span class="pill"><i class="fas fa-laptop-code"></i> Frontend Architect</span>
      <span class="pill"><i class="fas fa-chain"></i> Web3 Builder</span>
      <span class="pill"><i class="fas fa-pencil-ruler"></i> UI/UX & Graphic Design</span>
      <span class="pill"><i class="fas fa-brain"></i> Problem Solver</span>
    </div>

    <div class="bio-block">
      <div class="bio-text">
        <i class="fas fa-quote-left"></i>
        <span>
          <strong>⚡ Creative technologist</strong> with a passion for decentralized tech and clean interfaces. 
          Currently pursuing <strong>BSc. CSIT</strong> — building digital experiences that merge design thinking 
          with blockchain utility. I love turning complex problems into elegant, user-friendly solutions.
        </span>
      </div>
    </div>

    <!-- ========================================== -->
    <!-- 🔽 REPLACE THE # LINKS WITH YOUR REAL URLs 🔽 -->
    <!-- ========================================== -->
    <div class="contact-strip">
      <div class="social-links">
        <a href="linkedin.com/in/bhupendra-adhikari-69a41a347" class="social-link" target="_blank"><i class="fab fa-linkedin-in"></i> LinkedIn</a>
        <a href="https://www.instagram.com/bhupinadhikari/" class="social-link" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
       
        <a href="adhikaribhupen18@gmail.com" class="social-link" target="_blank"><i class="fas fa-envelope"></i> Email</a>
      </div>
      <div class="views-counter">
        <i class="fas fa-chart-simple"></i>
        <span>PROFILE VISITS</span>
        <strong>2,147</strong>
      </div>
    </div>
    <!-- ========================================== -->
    <!-- 🔼 REPLACE THE # LINKS WITH YOUR REAL URLs 🔼 -->
    <!-- ========================================== -->

    <div class="tech-wrapper">
      <div class="section-head">
        <i class="fas fa-microchip" style="font-size: 1.5rem; color: #2c6e9e;"></i>
        <h3>Toolkit & languages</h3>
      </div>
      <div class="tech-bricks">
        <span class="tech"><i class="fas fa-code"></i> C</span>
        <span class="tech"><i class="fas fa-plus-circle"></i> C++</span>
        <span class="tech"><i class="fab fa-js"></i> JavaScript (ES6+)</span>
        <span class="tech"><i class="fab fa-typescript"></i> TypeScript</span>
        <span class="tech"><i class="fab fa-react"></i> React / Next.js</span>
        <span class="tech"><i class="fab fa-node-js"></i> Node.js</span>
        <span class="tech"><i class="fas fa-database"></i> Solidity</span>
        <span class="tech"><i class="fas fa-link"></i> Ethers / Web3.js</span>
        <span class="tech"><i class="fab fa-python"></i> Python</span>
        <span class="tech"><i class="fas fa-wind"></i> Tailwind CSS</span>
        <span class="tech"><i class="fab fa-figma"></i> Figma</span>
        <span class="tech"><i class="fas fa-code-branch"></i> Git & CI/CD</span>
      </div>
    </div>

    <div class="feature-blocks">
      <div class="feature">
        <i class="fas fa-cube" style="color:#2563eb;"></i> 
        <span>WEB3 · dApps · Smart Contract Dev</span>
      </div>
      <div class="feature">
        <i class="fas fa-palette" style="color:#8b5cf6;"></i> 
        <span>Graphic Design · Brand Identity</span>
      </div>
      <div class="feature">
        <i class="fas fa-lightbulb" style="color:#eab308;"></i> 
        <span>Competitive Coding · Hackathons</span>
      </div>
    </div>

    <div style="background: linear-gradient(115deg, #f0f7fe 0%, #ffffff 100%); border-radius: 1.2rem; padding: 1rem 1.3rem; margin-top: 1rem;">
      <div style="display: flex; gap: 10px; align-items: center;">
        <i class="fas fa-terminal" style="color:#2c6e9e;"></i>
        <span style="font-weight: 600;">🚀 Currently exploring:</span>
      </div>
      <div style="display: flex; flex-wrap: wrap; gap: 0.6rem; margin-top: 8px;">
        <span style="background:#eef2ff; border-radius: 20px; padding: 0.2rem 0.9rem; font-size: 0.75rem;"><i class="fab fa-ethereum"></i> Ethers v6</span>
        <span style="background:#eef2ff; border-radius: 20px; padding: 0.2rem 0.9rem; font-size: 0.75rem;"><i class="fas fa-database"></i> IPFS · Fleek</span>
        <span style="background:#eef2ff; border-radius: 20px; padding: 0.2rem 0.9rem; font-size: 0.75rem;"><i class="fas fa-mobile-alt"></i> Motion Design</span>
      </div>
    </div>

    <div class="footer-note">
      <span><i class="far fa-clock"></i> #OpenToCollaborate · Web3, Frontend & creative projects</span>
      <span><i class="fas fa-map-marker-alt"></i> Kathmandu, Nepal</span>
    </div>

    <!-- Helpful hint for you -->
    <div class="edit-hint">
      <i class="fas fa-pen-fancy"></i>
      <span><strong>📝 Replace the <code style="background:#fff3bf;">#</code> inside each social link with your actual profile URLs!</strong> (GitHub, LinkedIn, X, Instagram, Facebook, Email)</span>
    </div>

    <div style="text-align: center; margin-top: 1rem; font-size: 0.68rem; color: #6c86a3;">
      <i class="fas fa-code"></i> Designed exclusively for BHUPIN-AD — unique & original
    </div>
  </div>
</div>
</body>
</html>

[![GitHub Streak](https://streak-stats.demolab.com?user=BHUPIN-AD)](https://git.io/streak-stats)
