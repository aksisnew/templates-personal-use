<div style="font-family:sans-serif; background:#0f172a; color:#e5e7eb; padding:20px;">

  <div style="margin-bottom:20px; font-size:1.4rem; font-weight:bold; color:#93c5fd;">
    📚 Assignment Tracker
  </div>

  <!-- Dropdown navigation -->
  <div style="margin-bottom:20px;">
    <label for="subjectSelect" style="font-weight:bold; margin-right:10px;">Filter by Subject:</label>
    <select id="subjectSelect" style="padding:6px; border-radius:6px; border:1px solid #334155; background:#111827; color:#e5e7eb;"
            onchange="location.href=this.value;">
      <option value="#all">All</option>
      <option value="#math">Math</option>
      <option value="#english">English</option>
      <option value="#science">Science</option>
      <option value="#history">History</option>
    </select>
  </div>

  <!-- All Assignments -->
  <div id="all" style="margin-bottom:30px;">
    <div style="display:flex; font-weight:bold; background:#111827; padding:8px; border:1px solid #334155;">
      <div style="flex:2;">Assignment</div>
      <div style="flex:1;">Subject</div>
      <div style="flex:1;">Due Date</div>
      <div style="flex:1;">Status</div>
    </div>

    <div style="display:flex; padding:8px; border:1px solid #334155;">
      <div style="flex:2;">Problem Set 1</div>
      <div style="flex:1;">Math</div>
      <div style="flex:1;">2025‑11‑25</div>
      <div style="flex:1;">⏳ In Progress</div>
    </div>

    <div style="display:flex; padding:8px; border:1px solid #334155;">
      <div style="flex:2;">Essay on Shakespeare</div>
      <div style="flex:1;">English</div>
      <div style="flex:1;">2025‑11‑28</div>
      <div style="flex:1;">✅ Completed</div>
    </div>

    <div style="display:flex; padding:8px; border:1px solid #334155;">
      <div style="flex:2;">Lab Report</div>
      <div style="flex:1;">Science</div>
      <div style="flex:1;">2025‑12‑01</div>
      <div style="flex:1;">⏳ In Progress</div>
    </div>

    <div style="display:flex; padding:8px; border:1px solid #334155;">
      <div style="flex:2;">History Timeline</div>
      <div style="flex:1;">History</div>
      <div style="flex:1;">2025‑12‑03</div>
      <div style="flex:1;">⏳ In Progress</div>
    </div>
  </div>

  <!-- Subject Sections -->
  <div id="math" style="margin-bottom:20px; color:#facc15; font-weight:bold;">Math</div>
  <div style="margin-left:10px;">Problem Set 1 — Due 2025‑11‑25 — ⏳ In Progress</div>

  <div id="english" style="margin-bottom:20px; color:#facc15; font-weight:bold;">English</div>
  <div style="margin-left:10px;">Essay on Shakespeare — Due 2025‑11‑28 — ✅ Completed</div>

  <div id="science" style="margin-bottom:20px; color:#facc15; font-weight:bold;">Science</div>
  <div style="margin-left:10px;">Lab Report — Due 2025‑12‑01 — ⏳ In Progress</div>

  <div id="history" style="margin-bottom:20px; color:#facc15; font-weight:bold;">History</div>
  <div style="margin-left:10px;">History Timeline — Due 2025‑12‑03 — ⏳ In Progress</div>

</div>

