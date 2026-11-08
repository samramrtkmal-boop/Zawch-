
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>ZAWCH Store</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;800&family=Outfit:wght@500;700;800&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#faf7f8; --surface:#ffffff; --surface2:#f3eef0; --text:#1b1217; --muted:#6f6169;
  --line:#e7dde1; --accent:#d4175a; --accent2:#7a0f3c; --accent-soft:#fde6ee;
  --ok:#0f9d58; --warn:#e8890c; --bad:#d93025; --shadow:0 10px 30px rgba(60,10,30,.10);
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){
    --bg:#0f0a0d; --surface:#181115; --surface2:#21171c; --text:#f6eef1; --muted:#a8969f;
    --line:#2f2228; --accent:#ff3f84; --accent2:#c01a5a; --accent-soft:#3a1424;
    --ok:#3ddc84; --warn:#ffb340; --bad:#ff6b5e; --shadow:0 10px 30px rgba(0,0,0,.45);
  }
}
:root[data-theme="dark"]{
  --bg:#0f0a0d; --surface:#181115; --surface2:#21171c; --text:#f6eef1; --muted:#a8969f;
  --line:#2f2228; --accent:#ff3f84; --accent2:#c01a5a; --accent-soft:#3a1424;
  --ok:#3ddc84; --warn:#ffb340; --bad:#ff6b5e; --shadow:0 10px 30px rgba(0,0,0,.45);
}
*{box-sizing:border-box;margin:0;padding:0}
[hidden]{display:none!important}
body{direction:rtl}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);z-index:60;background:var(--bg)}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--text);font-family:'Cairo',system-ui,sans-serif;line-height:1.6;-webkit-font-smoothing:antialiased}
.wrap{max-width:1180px;margin:0 auto;padding:0 16px}
