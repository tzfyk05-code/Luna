<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>Luna ❤️</title>

<style>
body {
  margin: 0;
  height: 100vh;
  font-family: Arial, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;

  /* الصورة الكبيرة */
  background-image: url("image.jpg"); /* نفس اسم الصورة */
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.box {
  background: rgba(255, 255, 255, 0.92);
  padding: 25px;
  width: 340px;
  border-radius: 20px;
  text-align: center;
  box-shadow: 0 0 20px rgba(0,0,0,0.3);
}

h1 {
  color: #e11d48;
}

input {
  width: 100%;
  padding: 10px;
  margin: 15px 0;
  border-radius: 10px;
  border: 1px solid #ccc;
  text-align: center;
  font-size: 16px;
}

button {
  width: 100%;
  padding: 12px;
  border: none;
  border-radius: 20px;
  background: linear-gradient(135deg,#ff9ecb,#b983ff);
  color: white;
  font-size: 16px;
  cursor: pointer;
}

#message {
  display: none;
  color: #e11d48;
  line-height: 1.8;
}

.video {
  margin-top: 15px;
  border-radius: 15px;
  overflow: hidden;
}
</style>
</head>

<body>

<div class="box">
  <h1>Luna ❤️</h1>

  <div id="login">
    <p>ادخلي الباسورد 🥺</p>
    <input type="password" id="password" placeholder="****">
    <button onclick="check()">دخول</button>
  </div>

  <div id="message">
    <p>
      في وسط الناس وفي عز انشغالي والضجيج<br>
      الذي يحيط بي وكل شيء من حولي<br>
      افكرُ بكِ وحدك<br>
      واحنُ اليكِ وحدك<br>
      واحبكِ وحدك...
    </p>

    <div class="video">
      <iframe width="100%" height="200"
        src="https://www.youtube.com/embed/G4VMiIbTfL0?autoplay=1"
        frameborder="0"
        allow="autoplay; encrypted-media"
        allowfullscreen>
      </iframe>
    </div>
  </div>
</div>

<script>
function check() {
  const pass = document.getElementById("password").value;
  if (pass === "28/1") {
    document.getElementById("login").style.display = "none";
    document.getElementById("message").style.display = "block";
  } else {
    alert("الباسورد غلط 😅");
  }
}
</script>

</body>
</html>
