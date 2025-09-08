<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>InterviewHub • Ke Xu</title>
  <meta name="description" content="Curated UK interview resources for Consulting, Finance, Tech, Big 4, Graduate Schemes, and Public Sector. Clean, fast, and no fluff." />
  <link rel="icon" href="https://fav.farm/%F0%9F%8E%AF" />
  <style>
    :root { --bg:#0b1220; --card:#0f172a; --muted:#93a4bf; --ring:#1f2a44; }
    html { scroll-behavior: smooth; }
    body { background: var(--bg); font-family: system-ui, -apple-system, Segoe UI, Roboto, sans-serif; margin:0; padding:0; line-height:1.6; }
    h1,h2,h3,p,a,li { color:#e5ecff; }
    a { text-decoration:none; }
    .badge { display:inline-block; padding:.18rem .5rem; border-radius:9999px; font-size:.8rem;
      background:rgba(59,130,246,.15); color:#cfe1ff; border:1px solid rgba(59,130,246,.35); }
    .card { border:1px solid var(--ring); border-radius:16px; padding:18px 18px 14px;
      background:var(--card); box-shadow:0 10px 30px rgba(0,0,0,.2); margin:14px 0; }
    .card h2 { margin-top:.2rem; }
    .linklist a { display:flex; align-items:center; gap:.5rem; padding:.55rem .7rem; border-radius:12px;
      border:1px solid var(--ring); background:#0b1328; transition:.15s ease; font-size:0.95rem; }
    .linklist a:hover { transform: translateY(-1px); border-color:#2f4473; background:#0d1933; }
    .mono { font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace; }
    .chips { display:flex; flex-wrap:wrap; gap:.5rem; margin:.5rem 0 0; }
    .chip { display:inline-flex; gap:.5rem; padding:.6rem .9rem; border-radius:12px; border:1px solid var(--ring);
      background:#0b1328; color:#e5ecff; font-weight:500; cursor:default; }
    .header { border:1px solid var(--ring); border-radius:18px; padding:22px; margin:20px auto; max-width:900px;
      background:linear-gradient(180deg,#0f1830,#0c1326); }
    .small { color:var(--muted); font-size:.95rem; }
    main { max-width:900px; margin:0 auto; padding:20px; }
    footer { text-align:center; margin:30px auto; font-size:.9rem; color:#93a4bf; }
  </style>
</head>
<body>
  <main>
    <div class="header">
      <h1>🎯 InterviewHub</h1>
      <p class="small">Your one-stop page for mastering job interviews in the UK & beyond. Curated links, no fluff.</p>
      <div class="chips">
        <span class="chip">🧠 Consulting</span>
        <span class="chip">💼 Finance/IB</span>
        <span class="chip">🧩 Tech/PM/BA</span>
        <span class="chip">📊 Big 4</span>
        <span class="chip">🎓 Grad Schemes</span>
        <span class="chip">🏛️ Public Sector</span>
      </div>
      <p class="small" style="margin-top:.7rem;">Maintained by <strong>Ke Xu</strong> · <a href="https://xke1.github.io/contact-hub/" target="_blank" rel="noopener noreferrer">Contact</a></p>
    </div>

    <section class="card" id="consulting">
      <h2>🧠 Consulting <span class="badge mono">case • fit • math</span></h2>
      <p class="small">Case interviews (MBB/strategy). Start with one structured course plus daily mock practice.</p>
      <div class="linklist">
        <a href="https://www.casecoach.com/" target="_blank" rel="noopener noreferrer">🧭 CaseCoach — structured training used by top UK schools</a>
        <a href="https://www.preplounge.com/" target="_blank" rel="noopener noreferrer">🤝 PrepLounge — peer mock interviews and mental math tools</a>
        <a href="https://www.caseinterview.com/" target="_blank" rel="noopener noreferrer">📚 Victor Cheng — free frameworks and drills</a>
        <a href="https://www.hackingthecaseinterview.com/" target="_blank" rel="noopener noreferrer">🧩 Hacking the Case — 50+ categorized cases</a>
        <a href="https://www.thecasecentre.org/" target="_blank" rel="noopener noreferrer">🏫 The Case Centre — real business school cases</a>
      </div>
    </section>

    <section class="card" id="finance">
      <h2>💼 Finance / Investment Banking <span class="badge mono">accounting • valuation</span></h2>
      <p class="small">Technical and behavioural. Focus on accounting, three statements, DCF, comps, and LBO logic.</p>
      <div class="linklist">
        <a href="https://breakingintowallstreet.com/" target="_blank" rel="noopener noreferrer">📈 Breaking Into Wall Street — premium technicals</a>
        <a href="https://mergersandinquisitions.com/" target="_blank" rel="noopener noreferrer">📰 Mergers & Inquisitions — free guides</a>
        <a href="https://www.wallstreetoasis.com/" target="_blank" rel="noopener noreferrer">💬 Wall Street Oasis — forums and interview experiences</a>
      </div>
    </section>

    <section class="card" id="tech">
      <h2>🧩 Tech / Product / Business Roles <span class="badge mono">BA • Strategy • PM • SWE</span></h2>
      <p class="small">Mix of case, behavioural, and technical (SQL/Python for analytics; product/system sense for PM).</p>
      <div class="linklist">
        <a href="https://leetcode.com/" target="_blank" rel="noopener noreferrer">🧮 LeetCode — coding and algorithms</a>
        <a href="https://www.tryexponent.com/" target="_blank" rel="noopener noreferrer">🧭 Exponent — PM/tech structured prep</a>
        <a href="https://interviewing.io/" target="_blank" rel="noopener noreferrer">🎙️ interviewing.io — anonymous mock interviews</a>
        <a href="https://www.glassdoor.com/" target="_blank" rel="noopener noreferrer">🔍 Glassdoor — interview reviews</a>
      </div>
    </section>

    <section class="card" id="big4">
      <h2>📊 Big 4 (Audit / Tax / Advisory) <span class="badge mono">SJT • video • AC</span></h2>
      <p class="small">Common UK flow: online tests → video interview → assessment centre.</p>
      <div class="linklist">
        <a href="https://www.assessmentday.co.uk/" target="_blank" rel="noopener noreferrer">🧪 AssessmentDay — UK SJT / numerical / logical</a>
        <a href="https://www.jobtestprep.co.uk/" target="_blank" rel="noopener noreferrer">🧰 JobTestPrep — aptitude tests library</a>
        <a href="https://www.pwc.co.uk/careers.html" target="_blank" rel="noopener noreferrer">PwC</a> ·
        <a href="https://home.kpmg/uk/en/home/careers.html" target="_blank" rel="noopener noreferrer">KPMG</a> ·
        <a href="https://www.ey.com/en_uk/careers" target="_blank" rel="noopener noreferrer">EY</a> ·
        <a href="https://www2.deloitte.com/uk/en/careers.html" target="_blank" rel="noopener noreferrer">Deloitte</a>
      </div>
    </section>

    <section class="card" id="grads">
      <h2>🎓 Graduate Schemes <span class="badge mono">multi-stage • competitive</span></h2>
      <p class="small">General graduate programmes across industries (FMCG, energy, retail, banks, transport).</p>
      <div class="linklist">
        <a href="https://www.prospects.ac.uk/careers-advice/getting-a-job/graduate-schemes" target="_blank" rel="noopener noreferrer">🎯 Prospects — official UK guidance</a>
        <a href="https://targetjobs.co.uk/" target="_blank" rel="noopener noreferrer">🎛️ TargetJobs — STAR and tricky questions</a>
        <a href="https://www.grb.uk.com/careers-advice/graduate-interviews" target="_blank" rel="noopener noreferrer">🧩 GRB — behavioural frameworks</a>
        <a href="https://www.savethestudent.org/student-jobs/graduate-training-schemes-2011.html" target="_blank" rel="noopener noreferrer">📋 SaveTheStudent — scheme lists</a>
      </div>
    </section>

    <section class="card" id="public">
      <h2>🏛️ Civil Service / Public Sector <span class="badge mono">behaviour • group</span></h2>
      <p class="small">Civil Service Fast Stream and NGOs: situational judgement, written exercises, group discussion.</p>
      <div class="linklist">
        <a href="https://www.faststream.gov.uk/" target="_blank" rel="noopener noreferrer">🏛️ Fast Stream — official portal and process</a>
        <a href="https://www.interviewgold.com/advice/graduate-interview-questions-and-answers/" target="_blank" rel="noopener noreferrer">🟨 InterviewGold — civil service questions</a>
        <a href="https://www.assessmentday.co.uk/" target="_blank" rel="noopener noreferrer">🧪 AssessmentDay — SJT and group exercises</a>
      </div>
    </section>

    <section class="card">
      <h2>🧠 General Interview Skills</h2>
      <div class="linklist">
        <a href="https://targetjobs.co.uk/careers-advice/interviews-and-assessment-centres/top-nine-tricky-interview-questions-and-how-answer-them" target="_blank" rel="noopener noreferrer">🧩 TargetJobs — tricky questions</a>
        <a href="https://www.grb.uk.com/careers-advice/graduate-interviews" target="_blank" rel="noopener noreferrer">🧭 GRB — STAR / SAFW techniques</a>
        <a href="https://www.theguardian.com/money/article/2024/aug/29/uk-graduates-struggle-job-market" target="_blank" rel="noopener noreferrer">📉 The Guardian — UK grad job market</a>
        <a href="https://www.thetimes.co.uk/article/a-thousand-applications-to-get-a-job-the-graduate-grind-c6hkm8nv9" target="_blank" rel="noopener noreferrer">📈 The Times — the grad grind</a>
      </div>
    </section>

    <footer>
      <p>🚀 Found something great? Open a PR or message me:
        <a href="https://xke1.github.io/contact-hub/" target="_blank" rel="noopener noreferrer">Contact Ke Xu</a>.
      </p>
    </footer>
  </main>
</body>
</html>
