````css
:root{--navy:#0A1B3D;--navy2:#12295A;--blue:#2E75B6;--sky:#EAF3FB;--gold:#E9B63A;--ink:#1B2433;--mut:#566175}
*{box-sizing:border-box;margin:0}
html{scroll-behavior:smooth}
body{font:400 17px/1.65 Roboto,sans-serif;color:var(--ink);background:#fff}
img{max-width:100%;height:auto}a{color:var(--blue)}
:focus-visible{outline:3px solid var(--gold);outline-offset:3px}
.w{max-width:1120px;margin:auto;padding:0 24px}
h1,h2,h3{line-height:1.15;color:var(--navy)}
h1{font-size:clamp(2.3rem,5.2vw,4rem);font-weight:900;letter-spacing:-.02em}
h2{font-size:clamp(1.7rem,3.2vw,2.5rem);font-weight:700;margin-bottom:16px}
h3{font-size:1.2rem;font-weight:700}
p{max-width:68ch}
header{background:var(--navy);position:sticky;top:0;z-index:9;border-bottom:3px solid var(--gold)}
.nav{display:flex;align-items:center;justify-content:space-between;min-height:76px}
.nav ul{display:flex;gap:28px;list-style:none;padding:0;align-items:center}
.nav a{color:#fff;text-decoration:none;font-weight:500}
.nav a[aria-current]{color:var(--gold)}
.btn{display:inline-block;background:var(--gold);color:var(--navy)!important;font-weight:700;padding:14px 28px;border-radius:999px;text-decoration:none;transition:transform .2s}
.btn:hover{transform:translateY(-2px)}
.btn.o{background:none;color:#fff!important;border:2px solid #fff}
#m,.bg{display:none}
.hero{background:var(--navy);color:#fff;position:relative;overflow:hidden;padding:110px 0 120px}
.hero h1{color:#fff;max-width:14ch}
.hero p{color:#cfdcf2;font-size:1.2rem;margin:24px 0 36px}
.hero .w{position:relative;z-index:1}
.hero::after{content:"";position:absolute;right:-200px;top:50%;width:820px;height:820px;margin-top:-410px;border-radius:50%;background:radial-gradient(circle,rgba(46,117,182,.6),transparent 58%),repeating-radial-gradient(circle,transparent 0 30px,rgba(233,182,58,.45) 31px 32px);animation:ring 1.8s ease-out both}
@keyframes ring{from{transform:scale(.55);opacity:0}to{transform:none;opacity:1}}
.hero.sm{padding:72px 0}.hero.sm h1{font-size:clamp(2rem,4vw,3rem);max-width:22ch}
.band{background:var(--navy2);color:#fff;padding:22px 0}
.band ul{display:flex;flex-wrap:wrap;gap:10px 34px;list-style:none;padding:0;font-weight:700;font-size:1.05rem}
.band li::before{content:"";display:inline-block;width:10px;height:10px;background:var(--gold);border-radius:50%;margin-right:10px}
.s{padding:88px 0}.alt{background:var(--sky)}
.lead{color:var(--mut);margin-bottom:40px}
.row{display:grid;grid-template-columns:1.1fr 2fr 1.3fr;gap:32px;padding:30px 0 30px 22px;border-top:1px solid #c9d8ea;border-left:5px solid var(--gold);margin-top:-1px}
.row p{color:var(--mut)}.row b{color:var(--blue)}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:24px}
.t{background:#fff;border-left:5px solid var(--blue);padding:26px;border-radius:0 14px 14px 0}
.t:nth-child(even){border-left-color:var(--gold)}
.t h3{margin-bottom:8px}.t p{color:var(--mut);font-size:.98rem}
.steps{display:grid;grid-template-columns:repeat(5,1fr);gap:18px;list-style:none;padding:0;counter-reset:n}
.steps li{counter-increment:n;border-top:4px solid var(--gold);padding-top:16px;font-weight:700;color:var(--navy)}
.steps li::before{content:counter(n);display:block;font-size:2.4rem;font-weight:900;color:var(--blue)}
.steps span{display:block;font-weight:400;color:var(--mut);font-size:.95rem}
.cta{background:var(--navy);color:#fff;text-align:center;padding:84px 0}
.cta h2{color:#fff}.cta p{margin:0 auto 30px;color:#cfdcf2}
.logos{display:flex;flex-wrap:wrap;gap:12px 30px;list-style:none;padding:0;color:var(--mut);font-weight:700}
.two{display:grid;grid-template-columns:1fr 1fr;gap:56px}
form{display:grid;gap:16px}label{font-weight:500;display:grid;gap:6px}
input,select,textarea{font:inherit;padding:13px;border:1px solid #b9c7da;border-radius:8px;width:100%}
footer{background:#071330;color:#b8c6e0;padding:56px 0 28px;font-size:.95rem}
footer .w{display:grid;grid-template-columns:2fr 1fr 1fr;gap:32px}
footer a{color:#fff}footer small{grid-column:1/-1;border-top:1px solid #1c3166;padding-top:20px}
@media(max-width:860px){
.bg{display:block;color:#fff;font-size:1.8rem;cursor:pointer}
.nav ul{display:none;position:absolute;top:76px;left:0;right:0;background:var(--navy);flex-direction:column;padding:20px 24px 28px;gap:18px;align-items:flex-start}
#m:checked~ul{display:flex}
.row,.two,footer .w{grid-template-columns:1fr}.steps{grid-template-columns:1fr 1fr}
.hero::after{opacity:.35;right:-420px}.hero{padding:72px 0 80px}.s{padding:60px 0}}
@media(prefers-reduced-motion:reduce){.hero::after{animation:none}html{scroll-behavior:auto}}

````
