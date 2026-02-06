<!DOCTYPE html>
<html>
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Navi ❤️ Riya Ji</title>

<body style="margin:0;display:flex;justify-content:center;align-items:center;height:100vh;background:linear-gradient(135deg,#ff758c,#ff7eb3);font-family:sans-serif;color:#fff;text-align:center">

<div id="p">
  <h2>Riya Ji 💖</h2>
  <p>Will you stay forever with Navi? 🌹</p>
  <button onclick="y()" style="padding:12px 20px;font-size:18px;background:#00c853;color:#fff;border:0;border-radius:8px">Yes ❤️</button>
  <button onmouseover="n()" id="no" style="padding:12px 20px;font-size:18px;background:#d50000;color:#fff;border:0;border-radius:8px;position:absolute">No 😢</button>
</div>

<div id="s" style="display:none">
  <h1>She Said YES! 💍</h1>
  <p>Forever Yours — Navi ❤️</p>
</div>

<script>
function y(){ p.style.display='none'; s.style.display='block'; }
function n(){
  let b=document.getElementById('no');
  b.style.left=Math.random()*(innerWidth-80)+'px';
  b.style.top=Math.random()*(innerHeight-40)+'px';
}
</script>

</body>
</html>
