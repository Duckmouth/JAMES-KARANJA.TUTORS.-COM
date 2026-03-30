<!JIMMY BRAINIAC TUTORS>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
  <title>James Karanja | PhD Consortium – Elite Assignment & Academic Experts</title>
  <!-- Google Fonts + Icons + Chart.js for live dynamics -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,600;14..32,700;14..32,800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: #f6f9fc;
      color: #0a1c2f;
      scroll-behavior: smooth;
    }

    /* premium glass morphism & shadows */
    .glass-card {
      background: rgba(255, 255, 255, 0.96);
      backdrop-filter: blur(0px);
      border-radius: 2rem;
      box-shadow: 0 20px 35px -12px rgba(0, 0, 0, 0.08), 0 1px 2px rgba(0,0,0,0.02);
      transition: all 0.25s ease;
    }

    .container {
      max-width: 1400px;
      margin: 0 auto;
      padding: 0 2rem;
    }

    /* header / nav */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1.2rem 0;
      flex-wrap: wrap;
    }

    .logo h1 {
      font-size: 1.9rem;
      font-weight: 800;
      background: linear-gradient(135deg, #1E3C72, #2A5298);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      letter-spacing: -0.5px;
    }
    .logo span {
      font-size: 0.9rem;
      font-weight: 500;
      color: #2c5f8a;
      display: block;
    }

    .nav-links a {
      margin-left: 2rem;
      text-decoration: none;
      font-weight: 600;
      color: #1e3c72;
      transition: 0.2s;
    }
    .nav-links a:hover { color: #e67e22; }

    /* Hero section */
    .hero {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      align-items: center;
      justify-content: space-between;
      margin: 3rem 0 3rem;
    }
    .hero-text {
      flex: 1.2;
    }
    .hero-badge {
      background: #eef2ff;
      display: inline-block;
      padding: 0.3rem 1rem;
      border-radius: 40px;
      font-weight: 600;
      font-size: 0.8rem;
      color: #1e4a76;
    }
    .hero-text h2 {
      font-size: 3.2rem;
      font-weight: 800;
      line-height: 1.2;
      margin: 1rem 0 1rem;
      background: linear-gradient(to right, #0f2b3d, #2c5282);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
    }
    .guarantee-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      margin: 1.5rem 0;
    }
    .guarantee-item {
      background: white;
      border-radius: 60px;
      padding: 0.4rem 1.2rem;
      font-weight: 600;
      font-size: 0.9rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.03);
      border: 1px solid #e2edf7;
    }
    .guarantee-item i { margin-right: 8px; color: #e67e22;}

    .hero-stats {
      flex: 0.9;
      background: #ffffffdd;
      border-radius: 2rem;
      padding: 1.5rem;
      box-shadow: 0 25px 40px -15px rgba(0,0,0,0.1);
    }

    /* real-time orders panel */
    .live-panel {
      background: #0b2b3b;
      border-radius: 2rem;
      padding: 1.5rem;
      margin: 2rem 0 3rem;
      color: white;
      box-shadow: 0 20px 30px -12px rgba(0,0,0,0.2);
    }
    .live-header {
      display: flex;
      justify-content: space-between;
      align-items: baseline;
      flex-wrap: wrap;
      margin-bottom: 1rem;
    }
    .order-feed {
      background: #05212b;
      border-radius: 1.5rem;
      padding: 1rem;
      max-height: 280px;
      overflow-y: auto;
    }
    .order-item {
      display: flex;
      justify-content: space-between;
      border-bottom: 1px solid #2c5a6e;
      padding: 0.8rem 0.5rem;
      font-size: 0.9rem;
    }
    .order-topic {
      font-weight: 600;
    }
    .order-status {
      background: #27ae60;
      padding: 0.2rem 0.7rem;
      border-radius: 30px;
      font-size: 0.7rem;
      font-weight: bold;
    }

    /* specialization grid */
    .specialization-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
      gap: 1rem;
      margin: 2rem 0;
    }
    .spec-card {
      background: white;
      border-radius: 1.2rem;
      padding: 1rem;
      text-align: center;
      transition: all 0.2s;
      border: 1px solid #eef2ff;
      font-weight: 500;
    }
    .spec-card i { font-size: 1.8rem; margin-bottom: 0.5rem; display: block; color: #2c5282;}

    /* CTA Buttons */
    .btn-wa {
      background: #25D366;
      color: white;
      border: none;
      padding: 0.9rem 2rem;
      border-radius: 50px;
      font-weight: 700;
      font-size: 1rem;
      display: inline-flex;
      align-items: center;
      gap: 10px;
      transition: 0.2s;
      text-decoration: none;
    }
    .btn-wa:hover { background: #128C7E; transform: translateY(-2px);}
    .btn-outline {
      background: transparent;
      border: 2px solid #1e3c72;
      padding: 0.8rem 1.8rem;
      border-radius: 50px;
      font-weight: 700;
      text-decoration: none;
      color: #1e3c72;
      margin-left: 1rem;
    }

    footer {
      background: #0a1927;
      color: #cdedf6;
      padding: 3rem 0;
      margin-top: 4rem;
      border-radius: 2rem 2rem 0 0;
    }
    @media (max-width: 800px) {
      .container { padding: 0 1.2rem; }
      .hero-text h2 { font-size: 2.2rem; }
      .nav-links a { margin-left: 1rem; }
    }
  </style>
</head>
<body>

<div class="container">
  <!-- Navigation -->
  <nav class="navbar">
    <div class="logo">
      <h1>James Karanja <span style="font-size:0.85rem;">✦ PhD Consortium</span></h1>
      <span>Elite Assignment Help | Qualified Experts Worldwide</span>
    </div>
    <div class="nav-links">
      <a href="#">Home</a>
      <a href="#specialties">Expertise</a>
      <a href="#liveOrders">Live Orders</a>
      <a href="#contact">Connect</a>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="hero">
    <div class="hero-text">
      <div class="hero-badge"><i class="fas fa-graduation-cap"></i> 200+ PhD & Masters Specialists</div>
      <h2>Transforming <br> Academic Excellence</h2>
      <p style="font-size: 1.1rem; color:#2c3e50; max-width: 550px;">A syndicate of qualified experts delivering bespoke solutions — from thesis defense to real-time coding. Your success, engineered with precision.</p>
      <div class="guarantee-grid">
        <div class="guarantee-item"><i class="fas fa-star"></i> Excellent Grades</div>
        <div class="guarantee-item"><i class="fas fa-clock"></i> Timely Delivery</div>
        <div class="guarantee-item"><i class="fas fa-coins"></i> Affordable</div>
        <div class="guarantee-item"><i class="fas fa-file-alt"></i> 0% Plagiarism</div>
        <div class="guarantee-item"><i class="fas fa-headset"></i> 24/7 Availability</div>
      </div>
      <div style="margin: 2rem 0 0;">
        <a href="https://wa.me/qr/4PKBWS2XMM4VF1" target="_blank" class="btn-wa"><i class="fab fa-whatsapp"></i> WhatsApp Direct</a>
        <a href="https://chat.whatsapp.com/K4pGzREL0Io5XN9v5McvbQ" target="_blank" class="btn-outline"><i class="fab fa-whatsapp"></i> Join Group</a>
      </div>
    </div>
    <div class="hero-stats">
      <h3 style="font-weight:800;"><i class="fas fa-chart-line"></i> Live Metrics</h3>
      <div style="margin: 1rem 0;">
        <p><strong>📊 Active experts:</strong> 47 online</p>
        <p><strong>✅ Orders completed (2025):</strong> 1,284+</p>
        <p><strong>⭐ Satisfaction rate:</strong> 98.7%</p>
      </div>
      <canvas id="completionChart" style="max-height: 140px; width:100%"></canvas>
    </div>
  </div>

  <!-- REAL-TIME ORDERS SECTION (LIVE SIMULATION) -->
  <div id="liveOrders" class="live-panel">
    <div class="live-header">
      <div><i class="fas fa-broadcast-tower" style="font-size:1.6rem;"></i> <strong style="font-size:1.4rem;">📡 REAL-TIME ORDER STREAM</strong> <span style="font-size:0.8rem; background:#00000055; padding:3px 8px; border-radius:30px;">LIVE FEED</span></div>
      <div><i class="fas fa-sync-alt"></i> Auto-updates every 8 sec</div>
    </div>
    <div id="orderFeedContainer" class="order-feed">
      <!-- dynamic orders injected -->
      <div class="order-item"><span class="order-topic">📚 PhD Dissertation (Literature Review)</span><span><span class="order-status">in progress</span> <i class="fas fa-user-graduate"></i> Dr. Ananya</span></div>
      <div class="order-item"><span class="order-topic">🐍 Python & Machine Learning Project</span><span><span class="order-status">just assigned</span> <i class="fas fa-code"></i> Expert R. </span></div>
    </div>
    <div style="margin-top: 1rem; display: flex; justify-content: space-between; font-size:0.8rem;">
      <span>🔥 Last order: <span id="lastOrderTime">just now</span></span>
      <span><i class="fas fa-charging-station"></i> 16 orders in last hour</span>
    </div>
  </div>

  <!-- SPECIALIZATION MEGA SECTION -->
  <div id="specialties">
    <h2 style="font-size:2rem; font-weight:800; margin: 2rem 0 1rem;">⚡ OUR SPECIALIZATION <span style="font-size:1rem; font-weight:400;">(PhD-led expertise)</span></h2>
    <div class="specialization-grid">
      <div class="spec-card"><i class="fas fa-laptop-code"></i> Online exams</div>
      <div class="spec-card"><i class="fas fa-book-open"></i> Coursework</div>
      <div class="spec-card"><i class="fas fa-pen-fancy"></i> Essays</div>
      <div class="spec-card"><i class="fas fa-scroll"></i> Thesis/Dissertation</div>
      <div class="spec-card"><i class="fas fa-comments"></i> Discussions</div>
      <div class="spec-card"><i class="fas fa-chart-bar"></i> Research summary</div>
      <div class="spec-card"><i class="fas fa-project-diagram"></i> Projects</div>
      <div class="spec-card"><i class="fas fa-chart-pie"></i> Data analysis</div>
      <div class="spec-card"><i class="fas fa-calculator"></i> Accounting/Finance</div>
      <div class="spec-card"><i class="fas fa-chart-line"></i> Economics</div>
      <div class="spec-card"><i class="fas fa-users"></i> Management</div>
      <div class="spec-card"><i class="fas fa-brain"></i> Psychology</div>
      <div class="spec-card"><i class="fas fa-dna"></i> Biology, Chemistry</div>
      <div class="spec-card"><i class="fab fa-python"></i> R, Java, Python, C++</div>
      <div class="spec-card"><i class="fas fa-chart-simple"></i> SPSS, Matlab, Stata</div>
      <div class="spec-card"><i class="fas fa-microchip"></i> Computer Science</div>
      <div class="spec-card"><i class="fas fa-cogs"></i> Engineering</div>
      <div class="spec-card"><i class="fas fa-chart-scatter"></i> Statistics</div>
      <div class="spec-card"><i class="fas fa-tasks"></i> AND ALL OTHER ASSIGNMENTS ✍️</div>
    </div>
  </div>

  <!-- why choose us + expert profiles -->
  <div style="background: linear-gradient(115deg, #F1F8FF 0%, #FFFFFF 100%); border-radius: 2rem; padding: 2rem; margin: 2rem 0;">
    <div style="display: flex; flex-wrap: wrap; gap: 2rem; align-items: center;">
      <div style="flex:1.2">
        <h3 style="font-size:1.8rem; font-weight:800;"><i class="fas fa-user-tie"></i> Meet The Faculty-Level Experts</h3>
        <p style="margin:1rem 0">Our consortium includes former university lecturers, data scientists, published researchers, and certified coders. Every assignment is matched with a domain specialist holding a minimum of a Master’s degree (70% PhD). <strong>James Karanja</strong> leads the quality assurance unit ensuring zero plagiarism and methodological rigor.</p>
        <ul style="list-style: none;">
          <li><i class="fas fa-check-circle" style="color:#2ecc71;"></i> 1-on-1 mentorship style delivery</li>
          <li><i class="fas fa-check-circle" style="color:#2ecc71;"></i> Turnitin & AI reports included</li>
          <li><i class="fas fa-check-circle" style="color:#2ecc71;"></i> 24/7 live support via WhatsApp & email</li>
        </ul>
      </div>
      <div style="flex:0.9; background: white; border-radius: 1.5rem; padding: 1.5rem; box-shadow: 0 12px 20px rgba(0,0,0,0.05);">
        <i class="fas fa-quote-left" style="font-size:2rem; color:#1e3c72;"></i>
        <p style="font-style:italic; margin:1rem 0">"James Karanja’s team delivered my entire thesis analysis in SPSS with detailed interpretation within 36 hours. Flawless formatting and statistical accuracy — truly PhD grade!"</p>
        <div><strong>- Sarah M., PhD Candidate (Public Health)</strong></div>
      </div>
    </div>
  </div>

  <!-- contact section with dual whatsapp -->
  <div id="contact" style="background: #0c2a36; border-radius: 2rem; padding: 2rem; color: white; margin: 2rem 0;">
    <div style="text-align: center;">
      <h2 style="font-size:2rem;">📞 Start Your Academic Triumph</h2>
      <p style="margin: 1rem 0;">Connect directly with the assignment help group. Instant response, expert matching within minutes.</p>
      <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 1.2rem; margin-top: 1.5rem;">
        <a href="https://wa.me/qr/4PKBWS2XMM4VF1" target="_blank" class="btn-wa" style="background:#075e54;"><i class="fab fa-whatsapp"></i> James Karanja Direct Line</a>
        <a href="https://chat.whatsapp.com/K4pGzREL0Io5XN9v5McvbQ" target="_blank" class="btn-wa" style="background:#25D366;"><i class="fab fa-whatsapp"></i> Join Official WhatsApp Group</a>
      </div>
      <p style="margin-top: 2rem; font-size:0.8rem;"><i class="fas fa-shield-alt"></i> 100% confidential | Secure payment | Money-back guarantee for quality assurance</p>
    </div>
  </div>
</div>

<footer>
  <div class="container">
    <div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 2rem;">
      <div><strong>James Karanja Assignment Help</strong><br>PhD & Masters Specialists Consortium<br>📍 Global Remote Delivery | 24/7</div>
      <div><i class="fab fa-whatsapp"></i> +254 700 000 000 (demo)<br><i class="fas fa-envelope"></i> help@jameskaranja-phd.com<br><i class="fas fa-clock"></i> Live support: always online</div>
      <div>© 2025 — Highest Academic Integrity <br> ✦ We guarantee excellence, every time ✦</div>
    </div>
    <hr style="margin: 2rem 0 1rem; border-color:#2c5a6e;">
    <p style="text-align: center; font-size:0.75rem;">"A group of qualified experts specialized in various fields" — Your success is our legacy.</p>
  </div>
</footer>

<script>
  // Real-time order simulation: dynamic feed with rich topics (PhD-level assignments)
  const orderTopics = [
    "📖 Critical Discourse Analysis (Linguistics PhD)", "🧠 fMRI Data Analysis using MATLAB", "📊 Econometrics Panel Data (Stata)", "⚙️ Finite Element Analysis - Mechanical Eng", "🧬 CRISPR Gene Editing Essay", "💻 Advanced Algorithms & Data Structures (C++)", "📈 Portfolio Optimization & R coding", "📝 Dissertation: Leadership & Organizational Behavior", "🎓 MBA Capstone Project", "🧪 Organic Chemistry Lab Report", "📚 Comparative Literature Thesis", "🐍 Deep Learning with PyTorch", "📉 Time Series Forecasting (SPSS)", "🏛️ Philosophy of Mind Essay", "💡 Renewable Energy Systems Project", "📑 Grant Proposal Writing", "🔢 Real Analysis Proofs (Mathematics)", "🖥️ Operating Systems Kernel Assignment", "🌍 Climate Change Policy Analysis", "🎨 UX Research & Usability Report"
  ];
  
  const statuses = ["⚡ in progress", "✅ completed", "🔄 being reviewed", "🎯 assigned to expert", "📊 quality check"];
  const experts = ["Dr. Kamau", "Prof. Njeri", "Dr. Omondi", "Dr. Esther", "PhD. Chen", "Prof. L. Muthoni", "Dr. R. Gupta", "Dr. F. Hassan"];

  function getRandomElement(arr) {
    return arr[Math.floor(Math.random() * arr.length)];
  }

  function getRandomTime() {
    const now = new Date();
    return now.toLocaleTimeString([], { hour: '2-digit', minute:'2-digit', second:'2-digit' });
  }

  function generateOrder() {
    const topic = getRandomElement(orderTopics);
    const status = getRandomElement(statuses);
    const expert = getRandomElement(experts);
    return { topic, status, expert, time: getRandomTime() };
  }

  // maintain order list (max 10 recent)
  let recentOrders = [
    { topic: "📊 Structural Equation Modeling (AMOS)", status: "⚡ in progress", expert: "Dr. Kamau", time: "11:23:45" },
    { topic: "🐍 Python for Computational Finance", status: "✅ completed", expert: "Dr. Omondi", time: "11:21:12" },
    { topic: "📝 Thesis: Postcolonial Theory", status: "🎯 assigned to expert", expert: "Prof. Njeri", time: "11:18:30" },
    { topic: "⚛️ Quantum Mechanics Problem Set", status: "🔄 being reviewed", expert: "Dr. F. Hassan", time: "11:15:22" }
  ];

  const orderContainer = document.getElementById("orderFeedContainer");
  const lastOrderSpan = document.getElementById("lastOrderTime");

  function renderOrderFeed() {
    if (!orderContainer) return;
    orderContainer.innerHTML = '';
    // show most recent first (reverse order or keep as is)
    [...recentOrders].reverse().forEach(order => {
      const div = document.createElement('div');
      div.className = 'order-item';
      div.innerHTML = `<span class="order-topic">${order.topic}</span>
                       <span><span class="order-status">${order.status}</span> <i class="fas fa-chalkboard-user"></i> ${order.expert} <small style="font-size:0.7rem;">${order.time}</small></span>`;
      orderContainer.appendChild(div);
    });
    if(recentOrders.length > 0) lastOrderSpan.innerText = recentOrders[0].time;
  }

  function addNewOrder() {
    const newOrd = generateOrder();
    recentOrders.unshift(newOrd);
    if (recentOrders.length > 10) recentOrders.pop();
    renderOrderFeed();
    // subtle highlight animation could be added but keep smooth
  }

  // Real-time simulation: every 8 seconds new order arrives (live feel)
  let interval = setInterval(() => {
    addNewOrder();
  }, 8000);

  // initial render
  renderOrderFeed();

  // Chart.js for "completion trends" (mini stats)
  const ctx = document.getElementById('completionChart')?.getContext('2d');
  if(ctx) {
    new Chart(ctx, {
      type: 'line',
      data: {
        labels: ['Week 1', 'Week 2', 'Week 3', 'Week 4', 'This Week'],
        datasets: [{
          label: 'Orders Completed',
          data: [42, 58, 71, 89, 47],
          borderColor: '#e67e22',
          backgroundColor: 'rgba(230,126,34,0.05)',
          tension: 0.3,
          fill: true,
          pointBackgroundColor: '#1e3c72',
          pointBorderColor: '#fff',
          borderWidth: 3
        }]
      },
      options: {
        responsive: true,
        maintainAspectRatio: true,
        plugins: { legend: { position: 'top', labels: { font: { size: 10 } } } }
      }
    });
  }

  // additional "real-time" counter to display active orders per minute simulation
  const activeOrderCounter = document.createElement('div');
  // we also add a subtle floating badge to show "new order arrived" but it's already dynamic

  // For extra 'live' context: add a moving indicator that updates the number of active orders in live-panel
  const liveMetricSpan = document.createElement('span');
  liveMetricSpan.style.marginLeft = '12px';
  liveMetricSpan.style.background = '#ffb347';
  liveMetricSpan.style.padding = '2px 12px';
  liveMetricSpan.style.borderRadius = '40px';
  liveMetricSpan.style.fontSize = '0.75rem';
  liveMetricSpan.style.fontWeight = 'bold';
  const headerLive = document.querySelector('.live-header div:first-child');
  if(headerLive) {
    liveMetricSpan.innerHTML = '<i class="fas fa-waveform"></i> ACTIVE STREAM';
    headerLive.appendChild(liveMetricSpan);
  }

  // additionally we can simulate a "currently being processed" counter
  let currentActive = 12;
  const activeSpan = document.createElement('span');
  activeSpan.style.marginLeft = '1rem';
  activeSpan.style.fontSize = '0.8rem';
  const orderFeedHeader = document.querySelector('.live-panel .live-header');
  if(orderFeedHeader) {
    const activeBadge = document.createElement('div');
    activeBadge.innerHTML = `🔥 <span id="activeExpertTasks">${currentActive}</span> assignments in progress`;
    activeBadge.style.fontSize = '0.85rem';
    activeBadge.style.background = '#00000033';
    activeBadge.style.padding = '0.2rem 0.8rem';
    activeBadge.style.borderRadius = '2rem';
    orderFeedHeader.appendChild(activeBadge);
    setInterval(() => {
      // vary active count between 9-23 to simulate real workload
      currentActive = Math.floor(Math.random() * (23 - 9 + 1) + 9);
      const activeSpanEl = document.getElementById('activeExpertTasks');
      if(activeSpanEl) activeSpanEl.innerText = currentActive;
    }, 13000);
  }

  // guarantee alert of "live help" - but no intrusive alerts, just elevate user trust
  console.log("James Karanja PhD consortium — elite assignment help with realtime orders");

  // optional: ensure that when clicking on group links it's seamless
  // Also add mouse parallax-like? No need but elegant

  // For ultra-rich context: manual simulation of order count in last hour
  let lastHourCount = 16;
  const hourSpan = document.querySelector('.live-panel div:last-child span:first-child');
  if(hourSpan) {
    setInterval(() => {
      lastHourCount += Math.floor(Math.random() * 3);
      const hourElem = document.querySelector('.live-panel div:last-child span:first-child');
      if(hourElem) hourElem.innerHTML = `<i class="fas fa-charging-station"></i> ${lastHourCount} orders in last hour`;
    }, 45000);
  }

  // on page unload clear interval (optional)
  window.addEventListener('beforeunload', () => {
    if(interval) clearInterval(interval);
  });
</script>
</body>
</html>
