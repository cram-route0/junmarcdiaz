<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Complete Workout & Exercise Guide</title>
  <style>
    :root{--accent:#0b76ef;--muted:#6b7280;--card:#ffffff;--bg:#f3f4f6}
    html,body{height:100%;margin:0;font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;background:var(--bg);color:#111}
    .container{max-width:1000px;margin:32px auto;padding:20px}
    header{display:flex;align-items:center;gap:16px}
    h1{margin:0;font-size:1.6rem}
    p.lead{margin:6px 0;color:var(--muted)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:18px;margin-top:18px}
    .card{background:var(--card);border-radius:12px;padding:16px;box-shadow:0 6px 18px rgba(15,23,42,0.06)}
    nav ul{list-style:none;padding:0;margin:0;display:flex;gap:8px;flex-wrap:wrap}
    nav a{display:inline-block;padding:6px 10px;border-radius:8px;text-decoration:none;color:var(--accent);font-weight:600}
    section h2{margin-top:0}
    .exercise{border-left:4px solid var(--accent);padding:10px 12px;margin:12px 0;border-radius:8px;background:#fbfdff}
    ol.steps{padding-left:18px}
    .meta{font-size:0.9rem;color:var(--muted);margin-top:8px}
    aside h3{margin-top:0}
    footer{margin-top:20px;text-align:center;color:var(--muted);font-size:0.9rem}
    .badge{display:inline-block;background:#eff6ff;color:var(--accent);padding:6px 8px;border-radius:999px;font-weight:600;font-size:0.85rem}
    .muscles{font-weight:700}
    @media (max-width:900px){.grid{grid-template-columns:1fr;}.container{padding:12px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div>
        <h1>Complete Workout & Exercise Guide</h1>
        <p class="lead">A single-file HTML guide with exercises, step-by-step execution, muscle focus, equipment and practical recommendations.</p>
      </div>
      <div style="margin-left:auto">
        <span class="badge">HTML only • No scripts</span>
      </div>
    </header>

    <div class="grid">
      <main class="card">
        <section id="warmup">
          <h2>Warm-up (Always start here)</h2>
          <p class="meta">5–10 minutes — light cardio + dynamic mobility.</p>
          <ul>
            <li>Arm circles (30s each direction)</li>
            <li>Leg swings front-to-back and side-to-side (10 each leg)</li>
            <li>Hip circles, torso twists (30s each)</li>
            <li>Jumping jacks or brisk march (1–3 minutes)</li>
          </ul>
        </section>

        <section id="push-exercises">
          <h2>Push (Chest, shoulders, triceps)</h2>

          <article class="exercise" id="pushup">
            <h3>Push-up (Standard)</h3>
            <p class="meta"><span class="muscles">Main: Chest, triceps, anterior deltoid</span> • Equipment: none • Level: Beginner → Advanced (progressions)</p>
            <ol class="steps">
              <li>Start in a high plank: hands under shoulders, body in straight line from head to heels.</li>
              <li>Brace core and glutes, lower chest toward the floor by bending elbows to ~90°.</li>
              <li>Keep elbows at ~45° from the body (not flared straight out) and neck neutral.</li>
              <li>Push through palms to return to start. Exhale as you push up.</li>
            </ol>
            <p class="meta">Progressions: knee push-ups → incline push-ups → standard → decline → weighted.</p>
            <p class="meta">Common faults: sagging hips, flared elbows, incomplete range of motion.</p>
          </article>

          <article class="exercise">
            <h3>Diamond push-up</h3>
            <p class="meta"><span class="muscles">Main: Triceps, chest</span> • Equipment: none • Level: Intermediate</p>
            <ol class="steps">
              <li>Hands form a diamond under chest (thumbs and index fingers touching).</li>
              <li>Keep elbows close to the body as you lower to the hands.</li>
              <li>Drive back up while maintaining core tension.</li>
            </ol>
            <p class="meta">Tip: use a slightly wider diamond if wrist pain occurs.</p>
          </article>

          <article class="exercise">
            <h3>Archer push-up</h3>
            <p class="meta"><span class="muscles">Main: Chest (one-sided emphasis), triceps, shoulders</span> • Level: Advanced</p>
            <ol class="steps">
              <li>Start wider than normal push-up width.</li>
              <li>Shift weight to one arm while the other arm straightens out to the side; lower to the dominant side.</li>
              <li>Push back to center and repeat other side.</li>
            </ol>
          </article>

          <article class="exercise">
            <h3>Handstand push-up</h3>
            <p class="meta"><span class="muscles">Main: Shoulders, triceps, upper chest</span> • Equipment: wall optional • Level: Expert</p>
            <ol class="steps">
              <li>Practice wall-supported handstand holds first.</li>
              <li>From handstand, lower head toward floor with control; press back up to full extension.</li>
              <li>Keep core tight and neck neutral; spot with a wall as needed.</li>
            </ol>
            <p class="meta">Progressions: pike push-ups → elevated pike → partial ROM → full HS push-up.</p>
          </article>

        </section>

        <section id="pull-exercises">
          <h2>Pull (Back, biceps)</h2>

          <article class="exercise">
            <h3>Pull-up</h3>
            <p class="meta"><span class="muscles">Main: Lats, biceps, rear delts</span> • Equipment: pull-up bar • Level: Beginner→Advanced</p>
            <ol class="steps">
              <li>Grip bar slightly wider than shoulder width, hang with full extension.</li>
              <li>Pull chest toward the bar by driving elbows down and back until chin clears the bar.</li>
              <li>Lower with control back to full hang.</li>
            </ol>
            <p class="meta">Progressions: band-assisted → negatives → full reps → weighted.</p>
          </article>

          <article class="exercise">
            <h3>Inverted row (Australian pull-up)</h3>
            <p class="meta"><span class="muscles">Main: Upper back, biceps</span> • Equipment: low bar or table</p>
            <ol class="steps">
              <li>Set bar at waist height. Hang underneath with heels on ground and body straight.</li>
              <li>Pull chest to bar, squeeze shoulder blades, and lower slowly.</li>
            </ol>
          </article>

        </section>

        <section id="legs">
          <h2>Legs & Lower Body</h2>

          <article class="exercise">
            <h3>Pistol squat</h3>
            <p class="meta"><span class="muscles">Main: Quads, glutes, hamstrings</span> • Equipment: none • Level: Advanced</p>
            <ol class="steps">
              <li>Stand on one leg, extend the other leg forward.</li>
              <li>Slowly lower into a one-legged squat keeping chest up and knee tracking over toes.</li>
              <li>Drive through the heel to stand back up.</li>
            </ol>
            <p class="meta">Progressions: assisted pistols → box pistol → negative-only → full pistol.</p>
          </article>

          <article class="exercise">
            <h3>Bulgarian split squat</h3>
            <p class="meta"><span class="muscles">Main: Quads, glutes</span> • Equipment: bench or step</p>
            <ol class="steps">
              <li>Place rear foot on bench behind you. Keep torso upright and front knee over ankle.</li>
              <li>Lower until front thigh is near parallel, then drive up through front heel.</li>
            </ol>
          </article>

          <article class="exercise">
            <h3>Dips</h3>
            <p class="meta"><span class="muscles">Main: Triceps, chest</span> • Equipment: parallel bars or chairs</p>
            <ol class="steps">
              <li>Support yourself on bars with arms straight. Lean slightly forward for chest emphasis.</li>
              <li>Lower until elbows ~90°, then press back up.</li>
            </ol>
            <p class="meta">Use assisted version to build strength safely.</p>
          </article>

        </section>

        <section id="core">
          <h2>Core</h2>

          <article class="exercise">
            <h3>Plank</h3>
            <p class="meta"><span class="muscles">Main: Transverse abdominis, rectus abdominis, obliques</span> • Equipment: none</p>
            <ol class="steps">
              <li>Forearms on ground, body in straight line, braced core and glutes.</li>
              <li>Breathe steadily and hold for time. Avoid sagging hips or piking.</li>
            </ol>
            <p class="meta">Progressions: single-arm/leg raises, weighted planks.</p>
          </article>

          <article class="exercise">
            <h3>Elbow lever (advanced core & balance)</h3>
            <p class="meta">Practice progressively with tuck supports and assisted holds before attempting full lever.</p>
          </article>

        </section>

        <section id="skills">
          <h2>Calisthenics Skills</h2>
          <ul>
            <li>Pulls: build to one-arm pull-up with negatives and heavy eccentric work.</li>
            <li>Handstand: daily wall-supported practice, shoulder mobility and wrist conditioning.</li>
            <li>Planche & Levers: progressions include tuck, advanced tuck, straddle, full.</li>
          </ul>
        </section>

        <section id="conditioning">
          <h2>Conditioning & Cardio</h2>
          <p class="meta">Options: sprints, cycling, jump rope, circuit training (EMOM/AMRAP), HIIT.</p>
          <p class="meta">Keep sessions 10–40 minutes depending on goal; prioritize recovery if strength is the main focus.</p>
        </section>

        <section id="cooldown">
          <h2>Cooldown & Recovery</h2>
          <ul>
            <li>5–10 minutes light cardio to lower heart rate</li>
            <li>Static stretching focusing on muscles worked (30–60s per stretch)</li>
            <li>Hydration, sleep, and periodic deload weeks</li>
          </ul>
        </section>

        <section id="sample-programs">
          <h2>Sample Programs & Templates</h2>
          <article>
            <h4>Beginner (3 days/week, full-body)</h4>
            <ol>
              <li>Warm-up</li>
              <li>Push: 3×8–12 (push-ups or incline)</li>
              <li>Pull: 3×5–8 (inverted rows or assisted pull-ups)</li>
              <li>Legs: 3×8–12 (split squats or bodyweight squats)</li>
              <li>Core: plank 3×30–60s</li>
              <li>Cooldown</li>
            </ol>

            <h4>Intermediate (4 days — upper/lower split)</h4>
            <ol>
              <li>Upper A: push, pull, accessory (3–4 sets each)</li>
              <li>Lower A: squat pattern, hinge, calves</li>
              <li>Upper B: vertical push/pull emphasis</li>
              <li>Lower B: unilateral work, explosive element</li>
            </ol>
          </article>
        </section>

        <section id="faq">
          <h2>FAQ & Troubleshooting</h2>
          <p><strong>How often should I train?</strong> 3–5 times per week depending on goals and recovery ability.</p>
          <p><strong>What about soreness?</strong> Delayed onset muscle soreness (DOMS) is normal when increasing load — decrease volume/intensity if it prevents daily function.</p>
          <p><strong>How long until progress?</strong> Strength gains can start within 4–8 weeks; consistency and progressive overload matter most.</p>
        </section>

      </main>

      <aside class="card">
        <h3>Quick Links</h3>
        <nav>
          <ul>
            <li><a href="#warmup">Warm-up</a></li>
            <li><a href="#push-exercises">Push</a></li>
            <li><a href="#pull-exercises">Pull</a></li>
            <li><a href="#legs">Legs</a></li>
            <li><a href="#core">Core</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#sample-programs">Programs</a></li>
          </ul>
        </nav>

        <h3>Recommendations & Suggestions</h3>
        <ul>
          <li><strong>Start slow:</strong> learn movement patterns before adding volume.</li>
          <li><strong>Progress safely:</strong> increase load, reps or difficulty gradually (5–10% per week where sensible).</li>
          <li><strong>Prioritize form:</strong> quality of reps beats quantity; use mirrors or record yourself.</li>
          <li><strong>Frequency:</strong> train each muscle group ~2×/week for balanced progress.</li>
          <li><strong>Recovery:</strong> sleep 7–9 hours, hydrate, and include rest or active recovery days.</li>
          <li><strong>Nutrition:</strong> eat adequate protein (~1.6–2.2 g/kg if strength-focused) and maintain calorie balance according to goals.</li>
          <li><strong>Injury prevention:</strong> warm up, progress slowly, and seek professional help for pain that persists.</li>
        </ul>

        <h3>Safety Notes</h3>
        <p class="meta">If you have medical conditions, are pregnant, or have recent injuries, consult a healthcare professional before starting a new program.</p>

        <h3>Equipment Cheat Sheet</h3>
        <p class="meta">None: bodyweight only • Basic: pull-up bar, resistance bands, sturdy chair/bench • Optional: dumbbells, kettlebells, gym rings.</p>
      </aside>
    </div>

    <footer class="card">
      <p>Use this HTML file as a printable guide or a quick on-screen reference. Train smart, stay consistent, and enjoy the process.</p>
    </footer>
  </div>
</body>
</html>
