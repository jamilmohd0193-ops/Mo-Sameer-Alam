# Mo-Sameer-Alam

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>NeoInvest AI Pro</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#050816;
color:white;
overflow-x:hidden;
}

/* NAVBAR */

nav{
width:100%;
padding:18px 7%;
display:flex;
justify-content:space-between;
align-items:center;
background:#0b1023;
position:sticky;
top:0;
z-index:1000;
border-bottom:1px solid rgba(255,255,255,0.1);
}

.logo{
font-size:28px;
font-weight:700;
color:#00e5ff;
}

nav ul{
display:flex;
gap:25px;
list-style:none;
}

nav ul li{
cursor:pointer;
transition:0.3s;
}

nav ul li:hover{
color:#00e5ff;
}

.nav-btn{
padding:10px 18px;
background:#00e5ff;
border:none;
border-radius:8px;
font-weight:600;
cursor:pointer;
}

/* HERO */

.hero{
min-height:90vh;
display:flex;
align-items:center;
justify-content:space-between;
padding:70px 7%;
flex-wrap:wrap;
gap:40px;
}

.hero-left{
flex:1;
min-width:300px;
}

.hero-left h1{
font-size:60px;
line-height:1.1;
margin-bottom:20px;
}

.hero-left span{
color:#00e5ff;
}

.hero-left p{
font-size:18px;
color:#b6b6b6;
margin-bottom:30px;
line-height:1.7;
}

.hero-buttons{
display:flex;
gap:15px;
flex-wrap:wrap;
}

.hero-buttons button{
padding:14px 25px;
border:none;
border-radius:10px;
font-size:16px;
font-weight:600;
cursor:pointer;
transition:0.3s;
}

.primary-btn{
background:#00e5ff;
color:black;
}

.secondary-btn{
background:transparent;
border:1px solid #00e5ff !important;
color:#00e5ff;
}

.hero-buttons button:hover{
transform:translateY(-3px);
}

.hero-right{
flex:1;
min-width:300px;
display:flex;
justify-content:center;
}

.dashboard{
width:100%;
max-width:500px;
background:#101935;
padding:25px;
border-radius:20px;
box-shadow:0 0 30px rgba(0,229,255,0.2);
}

.dashboard h3{
margin-bottom:20px;
color:#00e5ff;
}

.stock{
display:flex;
justify-content:space-between;
padding:15px;
background:#182347;
border-radius:12px;
margin-bottom:12px;
}

.buy{
color:#00ff99;
font-weight:bold;
}

.sell{
color:#ff4d4d;
font-weight:bold;
}

.hold{
color:#ffd166;
font-weight:bold;
}

/* FEATURES */

.section{
padding:80px 7%;
}

.section-title{
text-align:center;
font-size:42px;
margin-bottom:50px;
}

.section-title span{
color:#00e5ff;
}

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:25px;
}

.feature-card{
background:#101935;
padding:30px;
border-radius:18px;
transition:0.3s;
border:1px solid rgba(255,255,255,0.05);
}

.feature-card:hover{
transform:translateY(-8px);
box-shadow:0 0 25px rgba(0,229,255,0.15);
}

.feature-card h3{
margin:20px 0;
color:#00e5ff;
}

.feature-card p{
color:#b8b8b8;
line-height:1.7;
}

/* LIVE MARKET */

.market-box{
background:#101935;
padding:35px;
border-radius:20px;
margin-top:40px;
}

.market-controls{
display:flex;
gap:15px;
margin-bottom:20px;
flex-wrap:wrap;
}

.market-controls input{
flex:1;
padding:14px;
border:none;
border-radius:10px;
background:#182347;
color:white;
}

.market-controls button{
padding:14px 22px;
border:none;
border-radius:10px;
background:#00e5ff;
font-weight:600;
cursor:pointer;
}

.market-result{
margin-top:20px;
font-size:20px;
color:#00ff99;
}

/* AI BOT */

.ai-box{
background:#101935;
padding:35px;
border-radius:20px;
margin-top:40px;
}

.ai-box input{
width:100%;
padding:15px;
border:none;
border-radius:10px;
background:#182347;
color:white;
margin-top:20px;
}

.ai-box button{
margin-top:15px;
padding:14px 22px;
border:none;
border-radius:10px;
background:#00e5ff;
font-weight:600;
cursor:pointer;
}

.ai-response{
margin-top:20px;
line-height:1.7;
color:#d7d7d7;
}

/* PRICING */

.pricing{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:25px;
}

.price-card{
background:#101935;
padding:40px;
border-radius:20px;
text-align:center;
transition:0.3s;
}

.price-card:hover{
transform:scale(1.03);
}

.price-card h2{
color:#00e5ff;
margin-bottom:10px;
}

.price{
font-size:48px;
margin:20px 0;
}

.price-card ul{
list-style:none;
margin:25px 0;
}

.price-card ul li{
margin:12px 0;
color:#cfcfcf;
}

.price-card button{
padding:14px 24px;
border:none;
border-radius:10px;
background:#00e5ff;
font-weight:600;
cursor:pointer;
}

/* FOOTER */

footer{
padding:40px 7%;
background:#0b1023;
text-align:center;
margin-top:60px;
border-top:1px solid rgba(255,255,255,0.08);
}

