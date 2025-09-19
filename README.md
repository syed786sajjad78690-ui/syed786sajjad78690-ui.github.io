<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Your Site Title</title>
  <style>
    body { font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; margin:0; padding:40px; background:#f7f7fb; color:#111 }
    .card { max-width:900px; margin:40px auto; background:#fff; padding:28px; border-radius:12px; box-shadow:0 6px 24px rgba(20,20,50,0.06) }
    h1 { margin:0 0 8px; font-size:28px }
    p.lead { margin-top:0; color:#444 }
    a.btn { display:inline-block; margin-top:14px; padding:10px 14px; border-radius:8px; text-decoration:none; border:1px solid #e6e6ee }
    footer { text-align:center; font-size:13px; color:#777; margin-top:20px }
  </style>
</head>
<body>
  <div class="card">
    <h1>Hello — I built a free site!</h1>
    <p class="lead">This is a minimal starter page. Edit this file and redeploy to update content.</p>
    <p>Tips: replace this text, add images in an `assets/` folder, or link to other pages like <a href="/about.html">About</a>.</p>
    <a class="btn" href="https://github.com">Get started</a>
    <footer>&copy; <span id="y"></span> Your Name</footer>
  </div>
  <script>document.getElementById('y').textContent = new Date().getFullYear();</script>
</body>
</html>
