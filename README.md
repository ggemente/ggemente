<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Gabriel Gemente — Dev Full Stack</title>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,400;12..96,600;12..96,800&family=IBM+Plex+Mono:wght@400;500;600&display=swap" rel="stylesheet">
<style>.pg{--g-bg:#ECE6D6;--g-ik:#1F231D;--g-mt:#596052;--g-ln:#C7BEA7;--g-am:#9E6200;--g-as:#F2D9A6;--g-sg:#24677B;--g-ce:#D9D1BB;--g-cl:#B5AC93;--g-tb:#1B1F19;--g-ti:#DAD4C2;--g-td:#8C927F;--g-ta:#F0B13A;--g-to:#8FC79A;--g-ts:#7CC6DA;--g-fd:"Bricolage Grotesque","Arial Narrow",system-ui,sans-serif;--g-fm:"IBM Plex Mono",ui-monospace,Menlo,Consolas,monospace;color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}@media (prefers-color-scheme:dark){.pg{--g-bg:#181B16;--g-ik:#E8E2D0;--g-mt:#9CA190;--g-ln:#30362C;--g-am:#F0B13A;--g-as:#3A3120;--g-sg:#7CC6DA;--g-ce:#22271F;--g-cl:#3A4135;--g-tb:#10130F;color-scheme:dark}}.pg *,.pg ::before,.pg ::after{box-sizing:inherit;margin:0;padding:0}html{scroll-behavior:smooth;scroll-padding-top:calc(env(safe-area-inset-top,0px) + 64px)}.pg{background:var(--g-bg);color:var(--g-ik);font-family:var(--g-fd);font-size:1rem;line-height:1.55}.pg{container-type:inline-size;overflow-x:clip}.pg a{color:inherit}.pg :focus-visible{outline:2px solid var(--g-am);outline-offset:3px}.wrap{max-width:1180px;margin:0 auto;padding:0 clamp(1rem,5cqi,2.5rem)}.mono{font-family:var(--g-fm)}.top{position:sticky;top:env(safe-area-inset-top,0px);z-index:5;background:var(--g-bg);border-bottom:1px solid var(--g-ln)}.top .wrap{display:flex;align-items:center;justify-content:space-between;height:56px;gap:1rem}.brand{font-family:var(--g-fm);font-weight:600;font-size:.9rem;text-decoration:none}.brand span{color:var(--g-am)}.top nav{display:flex;gap:1.5rem;font-family:var(--g-fm);font-size:.85rem}.top nav a{text-decoration:none;color:var(--g-mt)}.top nav a:hover{color:var(--g-ik)}.top nav a:not(.keep){display:none}.hero{padding:2.5rem 0 3rem}.hero .wrap{display:grid;gap:2.5rem}.hero .wrap>*{min-width:0}.prompt{font-family:var(--g-fm);font-size:.85rem;color:var(--g-mt);display:flex;gap:.6ch;margin-bottom:1rem;white-space:nowrap}.prompt .path{color:var(--g-sg)}.prompt .cmd{display:inline-block;overflow:hidden;width:6ch;color:var(--g-ik);animation:type 1s steps(6) .3s both}@keyframes type{from{width:0}}.hero h1{font-size:clamp(2.6rem,16cqi,9rem);font-weight:800;line-height:.88;letter-spacing:-.045em}.hero h1 .line{display:block;white-space:nowrap}.cursor{display:inline-block;width:.42em;height:.78em;background:var(--g-am);margin-left:.06em;vertical-align:-.04em;animation:blink 1.1s steps(1) infinite}@keyframes blink{50%{opacity:0}}.lede{max-width:34rem;margin-top:1.25rem;font-size:1.06rem;line-height:1.5}.lede strong{font-weight:600}.status{display:flex;align-items:center;gap:.6rem;margin-top:1.25rem;font-family:var(--g-fm);font-size:.8rem;color:var(--g-mt)}.status::before{content:"";flex:none;width:9px;height:9px;border-radius:50%;background:#3FA35B;box-shadow:0 0 0 4px #3FA35B33}.ctas{display:flex;flex-direction:column;gap:.65rem;margin-top:1.75rem}.btn{display:flex;justify-content:center;padding:.85rem 1.2rem;font-family:var(--g-fm);font-size:.88rem;font-weight:600;text-decoration:none;border:2px solid var(--g-ik);transition:transform .15s,box-shadow .15s}.pg .btn{color:var(--g-ik)}.pg .btn-main{background:var(--g-ik);color:var(--g-bg)}.btn:hover{transform:translate(-3px,-3px);box-shadow:3px 3px 0 var(--g-am)}.btn:active{transform:none;box-shadow:none}.term{background:var(--g-tb);color:var(--g-ti);font-family:var(--g-fm);font-size:.72rem;line-height:1.7;border-radius:8px;overflow:hidden;box-shadow:6px 6px 0 var(--g-as);margin-right:6px}.term-bar{display:flex;align-items:center;gap:.4rem;padding:.6rem .8rem;border-bottom:1px solid #2A2F26}.term-bar i{width:10px;height:10px;border-radius:50%;background:#5FAF6E}.term-bar i:first-child{background:#D9634C}.term-bar i:nth-child(2){background:#E4B341}.term-bar span{margin-left:auto;color:var(--g-td);font-size:.7rem}.term-body{padding:.85rem .9rem 1rem;overflow-x:auto}.term-body p{white-space:pre}.t-dim{color:var(--g-td)}.t-amber{color:var(--g-ta)}.t-ok{color:var(--g-to)}.t-sig{color:var(--g-ts)}.t-you{font-weight:500}.term-cursor{display:inline-block;width:.6em;height:1.1em;background:var(--g-ti);vertical-align:-.2em;animation:blink 1.1s steps(1) infinite}.pg section{padding:3rem 0;border-top:1px solid var(--g-ln)}.sec-head{display:flex;align-items:baseline;justify-content:space-between;gap:.25rem 1rem;flex-wrap:wrap;margin-bottom:1.5rem}.pg h2{font-size:clamp(1.9rem,9cqi,3.4rem);font-weight:800;letter-spacing:-.035em;line-height:1}.sec-head .mono{font-size:.8rem;color:var(--g-mt)}.about{display:grid;gap:2rem}.about p{max-width:36rem}.about p+p{margin-top:1rem}.numbers{border-top:2px solid var(--g-ik)}.numbers div{padding:.9rem 0;border-bottom:1px solid var(--g-ln)}.numbers b{display:block;font-size:1.7rem;font-weight:800;letter-spacing:-.03em;line-height:1.1}.numbers span{color:var(--g-mt);font-size:.95rem}.stash{--g-u:80px;display:grid;grid-template-columns:repeat(4,1fr);grid-auto-rows:var(--g-u);grid-auto-flow:dense;gap:3px;padding:3px;background:var(--g-cl);border:2px solid var(--g-ik)}.item{position:relative;background:var(--g-ce);padding:.45rem .5rem;display:flex;flex-direction:column;justify-content:space-between;overflow:hidden;min-width:0}.item::after{content:"";position:absolute;inset:0;pointer-events:none;opacity:.35;background-image:linear-gradient(to right,var(--g-cl) 1px,transparent 1px),linear-gradient(to bottom,var(--g-cl) 1px,transparent 1px);background-size:var(--g-u) var(--g-u)}.item>*{position:relative;z-index:1}.item .name{font-weight:800;letter-spacing:-.02em;line-height:1.05;font-size:.92rem;overflow-wrap:anywhere}.item .note{font-family:var(--g-fm);font-size:.66rem;color:var(--g-mt);line-height:1.3}.item .slot{font-family:var(--g-fm);font-size:.62rem;color:var(--g-mt);line-height:1.2}.item.big .name{font-size:1.6rem}.item.mid .name{font-size:1.1rem}.item.hot{background:var(--g-as)}.item.hot .slot{color:var(--g-am);font-weight:600}.w2{grid-column:span 2}.w3{grid-column:span 3}.w4{grid-column:span 4}.h2{grid-row:span 2}.m2{grid-column:span 2}.empty{display:none}.stash-legend{display:flex;flex-wrap:wrap;gap:.5rem 1.25rem;margin-top:.9rem;font-family:var(--g-fm);font-size:.75rem;color:var(--g-mt)}.stash-legend span::before{content:"";display:inline-block;width:.8rem;height:.8rem;margin-right:.45rem;vertical-align:-.1rem;border:1px solid var(--g-cl);background:var(--g-ce)}.stash-legend .l-hot::before{background:var(--g-as)}.log{list-style:none;position:relative}.log::before{content:"";position:absolute;left:6px;top:.6rem;bottom:.6rem;width:2px;background:var(--g-ln)}.commit{position:relative;padding:0 0 2rem 1.9rem}.commit:last-child{padding-bottom:0}.commit::before{content:"";position:absolute;left:0;top:.4rem;width:14px;height:14px;border-radius:50%;background:var(--g-bg);border:3px solid var(--g-ik)}.commit.head::before{background:var(--g-am);border-color:var(--g-am)}.commit-meta{font-family:var(--g-fm);font-size:.76rem;color:var(--g-mt);display:flex;flex-wrap:wrap;gap:.3rem .8rem;align-items:center}.hash{color:var(--g-am);font-weight:600}.ref{border:1px solid var(--g-sg);color:var(--g-sg);padding:0 .4rem;border-radius:3px}.commit h3{font-size:clamp(1.3rem,6cqi,1.85rem);font-weight:800;letter-spacing:-.025em;line-height:1.15;margin:.3rem 0 .1rem}.commit .role{color:var(--g-mt);margin-bottom:.6rem;font-size:.95rem}.commit ul{list-style:none;max-width:44rem}.commit li{position:relative;padding-left:1.2rem;margin-top:.45rem;font-size:.97rem}.commit li::before{content:"+";position:absolute;left:0;font-family:var(--g-fm);color:#3FA35B;font-weight:600}.commit li b{font-weight:600}.off{display:grid;gap:1.75rem}.off article{padding-top:.9rem;border-top:2px solid var(--g-ik)}.off h3{font-size:1.35rem;font-weight:800;letter-spacing:-.02em;margin-bottom:.4rem}.off p{color:var(--g-mt);max-width:30rem}.off .mono{display:block;margin-top:.8rem;font-size:.76rem;color:var(--g-am)}section.contact{background:var(--g-ik);color:var(--g-bg);border-top:0}.contact h2{font-size:clamp(2.2rem,11cqi,5.5rem);max-width:14ch}.contact p{margin-top:1rem;max-width:34rem;opacity:.8}.pg .mail{display:inline-block;margin-top:1.5rem;font-family:var(--g-fm);font-weight:600;font-size:clamp(.9rem,4.4cqi,1.6rem);color:var(--g-bg);text-decoration:none;border-bottom:3px solid var(--g-am);padding-bottom:.2rem;overflow-wrap:anywhere}.pg .mail:hover{color:var(--g-am)}.links{display:flex;flex-wrap:wrap;gap:.75rem 1.5rem;margin-top:1.5rem;font-family:var(--g-fm);font-size:.85rem}.pg .links a{color:var(--g-bg);opacity:.75}.links a:hover{opacity:1}.pg footer{background:var(--g-ik);color:var(--g-bg);border-top:1px solid #8884}.pg footer .wrap{display:flex;flex-direction:column;gap:.3rem;padding-top:1.1rem;padding-bottom:1.3rem;font-family:var(--g-fm);font-size:.72rem;opacity:.6}@container (min-width:480px){.ctas{flex-direction:row;flex-wrap:wrap}.numbers div{display:grid;grid-template-columns:8.5rem 1fr;gap:1rem;align-items:baseline}.term{font-size:.8rem}}@container (min-width:640px){.top .wrap{height:64px}.top nav a:not(.keep){display:inline}.hero{padding:4.5rem 0 4rem}.pg section{padding:4.5rem 0}.sec-head{margin-bottom:2.25rem}.term{box-shadow:10px 10px 0 var(--g-as);margin-right:10px}.stash{--g-u:clamp(72px,9cqi,92px);grid-template-columns:repeat(8,1fr);gap:4px;padding:4px}.item{padding:.55rem .65rem}.item .slot{font-size:.68rem}.item .name{font-size:1.02rem}.item .note{font-size:.72rem}.item.big .name{font-size:clamp(1.6rem,4cqi,2.4rem)}.item.mid .name{font-size:1.3rem}.empty{display:block}.m2{grid-column:span 1}.commit{padding:0 0 2.5rem 2.4rem}.commit::before{width:16px;height:16px}.log::before{left:7px}.pg footer .wrap{flex-direction:row;justify-content:space-between}}@container (min-width:860px){.hero{padding:6rem 0 5rem}.hero .wrap{grid-template-columns:1.15fr .85fr;gap:3.5rem;align-items:end}.lede{font-size:1.25rem}.hero h1{font-size:min(9cqi,8.5rem)}.about{grid-template-columns:1fr 1fr;gap:4rem}.off{grid-template-columns:repeat(3,1fr);gap:2rem}.term{font-size:.84rem}}@media (prefers-reduced-motion:reduce){.pg *,.pg ::before,.pg ::after{animation:none!important;transition:none!important}html{scroll-behavior:auto}}</style>
</head>
<body>
<div class="pg">
<header class="top">
<div class="wrap">
<a class="brand" href="#inicio">gemente<span>.dev</span></a>
<nav aria-label="Seções">
<a href="#sobre">sobre</a>
<a href="#loadout">loadout</a>
<a href="#historico">histórico</a>
<a class="keep" href="#contato">contato</a>
</nav>
</div>
</header>
<main>
<div class="hero" id="inicio">
<div class="wrap">
<div>
<p class="prompt" aria-hidden="true"><span class="path">~/lavras-mg</span><span>$</span><span class="cmd">whoami</span></p>
<h1><span class="line">Gabriel</span><span class="line">Gemente<span class="cursor" aria-hidden="true"></span></span></h1>
<p class="lede">Dev full stack pleno. Escrevo <strong>PHP, Laravel, Node.js e Next.js</strong>, gosto de sistema que aguenta carga e uso IA no dia a dia pra entregar mais rápido sem abrir mão da qualidade.</p>
<p class="status">Full stack na Inovcorp, de Lavras pra Lisboa</p>
<div class="ctas">
<a class="btn btn-main" href="mailto:gabrielxgemente@gmail.com">Mandar um e-mail</a>
<a class="btn btn-ghost" href="https://github.com/ggemente" target="_blank" rel="noopener">Ver meu GitHub</a>
</div>
</div>
<div class="term" role="img" aria-label="Terminal mostrando uma sessão do Claude Code refatorando um listener Laravel e rodando os testes">
<div class="term-bar"><i></i><i></i><i></i><span>~/inovcorp/crm</span></div>
<div class="term-body">
<p><span class="t-sig">~/inovcorp/crm</span> <span class="t-dim">$</span> claude</p>
<p> </p>
<p><span class="t-amber">&gt;</span> <span class="t-you">move o sync de faturação pra fila</span></p>
<p><span class="t-you">  e escreve os testes do listener</span></p>
<p> </p>
<p><span class="t-dim">●</span> Lendo app/Listeners/InvoiceSync.php</p>
<p><span class="t-dim">●</span> Criando app/Jobs/SyncInvoiceJob.php</p>
<p><span class="t-dim">●</span> Atualizando EventServiceProvider</p>
<p><span class="t-dim">●</span> php artisan test</p>
<p>  <span class="t-ok">✓ 42 passed</span> <span class="t-dim">(3.1s)</span></p>
<p> </p>
<p><span class="t-amber">&gt;</span> <span class="t-you">beleza, agora eu reviso o diff</span> <span class="term-cursor"></span></p>
</div>
</div>
</div>
</div>
<section id="sobre">
<div class="wrap">
<div class="sec-head">
<h2>Sobre mim</h2>
<span class="mono">cat sobre.md</span>
</div>
<div class="about">
<div>
<p>Sou de Lavras, MG, e trabalho remoto para a Inovcorp, em Lisboa. No dia a dia eu cuido de tudo um pouco: API, front, banco, pipeline e aquela regra de negócio que ninguém documentou.</p>
<p>Curto arquitetura orientada a eventos, código que o próximo dev consegue ler e deploy que não dá frio na barriga. Uso o Claude Code como parceiro de trabalho: ele acelera implementação, refatoração e testes, e eu continuo responsável por revisar e decidir o que vai pra produção.</p>
<p>Estou terminando Sistemas de Informação na UFLA.</p>
</div>
<div class="numbers">
<div><b>600 mil+</b><span>registros num sistema que refatorei com eventos e integrações Azure</span></div>
<div><b>65+</b><span>endpoints numa API REST com OAuth 2.0 para operação logística</span></div>
<div><b>~1min30s</b><span>de deploy depois de migrar de FTP para SSH (antes eram 5–10 min)</span></div>
<div><b>3+ anos</b><span>entregando full stack em produção, sempre remoto</span></div>
</div>
</div>
</div>
</section>
<section id="loadout">
<div class="wrap">
<div class="sec-head">
<h2>Loadout</h2>
<span class="mono">o que eu levo pro raid</span>
</div>
<div class="stash" aria-label="Tecnologias que eu uso">
<div class="item big w4 h2 hot">
<span class="slot">primária</span>
<span class="name">Laravel + PHP</span>
<span class="note">events, listeners, observers, filas, APIs REST</span>
</div>
<div class="item mid w2 h2 hot">
<span class="slot">bolso</span>
<span class="name">Claude Code</span>
<span class="note">implementação, debug, refactor, testes</span>
</div>
<div class="item mid w2 h2">
<span class="slot">secundária</span>
<span class="name">Node.js + NestJS</span>
<span class="note">DDD, Clean Arch</span>
</div>
<div class="item mid w3">
<span class="slot">mira</span>
<span class="name">Next.js + React</span>
<span class="note">front que carrega rápido</span>
</div>
<div class="item w2">
<span class="name">TypeScript</span>
<span class="note">tipo tudo</span>
</div>
<div class="item">
<span class="name">Vue.js</span>
</div>
<div class="item w2">
<span class="name">OAuth 2.0</span>
<span class="note">autenticação</span>
</div>
<div class="item w2 hot">
<span class="slot">colete</span>
<span class="name">GitHub Actions</span>
<span class="note">CI/CD + SSH</span>
</div>
<div class="item w2">
<span class="name">Docker + AWS</span>
<span class="note">infra</span>
</div>
<div class="item w2">
<span class="name">MySQL + Postgres</span>
<span class="note">relacional</span>
</div>
<div class="item m2">
<span class="name">DynamoDB</span>
</div>
<div class="item">
<span class="name">Prisma</span>
</div>
<div class="item w2">
<span class="name">WebSockets</span>
<span class="note">chat em tempo real</span>
</div>
<div class="item">
<span class="name">Linux</span>
</div>
<div class="item w2">
<span class="name">Event Driven</span>
<span class="note">arquitetura</span>
</div>
<div class="item w2">
<span class="name">Tailwind + SCSS</span>
</div>
<div class="item empty" aria-hidden="true"></div>
</div>
<div class="stash-legend" aria-hidden="true">
<span class="l-hot">uso todo dia</span>
<span>uso quando o projeto pede</span>
</div>
</div>
</section>
<section id="historico">
<div class="wrap">
<div class="sec-head">
<h2>Histórico</h2>
<span class="mono">git log --graph</span>
</div>
<ol class="log">
<li class="commit head">
<div class="commit-meta"><span class="hash">a3f9c1e</span><span class="ref">HEAD -&gt; main</span><span>06/2025 até hoje</span></div>
<h3>Inovcorp</h3>
<p class="role">Full Stack Pleno, Lisboa (remoto)</p>
<ul>
<li>Refatorei um sistema com <b>600 mil+ registros</b> usando arquitetura orientada a eventos e APIs Azure.</li>
<li>Construí uma <b>API REST com 65+ endpoints</b>, OAuth 2.0 e vários bancos para operação logística.</li>
<li>Desenvolvi o CRM interno com chat em tempo real via WebSockets, boards de tarefas e agenda.</li>
<li>Criei um boilerplate com auto-discovery de relações e geração de CRUDs para novos projetos.</li>
<li>Migrei o deploy de FTP para SSH com GitHub Actions: de 5–10 min para <b>~1min30s</b>.</li>
<li>Uso IA para acelerar implementação, debugging e testes automatizados.</li>
</ul>
</li>
<li class="commit">
<div class="commit-meta"><span class="hash">7be20d4</span><span>02/2024 a 04/2024</span></div>
<h3>Dream On</h3>
<p class="role">Full Stack (remoto)</p>
<ul>
<li>Plataforma de venda de ingressos com Next.js, NestJS, Tailwind, Prisma e DynamoDB, aplicando DDD, Clean Architecture e SOLID.</li>
</ul>
</li>
<li class="commit">
<div class="commit-meta"><span class="hash">c41e8a9</span><span>03/2023 a 04/2025</span></div>
<h3>GAFIT</h3>
<p class="role">Full Stack (remoto)</p>
<ul>
<li>Sistema de credenciamento para o <b>Carnaval do Rio</b> com Next.js e NestJS, do levantamento de requisitos à entrega.</li>
<li>Marketplace e e-commerce de logística no Reino Unido com Laravel, JavaScript e SCSS.</li>
<li>Front responsivo e suporte técnico na Medicana, plataforma de saúde com cara de marketplace.</li>
</ul>
</li>
<li class="commit">
<div class="commit-meta"><span class="hash">0f12b37</span><span>2022 a 2026</span></div>
<h3>UFLA</h3>
<p class="role">Bacharelado em Sistemas de Informação, Lavras, MG</p>
</li>
</ol>
</div>
</section>
<section id="off">
<div class="wrap">
<div class="sec-head">
<h2>Fora do expediente</h2>
<span class="mono">git stash list</span>
</div>
<div class="off">
<article>
<h3>Tarkov</h3>
<p>Nas horas vagas sou PMC em Escape from Tarkov. O jogo me ensinou que planejar a extração vale mais que o loot. Serve pra deploy também.</p>
<span class="mono">// status da última raid: sobrevivi (às vezes)</span>
</article>
<article>
<h3>Jogos em geral</h3>
<p>Do competitivo ao jogo que dá pra largar no meio. Jogar é onde eu desligo a cabeça do trabalho e, de vez em quando, tenho a ideia que faltava.</p>
<span class="mono">// fila de jogos: maior que o backlog</span>
</article>
<article>
<h3>IA e Claude Code</h3>
<p>Gosto de testar ferramenta nova e entender como a IA muda o jeito de programar. O Claude Code virou parte do meu fluxo, do primeiro rascunho ao teste.</p>
<span class="mono">// a IA escreve, eu reviso</span>
</article>
</div>
</div>
</section>
<section class="contact" id="contato">
<div class="wrap">
<h2>Bora construir alguma coisa?</h2>
<p>Projeto, vaga, troca de ideia sobre arquitetura ou squad pra raid. Respondo rápido.</p>
<a class="mail" href="mailto:gabrielxgemente@gmail.com">gabrielxgemente@gmail.com</a>
<div class="links">
<a href="https://github.com/ggemente" target="_blank" rel="noopener">github.com/ggemente</a>
<a href="https://wa.me/5535998142009" target="_blank" rel="noopener">WhatsApp</a>
<span>Lavras, MG</span>
</div>
</div>
</section>
</main>
<footer>
<div class="wrap">
<span>// feito à mão com HTML e CSS puro, zero JavaScript</span>
<span>© 2026 Gabriel Gemente</span>
</div>
</footer>
</div>
</body>
</html>
