<!doctype html>
.card{background:rgba(255,255,255,0.03);padding:20px;border-radius:14px;box-shadow:0 6px 18px rgba(2,6,23,0.6)}
header{display:flex;align-items:center;gap:18px}
.avatar{width:96px;height:96px;border-radius:14px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:30px}
h1{margin:0;font-size:26px}
p.lead{margin:6px 0 0 0;color:#cfeafd}
.badges{margin-top:12px;display:flex;gap:8px;flex-wrap:wrap}
.badge{background:rgba(255,255,255,0.04);padding:6px 10px;border-radius:999px;font-size:13px}
.grid{display:grid;grid-template-columns:1fr 300px;gap:18px;margin-top:20px}
.section{margin-bottom:12px}
.title{font-weight:600;margin-bottom:8px}
ul{padding-left:18px}
.contact a{display:inline-block;margin:6px 6px 0 0;padding:8px 12px;border-radius:8px;background:rgba(255,255,255,0.03);text-decoration:none;color:var(--text)}
footer{margin-top:18px;text-align:center;color:#9fb6c9;font-size:13px}
@media(max-width:800px){.grid{grid-template-columns:1fr}}
</style>
</head>
<body>
<div class="container">
<div class="card">
<header>
<div class="avatar">AS</div>
<div>
<h1>اسمي هنا — موقعي الشخصي</h1>
<p class="lead">مطور / مهتم بالأمن السيبراني / صانع محتوى. أشارك مشاريع وأفكار بسيطة.</p>
<div class="badges">
<span class="badge">موقع شخصي</span>
<span class="badge">الهاتف: +971 50 000 0000</span>
<span class="badge">البريد: you@example.com</span>
</div>
</div>
</header>


<div class="grid">
<main>
<section class="section">
<div class="title">عنّي</div>
<p>هنا تكتب فقرة قصيرة عنك: تعليمك، خبراتك، وما الذي تبحث عنه. اجعلها 2-3 جمل بسيطة وواضحة.</p>
</section>


<section class="section">
<div class="title">المشاريع</div>
<ul>
<li><strong>مشروع 1:</strong> وصف بسيط لمشروع قمت به أو تعمل عليه.</li>
<li><strong>مشروع 2:</strong> رابط إلى GitHub أو معرض أعمال.</li>
<li><strong>مشروع تطوعي:</strong> وصف قصير إذا وُجد.</li>
</ul>
</section>


<section class="section">
<div class="title">خدمات أو مهارات</div>
<ul>
<li>تطوير ويب — HTML, CSS, JS</li>
<li>أمن سيبراني — تحليل ثغرات (قانوني)</li>
<li>تصميم مواد رقمية ومحتوى</li>
</ul>
</section>


<section class="section">
<div class="title">نماذج تواصل</div>
<p class="contact">
<a href="#">إنستجرام</a>
<a href="#">لينكدإن</a>
<a href="#">GitHub</a>
</p>
</section>
</main>


<aside>
<section class="section">
<div class="title">سيرة قصيرة</div>
<p>سنوات الخبرة: 2+</p>
<p>اللغات: العربية، الإنجليزية</p>
</section>


<section class="section">
<div class="title">اترك رسالة</div>
<p>أرسل لي على البريد: <a href="mailto:you@example.com">you@example.com</a></p>
</section>


<section class="section">
<div class="title">تحميل السيرة</div>
<p><a href="#">تحميل CV (PDF)</a></p>
</section>
</aside>
</div>


<footer>
صنع بعناية • تواصل معي لتعديل الصفحة أو إضافة مميزات.
</footer>
</div>
</div>
</body>
</html>
