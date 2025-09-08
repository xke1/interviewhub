<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>InterviewHub • Ke Xu</title>
  <style>
    :root { --bg:#0b1220; --card:#0f172a; --muted:#93a4bf; --accent:#3b82f6; --ring:#1f2a44;}
    body { background: var(--bg); font-family: system-ui, -apple-system, Segoe UI, Roboto, sans-serif; margin:0; padding:0; line-height:1.6;}
    h1,h2,h3,p,a,li { color:#e5ecff; }
    a { text-decoration:none; }
    .badge { display:inline-block; padding:.18rem .5rem; border-radius:9999px; font-size:.8rem;
      background:rgba(59,130,246,.15); color:#cfe1ff; border:1px solid rgba(59,130,246,.35);}
    .card { border:1px solid var(--ring); border-radius:16px; padding:18px 18px 14px;
      background:var(--card); box-shadow:0 10px 30px rgba(0,0,0,.2); margin:14px 0;}
    .card h2 { margin-top:.2rem; }
    .grid { display:grid; grid-template-columns:1fr; gap:14px; }
    @media (min-width: 880px){ .grid{ grid-template-columns: repeat(2, minmax(0,1fr)); } }
    .linklist a{ display:flex; align-items:center; gap:.5rem; padding:.55rem .7rem; border-radius:12px;
      border:1px solid var(--ring); background:#0b1328; transition:.15s ease; font-size:0.95rem;}
    .linklist a:hover{ transform: translateY(-1px); border-color:#2f4473; background:#0d1933;}
    .mono { font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace; }
    .cta { display:inline-flex; gap:.5rem; padding:.6rem .9rem; border-radius:12px; border:1px solid var(--ring);
      background:#0b1328; margin:4px; }
    .header { border:1px solid var(--ring); border-radius:18px; padding:22px; margin:20px auto; max-width:900px;
      background:linear-gradient(180deg,#0f1830,#0c1326); }
    .small { color:var(--muted); font-size:.95rem; }
    hr { border-color:#1a2541; margin:30px 0; }
    main { max-width:900px; margin:0 auto; padding:20px;}
  </style>
</head>
<body>
  <main>
    <div class="header">
      <h1>🎯 InterviewHub</h1>
      <p class="small">Your one-stop page for mastering job interviews in the UK & beyond. Curated links, no fluff.</p>
      <p>
        <a class="cta" href="#consulting">🧠 Consulting</a>
        <a class="cta" href="#finance">💼 Finance/IB</a>
        <a class="cta" href="#tech">🧩 Tech/PM/BA</a>
        <a class="cta" href="#big4">📊 Big 4</a>
        <a class="cta" href="#grads">🎓 Grad Schemes</a>
        <a class="cta" href="#public">🏛️ Public Sector</a>
      </p>
      <p class="small">Maintained by <strong>Ke Xu</strong> · <a href="https://xke1.github.io/contact-hub/">Contact</a></p>
    </div>

    <section id="consulting" class="card">
      <h2>🧠 Consulting <span class="badge mono">case • fit • math</span></h2>
      <p class="small">Case interviews (MBB/strategy). Start with one structured course + daily mock practice.</p>
      <div class="linklist">
        <a href="https://www.casecoach.com/">🧭 CaseCoach — structured training used by top UK schools</a>
        <a href="https://www.preplounge.com/">🤝 PrepLounge — peer mock interviews + mental math tools</a>
        <a href="https://www.caseinterview.com/">📚 Victor Cheng — free frameworks & drills</a>
        <a href="https://www.hackingthecaseinterview.com/">🧩 Hacking the Case — 50+ categorized cases</a>
        <a href="https://www.thecasecentre.org/">🏫 The Case Centre — real business school cases</a>
      </div>
    </section>

    <section id="finance" class="card">
      <h2>💼 Finance / Investment Banking <span class="badge mono">accounting • valuation</span></h2>
      <p class="small">Technical + behavioural. Focus on accounting, 3 statements, DCF, comps, LBO logic.</p>
      <div class="linklist">
        <a href="https://breakingintowallstreet.com/">📈 Breaking Into Wall Street — premium technicals</a>
        <a href="https://mergersandinquisitions.com/">📰 Mergers & Inquisitions — free guides</a>
        <a href="https://www.wallstreetoasis.com/">💬 WSO — forums & interview experiences</a>
      </div>
    </section>

    <section id="tech" class="card">
      <h2>🧩 Tech / Product / Business Roles <span class="badge mono">BA • Strategy • PM • SWE</span></h2>
      <p class="small">Case + behavioural + technical (SQL/Python for analytics; product/system sense for PM).</p>
      <div class="linklist">
        <a href="https://leetcode.com/">🧮 LeetCode — coding & algorithms</a>
        <a href="https://www.tryexponent.com/">🧭 Exponent — PM/tech structured prep</a>
        <a href="https://interviewing.io/">🎙️ interviewing.io — anonymous mock interviews</a>
        <a href="https://www.glassdoor.com/">🔍 Glassdoor — interview reviews</a>
      </div>
    </section>

    <section id="big4" class="card">
      <h2>📊 Big 4 (Audit / Tax / Advisory) <span class="badge mono">SJT • video • AC</span></h2>
      <p class="small">UK最常见流程：online tests ➜ video interview ➜ assessment centre.</p>
      <div class="linklist">
        <a href="https://www.assessmentday.co.uk/">🧪 AssessmentDay — UK SJT / numerical / logical</a>
        <a href="https://www.jobtestprep.co.uk/">🧰 JobTestPrep — aptitude tests library</a>
        <a href="https://www.pwc.co.uk/careers.html">PwC</a> · 
        <a href="https://home.kpmg/uk/en/home/careers.html">KPMG</a> · 
        <a href="https://www.ey.com/en_uk/careers">EY</a> · 
        <a href="https://www2.deloitte.com/uk/en/careers.html">Deloitte</a>
      </div>
    </section>

    <section id="grads" class="card">
      <h2>🎓 Graduate Schemes <span class="badge mono">multi-stage • competitive</span></h2>
      <p class="small">General graduate programmes across industries (FMCG, energy, retail, banks, transport).</p>
      <div class="linklist">
        <a href="https://www.prospects.ac.uk/careers-advice/getting-a-job/graduate-schemes">🎯 Prospects — official UK guidance</a>
        <a href="https://targetjobs.co.uk/">🎛️ TargetJobs — STAR & tricky Qs</a>
        <a href="https://www.grb.uk.com/careers-advice/graduate-interviews">🧩 GRB — behavioural frameworks</a>
        <a href="https://www.savethestudent.org/student-jobs/graduate-training-schemes-2011.html">📋 SaveTheStudent — scheme lists</a>
        <a href="https://blogs.lse.ac.uk/management/2024/09/12/how-to-prepare-for-graduate-scheme-applications/">📝 LSE Blog — uni-specific tips</a>
      </div>
    </section>

    <section id="public" class="card">
      <h2>🏛️ Civil Service / Public Sector <span class="badge mono">behaviour • group</span></h2>
      <p class="small">Civil Service Fast Stream & NGOs: situational judgement, written, group discussion.</p>
      <div class="linklist">
        <a href="https://www.faststream.gov.uk/">🏛️ Fast Stream — official portal & process</a>
        <a href="https://www.interviewgold.com/advice/graduate-interview-questions-and-answers/">🟨 InterviewGold — civil service Qs</a>
        <a href="https://www.assessmentday.co.uk/">🧪 AssessmentDay — SJT & group exercises</a>
      </div>
    </section>

    <section class="card">
      <h2>🧠 General Interview Skills</h2>
      <div class="linklist">
        <a href="https://targetjobs.co.uk/careers-advice/interviews-and-assessment-centres/top-nine-tricky-interview-questions-and-how-answer-them">🧩 TargetJobs — tricky questions</a>
        <a href="https://www.grb.uk.com/careers-advice/graduate-interviews">🧭 GRB — STAR / SAFW techniques</a>
        <a href="https://www.theguardian.com/money/article/2024/aug/29/uk-graduates-struggle-job-market">📉 Guardian — UK grad job market</a>
        <a href="https://www.thetimes.co.uk/article/a-thousand-applications-to-get-a-job-the-graduate-grind-c6hkm8nv9">📈 The Times — the grad grind</a>
      </div>
    </section>

    <footer style="text-align:center; margin:30px auto; font-size:.9rem; color:#93a4bf;">
      <p>🚀 Found something great? Open a PR or message me: 
        <a href="https://xke1.github.io/contact-hub/">Contact Ke Xu</a>.
      </p>
    </footer>
  </main>
</body>
</html>


