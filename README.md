<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>zawch | متجر المنتجات</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;800&display=swap" rel="stylesheet">
<style>
:root{--navy:#0f172a;--navy2:#1e293b;--gold:#d4a017;--gold2:#f5c542;--bg:#f6f7fb;--card:#fff;--txt:#1e293b;--mut:#64748b;--ok:#16a34a;--bad:#dc2626;--bd:#e2e8f0}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:'Cairo',Tahoma,sans-serif;background:var(--bg);color:var(--txt);line-height:1.7}
a{text-decoration:none;color:inherit}
.container{max-width:1150px;margin:auto;padding:0 16px}
header{background:var(--navy);position:sticky;top:0;z-index:50;box-shadow:0 2px 12px #0003}
.nav{display:flex;align-items:center;justify-content:space-between;height:64px}
.logo{font-size:28px;font-weight:800;color:#fff;letter-spacing:1px}
.logo span{color:var(--gold2)}
nav a{color:#cbd5e1;margin-inline-start:20px;font-weight:600;font-size:15px;transition:.2s}
nav a:hover{color:var(--gold2)}
.hero{background:linear-gradient(135deg,var(--navy),#1e3a5f);color:#fff;padding:70px 0;text-align:center}
.hero h1{font-size:clamp(28px,5vw,46px);font-weight:800}
.hero h1 span{color:var(--gold2)}
.hero p{color:#cbd5e1;margin:14px auto 26px;max-width:560px;font-size:17px}
.btn{display:inline-block;border:0;cursor:pointer;font-family:inherit;font-weight:700;font-size:16px;padding:12px 26px;border-radius:10px;background:var(--gold);color:#fff;transition:.2s}
.btn:hover{background:#b8880f;transform:translateY(-1px)}
.btn.sec{background:var(--navy2)}
.btn.ghost{background:transparent;border:2px solid var(--gold2);color:var(--gold2)}
.btn.sm{padding:7px 14px;font-size:14px;border-radius:8px}
.btn.red{background:var(--bad)}
.btn:disabled{background:#94a3b8;cursor:not-allowed;transform:none}
section{padding:50px 0}
h2.title{font-size:28px;font-weight:800;text-align:center;margin-bottom:8px}
h2.title::after{content:"";display:block;width:60px;height:4px;background:var(--gold);margin:8px auto 0;border-radius:4px}
.sub{text-align:center;color:var(--mut);margin-bottom:30px}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:20px}