footer p{
color:#999;
margin-top:10px;
}

/* RESPONSIVE */

@media(max-width:768px){

.hero-left h1{
font-size:42px;
}

nav ul{
display:none;
}

}

</style>
</head>

<body>

<!-- NAVBAR -->

<nav>

<div class="logo">NeoInvest AI</div>

<ul>
<li>Home</li>
<li>Features</li>
<li>Market</li>
<li>Pricing</li>
<li>Contact</li>
</ul>

<button class="nav-btn">Get Started</button>

</nav>

<!-- HERO -->

<section class="hero">

<div class="hero-left">

<h1>Future Of <span>AI Trading</span> Starts Here</h1>

<p>
Smart investing platform with AI signals,
real-time market insights, automated analytics,
and futuristic dashboard experience.
</p>

<div class="hero-buttons">
<button class="primary-btn">Start Trading</button>
<button class="secondary-btn">Live Demo</button>
</div>

</div>

<div class="hero-right">

<div class="dashboard">

<h3>📈 Live AI Signals</h3>

<div class="stock">
<span>RELIANCE</span>
<span class="buy">BUY</span>
</div>

<div class="stock">
<span>TCS</span>
<span class="hold">HOLD</span>
</div>

<div class="stock">
<span>INFY</span>
<span class="sell">SELL</span>
</div>

<div class="stock">
<span>HDFCBANK</span>
<span class="buy">BUY</span>
</div>

</div>

</div>

</section>

<!-- FEATURES -->

<section class="section">

<h1 class="section-title">
Powerful <span>Features</span>
</h1>

<div class="features">

<div class="feature-card">
<h3>🤖 AI Predictions</h3>
<p>
Advanced machine learning algorithms provide
buy and sell recommendations in real-time.
</p>
</div>

<div class="feature-card">
<h3>📊 Live Market</h3>
<p>
Track live prices, market movements,
candlestick charts and analytics.
</p>
</div>

<div class="feature-card">
<h3>🔐 Secure Wallet</h3>
<p>
Military-grade encrypted wallet and
safe payment integrations.
</p>
</div>

<div class="feature-card">
<h3>⚡ Fast Trading</h3>
<p>
Execute trades instantly with low latency
infrastructure and cloud servers.
</p>
</div>

</div>

</section>

<!-- LIVE MARKET -->

<section class="section">

<h1 class="section-title">
Live <span>Market</span>
</h1>

<div class="market-box">

<div class="market-controls">

<input id="stockInput" placeholder="Enter Stock Name (AAPL)">
<button onclick="loadStock()">Check Price</button>

</div>

<div class="market-result" id="marketResult">
Waiting for market data...
</div>

</div>

</section>

<!-- AI BOT -->

<section class="section">

<h1 class="section-title">
AI <span>Assistant</span>
</h1>

<div class="ai-box">

<h2>Ask Trading AI</h2>

<input id="aiInput" placeholder="Should I buy Tesla stock?">

<button onclick="askAI()">Ask AI</button>

<div class="ai-response" id="aiResponse">
AI response will appear here...
</div>

</div>

</section>

<!-- PRICING -->

<section class="section">

<h1 class="section-title">
Premium <span>Plans</span>
</h1>

<div class="pricing">

<div class="price-card">

<h2>Starter</h2>

<div class="price">$9</div>

<ul>
<li>AI Signals</li>
<li>Live Dashboard</li>
<li>Basic Analytics</li>
<li>Email Support</li>
</ul>

<button>Choose Plan</button>

</div>

<div class="price-card">

<h2>Pro Trader</h2>

<div class="price">$29</div>

<ul>
<li>Advanced AI</li>
<li>Real-time API</li>
<li>Portfolio Tracking</li>
<li>Priority Support</li>
</ul>

<button>Upgrade</button>

</div>

<div class="price-card">

<h2>Enterprise</h2>

<div class="price">$99</div>

<ul>
<li>Custom AI Models</li>
<li>Institutional Tools</li>
<li>Cloud Servers</li>
<li>Dedicated Manager</li>
</ul>

<button>Contact Us</button>

</div>

</div>

</section>

<!-- FOOTER -->

<footer>

<h2>🚀 NeoInvest AI Platform</h2>

<p>
© 2026 All Rights Reserved | Built With AI Technology
</p>

</footer>

<script>

function loadStock(){

let stock =
document.getElementById("stockInput").value;

if(stock==""){
alert("Please enter stock name");
return;
}

let fakePrice =
(Math.random()*1000).toFixed(2);

document.getElementById("marketResult")
.innerHTML =
"📈 " + stock.toUpperCase() +
" Current Price: $" + fakePrice;

}

function askAI(){

let text =
document.getElementById("aiInput").value
.toLowerCase();

let response="";

if(text.includes("buy")){

response =
"✅ AI Analysis: Strong BUY signal detected with bullish momentum.";

}

else if(text.includes("sell")){

response =
"📉 AI Analysis: SELL signal detected due to weak trend.";

}

else if(text.includes("tesla")){

response =
"⚡ Tesla is highly volatile. Risk management recommended.";

}

else{

response =
"⚖️ AI Suggestion: Diversify your portfolio for safer growth.";

}

document.getElementById("aiResponse")
.innerHTML=response;

}

</script>

</body>
</html>
