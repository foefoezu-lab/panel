<!doctype html><html lang="en"><head>
<meta charset="utf-8"><meta name="viewport" content="width=device-width, initial-scale=1" />
<title>CK44 – LinkedIn 30-Day Planner</title>
<style>
:root{--bg:#080f1c;--panel:#0e1a2e;--text:#eaf2ff;--muted:#a9bfd8;--gold:#1e90ff;--border:#1a2a44;--cyan:#8be0ff}
*{box-sizing:border-box} body{margin:0;background:linear-gradient(180deg,#07101e,#081224 40%,#07101e);color:var(--text);
font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial}
.container{max-width:1200px;margin:24px auto;padding:0 16px}
h1{margin:6px 0 8px} .subtitle{color:var(--muted)}
.panel{background:var(--panel);border:1px solid var(--border);border-radius:14px;padding:12px;margin-top:12px}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:12px} textarea{width:100%;min-height:100px;background:#0b172b;color:var(--text);
border:1px solid var(--border);border-radius:10px;padding:10px} .btn{padding:10px 14px;border-radius:10px;border:1px solid var(--border);background:#0b172b;color:var(--text);cursor:pointer}
.copy{display:flex;gap:8px;margin-top:8px;flex-wrap:wrap} .status{display:flex;align-items:center;gap:10px;margin-left:auto}
.day{display:flex;align-items:center;gap:10px;justify-content:space-between;background:#0b172b;border:1px solid var(--border);border-radius:10px;padding:10px;margin-top:10px}
.badge{border:1px solid var(--border);padding:4px 10px;border-radius:999px;background:#0b172b;color:var(--cyan)}
</style></head><body>
<div class="container">
  <h1>CK44 – LinkedIn 30-Day Planner</h1>
  <p class="subtitle">Blue–Gold CK44 aesthetic • Offline • Copy-ready • Export CSV (via browser)</p>
  <div id="root"></div>
</div>
<script>
function postTemplate(day, slot, defaultText){
  return `
  <div class="panel">
    <div class="day"><span class="badge">Day ${day} — ${slot}</span><label class="status"><input type="checkbox"> posted</label></div>
    <div class="grid">
      <div>
        <label>Text</label>
        <textarea id="t-${day}-${slot}">${defaultText}</textarea>
        <div class="copy"><button class="btn" onclick="copy('#t-${day}-${slot}')">Copy Text</button></div>
      </div>
      <div>
        <label>AI Image Prompt</label>
        <textarea id="p-${day}-${slot}">Create LinkedIn visual card in CK44 blue–gold style with subtle glow, minimal layout, and topic '{slot}' for day {day}.</textarea>
        <div class="copy"><button class="btn" onclick="copy('#p-${day}-${slot}')">Copy Prompt</button></div>
      </div>
    </div>
  </div>`;
}
const root = document.getElementById('root');
let html = "";
for(let d=1; d<=30; d++){ 
  html += postTemplate(d, 'Morning', 'LinkedIn • Morning insight about CK44, fun, positive vibe.');
  html += postTemplate(d, 'Afternoon', 'LinkedIn • Game highlight PG Soft/JILI with soft CTA.');
  html += postTemplate(d, 'Night', 'LinkedIn • Community/engagement question or reflection.');
}
root.innerHTML = html;

function copy(sel){
  const el = document.querySelector(sel);
  el.select(); el.setSelectionRange(0, 99999); document.execCommand('copy');
  el.style.outline='2px solid var(--cyan)'; setTimeout(()=>el.style.outline='none',600);
}
</script>
</body></html>
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>CK44 বাংলাদেশ – 30-Day Medium Publication Calendar (SEO & Organic Growth)</title>
  <style>
    :root{
      --bg:#0f172a;
      --card:#111827;
      --muted:#9ca3af;
      --text:#e5e7eb;
      --accent:#22d3ee;
      --accent-2:#f59e0b;
      --border:#1f2937;
      --success:#10b981;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial;
      background: linear-gradient(180deg, #0b1022, #0f172a 30%, #0f172a);
      color:var(--text);
    }
    .container{
      max-width:1100px;
      margin:40px auto;
      padding:0 16px;
    }
    .card{
      background:rgba(17,24,39,.85);
      backdrop-filter: blur(6px);
      border:1px solid var(--border);
      border-radius:16px;
      box-shadow: 0 10px 30px rgba(0,0,0,.35);
      padding:24px;
    }
    h1{
      margin:0 0 10px;
      font-size: clamp(24px, 3.3vw, 34px);
      letter-spacing:.2px;
    }
    .subtitle{
      margin:0 0 22px;
      color:var(--muted);
      font-size:14px;
    }
    .toolbar{
      display:flex;
      gap:12px;
      flex-wrap:wrap;
      margin: 6px 0 18px;
      align-items:center;
    }
    .toolbar input[type="text"]{
      flex:1;
      min-width:220px;
      padding:10px 12px;
      border-radius:10px;
      border:1px solid var(--border);
      background:#0b1220;
      color:var(--text);
      outline:none;
    }
    .toolbar .btn{
      padding:10px 14px;
      border-radius:10px;
      border:1px solid var(--border);
      background:#0b1220;
      color:var(--text);
      cursor:pointer;
    }
    .toolbar .btn:hover{border-color:#334155}
    table{
      width:100%;
      border-collapse:separate;
      border-spacing:0;
      overflow:hidden;
      border-radius:14px;
      border:1px solid var(--border);
    }
    thead th{
      position:sticky; top:0;
      background:#0b1220;
      color:#cbd5e1;
      text-align:left;
      font-weight:600;
      font-size:13px;
      letter-spacing:.3px;
      padding:12px 14px;
      border-bottom:1px solid var(--border);
      z-index:2;
    }
    tbody td{
      padding:12px 14px;
      border-bottom:1px solid var(--border);
      vertical-align:top;
      font-size:14px;
      line-height:1.45;
    }
    tbody tr:hover{background:#0c1424}
    .badge{
      display:inline-block;
      padding:2px 8px;
      border-radius:999px;
      font-size:12px;
      border:1px solid #22324a;
      color:#cfe9ff;
      background:linear-gradient(180deg,#0c1a2a,#0a1220);
    }
    .time{color:#c7f9ff}
    .muted{color:var(--muted)}
    .kw{color:var(--accent)}
    .status{
      display:flex;align-items:center;gap:8px;
    }
    .status input{width:18px;height:18px;cursor:pointer}
    .done{color:var(--success);font-weight:600}
    .note{
      margin-top:14px;
      color:#a7b4c4;
      font-size:13px;
    }
    a{color:#7dd3fc;text-decoration:none}
    a:hover{text-decoration:underline}
    .foot{
      margin-top:18px;
      display:flex;gap:12px;flex-wrap:wrap;
      font-size:13px;color:#a8b1c1;
    }
    .tag{
      padding:6px 10px;border-radius:999px;border:1px solid var(--border);
      background:#0b1220;color:#cbd5e1
    }
    @media (max-width:760px){
      thead th:nth-child(4), tbody td:nth-child(4){display:none}
      thead th:nth-child(3){min-width:150px}
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <h1>CK44 বাংলাদেশ – 30-Day Publication Calendar</h1>
      <p class="subtitle">SEO & Organic Growth · Jadwal ideal: <span class="badge">10:00 AM</span> dan <span class="badge">8:00 PM</span> (GMT+6)</p>

      <div class="toolbar">
        <input id="search" type="text" placeholder="Cari judul / keyword…" />
        <button class="btn" onclick="toggleAll(true)">Centang semua</button>
        <button class="btn" onclick="toggleAll(false)">Kosongkan centang</button>
        <button class="btn" onclick="exportCSV()">Export CSV</button>
      </div>

      <table id="calendar">
        <thead>
          <tr>
            <th>Hari</th>
            <th>Judul Artikel</th>
            <th>Fokus Keyword</th>
            <th>Gaya Penulisan</th>
            <th>Waktu Posting</th>
            <th>Status</th>
          </tr>
        </thead>
        <tbody>
          <!-- Rows generated below -->
        </tbody>
      </table>

      <p class="note">Tips: gunakan 5–10 tag per artikel: <span class="tag">CK44</span> <span class="tag">CK44 বাংলাদেশ</span> <span class="tag">Digital Entertainment</span> <span class="tag">Gaming</span> <span class="tag">Bangladesh</span> <span class="tag">Bonus</span> <span class="tag">Community</span></p>

      <div class="foot">
        <span>Tekan <strong>Export CSV</strong> untuk mengunduh progress.</span>
        <span>Gunakan kolom <em>Status</em> untuk checklist harian.</span>
      </div>
    </div>
  </div>

<script>
  const rows = [
    [1,'CK44 বাংলাদেশ: প্ল্যাটফর্মটি কেন এত জনপ্রিয় হয়ে উঠেছে','CK44 বাংলাদেশ','Cerita & pengenalan (soft intro)','10:00 AM'],
    [2,'CK44 কীভাবে অনলাইন বিনোদনের নতুন ধারা তৈরি করেছে','CK44','Analisis ringan & storytelling','8:00 PM'],
    [3,'CK44 Bangladesh – Where Entertainment Meets Opportunity','CK44 Bangladesh','English mix – lifestyle tone','10:00 AM'],
    [4,'CK44 VIP সিস্টেমের সম্পূর্ণ গাইড: কিভাবে কাজ করে?','CK44 VIP','Panduan informatif','8:00 PM'],
    [5,'CK44 বোনাস সিস্টেম: প্রতিদিনের রিওয়ার্ড পাওয়ার টিপস','CK44 bonus','Tutorial & tips harian','10:00 AM'],
    [6,'কেন মানুষ CK44 বাংলাদেশকে “Best Platform” বলে?','CK44 Bangladesh','Opini user-style','8:00 PM'],
    [7,'CK44 তে খেলার আগে যা জানা দরকার','CK44','Artikel edukatif','10:00 AM'],
    [8,'CK44 Bangladesh Referral Program: Earn While You Play','CK44 Bangladesh referral','Panduan affiliate','8:00 PM'],
    [9,'কিভাবে CK44 বাংলাদেশ নিরাপদ থাকে?','CK44 Bangladesh security','Edukasi & kepercayaan','10:00 AM'],
    [10,'Top 5 Reasons Why CK44 Is Trending in Bangladesh','CK44 Bangladesh','Artikel ringan bergaya blog','8:00 PM'],
    [11,'CK44 Bangladesh: অনলাইন প্ল্যাটফর্মের সফল গল্প','CK44 Bangladesh','Cerita inspiratif','10:00 AM'],
    [12,'CK44 VIP Level System: How to Level Up Faster','CK44 VIP','Guide & reward system','8:00 PM'],
    [13,'CK44 বাংলাদেশে জনপ্রিয় গেমগুলোর রিভিউ','CK44 games','Review format','10:00 AM'],
    [14,'CK44 Bangladesh vs Other Platforms: Who Wins?','CK44 Bangladesh comparison','Perbandingan kompetitif','8:00 PM'],
    [15,'CK44 বাংলাদেশ: বোনাস, নিরাপত্তা ও সাপোর্ট সিস্টেম','CK44 Bangladesh','Artikel lengkap (SEO heavy)','10:00 AM'],
    [16,'কিভাবে CK44 তে আপনার প্রথম গেম শুরু করবেন','CK44 Bangladesh register','Step-by-step guide','8:00 PM'],
    [17,'CK44 Bangladesh Community: Where Players Connect','CK44 Bangladesh community','Artikel sosial & interaktif','10:00 AM'],
    [18,'CK44 এর লুকানো ফিচার যেগুলো banyakেই জানে না','CK44 features','Tips & secret feature','8:00 PM'],
    [19,'CK44 Bangladesh: দৈনিক লগইন বোনাসের রহস্য','CK44 Bangladesh bonus','Cerita pendek + edukatif','10:00 AM'],
    [20,'CK44 তে সফল হওয়ার সেরা ৫টি টিপস','CK44 tips','Daftar ringan & menarik','8:00 PM'],
    [21,'The Rise of CK44 Bangladesh in 2025','CK44 Bangladesh 2025','English SEO trend article','10:00 AM'],
    [22,'CK44 বাংলাদেশ: অনলাইন আয়ের নতুন দিগন্ত','CK44 Bangladesh earn','Motivasi + panduan finansial','8:00 PM'],
    [23,'কিভাবে CK44 প্ল্যাটফর্মে দায়িত্বশীলভাবে খেলা যায়','CK44 safe play','Artikel edukatif','10:00 AM'],
    [24,'CK44 Bangladesh: What Makes It Unique?','CK44 Bangladesh unique','Gaya eksklusif & elegan','8:00 PM'],
    [25,'CK44 বাংলাদেশের সেরা সময় কোনটা খেলতে?','CK44 Bangladesh timing','Fun facts style','10:00 AM'],
    [26,'CK44 VIP Player Interview (কল্পিত গল্প)','CK44 VIP Bangladesh','Cerita naratif','8:00 PM'],
    [27,'CK44 Bangladesh Weekly Event Highlights','CK44 Bangladesh events','Recap mingguan','10:00 AM'],
    [28,'কেন CK44 বাংলাদেশ ভবিষ্যতের প্ল্যাটফর্ম','CK44 Bangladesh future','Visioner & optimistik','8:00 PM'],
    [29,'CK44 Bangladesh & Digital Future of Gaming','CK44 Bangladesh gaming','Artikel futuristik','10:00 AM'],
    [30,'CK44 বাংলাদেশ: এক মাসের অভিজ্ঞতা থেকে শেখা ১০টি জিনিস','CK44 Bangladesh review','Artikel penutup (refleksi pribadi)','8:00 PM']
  ];

  // Render rows
  const tbody = document.querySelector('#calendar tbody');
  rows.forEach(r => {
    const tr = document.createElement('tr');
    tr.innerHTML = `
      <td><span class="badge">Day ${r[0]}</span></td>
      <td>${r[1]}</td>
      <td class="kw">${r[2]}</td>
      <td class="muted">${r[3]}</td>
      <td class="time">${r[4]}</td>
      <td class="status">
        <input type="checkbox" aria-label="status ${r[0]}"/>
        <span class="muted">Belum diposting</span>
      </td>`;
    tbody.appendChild(tr);
  });

  // Search filter
  const search = document.getElementById('search');
  search.addEventListener('input', (e)=>{
    const q = e.target.value.toLowerCase();
    [...tbody.rows].forEach(row => {
      row.style.display = row.innerText.toLowerCase().includes(q) ? '' : 'none';
    });
  });

  // Toggle all checkboxes
  function toggleAll(v){
    document.querySelectorAll('.status input[type="checkbox"]').forEach(cb => {
      cb.checked = v;
      const label = cb.nextElementSibling;
      label.textContent = v ? 'Sudah diposting' : 'Belum diposting';
      label.className = v ? 'done' : 'muted';
    });
  }
  window.toggleAll = toggleAll;

  // Update single checkbox label on change
  document.addEventListener('change', (e)=>{
    if(e.target.matches('.status input[type="checkbox"]')){
      const label = e.target.nextElementSibling;
      label.textContent = e.target.checked ? 'Sudah diposting' : 'Belum diposting';
      label.className = e.target.checked ? 'done' : 'muted';
    }
  });

  // Export CSV
  function exportCSV(){
    const headers = ['Hari','Judul','Fokus Keyword','Gaya Penulisan','Waktu','Status'];
    const lines = [headers.join(',')];

    [...tbody.rows].forEach(row => {
      const cols = [...row.cells];
      const day = cols[0].innerText.replace('Day ','').trim();
      const title = cols[1].innerText.trim();
      const kw = cols[2].innerText.trim();
      const style = cols[3].innerText.trim();
      const time = cols[4].innerText.trim();
      const status = cols[5].querySelector('input').checked ? 'Posted' : 'Not Posted';
      const arr = [day,title,kw,style,time,status].map(v => `"${v.replace(/"/g,'""')}"`);
      lines.push(arr.join(','));
    });

    const blob = new Blob([lines.join('\n')], {type:'text/csv'});
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = 'ck44_calendar.csv';
    document.body.appendChild(a);
    a.click();
    document.body.removeChild(a);
    URL.revokeObjectURL(url);
  }
  window.exportCSV = exportCSV;
</script>
</body>
</html>

<!doctype html><html lang="en"><head>
<meta charset="utf-8"><meta name="viewport" content="width=device-width, initial-scale=1" />
<title>CK44 – Reddit 30-Day Planner</title>
<style>
:root{--bg:#080f1c;--panel:#0e1a2e;--text:#eaf2ff;--muted:#a9bfd8;--gold:#ff7a00;--border:#1a2a44;--cyan:#8be0ff}
*{box-sizing:border-box} body{margin:0;background:linear-gradient(180deg,#07101e,#081224 40%,#07101e);color:var(--text);
font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial}
.container{max-width:1200px;margin:24px auto;padding:0 16px}
h1{margin:6px 0 8px} .subtitle{color:var(--muted)}
.panel{background:var(--panel);border:1px solid var(--border);border-radius:14px;padding:12px;margin-top:12px}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:12px} textarea{width:100%;min-height:100px;background:#0b172b;color:var(--text);
border:1px solid var(--border);border-radius:10px;padding:10px} .btn{padding:10px 14px;border-radius:10px;border:1px solid var(--border);background:#0b172b;color:var(--text);cursor:pointer}
.copy{display:flex;gap:8px;margin-top:8px;flex-wrap:wrap} .status{display:flex;align-items:center;gap:10px;margin-left:auto}
.day{display:flex;align-items:center;gap:10px;justify-content:space-between;background:#0b172b;border:1px solid var(--border);border-radius:10px;padding:10px;margin-top:10px}
.badge{border:1px solid var(--border);padding:4px 10px;border-radius:999px;background:#0b172b;color:var(--cyan)}
</style></head><body>
<div class="container">
  <h1>CK44 – Reddit 30-Day Planner</h1>
  <p class="subtitle">Blue–Gold CK44 aesthetic • Offline • Copy-ready • Export CSV (via browser)</p>
  <div id="root"></div>
</div>
<script>
function postTemplate(day, slot, defaultText){
  return `
  <div class="panel">
    <div class="day"><span class="badge">Day ${day} — ${slot}</span><label class="status"><input type="checkbox"> posted</label></div>
    <div class="grid">
      <div>
        <label>Text</label>
        <textarea id="t-${day}-${slot}">${defaultText}</textarea>
        <div class="copy"><button class="btn" onclick="copy('#t-${day}-${slot}')">Copy Text</button></div>
      </div>
      <div>
        <label>AI Image Prompt</label>
        <textarea id="p-${day}-${slot}">Create Reddit visual card in CK44 blue–gold style with subtle glow, minimal layout, and topic '{slot}' for day {day}.</textarea>
        <div class="copy"><button class="btn" onclick="copy('#p-${day}-${slot}')">Copy Prompt</button></div>
      </div>
    </div>
  </div>`;
}
const root = document.getElementById('root');
let html = "";
for(let d=1; d<=30; d++){ 
  html += postTemplate(d, 'Morning', 'Reddit • Morning insight about CK44, fun, positive vibe.');
  html += postTemplate(d, 'Afternoon', 'Reddit • Game highlight PG Soft/JILI with soft CTA.');
  html += postTemplate(d, 'Night', 'Reddit • Community/engagement question or reflection.');
}
root.innerHTML = html;

function copy(sel){
  const el = document.querySelector(sel);
  el.select(); el.setSelectionRange(0, 99999); document.execCommand('copy');
  el.style.outline='2px solid var(--cyan)'; setTimeout(()=>el.style.outline='none',600);
}
</script>
</body></html>
<!doctype html><html lang="en"><head>
<meta charset="utf-8"><meta name="viewport" content="width=device-width, initial-scale=1" />
<title>CK44 – Threads 30-Day Planner</title>
<style>
:root{--bg:#080f1c;--panel:#0e1a2e;--text:#eaf2ff;--muted:#a9bfd8;--gold:#ffd700;--border:#1a2a44;--cyan:#8be0ff}
*{box-sizing:border-box} body{margin:0;background:linear-gradient(180deg,#07101e,#081224 40%,#07101e);color:var(--text);
font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial}
.container{max-width:1200px;margin:24px auto;padding:0 16px}
h1{margin:6px 0 8px} .subtitle{color:var(--muted)}
.panel{background:var(--panel);border:1px solid var(--border);border-radius:14px;padding:12px;margin-top:12px}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:12px} textarea{width:100%;min-height:100px;background:#0b172b;color:var(--text);
border:1px solid var(--border);border-radius:10px;padding:10px} .btn{padding:10px 14px;border-radius:10px;border:1px solid var(--border);background:#0b172b;color:var(--text);cursor:pointer}
.copy{display:flex;gap:8px;margin-top:8px;flex-wrap:wrap} .status{display:flex;align-items:center;gap:10px;margin-left:auto}
.day{display:flex;align-items:center;gap:10px;justify-content:space-between;background:#0b172b;border:1px solid var(--border);border-radius:10px;padding:10px;margin-top:10px}
.badge{border:1px solid var(--border);padding:4px 10px;border-radius:999px;background:#0b172b;color:var(--cyan)}
</style></head><body>
<div class="container">
  <h1>CK44 – Threads 30-Day Planner</h1>
  <p class="subtitle">Blue–Gold CK44 aesthetic • Offline • Copy-ready • Export CSV (via browser)</p>
  <div id="root"></div>
</div>
<script>
function postTemplate(day, slot, defaultText){
  return `
  <div class="panel">
    <div class="day"><span class="badge">Day ${day} — ${slot}</span><label class="status"><input type="checkbox"> posted</label></div>
    <div class="grid">
      <div>
        <label>Text</label>
        <textarea id="t-${day}-${slot}">${defaultText}</textarea>
        <div class="copy"><button class="btn" onclick="copy('#t-${day}-${slot}')">Copy Text</button></div>
      </div>
      <div>
        <label>AI Image Prompt</label>
        <textarea id="p-${day}-${slot}">Create Threads visual card in CK44 blue–gold style with subtle glow, minimal layout, and topic '{slot}' for day {day}.</textarea>
        <div class="copy"><button class="btn" onclick="copy('#p-${day}-${slot}')">Copy Prompt</button></div>
      </div>
    </div>
  </div>`;
}
const root = document.getElementById('root');
let html = "";
for(let d=1; d<=30; d++){ 
  html += postTemplate(d, 'Morning', 'Threads • Morning insight about CK44, fun, positive vibe.');
  html += postTemplate(d, 'Afternoon', 'Threads • Game highlight PG Soft/JILI with soft CTA.');
  html += postTemplate(d, 'Night', 'Threads • Community/engagement question or reflection.');
}
root.innerHTML = html;

function copy(sel){
  const el = document.querySelector(sel);
  el.select(); el.setSelectionRange(0, 99999); document.execCommand('copy');
  el.style.outline='2px solid var(--cyan)'; setTimeout(()=>el.style.outline='none',600);
}
</script>
</body></html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>CK44 Bangladesh – TikTok 30-Day Planner (PG Soft & JILI)</title>
<style>
  :root{
    --bg:#070b14; --card:#0c1322; --panel:#0e1a2e;
    --text:#e9f3ff; --muted:#a9c0d9; --gold:#ffd700; --blue:#1e90ff; --cyan:#7dd3fc;
    --border:#1a2a44; --success:#10b981;
  }
  *{box-sizing:border-box}
  body{margin:0;background:
      radial-gradient(1200px 700px at 20% -10%, rgba(30,144,255,.18), transparent),
      radial-gradient(1200px 700px at 90% 10%, rgba(255,215,0,.15), transparent),
      linear-gradient(180deg,#07101e,#070b14 40%,#07101e);
      color:var(--text);
      font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial}
  .container{max-width:1200px;margin:36px auto;padding:0 16px}
  h1{margin:0 0 6px;font-size:clamp(22px,3.2vw,34px)}
  .subtitle{color:var(--muted);margin:0 0 18px;font-size:14px}
  .card{background:linear-gradient(180deg,rgba(12,19,34,.92),rgba(12,19,34,.94));
        border:1px solid var(--border);border-radius:18px;padding:18px;box-shadow:0 12px 30px rgba(0,0,0,.45)}
  .toolbar{display:flex;gap:10px;flex-wrap:wrap;margin:10px 0 14px}
  input[type="text"],input[type="url"],textarea{width:100%;padding:10px 12px;background:#0b172b;
      color:var(--text);border:1px solid var(--border);border-radius:10px;outline:none}
  textarea{min-height:100px;resize:vertical}
  .btn{padding:10px 14px;border:1px solid var(--border);background:#0b172b;color:var(--text);border-radius:10px;cursor:pointer}
  .btn:hover{border-color:#274264}
  .btn-blue{background:linear-gradient(180deg,#0f2544,#0b172b);border-color:#274a7a;color:#bfe3ff}
  .badge{display:inline-block;padding:2px 8px;border-radius:999px;border:1px solid #1c2e4a;
         background:linear-gradient(180deg,#0e1a2e,#0c1626);color:#dff1ff;font-size:12px}
  .pill{padding:6px 10px;border:1px solid var(--border);border-radius:999px;background:#0b172b}
  .table-head{display:grid;grid-template-columns:70px 1.2fr .9fr 1fr 120px;gap:12px;
              padding:10px 16px;border:1px solid var(--border);border-radius:12px;background:#0b172b;color:#cfe7ff;font-size:13px}
  details{border:1px solid var(--border);border-radius:14px;background:#0b172b;margin-top:10px}
  summary{list-style:none;padding:14px 16px;cursor:pointer;border-bottom:1px solid rgba(255,255,255,.06);
          display:grid;grid-template-columns:70px 1.2fr .9fr 1fr 120px;gap:12px;align-items:center}
  summary::-webkit-details-marker{display:none}
  .kw{color:#8de3ff}
  .status{display:flex;align-items:center;gap:8px}
  .status input{width:18px;height:18px;cursor:pointer}
  .muted{color:var(--muted)}
  .done{color:var(--success);font-weight:600}
  .section{padding:14px 16px;display:grid;grid-template-columns:1fr 1fr;gap:16px}
  .panel{background:var(--panel);border:1px solid var(--border);border-radius:14px;padding:12px}
  .panel h3{margin:0 0 8px;font-size:16px;color:#bfe3ff}
  .row{display:grid;grid-template-columns:.9fr 1.1fr;gap:12px}
  .copy-row{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px}
  .foot{display:flex;gap:12px;flex-wrap:wrap;margin-top:14px;color:#c9def2;font-size:13px}
  .search{flex:1;min-width:260px}
  .hint{font-size:12px;color:#cde7ff}
  @media (max-width:980px){summary,.table-head{grid-template-columns:70px 1fr 1fr}
    summary .kw, .table-head div:nth-child(4){display:none}
    summary .status, .table-head div:nth-child(5){display:none}
    .section{grid-template-columns:1fr}
    .row{grid-template-columns:1fr}
  }
</style>
</head>
<body>
<div class="container">
  <div class="card">
    <h1>CK44 – TikTok 30-Day Planner (PG Soft & JILI)</h1>
    <p class="subtitle">Gold–Blue theme • Main TikTok only (no extra reaction prompts) • AI prompts • Captions • Hashtags • Schedule • Checklist • Export CSV</p>

    <div class="toolbar">
      <input id="search" class="search" type="text" placeholder="Cari game / brand / keyword…"/>
      <button class="btn" onclick="toggleAll(true)">Centang semua</button>
      <button class="btn" onclick="toggleAll(false)">Kosongkan centang</button>
      <button class="btn btn-blue" onclick="exportCSV()">Export CSV</button>
    </div>

    <div class="table-head">
      <div>Day</div><div>Game / Title</div><div>Brand</div><div>Keywords</div><div>Status</div>
    </div>

    <div id="root"></div>

    <div class="foot">
      <span>Jam ideal TikTok: <span class="badge">11:30</span> · <span class="badge">19:00</span> · <span class="badge">21:30</span> (GMT+6)</span>
      <span class="hint">Gunakan tone <b style="color:#ffd700">gold</b> + <b style="color:#1e90ff">blue</b> + <b style="color:#7dd3fc">cyan</b> ala CK44.</span>
    </div>
  </div>
</div>

<script>
const plan = [
  {brand:"PG Soft", game:"Lucky Neko"},
  {brand:"JILI", game:"Super Ace"},
  {brand:"PG Soft", game:"Fortune Tiger"},
  {brand:"JILI", game:"Boxing King"},
  {brand:"PG Soft", game:"Mahjong Ways 2"},
  {brand:"JILI", game:"Crazy Seven"},
  {brand:"PG Soft", game:"Fortune Ox"},
  {brand:"JILI", game:"Roma X"},
  {brand:"PG Soft", game:"Ways of the Qilin"},
  {brand:"JILI", game:"Golden Empire"},
  {brand:"PG Soft", game:"Treasures of Aztec"},
  {brand:"JILI", game:"Money Coming"},
  {brand:"PG Soft", game:"Dragon Tiger Luck"},
  {brand:"JILI", game:"Fortune Gems"},
  {brand:"PG Soft", game:"Wild Bandito"},
  {brand:"JILI", game:"Pharaoh's Treasure"},
  {brand:"PG Soft", game:"Dreams of Macau"},
  {brand:"JILI", game:"Bao Boon Chin"},
  {brand:"PG Soft", game:"Candy Burst"},
  {brand:"JILI", game:"Mega Ace"},
  {brand:"PG Soft", game:"Reel Love"},
  {brand:"JILI", game:"Phantom Thief"},
  {brand:"PG Soft", game:"Ganesha Fortune"},
  {brand:"JILI", game:"Win Drop"},
  {brand:"PG Soft", game:"Symbols of Egypt"},
  {brand:"JILI", game:"Charge Buffalo"},
  {brand:"PG Soft", game:"Vampire's Charm"},
  {brand:"JILI", game:"Jungle King"},
  {brand:"PG Soft", game:"Phoenix Rises"},
  {brand:"JILI", game:"Shanghai Beauty"}
];

function tiktokPrompt(brand, game){
  return `Create a 4K vertical (9:16) TikTok clip for ${brand} “${game}”: gold–blue CK44 aesthetic, glowing coins, quick cuts, camera push into reels, CK44 logo pulse, ending text “Play Now on CK44 Bangladesh”. Keep it 8–15 seconds.`;
}
function tiktokCaption(brand, game){
  return `🎮 ${game} by ${brand}
Spin • Win • Celebrate! Play CK44 Bangladesh 💎
#CK44 #${brand.replace(' ','')} #${game.replace(/\\s+/g,'')} #Bangladesh #TikTokGaming #Slots #BigWin`;
}
function tiktokHashtags(brand, game){
  return `#CK44 #${brand.replace(' ','')} #${game.replace(/\\s+/g,'')} #Bangladesh #TikTokGaming #Slots #CasinoVibes #DailyBonus #PlayNow`;
}

const root = document.getElementById('root');

function render(){
  root.innerHTML = '';
  plan.forEach((d,i)=>{
    const idx = i+1;
    const keywords = `${d.brand}, ${d.game}, CK44 Bangladesh, TikTok`;
    const details = document.createElement('details');
    details.innerHTML = `
      <summary>
        <div><span class="badge">Day ${idx}</span></div>
        <div><strong>${d.game}</strong></div>
        <div><span class="badge">${d.brand}</span></div>
        <div class="kw">${keywords}</div>
        <div class="status"><input type="checkbox"/><span class="muted">Belum diposting</span></div>
      </summary>

      <div class="section">
        <div class="panel">
          <h3>🎬 Main TikTok (11:30 / 19:00 / 21:30)</h3>
          <div class="row">
            <div>
              <label class="muted">Sora / Video Prompt</label>
              <textarea id="tp-${idx}">${tiktokPrompt(d.brand,d.game)}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#tp-${idx}')">Copy Prompt</button></div>
            </div>
            <div>
              <label class="muted">Caption (Bangla + English Mix)</label>
              <textarea id="tc-${idx}">${tiktokCaption(d.brand,d.game)}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#tc-${idx}')">Copy Caption</button></div>
              <label class="muted">Hashtags</label>
              <textarea id="th-${idx}">${tiktokHashtags(d.brand,d.game)}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#th-${idx}')">Copy Hashtags</button></div>
              <label class="muted">Link TikTok</label>
              <input id="tl-${idx}" type="url" placeholder="https://www.tiktok.com/@user/video/..." />
            </div>
          </div>
        </div>
      </div>
    `;
    root.appendChild(details);
  });
}
render();

// Search filter
document.getElementById('search').addEventListener('input', e => {
  const q = e.target.value.toLowerCase();
  [...root.children].forEach(item => {
    item.style.display = item.innerText.toLowerCase().includes(q) ? '' : 'none';
  });
});

// Copy helper
function copy(sel){
  const el = document.querySelector(sel);
  el.select(); el.setSelectionRange(0, 99999);
  document.execCommand('copy');
  el.style.outline='2px solid var(--cyan)';
  setTimeout(()=>{el.style.outline='none'},600);
}

// Toggle all checkboxes
function toggleAll(v){
  document.querySelectorAll('.status input[type="checkbox"]').forEach(cb => {
    cb.checked = v;
    const label = cb.nextElementSibling;
    label.textContent = v ? 'Sudah diposting' : 'Belum diposting';
    label.className = v ? 'done' : 'muted';
  });
}

// Update single status
document.addEventListener('change',(e)=>{
  if(e.target.matches('.status input[type="checkbox"]')){
    const label = e.target.nextElementSibling;
    label.textContent = e.target.checked ? 'Sudah diposting' : 'Belum diposting';
    label.className = e.target.checked ? 'done' : 'muted';
  }
});

// Export CSV
function exportCSV(){
  const headers = ['Day','Brand','Game','TikTokPrompt','Caption','Hashtags','Link','Status'];
  const lines = [headers];
  [...root.children].forEach((det,i)=>{
    const idx = i+1;
    const brand = det.querySelector('summary .badge').innerText;
    const game = det.querySelector('summary strong').innerText;
    const pr = det.querySelector('#tp-'+idx).value.replace(/\\n/g,' ').trim();
    const cp = det.querySelector('#tc-'+idx).value.replace(/\\n/g,' ').trim();
    const ht = det.querySelector('#th-'+idx).value.replace(/\\n/g,' ').trim();
    const lk = det.querySelector('#tl-'+idx).value.trim();
    const status = det.querySelector('.status input').checked ? 'Posted' : 'Not Posted';
    lines.push([idx,brand,game,pr,cp,ht,lk,status].map(v=>`"${String(v).replace(/"/g,'""')}"`).join(','));
  });
  const blob = new Blob([lines.join('\\n')],{type:'text/csv'});
  const url = URL.createObjectURL(blob);
  const a = document.createElement('a'); a.href=url; a.download='CK44_TikTok_30Day.csv';
  document.body.appendChild(a); a.click(); document.body.removeChild(a); URL.revokeObjectURL(url);
}
</script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>CK44 Bangladesh – X (Twitter) 30-Day Organic Planner</title>
<style>
  :root{
    --bg:#070c14; --card:#0b1321; --panel:#0e1a2e;
    --text:#e8f1ff; --muted:#aac1d8; --blue:#1e90ff; --gold:#ffd700; --cyan:#8be0ff;
    --border:#1a2a44; --success:#10b981;
  }
  *{box-sizing:border-box}
  body{margin:0;background:
      radial-gradient(1200px 720px at 10% -10%, rgba(30,144,255,.16), transparent),
      radial-gradient(1200px 720px at 100% 10%, rgba(255,215,0,.14), transparent),
      linear-gradient(180deg,#07101e,#070c14 40%,#07101e);
      color:var(--text);font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial}
  .container{max-width:1280px;margin:32px auto;padding:0 16px;display:grid;grid-template-columns:1.25fr .75fr;gap:16px}
  @media (max-width:1060px){.container{grid-template-columns:1fr} .preview{order:-1}}
  h1{margin:0 0 4px;font-size:clamp(22px,3.2vw,34px)}
  .subtitle{color:var(--muted);margin:0 0 16px;font-size:14px}
  .card{background:linear-gradient(180deg,rgba(11,19,33,.92),rgba(11,19,33,.94));
        border:1px solid var(--border);border-radius:18px;padding:18px;box-shadow:0 12px 30px rgba(0,0,0,.45)}
  .toolbar{display:flex;gap:10px;flex-wrap:wrap;margin:10px 0 16px}
  input[type="text"],input[type="url"],textarea{width:100%;padding:10px 12px;background:#0b172b;
      color:var(--text);border:1px solid var(--border);border-radius:10px;outline:none}
  textarea{min-height:100px;resize:vertical}
  .btn{padding:10px 14px;border:1px solid var(--border);background:#0b172b;color:var(--text);border-radius:10px;cursor:pointer}
  .btn:hover{border-color:#274264}
  .btn-blue{background:linear-gradient(180deg,#0f2544,#0b172b);border-color:#274a7a;color:#bfe3ff}
  .btn-gold{background:linear-gradient(180deg,#2a2214,#181104);border-color:#4a3914;color:#ffe39b}
  .table-head{display:grid;grid-template-columns:64px 1.2fr 170px 1fr 120px;gap:12px;
              padding:10px 16px;border:1px solid var(--border);border-radius:12px;background:#0b172b;color:#cfe0f7;font-size:13px}
  details{border:1px solid var(--border);border-radius:14px;background:#0b172b;margin-top:10px}
  summary{list-style:none;padding:14px 16px;cursor:pointer;border-bottom:1px solid rgba(255,255,255,.06);
          display:grid;grid-template-columns:64px 1.2fr 170px 1fr 120px;gap:12px;align-items:center}
  summary::-webkit-details-marker{display:none}
  .kw{color:#8de3ff}
  .status{display:flex;align-items:center;gap:8px}
  .status input{width:18px;height:18px;cursor:pointer}
  .muted{color:var(--muted)}
  .done{color:var(--success);font-weight:600}
  .section{padding:14px 16px;display:grid;grid-template-columns:1fr 1fr;gap:16px}
  .panel{background:var(--panel);border:1px solid var(--border);border-radius:14px;padding:12px}
  .panel h3{margin:0 0 8px;font-size:16px;color:#bfe3ff}
  .row{display:grid;grid-template-columns:.9fr 1.1fr;gap:12px}
  .copy-row{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px}
  .search{flex:1;min-width:260px}
  .foot{display:flex;gap:12px;flex-wrap:wrap;margin-top:14px;color:#c9def2;font-size:13px}
  .hint{font-size:12px;color:#cde7ff}

  /* Preview panel (tweet mock) */
  .preview{position:sticky;top:16px;height:calc(100vh - 64px)}
  .tweet{background:#0c1624;border:1px solid #1c2a44;border-radius:16px;padding:16px;box-shadow:0 10px 24px rgba(0,0,0,.35)}
  .tweet .hdr{display:flex;align-items:center;gap:10px;margin-bottom:8px}
  .avatar{width:42px;height:42px;border-radius:999px;background:linear-gradient(135deg,#1e90ff,#ffd700);box-shadow:0 0 18px rgba(30,144,255,.35)}
  .name{font-weight:700} .user{color:#9fb4cc}
  .tweet .body{white-space:pre-wrap;line-height:1.45;margin:8px 0}
  .tweet .media{margin-top:8px;border-radius:12px;border:1px solid #20324f;min-height:160px;background:linear-gradient(180deg,rgba(30,144,255,.18),rgba(255,215,0,.12));display:flex;align-items:center;justify-content:center;color:#bfe3ff;padding:10px;text-align:center}
  .tweet .meta{display:flex;gap:12px;margin-top:10px;color:#9fb4cc;font-size:12px}
</style>
</head>
<body>
<div class="container">
  <div>
    <div class="card">
      <h1>CK44 – X (Twitter) 30-Day Organic Planner</h1>
      <p class="subtitle">Blue–Gold aesthetic • 3 posts/day • Medium-style captions • Hashtags • AI prompts • Search • Tweet Preview • Export CSV</p>

      <div class="toolbar">
        <input id="search" class="search" type="text" placeholder="Cari tema / keyword…"/>
        <button class="btn" onclick="toggleAll(true)">Centang semua</button>
        <button class="btn" onclick="toggleAll(false)">Kosongkan centang</button>
        <button class="btn btn-gold" onclick="exportCSV()">Export CSV</button>
      </div>

      <div class="table-head">
        <div>Day</div><div>Judul / Tema</div><div>Slot Waktu</div><div>Keywords</div><div>Status</div>
      </div>

      <div id="root"></div>

      <div class="foot">
        <span>Jadwal ideal: <span class="btn-blue" style="padding:4px 10px;border-radius:999px">10:00</span> · <span class="btn-blue" style="padding:4px 10px;border-radius:999px">17:00</span> · <span class="btn-blue" style="padding:4px 10px;border-radius:999px">21:00</span> (GMT+6)</span>
        <span class="hint">Gunakan 3–5 hashtag saja per post untuk tampilan organik.</span>
      </div>
    </div>
  </div>

  <div class="preview">
    <div class="card tweet">
      <div class="hdr"><div class="avatar"></div><div><div class="name">CK44 Bangladesh</div><div class="user">@ck44_official</div></div></div>
      <div id="previewBody" class="body">Select a post to preview here…</div>
      <div id="previewMedia" class="media">Media Preview (AI Image / Minimal Card)</div>
      <div class="meta"><div>❤ 1.2K</div><div>🔁 210</div><div>👁 45K</div></div>
    </div>
  </div>
</div>

<script>
// Base content ideas (30 themes)
const themes = [
  "Luck is timing", "Chase mastery", "Lucky Neko feature", "Your luckiest moment", "PG Soft storytelling",
  "CK44 experience", "Never stop believing", "Fortune Tiger roar", "Rise energy", "Weekend chill",
  "JILI adrenaline", "Fun vs Fate", "Golden Empire feeling", "Small wins matter", "Balanced lifestyle",
  "Built step by step", "Unexpected big wins", "CK44 code", "Prep meets chance", "Every player has a story",
  "Rhythm not risk", "Now it’s your turn", "Fortune spins", "Tag your lucky friend", "Your vibe your tribe",
  "From 1 spin to 1M", "PG Soft mood?", "Memories stay", "Daily thrill", "Gratitude end"
];

// Games to rotate for 17:00 post
const games = [
  ["PG Soft","Lucky Neko"], ["PG Soft","Fortune Tiger"], ["PG Soft","Mahjong Ways 2"], ["PG Soft","Fortune Ox"], ["PG Soft","Ways of the Qilin"],
  ["PG Soft","Treasures of Aztec"], ["PG Soft","Dragon Tiger Luck"], ["PG Soft","Wild Bandito"], ["PG Soft","Dreams of Macau"], ["PG Soft","Candy Burst"],
  ["PG Soft","Reel Love"], ["PG Soft","Ganesha Fortune"], ["PG Soft","Symbols of Egypt"], ["PG Soft","Vampire's Charm"], ["PG Soft","Phoenix Rises"],
  ["JILI","Super Ace"], ["JILI","Boxing King"], ["JILI","Crazy Seven"], ["JILI","Roma X"], ["JILI","Golden Empire"],
  ["JILI","Money Coming"], ["JILI","Fortune Gems"], ["JILI","Pharaoh's Treasure"], ["JILI","Bao Boon Chin"], ["JILI","Mega Ace"],
  ["JILI","Phantom Thief"], ["JILI","Win Drop"], ["JILI","Charge Buffalo"], ["JILI","Jungle King"], ["JILI","Shanghai Beauty"]
];

function morningText(day){
  const lines = [
    "Luck is timing. CK44 is the moment. 🎰",
    "Some chase money. Others chase mastery. 💫",
    "Never stop spinning. Never stop believing. 🔁",
    "Success is built one spin at a time.",
    "There’s no such thing as luck — just preparation meeting chance.",
    "Morning coffee ☕, evening spins 🎰 — balance achieved.",
    "Your daily dose of thrill — CK44 style. ⚡",
  ];
  const l = lines[(day-1)%lines.length];
  return `${l}\n#CK44 #Bangladesh #PlaySmart`;
}

function afternoonText(day){
  const [brand, game] = games[(day-1)%games.length];
  const map = {
    "PG Soft": `Feature: ${game} by PG Soft — story-first, visually rich, and thrilling every spin.`,
    "JILI": `Highlight: ${game} by JILI — energetic, bold, and packed with adrenaline.`
  };
  return `${map[brand]}\n#CK44 #${brand.replace(' ','')} #${game.replace(/\\s+/g,'')} #Bangladesh`;
}

function nightText(day){
  const lines = [
    "Your luckiest moment? Drop your story 👇",
    "Tag your lucky friend who needs to try CK44!",
    "Big wins fade. Memories stay. Make yours today.",
    "Play smart, win smooth. That’s the CK44 code. 💎",
    "Some call it risk. We call it rhythm. 🎶",
    "We end this month not with luck, but with gratitude. 💛",
  ];
  const l = lines[(day-1)%lines.length];
  return `${l}\n#CK44 #Bangladesh #Community`;
}

function aiPrompt(theme){
  return `Create a clean X card in blue–gold CK44 style with minimal text '${theme}', subtle glow, CK44 logo corner, elegant composition.`;
}

const root = document.getElementById('root');

function render(){
  root.innerHTML = '';
  for(let i=1;i<=30;i++){
    const theme = themes[i-1] || `CK44 Day ${i}`;
    const details = document.createElement('details');
    const keywords = `CK44, Bangladesh, X Twitter, Organic, ${theme}`;
    details.innerHTML = `
      <summary>
        <div><span class="btn-blue" style="padding:4px 10px;border-radius:999px">Day ${i}</span></div>
        <div><strong>${theme}</strong></div>
        <div>10:00 • 17:00 • 21:00</div>
        <div class="kw">${keywords}</div>
        <div class="status"><input type="checkbox"/><span class="muted">Belum diposting</span></div>
      </summary>

      <div class="section">
        <div class="panel">
          <h3>🌞 Morning (10:00)</h3>
          <div class="row">
            <div>
              <label class="muted">Tweet Text</label>
              <textarea id="m-${i}">${morningText(i)}</textarea>
              <div class="copy-row">
                <button class="btn" onclick="copy('#m-${i}')">Copy Morning</button>
                <button class="btn" onclick="preview('Morning', ${i})">Preview</button>
              </div>
            </div>
            <div>
              <label class="muted">AI Image Prompt</label>
              <textarea id="mp-${i}">${aiPrompt('Morning Energy')}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#mp-${i}')">Copy Prompt</button></div>
            </div>
          </div>
        </div>

        <div class="panel">
          <h3>🎯 Afternoon (17:00)</h3>
          <div class="row">
            <div>
              <label class="muted">Tweet Text</label>
              <textarea id="a-${i}">${afternoonText(i)}</textarea>
              <div class="copy-row">
                <button class="btn" onclick="copy('#a-${i}')">Copy Afternoon</button>
                <button class="btn" onclick="preview('Afternoon', ${i})">Preview</button>
              </div>
            </div>
            <div>
              <label class="muted">AI Image Prompt</label>
              <textarea id="ap-${i}">${aiPrompt('Game Highlight')}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#ap-${i}')">Copy Prompt</button></div>
            </div>
          </div>
        </div>

        <div class="panel">
          <h3>🌙 Night (21:00)</h3>
          <div class="row">
            <div>
              <label class="muted">Tweet Text</label>
              <textarea id="n-${i}">${nightText(i)}</textarea>
              <div class="copy-row">
                <button class="btn" onclick="copy('#n-${i}')">Copy Night</button>
                <button class="btn" onclick="preview('Night', ${i})">Preview</button>
              </div>
            </div>
            <div>
              <label class="muted">AI Image Prompt</label>
              <textarea id="np-${i}">${aiPrompt('Community & Gratitude')}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#np-${i}')">Copy Prompt</button></div>
            </div>
          </div>
        </div>
      </div>
    `;
    root.appendChild(details);
  }
}
render();

// Search filter
document.getElementById('search').addEventListener('input', e => {
  const q = e.target.value.toLowerCase();
  [...root.children].forEach(item => {
    item.style.display = item.innerText.toLowerCase().includes(q) ? '' : 'none';
  });
});

// Copy helper
function copy(sel){
  const el = document.querySelector(sel);
  el.select(); el.setSelectionRange(0, 99999);
  document.execCommand('copy');
  el.style.outline='2px solid var(--cyan)';
  setTimeout(()=>{el.style.outline='none'},600);
}

// Toggle all checkboxes
function toggleAll(v){
  document.querySelectorAll('.status input[type="checkbox"]').forEach(cb => {
    cb.checked = v;
    const label = cb.nextElementSibling;
    label.textContent = v ? 'Sudah diposting' : 'Belum diposting';
    label.className = v ? 'done' : 'muted';
  });
}

// Per-item status
document.addEventListener('change',(e)=>{
  if(e.target.matches('.status input[type="checkbox"]')){
    const label = e.target.nextElementSibling;
    label.textContent = e.target.checked ? 'Sudah diposting' : 'Belum diposting';
    label.className = e.target.checked ? 'done' : 'muted';
  }
});

// Preview logic
function preview(slot, day){
  const body = document.getElementById('previewBody');
  const media = document.getElementById('previewMedia');
  const get = (id)=>document.getElementById(id).value.trim();

  const txt = slot==='Morning' ? get(`m-${day}`) : (slot==='Afternoon' ? get(`a-${day}`) : get(`n-${day}`));
  const prm = slot==='Morning' ? get(`mp-${day}`) : (slot==='Afternoon' ? get(`ap-${day}`) : get(`np-${day}`));

  body.textContent = txt;
  media.textContent = prm.length>0 ? "AI Visual: " + prm.slice(0,200) + (prm.length>200 ? "…" : "") : "Media Preview (AI Image / Minimal Card)";
}

// Export CSV
function exportCSV(){
  const headers = ['Day','Slot','Tweet','AIPrompt','Status'];
  const rows = [headers];
  [...root.children].forEach((det,i)=>{
    const idx = i+1;
    const slots = [['Morning',`m-${idx}`,`mp-${idx}`],['Afternoon',`a-${idx}`,`ap-${idx}`],['Night',`n-${idx}`,`np-${idx}`]];
    slots.forEach(s=>{
      const [slot, tid, pid] = s;
      const txt = document.getElementById(tid).value.replace(/\n/g,' ').trim();
      const prm = document.getElementById(pid).value.replace(/\n/g,' ').trim();
      const status = det.querySelector('.status input').checked ? 'Posted' : 'Not Posted';
      rows.push([idx,slot,txt,prm,status].map(v=>`"${String(v).replace(/"/g,'""')}"`).join(','));
    });
  });
  const csv = rows.join('\n');
  const blob = new Blob([csv], {type:'text/csv'});
  const url = URL.createObjectURL(blob);
  const a = document.createElement('a'); a.href=url; a.download='CK44_X_30Day.csv';
  document.body.appendChild(a); a.click(); document.body.removeChild(a); URL.revokeObjectURL(url);
}
</script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>CK44 Bangladesh – 30-Day YouTube Planner (PG Soft & JILI • Sora AI + SEO)</title>
<style>
  :root{
    --bg:#0a0f1c; --card:#0f172a; --text:#e5eaf3; --muted:#9fb0c6;
    --gold:#f6c453; --purple:#7c3aed; --cyan:#22d3ee; --green:#10b981; --border:#1f2a3d;
  }
  *{box-sizing:border-box}
  body{margin:0;background:linear-gradient(180deg,#080c16,#0a0f1c 40%,#0a0f1c);color:var(--text);
       font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial}
  .container{max-width:1200px;margin:34px auto;padding:0 16px}
  h1{margin:0 0 6px;font-size:clamp(22px,3.2vw,34px)}
  .subtitle{color:var(--muted);margin:0 0 16px;font-size:14px}
  .card{background:rgba(15,23,42,.9);border:1px solid var(--border);border-radius:18px;padding:18px;box-shadow:0 10px 30px rgba(0,0,0,.35)}
  .toolbar{display:flex;gap:10px;flex-wrap:wrap;margin:12px 0}
  input[type="text"], input[type="url"], textarea{width:100%;padding:10px 12px;background:#0b1220;color:var(--text);
    border:1px solid var(--border);border-radius:10px;outline:none}
  textarea{min-height:110px;resize:vertical}
  .btn{padding:10px 14px;border:1px solid var(--border);background:#0b1220;color:var(--text);
       border-radius:10px;cursor:pointer}
  .btn:hover{border-color:#314258}
  .btn-gold{background:linear-gradient(180deg,#231a0a,#141006);border-color:#3b2b0d;color:#ffd98a}
  .badge{display:inline-block;padding:2px 8px;border-radius:999px;border:1px solid #22324a;
         color:#cfe9ff;background:linear-gradient(180deg,#0c1a2a,#0a1220);font-size:12px}
  .pill{padding:6px 10px;border:1px solid var(--border);border-radius:999px;background:#0b1220}
  .table-head{display:grid;grid-template-columns:60px 1fr 180px 1fr 120px;gap:12px;
              padding:10px 16px;border:1px solid var(--border);border-radius:12px;background:#0b1220;color:#cbd5e1;font-size:13px}
  details{border:1px solid var(--border);border-radius:14px;background:#0b1220;margin-top:10px}
  summary{list-style:none;padding:14px 16px;cursor:pointer;border-bottom:1px solid rgba(255,255,255,.06);
          display:grid;grid-template-columns:60px 1fr 180px 1fr 120px;gap:12px;align-items:center}
  summary::-webkit-details-marker{display:none}
  .kw{color:#a7f3d0}
  .times{display:flex;gap:8px;flex-wrap:wrap}
  .status{display:flex;align-items:center;gap:8px}
  .status input{width:18px;height:18px;cursor:pointer}
  .muted{color:var(--muted)}
  .done{color:var(--green);font-weight:600}
  .section{padding:14px 16px;display:grid;grid-template-columns:1.1fr .9fr;gap:16px}
  .copy-row{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px}
  .foot{display:flex;gap:12px;flex-wrap:wrap;margin-top:14px;color:#aab5c8;font-size:13px}
  .search{flex:1;min-width:260px}
  @media (max-width:900px){
    summary, .table-head{grid-template-columns:60px 1fr 1fr; }
    summary .kw, .table-head div:nth-child(4){display:none}
    summary .status, .table-head div:nth-child(5){display:none}
    .section{grid-template-columns:1fr}
  }
</style>
</head>
<body>
<div class="container">
  <div class="card">
    <h1>CK44 বাংলাদেশ – 30-Day YouTube Planner (PG Soft & JILI)</h1>
    <p class="subtitle">100% fokus pengenalan & promosi game • Sora AI prompts • Jadwal posting • Keywords & Hashtags • Checklist • Export CSV</p>

    <div class="toolbar">
      <input id="search" class="search" type="text" placeholder="Cari judul / game / keyword…" />
      <button class="btn" onclick="toggleAll(true)">Centang semua</button>
      <button class="btn" onclick="toggleAll(false)">Kosongkan centang</button>
      <button class="btn btn-gold" onclick="exportCSV()">Export CSV</button>
    </div>

    <div class="table-head">
      <div>Day</div><div>Judul Video</div><div>Posting (GMT+6)</div><div>Keyword</div><div>Status</div>
    </div>

    <div id="root"></div>

    <div class="foot">
      <span>Waktu ideal: <span class="badge">18:00 (Shorts 9:16)</span> & <span class="badge">21:00 (Long 16:9)</span></span>
      <span>Gunakan tone <span class="badge" style="border-color:#4b2;">Gold</span> / <span class="badge" style="border-color:#26a;">Cyan</span> / <span class="badge" style="border-color:#83f;">Purple</span> untuk thumbnail.</span>
    </div>
  </div>
</div>

<script>
// 30-day hybrid plan: 15 PG Soft + 15 JILI (alternating).
// Titles, prompts, narrations, keywords, hashtags tailored for showcase & promo.
const plan = [
  // Day 1–15 PG Soft focus (examples of popular themes/titles)
  {brand:"PG Soft", game:"Lucky Neko", title:"PG Soft – Lucky Neko • CK44 Game Showcase", times:["18:00","21:00"], keywords:["PG Soft Lucky Neko","CK44 Bangladesh","slot showcase"], hashtags:"#PGSoft #LuckyNeko #CK44 #Bangladesh", narration:"আজকের গেম: Lucky Neko by PG Soft — smooth spin, bright wins. Play at CK44 Bangladesh!", prompt:"Create a 4K cinematic showcase for 'Lucky Neko' style slot theme: lucky cat, neon pink-purple ambiance, gold coins sparkle, elegant CK44 logo intro and outro; camera dolly-in on reels; crisp typography 'Play Now at CK44 Bangladesh'."},
  {brand:"JILI", game:"Super Ace", title:"JILI – Super Ace • Trailer & Bonus Info (CK44)", times:["18:00","21:00"], keywords:["JILI Super Ace","CK44 promo","bonus 50"], hashtags:"#JILI #SuperAce #CK44 #Bonus", narration:"Super Ace from JILI — fast reels, powerful combos. Bonus info inside — CK44 Bangladesh.", prompt:"Produce a fast-paced 4K trailer for 'Super Ace' style slot theme: electric neon, card symbols bursting, gold light flares, CK44 taglines; quick cuts synced to EDM; final card says 'Bonus Today • CK44 Bangladesh'."},
  {brand:"PG Soft", game:"Fortune Tiger", title:"PG Soft – Fortune Tiger • Quick Guide (Bangla)", times:["18:00","21:00"], keywords:["PG Soft Fortune Tiger","how to play","Bangla guide"], hashtags:"#PGSoft #FortuneTiger #CK44 #Guide", narration:"Bangla quick guide: how to play Fortune Tiger — simple, fast, and fun on CK44.", prompt:"Design a 4K educational short showing tap-to-play steps for 'Fortune Tiger' theme: golden tiger statue, warm lighting, UI highlights, step 1-2-3 captions, CK44 logo corner watermark; end slate 'Play Responsibly'."},
  {brand:"JILI", game:"Boxing King", title:"JILI – Boxing King • Highlight & KO Moments", times:["18:00","21:00"], keywords:["JILI Boxing King","highlight","KO moment"], hashtags:"#JILI #BoxingKing #CK44 #Highlight", narration:"Boxing King highlight — KO moments and fast punches! Watch now on CK44.", prompt:"Create a sports-arcade 4K highlight reel for 'Boxing King' vibe: ring lights, gloves punch effects, dynamic hit counters, golden sparks; CK44 banner transitions; finishing slate 'Try at CK44 Bangladesh'."},
  {brand:"PG Soft", game:"Mahjong Ways 2", title:"PG Soft – Mahjong Ways 2 • Tips & Tricks", times:["18:00","21:00"], keywords:["PG Soft Mahjong Ways 2","tips & tricks","CK44"], hashtags:"#PGSoft #MahjongWays2 #CK44 #Tips", narration:"Top 3 tips for Mahjong Ways 2 — simple & effective for new players at CK44.", prompt:"4K tutorial board: jade-green & gold palette; show tile-matching vibe, numbers overlay for tips 1-3; glowing arrows; CK44 logo in footer; clean typography, no clutter."},
  {brand:"JILI", game:"Crazy Seven", title:"JILI – Crazy Seven • Energy Trailer", times:["18:00","21:00"], keywords:["JILI Crazy Seven","trailer","energy"], hashtags:"#JILI #CrazySeven #CK44 #Trailer", narration:"Crazy Seven — upbeat, energetic, explosive symbols. CK44 Bangladesh showcase.", prompt:"High-energy 4K trailer: glowing 7 symbols, blue-cyan electricity, coin burst transitions, bass hits; CK44 logo intro/outro; callout 'Spin Now'."},
  {brand:"PG Soft", game:"Fortune Ox", title:"PG Soft – Fortune Ox • Big Moments Montage", times:["18:00","21:00"], keywords:["Fortune Ox montage","PG Soft big win","CK44"], hashtags:"#PGSoft #FortuneOx #CK44 #Montage", narration:"Fortune Ox montage — epic spins & golden charge. Only on CK44 Bangladesh.", prompt:"Create a 4K montage: golden ox charge rush, coin rain, reels zoom; rhythmic cuts; CK44 golden frame; end screen 'Join CK44'."},
  {brand:"JILI", game:"Roma X", title:"JILI – Roma X • Cinematic Showcase", times:["18:00","21:00"], keywords:["JILI Roma X","cinematic slot","CK44 Bangladesh"], hashtags:"#JILI #RomaX #CK44 #Cinematic", narration:"Step into the arena — Roma X cinematic showcase • CK44 Bangladesh.", prompt:"4K epic showcase: roman arena, shields & swords glint, crimson banners; slot vibe transitions; CK44 crest; dramatic choir hits."},
  {brand:"PG Soft", game:"Ways of the Qilin", title:"PG Soft – Ways of the Qilin • Trailer (4K)", times:["18:00","21:00"], keywords:["PG Soft Qilin","trailer 4K","CK44"], hashtags:"#PGSoft #Qilin #CK44 #4K", narration:"Mystical Qilin — luminous greens & ancient luck. CK44 trailer today.", prompt:"Mythic 4K trailer: jade Qilin statue, misty mountains, gold runes glow; smooth camera; CK44 neon-gold title at end."},
  {brand:"JILI", game:"Golden Empire", title:"JILI – Golden Empire • Feature Highlights", times:["18:00","21:00"], keywords:["JILI Golden Empire","feature","CK44"], hashtags:"#JILI #GoldenEmpire #CK44 #Features", narration:"Golden Empire features — crisp highlights in 45 seconds. CK44 Bangladesh.", prompt:"4K feature highlight: ancient temple gold, rolling reels, quick text callouts: Wild • Scatter • Multiplier; gold/cyan accents; CK44 watermark."},
  {brand:"PG Soft", game:"Treasures of Aztec", title:"PG Soft – Treasures of Aztec • Short Trailer", times:["18:00","21:00"], keywords:["PG Soft Treasures of Aztec","short trailer","CK44"], hashtags:"#PGSoft #Aztec #CK44 #Trailer", narration:"Explore Aztec riches — short trailer edition • CK44 Bangladesh.", prompt:"4K short: jungle ruins, glowing glyphs, gold dust; fast push-in to reels; CK44 logo outro; upbeat tribal percussion."},
  {brand:"JILI", game:"Money Coming", title:"JILI – Money Coming • Quick Promo", times:["18:00","21:00"], keywords:["JILI Money Coming","promo","CK44"], hashtags:"#JILI #MoneyComing #CK44 #Promo", narration:"Money Coming — bright & lucky vibe. Try it today at CK44.", prompt:"4K promo: cheerful gold-green palette, dancing coins, pop typography 'Money Coming'; CK44 'Play Now' button animation."},
  {brand:"PG Soft", game:"Dragon Tiger Luck", title:"PG Soft – Dragon Tiger Luck • Aesthetic Reel", times:["18:00","21:00"], keywords:["PG Soft Dragon Tiger Luck","aesthetic","CK44"], hashtags:"#PGSoft #DragonTiger #CK44 #Aesthetic", narration:"Dragon & Tiger — balanced power, clean aesthetic • CK44.", prompt:"4K aesthetic: split red dragon / blue tiger energy, yin-yang symmetry, slow camera glide; minimal clean text 'CK44 Bangladesh'."},
  {brand:"JILI", game:"Fortune Gems", title:"JILI – Fortune Gems • Neon Showcase", times:["18:00","21:00"], keywords:["JILI Fortune Gems","neon showcase","CK44"], hashtags:"#JILI #FortuneGems #CK44 #Neon", narration:"Neon gems — bright, punchy, satisfying. CK44 showcase.", prompt:"4K neon showcase: glowing gems rotate, refractive sparkles, upbeat transitions, CK44 end card 'Spin Today'."},
  {brand:"PG Soft", game:"Wild Bandito", title:"PG Soft – Wild Bandito • Music & Mood", times:["18:00","21:00"], keywords:["PG Soft Wild Bandito","music mood","CK44"], hashtags:"#PGSoft #WildBandito #CK44 #Vibes", narration:"Wild Bandito — guitar riff & thrilling mood • CK44.", prompt:"4K mood reel: night city fiesta, guitar strums sync with cuts, bandit mask flashes, CK44 neon signage."},

  // Day 16–30 JILI/PG alternating continued
  {brand:"JILI", game:"Pharaoh's Treasure", title:"JILI – Pharaoh's Treasure • Short Trailer", times:["18:00","21:00"], keywords:["JILI Pharaoh's Treasure","trailer","CK44"], hashtags:"#JILI #PharaohsTreasure #CK44 #Trailer", narration:"Ancient treasure waits — Pharaoh’s Treasure at CK44.", prompt:"4K short: desert pyramid glow, hieroglyphs, gold beam opening chest; CK44 end slate."},
  {brand:"PG Soft", game:"Dreams of Macau", title:"PG Soft – Dreams of Macau • Lux Showcase", times:["18:00","21:00"], keywords:["PG Soft Dreams of Macau","luxury","CK44"], hashtags:"#PGSoft #Macau #CK44 #Lux", narration:"Macau nights — luxury lights & wins • CK44.", prompt:"4K luxury reel: city neon, roulette bokeh, soft lens flares, CK44 logo in gold."},
  {brand:"JILI", game:"Bao Boon Chin", title:"JILI – Bao Boon Chin • Feature Focus", times:["18:00","21:00"], keywords:["JILI Bao Boon Chin","features","CK44"], hashtags:"#JILI #BaoBoonChin #CK44 #Features", narration:"Bao Boon Chin — feature focus in 60 seconds • CK44.", prompt:"4K feature explainer: martial motif, clean labels for Wild/Scatter/Bonus; CK44 watermark; cyan/gold UI."},
  {brand:"PG Soft", game:"Candy Burst", title:"PG Soft – Candy Burst • Fun & Bright", times:["18:00","21:00"], keywords:["PG Soft Candy Burst","fun bright","CK44"], hashtags:"#PGSoft #CandyBurst #CK44 #Fun", narration:"Sweet vibes only — Candy Burst highlights • CK44.", prompt:"4K fun reel: candy explosions, pastel neon, upbeat bounce music; CK44 end button."},
  {brand:"JILI", game:"Mega Ace", title:"JILI – Mega Ace • Power Teaser", times:["18:00","21:00"], keywords:["JILI Mega Ace","teaser","CK44"], hashtags:"#JILI #MegaAce #CK44 #Teaser", narration:"Mega Ace — power-packed teaser on CK44.", prompt:"4K power teaser: card A ace lightning, chrome reflections, bass hits; CK44 'Play Now'."},
  {brand:"PG Soft", game:"Reel Love", title:"PG Soft – Reel Love • Romantic Vibe", times:["18:00","21:00"], keywords:["PG Soft Reel Love","romantic vibe","CK44"], hashtags:"#PGSoft #ReelLove #CK44 #Romance", narration:"Romantic spin — soft pink/cyan lights • CK44.", prompt:"4K romantic montage: heart-shaped flares, glossy text, soft motion graphics; CK44 watermark."},
  {brand:"JILI", game:"Phantom Thief", title:"JILI – Phantom Thief • Sneak Peek", times:["18:00","21:00"], keywords:["JILI Phantom Thief","sneak peek","CK44"], hashtags:"#JILI #PhantomThief #CK44 #SneakPeek", narration:"Steal the spotlight — Phantom Thief sneak peek • CK44.", prompt:"4K noir style: city night, silhouette thief, blue neon edge light; fast cut to reels; CK44 glow outro."},
  {brand:"PG Soft", game:"Ganesha Fortune", title:"PG Soft – Ganesha Fortune • Calm Trailer", times:["18:00","21:00"], keywords:["PG Soft Ganesha Fortune","calm trailer","CK44"], hashtags:"#PGSoft #GaneshaFortune #CK44 #Trailer", narration:"Calm & blessed — Ganesha Fortune at CK44.", prompt:"4K serene trailer: warm golden temple light, gentle particles, tasteful typography; CK44 end slate."},
  {brand:"JILI", game:"Win Drop", title:"JILI – Win Drop • Quick Promo", times:["18:00","21:00"], keywords:["JILI Win Drop","promo CK44","Bangladesh"], hashtags:"#JILI #WinDrop #CK44 #Promo", narration:"Win Drop — quick promo day at CK44 Bangladesh.", prompt:"4K promo: dynamic number drops, confetti, cyan-gold palette; CTA 'Play Today'."},
  {brand:"PG Soft", game:"Symbols of Egypt", title:"PG Soft – Symbols of Egypt • Short Feature", times:["18:00","21:00"], keywords:["Symbols of Egypt","PG Soft feature","CK44"], hashtags:"#PGSoft #SymbolsOfEgypt #CK44 #Feature", narration:"Symbols of Egypt — crisp feature points • CK44.", prompt:"4K feature short: desert night blue, glowing symbols, minimal captions; CK44 corner logo."},
  {brand:"JILI", game:"Charge Buffalo", title:"JILI – Charge Buffalo • Power Reel", times:["18:00","21:00"], keywords:["JILI Charge Buffalo","power reel","CK44"], hashtags:"#JILI #ChargeBuffalo #CK44 #Power", narration:"Feel the charge — Charge Buffalo showcase • CK44.", prompt:"4K power reel: buffalo charge dust, sunset orange glow, epic drums; CK44 frame."},
  {brand:"PG Soft", game:"Vampire's Charm", title:"PG Soft – Vampire's Charm • Dark Aesthetic", times:["18:00","21:00"], keywords:["Vampire's Charm","PG Soft dark","CK44"], hashtags:"#PGSoft #VampiresCharm #CK44 #Aesthetic", narration:"Dark & elegant — Vampire’s Charm visual • CK44.", prompt:"4K dark aesthetic: crimson velvet, glass shards, neon edge lights; CK44 signet."},
  {brand:"JILI", game:"Jungle King", title:"JILI – Jungle King • Adventure Trailer", times:["18:00","21:00"], keywords:["JILI Jungle King","adventure","CK44"], hashtags:"#JILI #JungleKing #CK44 #Adventure", narration:"Jungle King adventure — roar & rewards at CK44.", prompt:"4K adventure: lush jungle, roaring king, drum beats; reels overlay; CK44 end card."},
  {brand:"PG Soft", game:"Phoenix Rises", title:"PG Soft – Phoenix Rises • Flame Showcase", times:["18:00","21:00"], keywords:["Phoenix Rises","PG Soft flame","CK44"], hashtags:"#PGSoft #PhoenixRises #CK44 #Flame", narration:"Rise with the flame — Phoenix Rises at CK44.", prompt:"4K flame showcase: phoenix wings of fire, ember bursts, slow-mo feathers; CK44 golden glow."},
  {brand:"JILI", game:"Shanghai Beauty", title:"JILI – Shanghai Beauty • Elegant Reel", times:["18:00","21:00"], keywords:["JILI Shanghai Beauty","elegant reel","CK44"], hashtags:"#JILI #ShanghaiBeauty #CK44 #Elegant", narration:"Elegant & classy — Shanghai Beauty on CK44.", prompt:"4K elegant reel: city neon, silk fabric motion, soft piano; CK44 outro label."},
  {brand:"PG Soft", game:"Majestic Treasures", title:"PG Soft – Majestic Treasures • Gem Trailer", times:["18:00","21:00"], keywords:["Majestic Treasures","PG Soft gems","CK44"], hashtags:"#PGSoft #MajesticTreasures #CK44 #Gems", narration:"Majestic Treasures — gem glow & golden tone • CK44.", prompt:"4K gem trailer: refractive jewels, gold trims, clear bold titles; CK44 'Play Now'."}
];

const root = document.getElementById('root');

function render(){
  root.innerHTML = '';
  plan.forEach((d,i)=>{
    const idx = i+1;
    const details = document.createElement('details');
    const kw = [d.brand, d.game].concat(d.keywords||[]).join(', ');
    details.innerHTML = `
      <summary>
        <div><span class="badge">Day ${idx}</span></div>
        <div><strong>${d.title}</strong> <span class="badge">${d.brand}</span> <span class="badge">${d.game}</span></div>
        <div class="times"><span class="pill">Shorts ${d.times[0]}</span><span class="pill">Long ${d.times[1]}</span></div>
        <div class="kw">${kw}</div>
        <div class="status"><input type="checkbox" aria-label="status ${idx}"/><span class="muted">Belum diposting</span></div>
      </summary>
      <div class="section">
        <div>
          <label class="muted">Sora AI Prompt</label>
          <textarea id="p-${idx}">${d.prompt}</textarea>
          <div class="copy-row">
            <button class="btn" onclick="copy('#p-${idx}')">Copy Prompt</button>
          </div>
          <label class="muted" style="margin-top:10px;">Narration (Bangla + English)</label>
          <textarea id="n-${idx}">${d.narration}</textarea>
          <div class="copy-row">
            <button class="btn" onclick="copy('#n-${idx}')">Copy Narration</button>
          </div>
          <label class="muted" style="margin-top:10px;">YouTube Description Template</label>
          <textarea id="d-{idx}">🔥 Welcome to CK44 Bangladesh 🔥
🎮 Game: {game} ({brand})
Experience the excitement of {game} by {brand} — now available on CK44 Bangladesh!

💎 Enjoy exclusive bonuses, daily rewards, and VIP privileges only at CK44.
👉 Join the action today and spin your luck!

🌐 Visit: www.ck44.com
📱 Follow for daily updates & rewards

#CK44 #Bangladesh #{brand} #{game} #Casino #Gaming #Bonus #Slots</textarea>
          <div class="copy-row">
            <button class="btn" onclick="copy('#d-{idx}')">Copy Description</button>
          </div>

        </div>
        <div>
          <label class="muted">Keywords</label>
          <textarea id="k-${idx}">${kw}</textarea>
          <div class="copy-row">
            <button class="btn" onclick="copy('#k-${idx}')">Copy Keywords</button>
          </div>
          <label class="muted">Hashtags</label>
          <textarea id="h-${idx}">${d.hashtags}</textarea>
          <div class="copy-row">
            <button class="btn" onclick="copy('#h-${idx}')">Copy Hashtags</button>
          </div>
          <label class="muted">Link YouTube</label>
          <input id="l-${idx}" type="url" placeholder="https://youtube.com/..." />
        </div>
      </div>
    `;
    root.appendChild(details);
  });
}
render();

// Search filter
document.getElementById('search').addEventListener('input', e => {
  const q = e.target.value.toLowerCase();
  [...root.children].forEach(item => {
    item.style.display = item.innerText.toLowerCase().includes(q) ? '' : 'none';
  });
});

// Copy helper
function copy(sel){
  const el = document.querySelector(sel);
  el.select(); el.setSelectionRange(0, 99999);
  document.execCommand('copy');
  el.style.outline='2px solid var(--cyan)';
  setTimeout(()=>{el.style.outline='none'},600);
}

// Toggle all checkboxes
function toggleAll(v){
  document.querySelectorAll('.status input[type="checkbox"]').forEach(cb => {
    cb.checked = v;
    const label = cb.nextElementSibling;
    label.textContent = v ? 'Sudah diposting' : 'Belum diposting';
    label.className = v ? 'done' : 'muted';
  });
}

// Update single checkbox label
document.addEventListener('change', (e)=>{
  if(e.target.matches('.status input[type="checkbox"]')){
    const label = e.target.nextElementSibling;
    label.textContent = e.target.checked ? 'Sudah diposting' : 'Belum diposting';
    label.className = e.target.checked ? 'done' : 'muted';
  }
});

// Export CSV
function exportCSV(){
  const headers = ['Day','Brand','Game','Title','ShortsTime','LongTime','Keywords','Hashtags','Narration','Prompt','Status','YouTubeLink'];
  const rows = [headers];
  [...root.children].forEach((det, i)=>{
    const idx = i+1;
    const brand = det.querySelectorAll('.badge')[1].innerText;
    const game  = det.querySelectorAll('.badge')[2].innerText;
    const title = det.querySelector('strong').innerText.trim();
    const times = [...det.querySelectorAll('.pill')].map(x=>x.innerText.replace('Shorts ','').replace('Long ',''));
    const kw = det.querySelector('textarea[id^="k-"]').value.replace(/\n/g,' ').trim();
    const tag = det.querySelector('textarea[id^="h-"]').value.replace(/\n/g,' ').trim();
    const nar = det.querySelector('textarea[id^="n-"]').value.replace(/\n/g,' ').trim();
    const pr = det.querySelector('textarea[id^="p-"]').value.replace(/\n/g,' ').trim();
    const status = det.querySelector('.status input').checked ? 'Posted' : 'Not Posted';
    const link = det.querySelector('input[type="url"]').value.trim();
    rows.push([idx,brand,game,title,times[0]||'',times[1]||'',kw,tag,nar,pr,status,link]);
  });
  const csv = rows.map(r => r.map(v=>`"${String(v).replace(/"/g,'""')}"`).join(',')).join('\n');
  const blob = new Blob([csv], {type:'text/csv'});
  const url = URL.createObjectURL(blob);
  const a = document.createElement('a'); a.href=url; a.download='CK44_PGSoft_JILI_YouTube_30Day.csv';
  document.body.appendChild(a); a.click(); document.body.removeChild(a); URL.revokeObjectURL(url);
}
</script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>CK44 Bangladesh – Instagram 30-Day Planner (PG Soft & JILI)</title>
<style>
  :root{
    --bg:#0b0a14; --card:#120f1f; --panel:#17142a;
    --text:#efeafc; --muted:#bcaee6; --gold:#f5d061; --purple:#7c3aed; --accent:#22d3ee;
    --border:#2b2542; --success:#10b981;
  }
  *{box-sizing:border-box}
  body{margin:0;background:radial-gradient(1200px 700px at 20% -10%,rgba(124,58,237,.18),transparent),
                      radial-gradient(1200px 700px at 90% 10%,rgba(245,208,97,.15),transparent),
                      linear-gradient(180deg,#0b0a14,#0d0b18 40%,#0b0a14);
       color:var(--text);font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial}
  .container{max-width:1200px;margin:36px auto;padding:0 16px}
  h1{margin:0 0 6px;font-size:clamp(22px,3.2vw,34px)}
  .subtitle{color:var(--muted);margin:0 0 18px;font-size:14px}
  .card{background:linear-gradient(180deg,rgba(18,15,31,.9),rgba(18,15,31,.92));
        border:1px solid var(--border);border-radius:18px;padding:18px;box-shadow:0 12px 30px rgba(0,0,0,.45)}
  .toolbar{display:flex;gap:10px;flex-wrap:wrap;margin:10px 0 14px}
  input[type="text"],input[type="url"],textarea{width:100%;padding:10px 12px;background:#0f0c1f;
      color:var(--text);border:1px solid var(--border);border-radius:10px;outline:none}
  textarea{min-height:100px;resize:vertical}
  .btn{padding:10px 14px;border:1px solid var(--border);background:#120f1f;color:var(--text);border-radius:10px;cursor:pointer}
  .btn:hover{border-color:#3a3457}
  .btn-gold{background:linear-gradient(180deg,#2a2214,#181104);border-color:#4a3914;color:#ffe39b}
  .badge{display:inline-block;padding:2px 8px;border-radius:999px;border:1px solid #3a2a62;
         background:linear-gradient(180deg,#1a1530,#140f26);color:#e9dcff;font-size:12px}
  .pill{padding:6px 10px;border:1px solid var(--border);border-radius:999px;background:#120f1f}
  .table-head{display:grid;grid-template-columns:70px 1.2fr .9fr 1fr 120px;gap:12px;
              padding:10px 16px;border:1px solid var(--border);border-radius:12px;background:#120f1f;color:#d9cfff;font-size:13px}
  details{border:1px solid var(--border);border-radius:14px;background:#120f1f;margin-top:10px}
  summary{list-style:none;padding:14px 16px;cursor:pointer;border-bottom:1px solid rgba(255,255,255,.06);
          display:grid;grid-template-columns:70px 1.2fr .9fr 1fr 120px;gap:12px;align-items:center}
  summary::-webkit-details-marker{display:none}
  .kw{color:#b0f6ef}
  .status{display:flex;align-items:center;gap:8px}
  .status input{width:18px;height:18px;cursor:pointer}
  .muted{color:var(--muted)}
  .done{color:var(--success);font-weight:600}
  .section{padding:14px 16px;display:grid;grid-template-columns:1fr 1fr;gap:16px}
  .panel{background:var(--panel);border:1px solid var(--border);border-radius:14px;padding:12px}
  .panel h3{margin:0 0 8px;font-size:16px;color:#ffe39b}
  .row{display:grid;grid-template-columns:.9fr 1.1fr;gap:12px}
  .copy-row{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px}
  .foot{display:flex;gap:12px;flex-wrap:wrap;margin-top:14px;color:#c9bdf0;font-size:13px}
  .search{flex:1;min-width:260px}
  .hint{font-size:12px;color:#d7c7ff}
  @media (max-width:980px){summary,.table-head{grid-template-columns:70px 1fr 1fr}
    summary .kw, .table-head div:nth-child(4){display:none}
    summary .status, .table-head div:nth-child(5){display:none}
    .section{grid-template-columns:1fr}
    .row{grid-template-columns:1fr}
  }
</style>
</head>
<body>
<div class="container">
  <div class="card">
    <h1>CK44 – Instagram 30-Day Planner (PG Soft & JILI)</h1>
    <p class="subtitle">Gold–Purple theme • Reels • Story • Feed • AI prompts • Captions • Hashtags • Schedule • Checklist • Export CSV</p>

    <div class="toolbar">
      <input id="search" class="search" type="text" placeholder="Cari game / brand / keyword…"/>
      <button class="btn" onclick="toggleAll(true)">Centang semua</button>
      <button class="btn" onclick="toggleAll(false)">Kosongkan centang</button>
      <button class="btn btn-gold" onclick="exportCSV()">Export CSV</button>
    </div>

    <div class="table-head">
      <div>Day</div><div>Game / Title</div><div>Brand</div><div>Keywords</div><div>Status</div>
    </div>

    <div id="root"></div>

    <div class="foot">
      <span>Jam ideal: <span class="badge">Story 12:00 & 20:30</span> · <span class="badge">Reels 19:30</span> · <span class="badge">Feed 17:00</span> (GMT+6)</span>
      <span class="hint">Gunakan warna <b style="color:#ffd76d">gold</b> + <b style="color:#a78bfa">purple</b> + <b style="color:#8df3ff">cyan</b> untuk konsistensi CK44.</span>
    </div>
  </div>
</div>

<script>
// Alternating PG Soft & JILI with curated games
const plan = [
  {brand:"PG Soft", game:"Lucky Neko"},
  {brand:"JILI", game:"Super Ace"},
  {brand:"PG Soft", game:"Fortune Tiger"},
  {brand:"JILI", game:"Boxing King"},
  {brand:"PG Soft", game:"Mahjong Ways 2"},
  {brand:"JILI", game:"Crazy Seven"},
  {brand:"PG Soft", game:"Fortune Ox"},
  {brand:"JILI", game:"Roma X"},
  {brand:"PG Soft", game:"Ways of the Qilin"},
  {brand:"JILI", game:"Golden Empire"},
  {brand:"PG Soft", game:"Treasures of Aztec"},
  {brand:"JILI", game:"Money Coming"},
  {brand:"PG Soft", game:"Dragon Tiger Luck"},
  {brand:"JILI", game:"Fortune Gems"},
  {brand:"PG Soft", game:"Wild Bandito"},
  {brand:"JILI", game:"Pharaoh's Treasure"},
  {brand:"PG Soft", game:"Dreams of Macau"},
  {brand:"JILI", game:"Bao Boon Chin"},
  {brand:"PG Soft", game:"Candy Burst"},
  {brand:"JILI", game:"Mega Ace"},
  {brand:"PG Soft", game:"Reel Love"},
  {brand:"JILI", game:"Phantom Thief"},
  {brand:"PG Soft", game:"Ganesha Fortune"},
  {brand:"JILI", game:"Win Drop"},
  {brand:"PG Soft", game:"Symbols of Egypt"},
  {brand:"JILI", game:"Charge Buffalo"},
  {brand:"PG Soft", game:"Vampire's Charm"},
  {brand:"JILI", game:"Jungle King"},
  {brand:"PG Soft", game:"Phoenix Rises"},
  {brand:"JILI", game:"Shanghai Beauty"}
];

function reelsPrompt(brand, game){
  return `Create a 4K vertical (9:16) cinematic Reels clip for ${brand} “${game}”: gold–purple CK44 aesthetic, glowing coins, clean typography with “Play Now at CK44 Bangladesh”, dynamic camera moves, crisp sharp focus, 60fps.`;
}
function reelsCaption(brand, game){
  return `🎰 ${game} by ${brand}
আজকের ভাগ্যবান স্পিন! Play now on CK44 Bangladesh 💎
#CK44 #${brand.replace(' ','')} #${game.replace(/\\s+/g,'')} #Bangladesh #Slots #Gaming #CasinoVibes`;
}
function storyBonusPrompt(){
  return "Design a minimal gold–purple story card: '🎁 Bonus Hari Ini 50% — CK44 Bangladesh — www.ck44.com' with glowing frame and soft bokeh.";
}
function storyJoinPrompt(){
  return "Create a bold CTA story: 'Join CK44 Now — Play & Win' gold aura, big button style, clean text, CK44 logo bottom.";
}
function storyCaptionBonus(){
  return "🎁 Bonus Hari Ini 50% — CK44 Bangladesh\nTap link • Play responsibly";
}
function storyCaptionJoin(){
  return "💎 Join CK44 Now — Spin your luck tonight!";
}
function feedPrompt(brand, game){
  return `Create a square 1:1 poster for ${brand} “${game}”: elegant gold frame, purple gradient background, CK44 logo, tagline “Play & Win Today”, clean composition.`;
}
function feedCaption(brand, game){
  return `🌟 Game Highlight: ${game} by ${brand}
Win, shine, and celebrate your luck on CK44 Bangladesh!
#CK44 #${brand.replace(' ','')} #${game.replace(/\\s+/g,'')} #Bangladesh #CasinoVibes`;
}

const root = document.getElementById('root');

function render(){
  root.innerHTML = '';
  plan.forEach((d,i)=>{
    const idx = i+1;
    const keywords = `${d.brand}, ${d.game}, CK44 Bangladesh, Instagram Reels, Story, Feed`;
    const details = document.createElement('details');
    details.innerHTML = `
      <summary>
        <div><span class="badge">Day ${idx}</span></div>
        <div><strong>${d.game}</strong></div>
        <div><span class="badge">${d.brand}</span></div>
        <div class="kw">${keywords}</div>
        <div class="status"><input type="checkbox"/><span class="muted">Belum diposting</span></div>
      </summary>

      <div class="section">
        <div class="panel">
          <h3>🎥 Reels (19:30)</h3>
          <div class="row">
            <div>
              <label class="muted">Sora / Video Prompt</label>
              <textarea id="rp-${idx}">${reelsPrompt(d.brand,d.game)}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#rp-${idx}')">Copy Prompt</button></div>
            </div>
            <div>
              <label class="muted">Caption</label>
              <textarea id="rc-${idx}">${reelsCaption(d.brand,d.game)}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#rc-${idx}')">Copy Caption</button></div>
              <label class="muted">Link Reels</label>
              <input id="rl-${idx}" type="url" placeholder="https://instagram.com/reel/..." />
            </div>
          </div>
        </div>

        <div class="panel">
          <h3>📱 Story (12:00 & 20:30)</h3>
          <div class="row">
            <div>
              <label class="muted">Prompt (Bonus 12:00)</label>
              <textarea id="sbp-${idx}">${storyBonusPrompt()}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#sbp-${idx}')">Copy Prompt</button></div>
              <label class="muted">Caption</label>
              <textarea id="sbc-${idx}">${storyCaptionBonus()}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#sbc-${idx}')">Copy Caption</button></div>
            </div>
            <div>
              <label class="muted">Prompt (Join 20:30)</label>
              <textarea id="sjp-${idx}">${storyJoinPrompt()}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#sjp-${idx}')">Copy Prompt</button></div>
              <label class="muted">Caption</label>
              <textarea id="sjc-${idx}">${storyCaptionJoin()}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#sjc-${idx}')">Copy Caption</button></div>
            </div>
          </div>
        </div>

        <div class="panel">
          <h3>🖼️ Feed (17:00) ${idx%3===0 ? '' : '<span class="hint">• optional today</span>'}</h3>
          <div class="row">
            <div>
              <label class="muted">Image Prompt</label>
              <textarea id="fp-${idx}">${feedPrompt(d.brand,d.game)}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#fp-${idx}')">Copy Prompt</button></div>
            </div>
            <div>
              <label class="muted">Caption</label>
              <textarea id="fc-${idx}">${feedCaption(d.brand,d.game)}</textarea>
              <div class="copy-row"><button class="btn" onclick="copy('#fc-${idx}')">Copy Caption</button></div>
              <label class="muted">Link Post</label>
              <input id="fl-${idx}" type="url" placeholder="https://instagram.com/p/..." />
            </div>
          </div>
        </div>
      </div>
    `;
    root.appendChild(details);
  });
}
render();

// Search filter
document.getElementById('search').addEventListener('input', e => {
  const q = e.target.value.toLowerCase();
  [...root.children].forEach(item => {
    item.style.display = item.innerText.toLowerCase().includes(q) ? '' : 'none';
  });
});

// Copy helper
function copy(sel){
  const el = document.querySelector(sel);
  el.select(); el.setSelectionRange(0, 99999);
  document.execCommand('copy');
  el.style.outline='2px solid var(--accent)';
  setTimeout(()=>{el.style.outline='none'},600);
}

// Toggle all checkboxes
function toggleAll(v){
  document.querySelectorAll('.status input[type="checkbox"]').forEach(cb => {
    cb.checked = v;
    const label = cb.nextElementSibling;
    label.textContent = v ? 'Sudah diposting' : 'Belum diposting';
    label.className = v ? 'done' : 'muted';
  });
}

// Per-item status
document.addEventListener('change',(e)=>{
  if(e.target.matches('.status input[type="checkbox"]')){
    const label = e.target.nextElementSibling;
    label.textContent = e.target.checked ? 'Sudah diposting' : 'Belum diposting';
    label.className = e.target.checked ? 'done' : 'muted';
  }
});

// Export CSV
function exportCSV(){
  const headers = ['Day','Brand','Game',
    'ReelsPrompt','ReelsCaption','ReelsLink',
    'StoryBonusPrompt','StoryBonusCaption','StoryJoinPrompt','StoryJoinCaption',
    'FeedPrompt','FeedCaption','FeedLink','Status'];
  const lines = [headers];
  [...root.children].forEach((det,i)=>{
    const idx = i+1;
    const brand = det.querySelector('summary .badge').innerText;
    const game = det.querySelector('summary strong').innerText;
    const rp = det.querySelector('#rp-'+idx).value.replace(/\\n/g,' ').trim();
    const rc = det.querySelector('#rc-'+idx).value.replace(/\\n/g,' ').trim();
    const rl = det.querySelector('#rl-'+idx).value.trim();
    const sbp = det.querySelector('#sbp-'+idx).value.replace(/\\n/g,' ').trim();
    const sbc = det.querySelector('#sbc-'+idx).value.replace(/\\n/g,' ').trim();
    const sjp = det.querySelector('#sjp-'+idx).value.replace(/\\n/g,' ').trim();
    const sjc = det.querySelector('#sjc-'+idx).value.replace(/\\n/g,' ').trim();
    const fp = det.querySelector('#fp-'+idx).value.replace(/\\n/g,' ').trim();
    const fc = det.querySelector('#fc-'+idx).value.replace(/\\n/g,' ').trim();
    const fl = det.querySelector('#fl-'+idx).value.trim();
    const status = det.querySelector('.status input').checked ? 'Posted' : 'Not Posted';
    lines.push([idx,brand,game,rp,rc,rl,sbp,sbc,sjp,sjc,fp,fc,fl,status].map(v=>`"${String(v).replace(/"/g,'""')}"`).join(','));
  });
  const blob = new Blob([lines.join('\\n')],{type:'text/csv'});
  const url = URL.createObjectURL(blob);
  const a = document.createElement('a'); a.href=url; a.download='CK44_Instagram_30Day.csv';
  document.body.appendChild(a); a.click(); document.body.removeChild(a); URL.revokeObjectURL(url);
}
</script>
</body>
</html>
