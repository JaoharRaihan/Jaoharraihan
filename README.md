<div style="font-family: 'Segoe UI', sans-serif; line-height:1.6;">

<!-- Title -->
<h1 style="animation: fadeIn 1.2s ease-in-out;">👋 Yo, I’m <span style="color:#ff4c4c;">Jaohar</span></h1>
<h3 style="animation: fadeIn 1.5s ease-in-out 0.3s;">React Native Dev | ML Explorer | Cricket Data Nerd</h3>
<p style="animation: fadeIn 1.8s ease-in-out 0.6s;">📍 Dhaka, Bangladesh | 🌐 <a href="https://jaoharraihan.github.io">Portfolio</a></p>

<!-- About Me with typing effect -->
<p style="animation: typing 4s steps(60, end), blink-caret .75s step-end infinite;">
💡 About Me: I turn code & data into real-world magic. From spotting crop diseases with AI to predicting cricket plays, I make tech actually useful.
</p>

<!-- Skills with animated bars -->
<h4 style="animation: fadeIn 2.5s ease-in-out 1s;">🛠️ Skills</h4>
<div style="max-width:400px;">
  <div style="margin:6px 0;">JS <span style="display:inline-block; width:0; height:10px; background:#f0db4f; animation: skillBarJS 2s forwards;"></span></div>
  <div style="margin:6px 0;">Python <span style="display:inline-block; width:0; height:10px; background:#3572A5; animation: skillBarPy 2s forwards 0.2s;"></span></div>
  <div style="margin:6px 0;">React Native <span style="display:inline-block; width:0; height:10px; background:#61dafb; animation: skillBarRN 2s forwards 0.4s;"></span></div>
  <div style="margin:6px 0;">ML & Data <span style="display:inline-block; width:0; height:10px; background:#ff4c4c; animation: skillBarML 2s forwards 0.6s;"></span></div>
</div>

<!-- Projects with bouncing emojis -->
<h4 style="animation: fadeIn 3s ease-in-out 1.5s;">🚀 Highlights</h4>
<ul style="animation: fadeIn 3.2s ease-in-out 1.7s;">
  <li>🌾 <b>Crop Disease Detector</b> – 97% accuracy for Rice, Potato & Corn</li>
  <li>🖼️ <b>Full-stack Image Classifier</b> – Django + React + ML model</li>
  <li>🏏 <b>Cricket Analytics Dashboard</b> – Predictive player & match insights <span class="bounce">🏏</span></li>
</ul>

<!-- Looking For -->
<h4 style="animation: fadeIn 3.5s ease-in-out 2s;">🎯 Looking For</h4>
<p style="animation: fadeIn 3.7s ease-in-out 2.2s;">
Junior Dev roles (React Native/Web/ML) on teams that want real impact.
</p>

<!-- Connect -->
<h4 style="animation: fadeIn 4s ease-in-out 2.5s;">📫 Connect</h4>
<p style="animation: fadeIn 4.2s ease-in-out 2.7s;">
<a href="https://www.linkedin.com/in/jaoharraihan">LinkedIn</a> | ✉️ jaoharraihan.dev@gmail.com
</p>

<!-- Fun Fact with moving cricket ball -->
<h4 style="animation: fadeIn 4.5s ease-in-out 3s;">⚡ Fun Fact</h4>
<p style="animation: fadeIn 4.7s ease-in-out 3.2s;">
I geek out on cricket data—<span class="cricket-ball">🏏</span> smart plays, smarter wins.
</p>
</div>

<style>
/* Fade In Animation */
@keyframes fadeIn {
  0% {opacity:0; transform: translateY(15px);}
  100% {opacity:1; transform: translateY(0);}
}

/* Typing effect */
@keyframes typing {
  from {width:0;}
  to {width:100%;}
}
@keyframes blink-caret {
  50% { border-right-color: transparent; }
}
p { border-right: 2px solid #ff4c4c; padding-right:2px; display:inline-block; overflow:hidden; white-space:nowrap;}

/* Skill Bars */
@keyframes skillBarJS { 0%{width:0;} 100%{width:90%;} }
@keyframes skillBarPy { 0%{width:0;} 100%{width:85%;} }
@keyframes skillBarRN { 0%{width:0;} 100%{width:80%;} }
@keyframes skillBarML { 0%{width:0;} 100%{width:75%;} }

/* Bouncing Emoji */
@keyframes bounceAnim {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-10px); }
}
.bounce { display:inline-block; animation: bounceAnim 1s infinite; }

/* Moving Cricket Ball */
@keyframes ballMove {
  0% { transform: translateX(0); }
  50% { transform: translateX(10px); }
  100% { transform: translateX(0); }
}
.cricket-ball { display:inline-block; animation: ballMove 1s infinite linear; }
</style>
