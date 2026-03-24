<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pixelwise Login</title>
  <style>
    :root{
      --bg:#ffffff;
      --text:#000000;
      --muted:#666666;
      --border:#dddddd;
      --soft:#f7f7f7;
      --pill:#f4f4f4;
      --danger:#b42318;
    }

    *{box-sizing:border-box}

    html,body{
      margin:0;
      padding:0;
      background:var(--bg);
      color:var(--text);
      font-family:Inter, system-ui, Arial, sans-serif;
    }

    a{
      color:inherit;
      text-decoration:none;
    }

    button,input{
      font:inherit;
    }

    body{
      min-height:100vh;
    }

    header{
      position:fixed;
      top:0;
      left:0;
      right:0;
      z-index:10;
      background:#ffffff;
      border-bottom:1px solid transparent;
      transition:border-color .25s ease, background .25s ease;
    }

    header.scrolled{
      border-bottom:1px solid #eee;
    }

    .header-inner{
      width:100%;
      max-width:none;
      margin:0 auto;
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:14px 32px;
      gap:18px;
    }

    .header-left{
      display:flex;
      align-items:center;
      gap:10px;
      flex:0 0 auto;
    }

    .brand-lockup{
      display:flex;
      align-items:center;
      gap:10px;
      text-decoration:none;
      color:#000;
      font-weight:700;
      letter-spacing:-0.02em;
    }

    .brand-text{
      font-size:20px;
      line-height:1;
    }

    .header-right{
      display:flex;
      align-items:center;
      gap:12px;
      margin-left:auto;
    }

    .header-link{
      display:inline-flex;
      align-items:center;
      justify-content:center;
      padding:10px 16px;
      border:1px solid var(--border);
      border-radius:999px;
      background:#fff;
      color:#000;
      text-decoration:none;
      font-family:inherit;
      font-size:13px;
      font-weight:600;
      white-space:nowrap;
      transition:background .2s ease, border-color .2s ease, transform .2s ease;
    }

    .header-link:hover{
      background:#f7f7f7;
      transform:translateY(-1px);
    }

    .menu-btn{
      font-size:22px;
      border:none;
      background:none;
      cursor:pointer;
      color:#000;
      padding:0;
      line-height:1;
    }

    .drawer{
      position:fixed;
      top:0;
      right:0;
      height:100%;
      width:280px;
      background:#ffffff;
      border-left:1px solid var(--border);
      transform:translateX(100%);
      transition:transform .25s ease;
      z-index:1000;
      padding:24px;
      display:flex;
      flex-direction:column;
    }

    .drawer.open{
      transform:translateX(0);
    }

    .drawer-close{
      position:absolute;
      top:18px;
      right:18px;
      font-size:22px;
      border:none;
      background:none;
      cursor:pointer;
    }

    .drawer a{
      display:block;
      padding:14px 0;
      text-decoration:none;
      color:#000;
      font-size:18px;
      border-bottom:1px solid #f1f1f1;
    }

    .drawer a:last-child{
      border-bottom:none;
    }

    .drawer-top a{
      font-size:18px;
    }

    .drawer-section-label{
      font-size:12px;
      letter-spacing:.08em;
      text-transform:uppercase;
      color:#888;
      margin:18px 0 8px;
    }

    .drawer-submenu{
      display:block;
      padding:8px 0 4px 14px;
      border-bottom:1px solid #f1f1f1;
    }

    .drawer-submenu a{
      font-size:16px;
      padding:10px 0;
      border-bottom:none;
      color:#555;
    }

    .drawer-bottom{
      margin-top:auto;
      padding-top:20px;
    }

    .drawer-join{
      display:block;
      text-align:center;
      padding:14px 18px;
      background:#2563eb;
      color:#ffffff !important;
      border-radius:10px;
      border-bottom:none;
      font-size:18px;
      font-weight:600;
      margin-bottom:14px;
    }

    .drawer-login{
      display:block;
      text-align:center;
      padding:12px 0;
      color:#000;
      text-decoration:none;
      font-size:16px;
      border-bottom:none;
    }

    .overlay{
      position:fixed;
      top:0;
      left:0;
      width:100%;
      height:100%;
      background:rgba(0,0,0,.25);
      opacity:0;
      pointer-events:none;
      transition:opacity .2s ease;
      z-index:900;
    }

    .overlay.open{
      opacity:1;
      pointer-events:auto;
    }

    .header-logo,
    .drawer-logo{
      width:22px;
      height:22px;
      display:block;
      flex:0 0 auto;
    }

    main{
      min-height:100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:130px 20px 60px;
    }

    .login-wrap{
      width:100%;
      max-width:1080px;
      display:grid;
      grid-template-columns:1.05fr .95fr;
      gap:28px;
      align-items:stretch;
    }

    .login-copy{
      display:flex;
      flex-direction:column;
      justify-content:center;
      padding-right:12px;
    }

    .eyebrow{
      display:inline-flex;
      align-items:center;
      padding:8px 12px;
      border:1px solid var(--border);
      border-radius:999px;
      background:#fff;
      color:#555;
      font-size:12px;
      font-weight:600;
      margin-bottom:18px;
      width:max-content;
    }

    h1{
      font-size:64px;
      font-weight:600;
      letter-spacing:-0.05em;
      line-height:0.95;
      margin:0 0 20px;
      max-width:620px;
    }

    .login-subtext{
      font-size:20px;
      color:var(--muted);
      line-height:1.45;
      max-width:620px;
      margin-bottom:24px;
    }

    .login-helper{
      font-size:14px;
      color:#7a7a7a;
      max-width:620px;
      line-height:1.6;
    }

    .benefit-list{
      list-style:none;
      padding:0;
      margin:28px 0 0;
      display:grid;
      gap:12px;
      max-width:560px;
    }

    .benefit-list li{
      border:1px solid var(--border);
      border-radius:14px;
      padding:14px 16px;
      background:#fff;
      font-size:14px;
      color:#444;
      line-height:1.5;
    }

    .login-card{
      border:1px solid var(--border);
      border-radius:24px;
      background:#fff;
      overflow:hidden;
    }

    .card-topbar{
      height:14px;
      background:#000;
    }

    .card-body{
      padding:30px 28px 28px;
    }

    .card-label{
      display:inline-flex;
      align-items:center;
      padding:8px 12px;
      border-radius:999px;
      border:1px solid var(--border);
      background:var(--pill);
      color:#666;
      font-size:13px;
      font-weight:600;
      margin-bottom:18px;
    }

    .card-title{
      font-size:34px;
      line-height:1;
      letter-spacing:-0.04em;
      margin:0 0 10px;
      font-weight:600;
    }

    .card-copy{
      font-size:15px;
      color:#666;
      line-height:1.5;
      margin:0 0 24px;
    }

    .field{
      margin-bottom:14px;
    }

    .field label{
      display:block;
      font-size:13px;
      font-weight:600;
      margin-bottom:8px;
      color:#444;
    }

    .field input{
      width:100%;
      height:56px;
      border:1px solid var(--border);
      border-radius:14px;
      padding:0 16px;
      background:#fff;
      color:#000;
      outline:none;
      font-size:15px;
    }

    .field input:focus{
      border-color:#bdbdbd;
    }

    .field input::placeholder{
      color:#999;
    }

    .card-actions{
      display:flex;
      gap:10px;
      margin-top:8px;
      flex-wrap:wrap;
    }

    .btn{
      appearance:none;
      border:none;
      cursor:pointer;
      font-family:inherit;
      font-weight:600;
      font-size:15px;
      height:56px;
      border-radius:14px;
      padding:0 18px;
      transition:transform .2s ease, background .2s ease, border-color .2s ease;
    }

    .btn:hover{
      transform:translateY(-1px);
    }

    .btn-primary{
      background:#000;
      color:#fff;
      flex:1 1 220px;
    }

    .btn-primary:hover{
      background:#111;
    }

    .btn-secondary{
      background:#fff;
      color:#000;
      border:1px solid var(--border);
      flex:1 1 180px;
    }

    .btn-secondary:hover{
      background:#f7f7f7;
    }

    .status{
      min-height:24px;
      margin-top:14px;
      font-size:14px;
      line-height:1.5;
      color:#555;
    }

    .status.error{
      color:var(--danger);
    }

    .status.success{
      color:#166534;
    }

    .microcopy{
      margin-top:18px;
      font-size:13px;
      color:#7a7a7a;
      line-height:1.55;
    }

    .login-footer-link{
      margin-top:18px;
      font-size:14px;
      color:#666;
    }

    .login-footer-link a{
      text-decoration:underline;
    }

    @media (max-width: 1020px){
      .login-wrap{
        grid-template-columns:1fr;
      }

      .login-copy{
        padding-right:0;
      }

      h1{
        font-size:52px;
      }
    }

    @media (max-width: 700px){
      .header-inner{
        padding:12px 12px;
        gap:8px;
      }

      .brand-text{
        font-size:18px;
      }

      .header-right{
        gap:6px;
      }

      .header-link{
        padding:8px 11px;
        font-size:10px;
      }

      .menu-btn{
        font-size:20px;
      }

      main{
        padding:110px 16px 40px;
      }

      h1{
        font-size:44px;
      }

      .login-subtext{
        font-size:17px;
      }

      .card-body{
        padding:24px 18px 22px;
      }

      .card-title{
        font-size:28px;
      }

      .btn-primary,
      .btn-secondary{
        flex:1 1 100%;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="header-inner">
      <div class="header-left">
        <a href="/" class="brand-lockup" aria-label="Pixelwise home">
          <svg class="header-logo" viewBox="0 0 22 22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" shape-rendering="crispEdges">
            <rect x="1" y="1" width="4" height="4" fill="#7B5CFF"/>
            <rect x="5" y="1" width="4" height="4" fill="#7B5CFF"/>
            <rect x="9" y="1" width="4" height="4" fill="#000000"/>
            <rect x="13" y="1" width="4" height="4" fill="#000000"/>
            <rect x="1" y="5" width="4" height="4" fill="#FF5A4F"/>
            <rect x="5" y="5" width="4" height="4" fill="#FFC83D"/>
            <rect x="9" y="5" width="4" height="4" fill="#FFC83D"/>
            <rect x="13" y="5" width="4" height="4" fill="#000000"/>
            <rect x="1" y="9" width="4" height="4" fill="#7B5CFF"/>
            <rect x="5" y="9" width="4" height="4" fill="#000000"/>
            <rect x="9" y="9" width="4" height="4" fill="#000000"/>
            <rect x="1" y="13" width="4" height="4" fill="#000000"/>
            <rect x="5" y="13" width="4" height="4" fill="#000000"/>
          </svg>
          <span class="brand-text">Pixelwise</span>
        </a>
      </div>

      <div class="header-right">
        <a href="/" class="header-link">Back to site</a>
        <button class="menu-btn" onclick="openDrawer()" aria-label="Open menu">☰</button>
      </div>
    </div>
  </header>

  <div id="overlay" class="overlay" onclick="closeDrawer()"></div>

  <div id="drawer" class="drawer">
    <button class="drawer-close" onclick="closeDrawer()">✕</button>
    <div style="display:flex;align-items:center;gap:10px;font-weight:700;margin-bottom:20px;font-size:20px;">
      <svg class="drawer-logo" viewBox="0 0 22 22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" shape-rendering="crispEdges">
        <rect x="1" y="1" width="4" height="4" fill="#7B5CFF"/>
        <rect x="5" y="1" width="4" height="4" fill="#7B5CFF"/>
        <rect x="9" y="1" width="4" height="4" fill="#000000"/>
        <rect x="13" y="1" width="4" height="4" fill="#000000"/>
        <rect x="1" y="5" width="4" height="4" fill="#FF5A4F"/>
        <rect x="5" y="5" width="4" height="4" fill="#FFC83D"/>
        <rect x="9" y="5" width="4" height="4" fill="#FFC83D"/>
        <rect x="13" y="5" width="4" height="4" fill="#000000"/>
        <rect x="1" y="9" width="4" height="4" fill="#7B5CFF"/>
        <rect x="5" y="9" width="4" height="4" fill="#000000"/>
        <rect x="9" y="9" width="4" height="4" fill="#000000"/>
        <rect x="1" y="13" width="4" height="4" fill="#000000"/>
        <rect x="5" y="13" width="4" height="4" fill="#000000"/>
      </svg>
      <span>Pixelwise</span>
    </div>

    <div class="drawer-top">
      <a href="/" onclick="closeDrawer()">Homepage</a>
      <a href="/library.html" onclick="closeDrawer()">Resource Library</a>
      <a href="/#templates" onclick="closeDrawer()">Templates & Playbooks</a>
      <a href="/#faq" onclick="closeDrawer()">FAQ</a>
    </div>

    <div class="drawer-section-label">Privacy topics</div>
    <div class="drawer-submenu">
      <a href="#" onclick="closeDrawer()">HIPAA & privacy</a>
      <a href="#" onclick="closeDrawer()">Tracking tech</a>
      <a href="#" onclick="closeDrawer()">Digital health</a>
      <a href="#" onclick="closeDrawer()">Marketing compliance</a>
    </div>

    <div class="drawer-bottom">
      <a href="/#risk-brief" class="drawer-join">Get free brief</a>
      <a href="/library.html" class="drawer-login">Go to library</a>
    </div>
  </div>

  <main>
    <div class="login-wrap">
      <div class="login-copy">
        <div class="eyebrow">Member access</div>
        <h1>Log in to access your Pixelwise resource library</h1>
        <div class="login-subtext">
          Sign in to access templates, playbooks, books, podcasts, and risk tools tied to your account.
        </div>
        <div class="login-helper">
          Your library access depends on your account tier. After login, you’ll be taken directly to the Resource Library.
        </div>

        <ul class="benefit-list">
          <li>Access the documents included with your plan.</li>
          <li>View locked premium resources and upgrade later if needed.</li>
          <li>Download PDF and .doc resources from one central library.</li>
        </ul>
      </div>

      <div class="login-card">
        <div class="card-topbar"></div>
        <div class="card-body">
          <div class="card-label">Account login</div>
          <h2 class="card-title">Welcome back</h2>
          <p class="card-copy">
            Use the email and password connected to your Pixelwise access.
          </p>

          <form id="loginForm">
            <div class="field">
              <label for="email">Email</label>
              <input id="email" type="email" placeholder="Enter your email" autocomplete="email" required />
            </div>

            <div class="field">
              <label for="password">Password</label>
              <input id="password" type="password" placeholder="Enter your password" autocomplete="current-password" required />
            </div>

            <div class="card-actions">
              <button type="submit" class="btn btn-primary" id="loginBtn">Log in</button>
              <button type="button" class="btn btn-secondary" id="forgotBtn">Send magic link</button>
            </div>
          </form>

          <div id="statusMessage" class="status"></div>

          <div class="microcopy">
            If your account already exists, you can sign in with your password or request a magic link to your email.
          </div>

          <div class="login-footer-link">
            Need to buy access first? <a href="/">Go back to the homepage</a>
          </div>
        </div>
      </div>
    </div>
  </main>

  <script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
  <script>
    const supabaseUrl = "https://zytcznhxiszqypflgvhz.supabase.co";
    const supabaseKey = "sb_publishable_g-lpsZTEaID3cbgEPQyA2Q_dnDNDyAv";
    const supabaseClient = supabase.createClient(supabaseUrl, supabaseKey);

    function openDrawer(){
      document.getElementById('drawer').classList.add('open');
      document.getElementById('overlay').classList.add('open');
    }

    function closeDrawer(){
      document.getElementById('drawer').classList.remove('open');
      document.getElementById('overlay').classList.remove('open');
    }

    const statusMessage = document.getElementById('statusMessage');
    const loginForm = document.getElementById('loginForm');
    const loginBtn = document.getElementById('loginBtn');
    const forgotBtn = document.getElementById('forgotBtn');

    function setStatus(message, type = "") {
      statusMessage.textContent = message;
      statusMessage.className = "status";
      if (type) {
        statusMessage.classList.add(type);
      }
    }

    async function redirectIfLoggedIn() {
      const { data, error } = await supabaseClient.auth.getSession();
      if (!error && data.session) {
        window.location.href = "/library.html";
      }
    }

    loginForm.addEventListener('submit', async function(e) {
      e.preventDefault();

      const email = document.getElementById('email').value.trim();
      const password = document.getElementById('password').value;

      setStatus("");
      loginBtn.disabled = true;
      loginBtn.textContent = "Logging in...";

      const { error } = await supabaseClient.auth.signInWithPassword({
        email,
        password
      });

      if (error) {
        setStatus(error.message, "error");
        loginBtn.disabled = false;
        loginBtn.textContent = "Log in";
        return;
      }

      setStatus("Login successful. Redirecting...", "success");
      window.location.href = "/library.html";
    });

    forgotBtn.addEventListener('click', async function() {
      const email = document.getElementById('email').value.trim();

      if (!email) {
        setStatus("Enter your email first, then click Send magic link.", "error");
        return;
      }

      forgotBtn.disabled = true;
      forgotBtn.textContent = "Sending...";

      const { error } = await supabaseClient.auth.signInWithOtp({
        email,
        options: {
          emailRedirectTo: window.location.origin + "/library.html"
        }
      });

      if (error) {
        setStatus(error.message, "error");
        forgotBtn.disabled = false;
        forgotBtn.textContent = "Send magic link";
        return;
      }

      setStatus("Magic link sent. Check your email.", "success");
      forgotBtn.disabled = false;
      forgotBtn.textContent = "Send magic link";
    });

    window.addEventListener('scroll', () => {
      const header = document.querySelector('header');
      if(window.scrollY > 20){
        header.classList.add('scrolled');
      } else {
        header.classList.remove('scrolled');
      }
    });

    redirectIfLoggedIn();
  </script>
</body>
</html>
