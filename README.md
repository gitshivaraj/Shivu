<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>NyayaDwar - Know Your Rights</title>

<link rel="stylesheet" href="style.css">

<link rel="manifest" href="manifest.json">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

</head>

<body>

<!-- SPLASH SCREEN -->

<div id="splash">

<img src="logo.png" class="logo">

<h1>NyayaDwar</h1>
<p>Know Your Rights</p>

</div>



<!-- LOGIN / REGISTER -->

<div id="auth">

<div class="glass-card">

<img src="logo.png" class="logo-small">

<h2>Welcome to NyayaDwar</h2>

<input type="text" placeholder="Full Name">

<input type="text" placeholder="Phone Number">

<input type="email" placeholder="Email Address">

<button class="primary">Register</button>

<button class="secondary">Login</button>

<button class="ghost">Continue as Guest</button>

</div>

</div>



<!-- MAIN APP -->

<div id="app">

<header>

<div class="brand">

<img src="logo.png">

<div>
<h3>NyayaDwar</h3>
<span>Know Your Rights</span>
</div>

</div>

<div class="menu">

<span>⚙️</span>
<span>👤</span>

</div>

</header>



<!-- QUICK ACTIONS -->

<section class="quick-actions">

<button class="glass-btn">📄 Upload Legal Document</button>

<button class="glass-btn">📷 Scan Paper Document</button>

<button class="glass-btn">🎤 Speak Your Problem</button>

<button class="glass-btn">⚖️ Know My Rights</button>

</section>



<!-- CHAT AREA -->

<section class="chat">

<div class="ai-message">

<h4>Summary</h4>
<p>This document appears to be a rental agreement.</p>

<h4>Your Rights</h4>
<p>You have the right to receive written notice before eviction.</p>

<h4>Risks Detected</h4>
<p>The contract has a clause allowing immediate eviction.</p>

<h4>Recommended Actions</h4>
<p>Request a revised agreement or consult a local lawyer.</p>

</div>

<div class="user-message">
Can you explain this contract?
</div>

</section>



<!-- PROMPTS -->

<section class="prompts">

<button>Explain my land agreement</button>

<button>Check my rental contract</button>

<button>What are my rights if police stop me</button>

<button>Generate a complaint letter</button>

</section>



<!-- INPUT BAR -->

<footer>

<input type="text" placeholder="Ask anything about your legal rights...">

<button>📎</button>

<button>📷</button>

<button>🎤</button>

<button class="send">➤</button>

</footer>

</div>


<script src="app.js"></script>

</body>
</html>
