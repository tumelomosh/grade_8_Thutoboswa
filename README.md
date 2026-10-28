<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#0d2340">
<title>Grade 8 Robotics & Technology | Olympiad Sparring Arena</title>
<style>
:root{--navy:#0d2340;--blue:#1769aa;--sky:#8ed8ff;--ice:#eef8ff;--white:#fff;--ink:#182536;--muted:#63748a;--green:#13845b;--red:#b93838;--gold:#f4bd50;--line:#d8e5ef;--shadow:0 12px 32px #09213b14}
*{box-sizing:border-box}body{margin:0;background:#f3f8fc;color:var(--ink);font-family:Inter,Segoe UI,Arial,sans-serif;line-height:1.5}
header{background:linear-gradient(125deg,#0d2340,#155b91);color:white;padding:24px 18px 30px}
.wrap{max-width:1020px;margin:auto}.topline{display:flex;align-items:center;justify-content:space-between;gap:12px;flex-wrap:wrap}
.brand{font-size:.85rem;font-weight:800;letter-spacing:.12em;text-transform:uppercase;color:#b9e8ff}
.pill{border:1px solid #ffffff55;border-radius:999px;padding:5px 10px;font-size:.78rem}
h1{font-size:clamp(1.8rem,5vw,3rem);line-height:1.08;margin:24px 0 12px;max-width:750px}
header p{color:#e2f4ff;max-width:720px;margin:0}
main{max-width:1020px;margin:-14px auto 40px;padding:0 16px}
.nav{display:flex;gap:8px;flex-wrap:wrap;background:white;padding:10px;border-radius:15px;box-shadow:var(--shadow);margin-bottom:18px}
.nav button{border:0;background:transparent;padding:10px 13px;border-radius:10px;font-weight:750;color:var(--navy);cursor:pointer}
.nav button.active{background:var(--navy);color:white}
.panel{background:white;border:1px solid var(--line);border-radius:18px;padding:clamp(16px,3vw,28px);box-shadow:var(--shadow);margin-bottom:16px}
h2{margin:0 0 8px;font-size:1.45rem;color:var(--navy)}h3{margin:0 0 6px;color:var(--navy)}
.muted{color:var(--muted)}.grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:12px;margin:18px 0}
.stat{padding:15px;background:var(--ice);border-radius:13px}.stat strong{display:block;font-size:1.35rem;color:var(--navy)}
.actions{display:flex;gap:10px;flex-wrap:wrap;margin-top:18px}
button,.btn{font:inherit;cursor:pointer}.primary,.secondary,.danger{border:0;border-radius:11px;padding:12px 16px;font-weight:800}
.primary{background:var(--blue);color:white}.primary:hover{background:#0d528b}
.secondary{background:#eaf5fd;color:var(--navy);border:1px solid #c7e5f7}.danger{background:#fff0f0;color:#8b2020;border:1px solid #f1caca}
label{display:block;font-weight:700;margin:14px 0 6px}select,input[type=text]{width:100%;padding:12px;border:1px solid #cbd9e5;border-radius:10px;background:white;font:inherit}
.topic-list{display:flex;gap:7px;flex-wrap:wrap;margin-top:12px}.topic{background:#edf7ff;color:#174e78;border-radius:999px;padding:5px 10px;font-size:.85rem}
.question-top{display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap;align-items:center}
.progress{height:8px;background:#e8eff5;border-radius:99px;overflow:hidden;margin:13px 0 20px}.progress div{height:100%;width:0;background:var(--sky);transition:width .2s}
.qtext{font-size:1.18rem;font-weight:800;margin:16px 0}
.options{display:grid;gap:10px}
.option{display:flex;align-items:flex-start;gap:10px;text-align:left;width:100%;border:1.5px solid var(--line);background:white;border-radius:12px;padding:13px;color:var(--ink)}
.option:hover{border-color:var(--blue);background:#f7fbff}.option.selected{border-color:var(--blue);background:#eaf6ff}.option.correct{border-color:#55b993;background:#e9fbf3}.option.wrong{border-color:#e4a1a1;background:#fff0f0}
.letter{flex:0 0 28px;height:28px;display:grid;place-items:center;border-radius:8px;background:#edf2f7;font-weight:900;color:var(--navy)}
.feedback{padding:14px;border-radius:12px;margin-top:14px}.feedback.good{background:#e9fbf3;border:1px solid #b5e8d2}.feedback.bad{background:#fff3e8;border:1px solid #f0d1ae}
.hidden{display:none!important}.timer{font-variant-numeric:tabular-nums;font-weight:900;color:var(--navy);background:#eaf5fd;padding:7px 11px;border-radius:9px}
.result-score{font-size:3rem;font-weight:900;color:var(--blue);line-height:1.1}.result-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:12px;margin-top:18px}
.mini{border:1px solid var(--line);border-radius:12px;padding:14px}.mini strong{display:block;color:var(--navy)}
details{border-bottom:1px solid var(--line);padding:13px 0}summary{cursor:pointer;font-weight:800;color:var(--navy)}details p{margin-bottom:0}
footer{text-align:center;color:var(--muted);padding:22px 16px;font-size:.88rem}
.notice{background:#fff8e8;border:1px solid #f1dda9;padding:12px 14px;border-radius:12px;font-size:.92rem}
@media(max-width:650px){.grid{grid-template-columns:1fr}.result-grid{grid-template-columns:1fr}.nav button{flex:1}.panel{border-radius:14px}}
</style>
</head>
<body>
<header><div class="wrap">
  <div class="topline"><div class="brand">⚡ Olympiad Sparring Arena</div><div class="pill">GRADE 8 • CAPS-ALIGNED PRACTICE</div></div>
  <h1>Think like a coder.<br>Build like an engineer.</h1>
  <p>Train your logic, robotics knowledge and digital judgement. Practise, learn from mistakes, then take on the timed challenge.</p>
</div></header>
<main>
  <nav class="nav" aria-label="Main navigation">
    <button class="active" data-tab="home">Home</button><button data-tab="practice">Practice</button><button data-tab="challenge">Timed challenge</button><button data-tab="guide">Quick revision</button>
  </nav>
  <section id="home" class="panel">
    <h2>Welcome, Olympian 👋</h2>
    <p>Strong competitors do not just memorise definitions. They trace instructions carefully, test ideas, spot errors and explain why an answer works.</p>
    <div class="grid">
      <div class="stat"><strong>30</strong><span>practice questions</span></div>
      <div class="stat"><strong>10 min</strong><span>timed challenge</span></div>
      <div class="stat"><strong>Instant</strong><span>feedback and explanations</span></div>
    </div>
    <h3>Training route</h3>
    <div class="topic-list"><span class="topic">Algorithms & logic</span><span class="topic">Robotics components</span><span class="topic">Computing devices</span><span class="topic">Sensors & control</span><span class="topic">Digital citizenship</span><span class="topic">Networks & applications</span></div>
    <div class="actions"><button class="primary" onclick="showTab('practice')">Start practice →</button><button class="secondary" onclick="showTab('challenge')">Take the timed challenge</button></div>
    <p class="muted" style="font-size:.88rem;margin-top:16px">This is an independent revision resource, not an official Olympiad paper. The actual competition may cover additional topics or use a different format.</p>
  </section>
  <section id="practice" class="panel hidden">
    <h2>Practice mode</h2><p class="muted">Choose a topic. You can answer at your own pace and learn after every question.</p>
    <label for="topicSelect">Training topic</label>
    <select id="topicSelect">
      <option value="all">Mixed practice (all topics)</option><option value="Algorithms & logic">Algorithms & logic</option><option value="Robotics components">Robotics components</option><option value="Computing devices">Computing devices</option><option value="Sensors & control">Sensors & control</option><option value="Digital citizenship">Digital citizenship</option><option value="Networks & applications">Networks & applications</option>
    </select>
    <div class="actions"><button class="primary" id="startPractice">Begin practice</button></div>
    <div id="practiceQuiz" class="hidden"></div>
  </section>
  <section id="challenge" class="panel hidden">
    <h2>Timed Olympiad challenge</h2><p>Answer 15 mixed questions in 10 minutes. Try not to guess too quickly: read every option carefully.</p>
    <div class="notice">Challenge rules: one point per correct answer; no penalty for an incorrect answer. The timer starts when you begin.</div>
    <div class="actions"><button class="primary" id="startChallenge">Start 10-minute challenge</button></div>
    <div id="challengeQuiz" class="hidden"></div>
  </section>
  <section id="guide" class="panel hidden">
    <h2>Quick revision deck</h2><p class="muted">Review these ideas before attempting the challenge.</p>
    <details open><summary>1. Computational thinking</summary><p><b>Decomposition:</b> break a large problem into smaller parts. <b>Pattern recognition:</b> find similarities. <b>Abstraction:</b> focus on relevant information. <b>Algorithm:</b> an ordered set of steps to solve a problem.</p></details>
    <details><summary>2. Sequence, repetition and selection</summary><p><b>Sequence</b> runs instructions in order. <b>Repetition/loop</b> repeats instructions. <b>Selection/condition</b> chooses what happens based on a test, such as IF an obstacle is detected, THEN stop.</p></details>
    <details><summary>3. The input–process–output model</summary><p><b>Input</b> is data entering a system; <b>processing</b> is what the system does with data; <b>output</b> is the result; <b>storage</b> keeps data for later use. Example: a sensor measures light, a controller compares it with a threshold, and a lamp turns on.</p></details>
    <details><summary>4. Robot components</summary><p><b>Sensor:</b> detects or measures something. <b>Controller:</b> interprets input and coordinates actions. <b>Actuator:</b> creates physical action, such as a motor moving a wheel. <b>Power source:</b> supplies energy. A microcontroller is a small programmable controller used in embedded systems.</p></details>
    <details><summary>5. Computers and robots</summary><p>A computer is a device that processes data according to instructions. A robot is a programmable machine that can sense, process information and act in the physical or digital world. They overlap, but not every computer is a robot and not every robot looks human.</p></details>
    <details><summary>6. Digital citizenship and safety</summary><p>Protect passwords, avoid sharing personal details publicly, check links before opening them, report suspicious messages, respect others online and think about your digital footprint. A password or one-time code should not be shared with someone who contacts you unexpectedly.</p></details>
    <details><summary>7. Networks and the web</summary><p>A network connects devices so they can communicate or share resources. A router directs traffic between networks; a modem connects to an internet service over the provider's access link. The internet is a global network of networks; the World Wide Web is one service that uses the internet.</p></details>
    <details><summary>8. Online test strategy</summary><p>Read the question stem first. Identify words like <i>best</i>, <i>first</i>, <i>NOT</i> and <i>most likely</i>. Eliminate clearly wrong options. For code questions, trace each instruction in order. Keep an eye on time, but do not sacrifice accuracy by rushing.</p></details>
    <div class="actions"><button class="primary" onclick="showTab('practice')">Test what you know</button></div>
  </section>
</main>
<footer>Built for learning and repeated practice • Save this HTML file and open it in a browser, even when offline.</footer>
<script>
const questions = [
{t:"Algorithms & logic",q:"A learner is designing instructions for a robot to travel from a start point to a desk. What should an algorithm provide?",o:["A random collection of actions","A clear sequence of steps to reach the goal","Only a list of robot parts","A picture with no instructions"],a:1,e:"An algorithm is an ordered, unambiguous set of instructions for solving a problem."},
{t:"Algorithms & logic",q:"A robot repeats 'move forward' four times. Which programming idea is being used?",o:["Selection","Storage","Repetition or a loop","Authentication"],a:2,e:"A loop repeats a command or group of commands, reducing the need to write the same instruction repeatedly."},
{t:"Algorithms & logic",q:"IF the distance sensor detects an obstacle, THEN stop the motors. This is an example of…",o:["A conditional decision","A power source","A spreadsheet formula","A digital footprint"],a:0,e:"The action depends on a condition being true, so this is selection/conditional logic."},
{t:"Algorithms & logic",q:"A programme should turn a light on, wait two seconds, then turn it off. Which order is correct?",o:["Off → on → wait","Wait → off → on","On → wait → off","On and off at exactly the same time"],a:2,e:"Sequence matters: first turn on, then wait, then turn off."},
{t:"Algorithms & logic",q:"Breaking a large task such as building a smart garden into sensing, watering and alert tasks is called…",o:["Decomposition","Phishing","Formatting","Actuation"],a:0,e:"Decomposition divides a complex problem into manageable sub-problems."},
{t:"Algorithms & logic",q:"A robot should turn left at every junction where the floor marker is blue. What information is essential to the decision?",o:["The robot's colour","Whether the marker is blue","The name of the learner","The price of the robot"],a:1,e:"The condition must use relevant information: whether the marker is blue."},
{t:"Algorithms & logic",q:"A robot should move forward 3 steps, turn right, then move forward 2 steps. If the turn instruction is accidentally placed first, what is the likely issue?",o:["The sequence may lead to a different route","The battery gains power","The sensor becomes storage","The algorithm becomes a password"],a:0,e:"Changing instruction order can change the robot's behaviour and route."},
{t:"Algorithms & logic",q:"What is debugging?",o:["Decorating a robot","Finding and correcting errors in a programme","Deleting all saved work","Increasing internet speed"],a:1,e:"Debugging means identifying, tracing and fixing errors."},
{t:"Robotics components",q:"Which component detects an obstacle without physically touching it?",o:["Wheel","Ultrasonic distance sensor","Battery","Chassis"],a:1,e:"An ultrasonic sensor sends sound pulses and uses returning echoes to estimate distance."},
{t:"Robotics components",q:"Which robot component converts a control signal into physical movement?",o:["Actuator, such as a motor","Password","Web browser","File folder"],a:0,e:"Actuators create action. Motors can rotate wheels or move mechanisms."},
{t:"Robotics components",q:"What is the main role of a controller in a robot?",o:["Supply all the energy by itself","Make a robot look attractive","Process inputs and coordinate outputs","Replace every sensor"],a:2,e:"The controller interprets inputs and runs the logic that determines outputs."},
{t:"Robotics components",q:"Which statement best describes a sensor?",o:["A component that detects or measures a condition","A component that always moves a wheel","A type of username","A device used only for printing"],a:0,e:"Sensors gather information about the environment, such as light, temperature or distance."},
{t:"Robotics components",q:"A small programmable chip controls a sensor and two LEDs in an embedded project. It is most likely a…",o:["Router","Microcontroller","Loudspeaker","Spreadsheet"],a:1,e:"A microcontroller is a compact programmable integrated circuit used to control embedded devices."},
{t:"Robotics components",q:"Which is the best example of automation?",o:["A person manually switches a lamp every minute","A system turns a lamp on when a light sensor detects darkness","A learner draws a lamp","A computer is unplugged"],a:1,e:"Automation uses a system to perform an action in response to conditions with limited ongoing human intervention."},
{t:"Robotics components",q:"Why does a robot need a power source?",o:["To provide energy for its electronic and mechanical components","To make its code private","To guarantee Wi-Fi","To turn software into a sensor"],a:0,e:"Batteries or other supplies provide energy for controllers, sensors and actuators."},
{t:"Computing devices",q:"In an input–process–output system, a keyboard is mainly a(n)…",o:["Output device","Input device","Actuator only","Power source"],a:1,e:"A keyboard sends data into a computer, so it is an input device."},
{t:"Computing devices",q:"Which option is software?",o:["A physical keyboard","A laptop screen","A web browser application","A USB cable"],a:2,e:"Software is a programme or set of instructions; the other choices are physical hardware."},
{t:"Computing devices",q:"A computer calculates a learner's score and displays 82%. The calculation is…",o:["Input","Processing","Storage only","A sensor reading"],a:1,e:"Processing transforms or works on input data to produce a result."},
{t:"Computing devices",q:"Which statement is most accurate?",o:["Every computer is a robot","Every robot must look like a human","Computers and robots overlap, but they are not identical categories","A robot cannot use software"],a:2,e:"Robots often contain computing systems, but many computers do not sense and act as robots do."},
{t:"Computing devices",q:"What is the purpose of data storage?",o:["To keep data so it can be used later","To detect heat without a sensor","To make every file public","To physically rotate a motor"],a:0,e:"Storage retains data and instructions for later access."},
{t:"Sensors & control",q:"A smart garden measures dry soil and switches on a water pump. Which sequence is most logical?",o:["Pump → sensor → ignore reading","Sensor measures soil → controller checks condition → pump activates","Password → browser → wheel","Storage deletes the soil"],a:1,e:"The sensor provides input, the controller applies logic, and the pump actuator performs the action."},
{t:"Sensors & control",q:"A temperature sensor reports 35°C. What does the sensor provide to the controller?",o:["A measurement/input","A physical wheel movement","A guarantee that the internet works","A password reset"],a:0,e:"The sensor provides data about the environment; the controller decides what to do with it."},
{t:"Sensors & control",q:"A robot turns away when its distance sensor detects an object too close. What makes this behaviour responsive?",o:["It always follows the same fixed route regardless of surroundings","It uses sensor input and a programmed condition","It has no controller","It stores no instructions"],a:1,e:"The robot responds to its environment by using sensor data in a conditional decision."},
{t:"Digital citizenship",q:"A message says you have won a prize and asks you to click a strange link and enter your password. What is the safest response?",o:["Click quickly before it expires","Share it with all classmates","Do not enter details; verify the sender and report it if suspicious","Reply with your password only"],a:2,e:"This may be phishing. Avoid suspicious links and never disclose passwords through unexpected messages."},
{t:"Digital citizenship",q:"What is a digital footprint?",o:["A shoe print scanned into a computer only","The trail of information and activity associated with a person online","A robot's wheel pattern","A computer's power cable"],a:1,e:"Posts, comments, searches and other online actions can leave traces that affect privacy and reputation."},
{t:"Digital citizenship",q:"Which password practice is safest?",o:["Use the same easy password everywhere","Share passwords with a new online friend","Use a long, unique password and keep it private","Write your password in a public profile"],a:2,e:"Unique, hard-to-guess passwords reduce the damage if one account is compromised. A password manager can help."},
{t:"Digital citizenship",q:"A classmate posts an embarrassing photo of another learner without permission. What is the most responsible action?",o:["Forward it to more groups","Add insulting comments","Do not spread it; support the learner and report it appropriately","Save it to mock them later"],a:2,e:"Respect privacy and dignity. Do not amplify harmful content; seek help from a trusted adult or platform reporting tools."},
{t:"Networks & applications",q:"What is the main difference between the internet and the World Wide Web?",o:["They are exactly the same thing","The internet is a global network; the Web is a service that uses it","The Web is hardware and the internet is a keyboard","The internet works only on phones"],a:1,e:"The internet is the underlying network infrastructure; the Web is one service running on it."},
{t:"Networks & applications",q:"Which device commonly directs data between your home network and other networks?",o:["Router","Mouse","Servo","Temperature sensor"],a:0,e:"A router forwards data between networks. A modem provides the connection over the internet provider's access technology."}
];
let mode="practice", pool=[], index=0, score=0, answered=false, timer=null, remaining=600, started=false;
const $=id=>document.getElementById(id);
function showTab(id){document.querySelectorAll("main>section").forEach(s=>s.classList.add("hidden"));$(id).classList.remove("hidden");document.querySelectorAll(".nav button").forEach(b=>b.classList.toggle("active",b.dataset.tab===id));}
document.querySelectorAll(".nav button").forEach(b=>b.addEventListener("click",()=>showTab(b.dataset.tab)));
function shuffle(arr){let a=[...arr];for(let i=a.length-1;i>0;i--){let j=Math.floor(Math.random()*(i+1));[a[i],a[j]]=[a[j],a[i]]}return a}
$("startPractice").addEventListener("click",()=>{mode="practice";let topic=$("topicSelect").value;pool=shuffle(questions.filter(q=>topic==="all"||q.t===topic));index=0;score=0;started=true;render("practiceQuiz");});
$("startChallenge").addEventListener("click",()=>{mode="challenge";pool=shuffle(questions).slice(0,15);index=0;score=0;remaining=600;started=true;clearInterval(timer);render("challengeQuiz");timer=setInterval(()=>{remaining--;updateTimer();if(remaining<=0){clearInterval(timer);finish();}},1000);});
function render(id){$(id).classList.remove("hidden");drawQuestion(id);}
function drawQuestion(id){
 const root=$(id);if(index>=pool.length){finish();return}answered=false;const q=pool[index];
 root.innerHTML=`<div class="question-top"><span class="muted">Question ${index+1} of ${pool.length} • ${esc(q.t)}</span>${mode==="challenge"?'<span class="timer" id="timerText">10:00</span>':`<span class="pill" style="color:#174e78;border-color:#c7e5f7">Score: ${score}</span>`}</div><div class="progress"><div style="width:${index/pool.length*100}%"></div></div><div class="qtext">${esc(q.q)}</div><div class="options">${q.o.map((o,i)=>`<button class="option" data-i="${i}"><span class="letter">${"ABCD"[i]}</span><span>${esc(o)}</span></button>`).join("")}</div><div id="feedback"></div><div class="actions"><button class="primary hidden" id="nextBtn">${index===pool.length-1?"See results":"Next question →"}</button></div>`;
 root.querySelectorAll(".option").forEach(b=>b.addEventListener("click",()=>choose(Number(b.dataset.i),root)));
 if(mode==="challenge")updateTimer();
}
function choose(choice,root){if(answered)return;answered=true;const q=pool[index];const opts=root.querySelectorAll(".option");opts.forEach((b,i)=>{b.disabled=true;if(i===q.a)b.classList.add("correct");if(i===choice&&choice!==q.a)b.classList.add("wrong");});const good=choice===q.a;if(good)score++;const fb=root.querySelector("#feedback");if(mode==="practice"){fb.className="feedback "+(good?"good":"bad");fb.innerHTML=`<b>${good?"Correct! ✓":"Not quite."}</b> ${esc(q.e)}`;}else{fb.className="feedback "+(good?"good":"bad");fb.innerHTML=good?"Correct — one point earned.":"Not correct. The correct answer is highlighted.";fb.innerHTML+=" "+esc(q.e);}const next=root.querySelector("#nextBtn");next.classList.remove("hidden");next.addEventListener("click",()=>{index++;drawQuestion(root.id);});}
function updateTimer(){const m=Math.floor(remaining/60),s=remaining%60;const el=document.getElementById("timerText");if(el)el.textContent=`${m}:${String(s).padStart(2,"0")}`;}
function finish(){clearInterval(timer);started=false;const id=mode==="challenge"?"challengeQuiz":"practiceQuiz";const root=$(id);root.classList.remove("hidden");const pct=Math.round(score/Math.max(pool.length,1)*100);let message=pct>=85?"Excellent work — you are building Olympiad-level accuracy.":pct>=65?"Good progress. Review the explanations for every missed question, then try again.":"Keep training. Focus on understanding why each answer is correct, not just memorising it.";root.innerHTML=`<div class="progress"><div style="width:100%"></div></div><h2>${mode==="challenge"?"Challenge complete!":"Practice round complete!"}</h2><p class="result-score">${score}/${pool.length}</p><p><b>${pct}%</b> correct</p><p>${message}</p><div class="result-grid"><div class="mini"><strong>Next best move</strong>Review the revision deck, especially the topics you found difficult.</div><div class="mini"><strong>Training rule</strong>Repeat the round and aim to improve both accuracy and speed.</div></div><div class="actions"><button class="primary" id="again">Try another round</button><button class="secondary" id="revise">Open quick revision</button></div>`; $("again").addEventListener("click",()=>{if(mode==="challenge")$("startChallenge").click();else $("startPractice").click();});$("revise").addEventListener("click",()=>showTab("guide"));}
function esc(s){return String(s).replace(/[&<>"']/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]));}
</script>
</body>
</html># grade_8_Thutoboswa
Grade 8 Olympiad practice 
