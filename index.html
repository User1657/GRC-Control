<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>GRC-Control — Risk Management</title>
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/email.min.js"></script>
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{
--bg:#0f1117;--bg2:#161b27;--bg3:#1e2535;--bg4:#252d40;
--border:#2a3352;--border2:#3a4a6b;
--text:#e2e8f0;--text2:#94a3b8;--text3:#64748b;
--purple:#7c6af7;--purple2:#6355e0;--purple-bg:#1e1a3a;
--teal:#10b981;--teal-bg:#0d2d22;
--amber:#f59e0b;--amber-bg:#2d1f07;
--red:#ef4444;--red-bg:#2d0f0f;
--blue:#3b82f6;--blue-bg:#0f1f3a;
--green:#22c55e;--green-bg:#0d2d1a;
--radius:10px;--radius-sm:6px;
--font:'Inter',system-ui,sans-serif;
}
body{font-family:var(--font);background:var(--bg);color:var(--text);min-height:100vh;display:flex}
.sidebar{width:225px;min-height:100vh;background:var(--bg2);border-right:1px solid var(--border);display:flex;flex-direction:column;flex-shrink:0;position:fixed;top:0;left:0;height:100vh;overflow-y:auto}
.logo{padding:18px 16px 14px;border-bottom:1px solid var(--border)}
.logo-mark{display:flex;align-items:center;gap:10px}
.logo-icon{width:34px;height:34px;background:var(--purple-bg);border:1px solid var(--purple);border-radius:8px;display:flex;align-items:center;justify-content:center;font-size:16px}
.logo-text{font-size:15px;font-weight:600}
.logo-sub{font-size:11px;color:var(--text3);margin-top:1px}
.nav{padding:10px 8px;flex:1}
.nav-section{font-size:10px;font-weight:600;color:var(--text3);letter-spacing:.08em;text-transform:uppercase;padding:10px 8px 5px}
.nav-item{display:flex;align-items:center;gap:9px;padding:7px 10px;border-radius:var(--radius-sm);cursor:pointer;color:var(--text2);font-size:13px;font-weight:500;transition:all .15s;margin-bottom:2px;border:none;background:none;width:100%;text-align:left}
.nav-item:hover{background:var(--bg3);color:var(--text)}
.nav-item.active{background:var(--purple-bg);color:var(--purple);border:1px solid rgba(124,106,247,.2)}
.nav-item svg{width:15px;height:15px;flex-shrink:0}
.nav-badge{margin-left:auto;background:var(--red);color:#fff;font-size:10px;font-weight:600;padding:1px 6px;border-radius:10px}
.main{margin-left:225px;flex:1;min-height:100vh;display:flex;flex-direction:column}
.topbar{padding:14px 26px;border-bottom:1px solid var(--border);display:flex;align-items:center;justify-content:space-between;background:var(--bg2)}
.topbar-title{font-size:18px;font-weight:600}
.topbar-sub{font-size:12px;color:var(--text3);margin-top:2px}
.btn{display:inline-flex;align-items:center;gap:6px;padding:7px 14px;border-radius:var(--radius-sm);font-size:13px;font-weight:500;cursor:pointer;border:none;transition:all .15s}
.btn-primary{background:var(--purple);color:#fff}.btn-primary:hover{background:var(--purple2)}
.btn-ghost{background:transparent;color:var(--text2);border:1px solid var(--border)}.btn-ghost:hover{background:var(--bg3);color:var(--text)}
.btn-danger{background:var(--red-bg);color:var(--red);border:1px solid rgba(239,68,68,.2)}.btn-danger:hover{background:rgba(239,68,68,.15)}
.btn-teal{background:var(--teal-bg);color:var(--teal);border:1px solid rgba(16,185,129,.2)}.btn-teal:hover{background:rgba(16,185,129,.15)}
.btn-amber{background:var(--amber-bg);color:var(--amber);border:1px solid rgba(245,158,11,.2)}.btn-amber:hover{background:rgba(245,158,11,.15)}
.content{padding:22px 26px;flex:1}
.stat-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-bottom:20px}
.stat-card{background:var(--bg2);border:1px solid var(--border);border-radius:var(--radius);padding:14px 16px}
.stat-top{display:flex;align-items:center;justify-content:space-between;margin-bottom:8px}
.stat-label{font-size:12px;color:var(--text3);font-weight:500}
.stat-icon{width:28px;height:28px;border-radius:7px;display:flex;align-items:center;justify-content:center;font-size:13px}
.stat-value{font-size:24px;font-weight:700;line-height:1}
.stat-sub{font-size:11px;color:var(--text3);margin-top:3px}
.section-card{background:var(--bg2);border:1px solid var(--border);border-radius:var(--radius);margin-bottom:18px;overflow:hidden}
.section-header{padding:12px 16px;border-bottom:1px solid var(--border);display:flex;align-items:center;justify-content:space-between}
.section-title{font-size:14px;font-weight:600}
.section-sub{font-size:12px;color:var(--text3)}
table{width:100%;border-collapse:collapse}
th{padding:9px 14px;text-align:left;font-size:11px;font-weight:600;color:var(--text3);text-transform:uppercase;letter-spacing:.04em;border-bottom:1px solid var(--border)}
td{padding:10px 14px;font-size:13px;border-bottom:1px solid rgba(42,51,82,.4)}
tr:last-child td{border-bottom:none}
tr:hover td{background:rgba(255,255,255,.02)}
.badge{display:inline-flex;align-items:center;padding:2px 8px;border-radius:20px;font-size:11px;font-weight:600}
.badge-critical{background:rgba(239,68,68,.15);color:#f87171}
.badge-high{background:rgba(245,158,11,.15);color:#fbbf24}
.badge-medium{background:rgba(59,130,246,.15);color:#60a5fa}
.badge-low{background:rgba(34,197,94,.15);color:#4ade80}
.badge-open{background:rgba(239,68,68,.12);color:#f87171}
.badge-progress{background:rgba(245,158,11,.12);color:#fbbf24}
.badge-closed{background:rgba(34,197,94,.12);color:#4ade80}
.badge-compliant{background:rgba(34,197,94,.12);color:#4ade80}
.badge-noncompliant{background:rgba(239,68,68,.12);color:#f87171}
.badge-partial-c{background:rgba(245,158,11,.12);color:#fbbf24}
.badge-active{background:rgba(34,197,94,.12);color:#4ade80}
.badge-draft{background:rgba(100,116,139,.12);color:#94a3b8}
.badge-review{background:rgba(245,158,11,.12);color:#fbbf24}
.badge-expired{background:rgba(239,68,68,.12);color:#f87171}
.badge-yes{background:rgba(239,68,68,.15);color:#f87171}
.badge-no{background:rgba(34,197,94,.12);color:#4ade80}
.progress-wrap{display:flex;align-items:center;gap:8px}
.progress-bar{flex:1;height:5px;background:var(--bg4);border-radius:3px;overflow:hidden}
.progress-fill{height:100%;border-radius:3px;transition:width .3s}
.heatmap-wrap{padding:18px}
.heatmap-grid{display:grid;grid-template-columns:36px repeat(5,1fr);grid-template-rows:repeat(5,42px) 30px;gap:4px}
.hm-cell{border-radius:6px;display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:600;cursor:pointer;transition:all .15s}
.hm-cell:hover{transform:scale(1.06);z-index:2}
.hm-label{font-size:9px;color:var(--text3);display:flex;align-items:center;justify-content:center;text-align:center}
.hm-low{background:rgba(34,197,94,.15);color:#4ade80;border:1px solid rgba(34,197,94,.2)}
.hm-medium{background:rgba(59,130,246,.15);color:#60a5fa;border:1px solid rgba(59,130,246,.2)}
.hm-high{background:rgba(245,158,11,.18);color:#fbbf24;border:1px solid rgba(245,158,11,.25)}
.hm-critical{background:rgba(239,68,68,.18);color:#f87171;border:1px solid rgba(239,68,68,.25)}
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.75);display:flex;align-items:center;justify-content:center;z-index:100;padding:20px}
.modal{background:var(--bg2);border:1px solid var(--border2);border-radius:14px;width:100%;max-width:620px;max-height:92vh;overflow-y:auto}
.modal-header{padding:16px 20px;border-bottom:1px solid var(--border);display:flex;align-items:center;justify-content:space-between}
.modal-title{font-size:15px;font-weight:600}
.modal-body{padding:20px}
.modal-footer{padding:14px 20px;border-top:1px solid var(--border);display:flex;justify-content:flex-end;gap:8px}
.form-group{margin-bottom:14px}
label{display:block;font-size:12px;font-weight:500;color:var(--text2);margin-bottom:4px}
input,select,textarea{width:100%;background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius-sm);padding:8px 11px;font-size:13px;color:var(--text);font-family:var(--font);outline:none;transition:border-color .15s}
input:focus,select:focus,textarea:focus{border-color:var(--purple)}
textarea{resize:vertical;min-height:70px}
select option{background:var(--bg3)}
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.form-row-3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:10px}
.page{display:none}.page.active{display:block}
.actions-bar{display:flex;align-items:center;gap:8px;margin-bottom:16px;flex-wrap:wrap}
.search-input{flex:1;min-width:160px;max-width:260px;background:var(--bg2);border:1px solid var(--border);border-radius:var(--radius-sm);padding:7px 12px;font-size:13px;color:var(--text);outline:none}
.search-input:focus{border-color:var(--purple)}
.risk-score{display:inline-flex;align-items:center;justify-content:center;width:28px;height:28px;border-radius:6px;font-size:12px;font-weight:700}
.avatar{width:24px;height:24px;border-radius:50%;background:var(--purple-bg);border:1px solid var(--purple);display:inline-flex;align-items:center;justify-content:center;font-size:9px;font-weight:600;color:var(--purple);margin-right:5px}
.kri-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-bottom:18px}
.kri-card{background:var(--bg2);border:1px solid var(--border);border-radius:var(--radius);padding:14px}
.kri-title{font-size:11px;color:var(--text3);margin-bottom:5px}
.kri-value{font-size:22px;font-weight:700}
.kri-bar-wrap{margin-top:7px}
.kri-threshold{font-size:10px;color:var(--text3);margin-top:3px}
.empty{padding:40px 20px;text-align:center;color:var(--text3)}
.empty-icon{font-size:32px;margin-bottom:10px}
.toast{position:fixed;bottom:22px;right:22px;background:var(--bg3);border:1px solid var(--border2);border-radius:var(--radius);padding:11px 16px;font-size:13px;color:var(--text);z-index:200;display:flex;align-items:center;gap:9px;transform:translateY(80px);opacity:0;transition:all .3s;max-width:320px}
.toast.show{transform:translateY(0);opacity:1}
.toast-dot{width:8px;height:8px;border-radius:50%;flex-shrink:0}
.policy-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(270px,1fr));gap:12px}
.policy-card{background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius);padding:14px}
.policy-card:hover{border-color:var(--border2)}
.policy-card-top{display:flex;align-items:flex-start;justify-content:space-between;margin-bottom:7px}
.policy-card-title{font-size:14px;font-weight:600;flex:1;margin-right:8px}
.policy-card-meta{font-size:11px;color:var(--text3);margin-bottom:9px;line-height:1.6}
.settings-panel{background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius);padding:18px;margin-bottom:18px}
.settings-title{font-size:14px;font-weight:600;margin-bottom:3px}
.settings-sub{font-size:12px;color:var(--text3);margin-bottom:14px}
.toggle-row{display:flex;align-items:center;justify-content:space-between;padding:9px 0;border-bottom:1px solid var(--border)}
.toggle-row:last-child{border-bottom:none}
.toggle-label{font-size:13px}
.toggle-sub{font-size:11px;color:var(--text3);margin-top:1px}
.toggle{position:relative;width:36px;height:19px;flex-shrink:0}
.toggle input{opacity:0;width:0;height:0}
.toggle-slider{position:absolute;inset:0;background:var(--bg4);border-radius:20px;cursor:pointer;transition:.2s}
.toggle-slider:before{content:'';position:absolute;width:13px;height:13px;left:3px;top:3px;background:var(--text3);border-radius:50%;transition:.2s}
.toggle input:checked+.toggle-slider{background:var(--purple)}
.toggle input:checked+.toggle-slider:before{transform:translateX(17px);background:#fff}
.info-box{background:var(--blue-bg);border:1px solid rgba(59,130,246,.2);border-radius:var(--radius-sm);padding:11px 14px;font-size:12px;color:var(--text2);margin-bottom:14px;line-height:1.6}
.info-box a{color:var(--blue)}
.warn-box{background:var(--amber-bg);border:1px solid rgba(245,158,11,.2);border-radius:var(--radius-sm);padding:11px 14px;font-size:12px;color:var(--text2);margin-bottom:14px;line-height:1.6}
.trend-up{color:#f87171;font-size:14px}
.trend-down{color:#4ade80;font-size:14px}
.trend-flat{color:#60a5fa;font-size:14px}
.appetite-yes{color:#f87171;font-weight:700}
.appetite-no{color:#4ade80;font-weight:600}
/* Report styles */
.report-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-bottom:18px}
.report-card{background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius);padding:16px;cursor:pointer;transition:all .15s;text-align:center}
.report-card:hover{border-color:var(--purple);background:var(--purple-bg)}
.report-icon{font-size:28px;margin-bottom:8px}
.report-title{font-size:13px;font-weight:600;margin-bottom:4px}
.report-sub{font-size:11px;color:var(--text3)}
/* Asset styles */
.asset-type-icon{width:30px;height:30px;border-radius:7px;display:inline-flex;align-items:center;justify-content:center;font-size:14px;margin-right:8px;vertical-align:middle}
@media(max-width:900px){.stat-grid{grid-template-columns:repeat(2,1fr)}.kri-grid{grid-template-columns:repeat(2,1fr)}.report-grid{grid-template-columns:repeat(2,1fr)}}
</style>
</head>
<body>
<nav class="sidebar">
  <div class="logo">
    <div class="logo-mark">
      <div class="logo-icon">🛡️</div>
      <div><div class="logo-text">GRC-Control</div><div class="logo-sub">Risk Management</div></div>
    </div>
  </div>
  <div class="nav">
    <div class="nav-section">Workspace</div>
    <button class="nav-item active" onclick="showPage('dashboard',this)"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="3" width="7" height="7" rx="1"/><rect x="14" y="3" width="7" height="7" rx="1"/><rect x="3" y="14" width="7" height="7" rx="1"/><rect x="14" y="14" width="7" height="7" rx="1"/></svg>Dashboard</button>
    <button class="nav-item" onclick="showPage('risks',this)"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>Risk Register<span class="nav-badge" id="risk-badge">0</span></button>
    <button class="nav-item" onclick="showPage('heatmap',this)"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M9 3v18M15 3v18M3 9h18M3 15h18"/></svg>Heat Map</button>
    <button class="nav-item" onclick="showPage('controls',this)"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>Controls</button>
    <button class="nav-item" onclick="showPage('policies',this)"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V8z"/><polyline points="14,2 14,8 20,8"/></svg>Policies</button>
    <button class="nav-item" onclick="showPage('compliance',this)"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 11l3 3L22 4"/><path d="M21 12v7a2 2 0 01-2 2H5a2 2 0 01-2-2V5a2 2 0 012-2h11"/></svg>Compliance</button>
    <button class="nav-item" onclick="showPage('issues',this)"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><line x1="12" y1="8" x2="12" y2="12"/><line x1="12" y1="16" x2="12.01" y2="16"/></svg>Issues & Actions</button>
    <button class="nav-item" onclick="showPage('assets',this)"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="3" width="20" height="14" rx="2"/><path d="M8 21h8M12 17v4"/></svg>Asset Inventory</button>
    <button class="nav-item" onclick="showPage('reports',this)"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V8z"/><polyline points="14,2 14,8 20,8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/><line x1="10" y1="9" x2="8" y2="9"/></svg>Reports</button>
    <div class="nav-section">Settings</div>
    <button class="nav-item" onclick="showPage('email',this)"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>Email Alerts</button>
    <button class="nav-item" onclick="exportCSV()"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 15v4a2 2 0 01-2 2H5a2 2 0 01-2-2v-4"/><polyline points="7,10 12,15 17,10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>Export CSV</button>
  </div>
</nav>
<div class="main">

<!-- DASHBOARD -->
<div class="page active" id="page-dashboard">
  <div class="topbar"><div><div class="topbar-title">Dashboard</div><div class="topbar-sub">Risk overview and key indicators</div></div></div>
  <div class="content"><div class="stat-grid" id="stat-grid"></div><div class="kri-grid" id="kri-grid"></div><div class="kri-grid" id="kpi-grid"></div>
    <div class="section-card" id="overdue-section" style="display:none">
      <div class="section-header"><span class="section-title" style="color:var(--red)">⏰ Overdue Risks</span><span class="section-sub" id="overdue-count"></span></div>
      <table><thead><tr><th>ID</th><th>Risk</th><th>Score</th><th>Severity</th><th>Owner</th><th>Due Date</th><th>Days Overdue</th></tr></thead><tbody id="overdue-table"></tbody></table>
    </div>
    <div class="section-card" id="duesoon-section" style="display:none">
      <div class="section-header"><span class="section-title" style="color:var(--amber)">📅 Due This Week</span><span class="section-sub" id="duesoon-count"></span></div>
      <table><thead><tr><th>ID</th><th>Risk</th><th>Score</th><th>Owner</th><th>Treatment Status</th><th>Due Date</th></tr></thead><tbody id="duesoon-table"></tbody></table>
    </div>
    <div class="section-card"><div class="section-header"><span class="section-title">Top risks requiring attention</span></div>
    <table><thead><tr><th>ID</th><th>Risk</th><th>Score</th><th>Residual</th><th>Severity</th><th>Trend</th><th>Appetite Breach</th><th>Owner</th><th>Due Date</th></tr></thead><tbody id="top-risks-table"></tbody></table></div>
  </div>
</div>

<!-- RISK REGISTER -->
<div class="page" id="page-risks">
  <div class="topbar"><div><div class="topbar-title">Risk Register</div><div class="topbar-sub">Full risk register with ratings, residual risk and trends</div></div><button class="btn btn-primary" onclick="openModal('risk')">+ New Risk</button></div>
  <div class="content">
    <div class="actions-bar">
      <input class="search-input" type="text" placeholder="Search risks…" oninput="filterRisks()" id="risk-search"/>
      <select class="btn btn-ghost" style="padding:7px 10px;font-size:12px" onchange="filterRisks()" id="risk-filter-cat"><option value="">All categories</option><option>Operational</option><option>Financial</option><option>Strategic</option><option>Compliance</option><option>Technology</option><option>Reputational</option></select>
      <select class="btn btn-ghost" style="padding:7px 10px;font-size:12px" onchange="filterRisks()" id="risk-filter-sev"><option value="">All severities</option><option>Critical</option><option>High</option><option>Medium</option><option>Low</option></select>
      <select class="btn btn-ghost" style="padding:7px 10px;font-size:12px" onchange="filterRisks()" id="risk-filter-breach"><option value="">All</option><option value="Yes">Appetite Breach</option><option value="No">Within Appetite</option></select>
    </div>
    <div class="section-card" style="overflow-x:auto">
      <table><thead><tr><th>ID</th><th>Risk</th><th>Cat</th><th>L</th><th>I</th><th>Score</th><th>Residual</th><th>Rating</th><th>Appetite</th><th>Trend</th><th>Owner</th><th>Treatment</th><th>Due Date</th><th>Last Review</th><th>Status</th><th>Actions</th></tr></thead>
      <tbody id="risk-table"></tbody></table>
    </div>
  </div>
</div>

<!-- HEAT MAP -->
<div class="page" id="page-heatmap">
  <div class="topbar"><div><div class="topbar-title">Risk Heat Map</div><div class="topbar-sub">Likelihood vs Impact matrix</div></div></div>
  <div class="content">
    <div class="section-card"><div class="section-header"><span class="section-title">5×5 Risk Matrix</span><span class="section-sub">Click a cell to view risks</span></div><div class="heatmap-wrap" id="heatmap-container"></div></div>
    <div class="section-card" id="heatmap-risks-section" style="display:none"><div class="section-header"><span class="section-title" id="heatmap-risks-title">Risks in zone</span></div><table><thead><tr><th>ID</th><th>Risk</th><th>Residual</th><th>Trend</th><th>Owner</th><th>Status</th></tr></thead><tbody id="heatmap-risks-table"></tbody></table></div>
  </div>
</div>

<!-- CONTROLS -->
<div class="page" id="page-controls">
  <div class="topbar"><div><div class="topbar-title">Controls & Mitigation</div><div class="topbar-sub">Track control effectiveness</div></div><button class="btn btn-primary" onclick="openModal('control')">+ New Control</button></div>
  <div class="content"><div class="stat-grid" id="control-stats"></div><div class="section-card"><table><thead><tr><th>ID</th><th>Control</th><th>Type</th><th>Effectiveness</th><th>Owner</th><th>Last Tested</th><th>Mitigates</th><th>Actions</th></tr></thead><tbody id="controls-table"></tbody></table></div></div>
</div>

<!-- POLICIES -->
<div class="page" id="page-policies">
  <div class="topbar"><div><div class="topbar-title">Policies</div><div class="topbar-sub">Organizational policies and procedures</div></div><button class="btn btn-primary" onclick="openModal('policy')">+ New Policy</button></div>
  <div class="content">
    <div class="stat-grid" id="policy-stats"></div>
    <div class="actions-bar">
      <input class="search-input" type="text" placeholder="Search policies…" oninput="filterPolicies()" id="policy-search"/>
      <select class="btn btn-ghost" style="padding:7px 10px;font-size:12px" onchange="filterPolicies()" id="policy-filter-status"><option value="">All statuses</option><option>Active</option><option>Draft</option><option>Under Review</option><option>Expired</option></select>
    </div>
    <div class="policy-grid" id="policy-grid"></div>
  </div>
</div>

<!-- COMPLIANCE -->
<div class="page" id="page-compliance">
  <div class="topbar"><div><div class="topbar-title">Compliance</div><div class="topbar-sub">Framework and regulatory compliance tracking</div></div><button class="btn btn-primary" onclick="openModal('compliance')">+ Add Item</button></div>
  <div class="content"><div class="section-card"><table><thead><tr><th>Framework</th><th>Requirement</th><th>Status</th><th>Owner</th><th>Due Date</th><th>Progress</th><th>Actions</th></tr></thead><tbody id="compliance-table"></tbody></table></div></div>
</div>

<!-- ISSUES -->
<div class="page" id="page-issues">
  <div class="topbar"><div><div class="topbar-title">Issues & Actions</div><div class="topbar-sub">Track open issues and remediation actions</div></div><button class="btn btn-primary" onclick="openModal('issue')">+ New Issue</button></div>
  <div class="content"><div class="section-card"><table><thead><tr><th>ID</th><th>Issue</th><th>Risk</th><th>Priority</th><th>Owner</th><th>Due Date</th><th>Status</th><th>Actions</th></tr></thead><tbody id="issues-table"></tbody></table></div></div>
</div>

<!-- ASSET INVENTORY -->
<div class="page" id="page-assets">
  <div class="topbar"><div><div class="topbar-title">Asset Inventory</div><div class="topbar-sub">Track all organizational assets and their risk exposure</div></div><button class="btn btn-primary" onclick="openModal('asset')">+ New Asset</button></div>
  <div class="content">
    <div class="stat-grid" id="asset-stats"></div>
    <div class="actions-bar">
      <input class="search-input" type="text" placeholder="Search assets…" oninput="filterAssets()" id="asset-search"/>
      <select class="btn btn-ghost" style="padding:7px 10px;font-size:12px" onchange="filterAssets()" id="asset-filter-type"><option value="">All types</option><option>Hardware</option><option>Software</option><option>Data</option><option>People</option><option>Facility</option><option>Cloud Service</option></select>
      <select class="btn btn-ghost" style="padding:7px 10px;font-size:12px" onchange="filterAssets()" id="asset-filter-crit"><option value="">All criticality</option><option>Critical</option><option>High</option><option>Medium</option><option>Low</option></select>
    </div>
    <div class="section-card" style="overflow-x:auto"><table><thead><tr><th>ID</th><th>Asset</th><th>Type</th><th>Owner</th><th>Criticality</th><th>Location</th><th>Linked Risks</th><th>Last Reviewed</th><th>Actions</th></tr></thead><tbody id="assets-table"></tbody></table></div>
  </div>
</div>

<!-- REPORTS -->
<div class="page" id="page-reports">
  <div class="topbar"><div><div class="topbar-title">Reports</div><div class="topbar-sub">Generate and export GRC reports</div></div></div>
  <div class="content">
    <div class="report-grid">
      <div class="report-card" onclick="generateReport('executive')"><div class="report-icon">📊</div><div class="report-title">Executive Risk Summary</div><div class="report-sub">Board-ready risk overview with KRIs</div></div>
      <div class="report-card" onclick="generateReport('register')"><div class="report-icon">📋</div><div class="report-title">Full Risk Register</div><div class="report-sub">All risks with scores, owners and status</div></div>
      <div class="report-card" onclick="generateReport('appetite')"><div class="report-icon">🎯</div><div class="report-title">Risk Appetite Report</div><div class="report-sub">Risks breaching appetite thresholds</div></div>
      <div class="report-card" onclick="generateReport('residual')"><div class="report-icon">🔻</div><div class="report-title">Residual Risk Report</div><div class="report-sub">Inherent vs residual risk comparison</div></div>
      <div class="report-card" onclick="generateReport('compliance')"><div class="report-icon">✅</div><div class="report-title">Compliance Status</div><div class="report-sub">Framework compliance by requirement</div></div>
      <div class="report-card" onclick="generateReport('assets')"><div class="report-icon">🖥️</div><div class="report-title">Asset Risk Report</div><div class="report-sub">Assets with linked risks and criticality</div></div>
    </div>
    <div class="section-card" id="report-output" style="display:none">
      <div class="section-header"><span class="section-title" id="report-title">Report</span><div style="display:flex;gap:8px"><button class="btn btn-teal" onclick="printReport()">🖨️ Print</button><button class="btn btn-ghost" onclick="document.getElementById('report-output').style.display='none'">✕ Close</button></div></div>
      <div id="report-body" style="padding:20px"></div>
    </div>
  </div>
</div>

<!-- EMAIL -->
<div class="page" id="page-email">
  <div class="topbar"><div><div class="topbar-title">Email Alerts</div><div class="topbar-sub">Configure notifications via EmailJS (free)</div></div></div>
  <div class="content">
    <div class="info-box">📧 <strong>Setup:</strong> 1. Go to <a href="https://www.emailjs.com" target="_blank">emailjs.com</a> → free account → 2. Connect Gmail → 3. Create Template with: {{subject}}, {{message}}, {{to_email}} → 4. Paste keys below → Save & Test</div>
    <div class="settings-panel">
      <div class="settings-title">EmailJS Configuration</div><div class="settings-sub">Enter your credentials</div>
      <div class="form-row"><div class="form-group"><label>Public Key</label><input id="ejs-pubkey" placeholder="user_xxx"/></div><div class="form-group"><label>Service ID</label><input id="ejs-service" placeholder="service_xxx"/></div></div>
      <div class="form-row"><div class="form-group"><label>Template ID</label><input id="ejs-template" placeholder="template_xxx"/></div><div class="form-group"><label>Your Email</label><input id="ejs-email" type="email" placeholder="you@email.com"/></div></div>
      <div style="display:flex;gap:8px"><button class="btn btn-primary" onclick="saveEmailConfig()">💾 Save</button><button class="btn btn-teal" onclick="testEmail()">📧 Test</button></div>
    </div>
    <div class="settings-panel">
      <div class="settings-title">Alert Preferences</div><div class="settings-sub">Choose trigger events</div>
      <div class="toggle-row"><div><div class="toggle-label">Critical Risk Added</div></div><label class="toggle"><input type="checkbox" id="alert-critical" checked/><span class="toggle-slider"></span></label></div>
      <div class="toggle-row"><div><div class="toggle-label">High Risk Added</div></div><label class="toggle"><input type="checkbox" id="alert-high" checked/><span class="toggle-slider"></span></label></div>
      <div class="toggle-row"><div><div class="toggle-label">Risk Appetite Breach</div></div><label class="toggle"><input type="checkbox" id="alert-appetite" checked/><span class="toggle-slider"></span></label></div>
      <div class="toggle-row"><div><div class="toggle-label">Issue Overdue</div></div><label class="toggle"><input type="checkbox" id="alert-overdue" checked/><span class="toggle-slider"></span></label></div>
      <div class="toggle-row"><div><div class="toggle-label">Policy Expiring Soon</div></div><label class="toggle"><input type="checkbox" id="alert-policy" checked/><span class="toggle-slider"></span></label></div>
      <div style="margin-top:12px"><button class="btn btn-primary" onclick="saveAlertPrefs()">Save Preferences</button></div>
    </div>
    <div class="warn-box">⚠️ EmailJS free tier: 200 emails/month.</div>
  </div>
</div>

</div><!-- end main -->

<!-- MODAL -->
<div class="modal-overlay" id="modal" style="display:none" onclick="if(event.target===this)closeModal()">
  <div class="modal"><div class="modal-header"><span class="modal-title" id="modal-title">Add</span><button class="btn btn-ghost" style="padding:4px 10px" onclick="closeModal()">✕</button></div><div class="modal-body" id="modal-body"></div><div class="modal-footer"><button class="btn btn-ghost" onclick="closeModal()">Cancel</button><button class="btn btn-primary" onclick="saveModal()">Save</button></div></div>
</div>
<div class="toast" id="toast"><div class="toast-dot" id="toast-dot"></div><span id="toast-msg">Saved</span></div>

<script>
const STORE_KEY='grc_data_v4';
let data=JSON.parse(localStorage.getItem(STORE_KEY)||'null')||{
risks:[
{id:'RSK-001',name:'Data breach via phishing',category:'Technology',likelihood:4,impact:5,residualScore:12,owner:'Ahmed Al-Rashid',status:'Open',description:'Phishing attacks leading to credential theft.',treatment:'Mitigate',treatmentStatus:'In Progress',dueDate:'2026-08-01',lastReview:'2026-05-01',trend:'Up',appetiteBreach:'Yes'},
{id:'RSK-002',name:'Vendor SLA non-compliance',category:'Operational',likelihood:3,impact:4,residualScore:8,owner:'Sara Mohammed',status:'In Progress',description:'Key vendors failing SLAs.',treatment:'Transfer',treatmentStatus:'In Progress',dueDate:'2026-07-15',lastReview:'2026-04-10',trend:'Flat',appetiteBreach:'No'},
{id:'RSK-003',name:'Regulatory fine - GDPR',category:'Compliance',likelihood:2,impact:5,residualScore:6,owner:'Khalid Hassan',status:'Open',description:'Non-compliance with GDPR retention.',treatment:'Mitigate',treatmentStatus:'Planned',dueDate:'2026-07-01',lastReview:'2026-03-20',trend:'Down',appetiteBreach:'Yes'},
{id:'RSK-004',name:'Cloud outage - AWS',category:'Technology',likelihood:2,impact:4,residualScore:4,owner:'Priya Nair',status:'Open',description:'Single region dependency.',treatment:'Mitigate',treatmentStatus:'In Progress',dueDate:'2026-09-01',lastReview:'2026-05-15',trend:'Down',appetiteBreach:'No'},
{id:'RSK-005',name:'Key person dependency',category:'Strategic',likelihood:3,impact:3,residualScore:7,owner:'Marcus Webb',status:'Open',description:'Core processes depend on 2-3 people.',treatment:'Accept',treatmentStatus:'Accepted',dueDate:'2026-12-31',lastReview:'2026-04-01',trend:'Flat',appetiteBreach:'No'},
{id:'RSK-006',name:'Budget overrun - IT',category:'Financial',likelihood:3,impact:3,residualScore:3,owner:'Ahmed Al-Rashid',status:'Closed',description:'IT projects historically overspend.',treatment:'Mitigate',treatmentStatus:'Completed',dueDate:'2026-06-01',lastReview:'2026-05-20',trend:'Down',appetiteBreach:'No'},
],
controls:[
{id:'CTL-001',name:'Role-based access control',type:'Preventive',effectiveness:88,owner:'Priya Nair',lastTested:'2026-05-12',mitigates:['RSK-001','RSK-006']},
{id:'CTL-002',name:'Vendor security assessments',type:'Detective',effectiveness:54,owner:'Marcus Webb',lastTested:'2026-03-02',mitigates:['RSK-002']},
{id:'CTL-003',name:'Encrypted offsite backups',type:'Corrective',effectiveness:91,owner:'Sara Mohammed',lastTested:'2026-05-28',mitigates:['RSK-004']},
{id:'CTL-004',name:'Privileged access monitoring',type:'Detective',effectiveness:67,owner:'Khalid Hassan',lastTested:'2026-04-15',mitigates:['RSK-001']},
{id:'CTL-005',name:'Security awareness training',type:'Preventive',effectiveness:72,owner:'Ahmed Al-Rashid',lastTested:'2026-02-10',mitigates:['RSK-001']},
],
compliance:[
{framework:'ISO 27001',requirement:'Access Control Policy',status:'Compliant',owner:'Priya Nair',dueDate:'2026-12-31',progress:100},
{framework:'GDPR',requirement:'Data Retention Schedule',status:'Non-Compliant',owner:'Khalid Hassan',dueDate:'2026-07-15',progress:35},
{framework:'SOC 2',requirement:'Incident Response Plan',status:'Partial',owner:'Sara Mohammed',dueDate:'2026-09-30',progress:60},
{framework:'ISO 27001',requirement:'Risk Assessment Process',status:'Compliant',owner:'Marcus Webb',dueDate:'2026-12-31',progress:100},
{framework:'NIST CSF',requirement:'Asset Inventory',status:'Partial',owner:'Ahmed Al-Rashid',dueDate:'2026-08-01',progress:75},
],
issues:[
{id:'ISS-001',issue:'Phishing simulation failure >30%',linkedRisk:'RSK-001',priority:'High',owner:'Ahmed Al-Rashid',dueDate:'2026-07-01',status:'Open'},
{id:'ISS-002',issue:'Vendor contract review overdue',linkedRisk:'RSK-002',priority:'Medium',owner:'Marcus Webb',dueDate:'2026-06-30',status:'In Progress'},
{id:'ISS-003',issue:'GDPR consent forms not updated',linkedRisk:'RSK-003',priority:'Critical',owner:'Khalid Hassan',dueDate:'2026-06-15',status:'Open'},
{id:'ISS-004',issue:'DR failover test not done',linkedRisk:'RSK-004',priority:'High',owner:'Priya Nair',dueDate:'2026-07-31',status:'Open'},
],
policies:[
{id:'POL-001',title:'Information Security Policy',category:'Information Security',status:'Active',owner:'Priya Nair',version:'2.1',reviewDate:'2026-12-31',framework:'ISO 27001',description:'Defines approach to protecting information assets.'},
{id:'POL-002',title:'Data Privacy & GDPR Policy',category:'Data Privacy',status:'Under Review',owner:'Khalid Hassan',version:'1.3',reviewDate:'2026-07-01',framework:'GDPR',description:'Governs collection and processing of personal data.'},
{id:'POL-003',title:'Acceptable Use Policy',category:'IT & Technology',status:'Active',owner:'Ahmed Al-Rashid',version:'3.0',reviewDate:'2026-11-30',framework:'ISO 27001',description:'Rules for acceptable use of IT systems.'},
{id:'POL-004',title:'Business Continuity Plan',category:'Operational',status:'Draft',owner:'Sara Mohammed',version:'0.9',reviewDate:'2026-09-15',framework:'ISO 22301',description:'Procedures to ensure critical functions continue.'},
{id:'POL-005',title:'Vendor Management Policy',category:'Operational',status:'Active',owner:'Marcus Webb',version:'1.1',reviewDate:'2026-10-31',framework:'SOC 2',description:'Standards for managing third-party vendors.'},
],
assets:[
{id:'AST-001',name:'Core Banking System',type:'Software',owner:'Priya Nair',criticality:'Critical',location:'AWS us-east-1',linkedRisks:['RSK-001','RSK-004'],lastReviewed:'2026-05-01',description:'Primary banking application handling all transactions.'},
{id:'AST-002',name:'Customer Database',type:'Data',owner:'Khalid Hassan',criticality:'Critical',location:'AWS RDS',linkedRisks:['RSK-001','RSK-003'],lastReviewed:'2026-04-15',description:'All customer PII and transaction records.'},
{id:'AST-003',name:'Office Network Infrastructure',type:'Hardware',owner:'Ahmed Al-Rashid',criticality:'High',location:'Doha HQ',linkedRisks:['RSK-002'],lastReviewed:'2026-03-10',description:'Routers, switches and firewall hardware.'},
{id:'AST-004',name:'Finance ERP System',type:'Software',owner:'Sara Mohammed',criticality:'High',location:'On-Premise',linkedRisks:['RSK-006'],lastReviewed:'2026-05-20',description:'SAP ERP for financial management.'},
{id:'AST-005',name:'IT Operations Team',type:'People',owner:'Marcus Webb',criticality:'High',location:'Doha HQ',linkedRisks:['RSK-005'],lastReviewed:'2026-04-01',description:'Core team managing critical systems.'},
],
emailConfig:{pubKey:'',serviceId:'',templateId:'',email:''},
alertPrefs:{critical:true,high:true,appetite:true,overdue:true,policy:true}
};
function save(){localStorage.setItem(STORE_KEY,JSON.stringify(data));}
function severity(s){if(s>=16)return'Critical';if(s>=9)return'High';if(s>=4)return'Medium';return'Low';}
function sevClass(s){return'badge-'+s.toLowerCase();}
function sc(r){return r.likelihood*r.impact;}
function initials(n){return n.split(' ').map(w=>w[0]).join('').slice(0,2).toUpperCase();}
function scoreColor(s){if(s>=16)return'rgba(239,68,68,.25)';if(s>=9)return'rgba(245,158,11,.25)';if(s>=4)return'rgba(59,130,246,.2)';return'rgba(34,197,94,.15)';}
function trendIcon(t){if(t==='Up')return'<span class="trend-up">↑</span>';if(t==='Down')return'<span class="trend-down">↓</span>';return'<span class="trend-flat">→</span>';}
function daysUntil(d){return d?Math.ceil((new Date(d)-new Date())/(1000*60*60*24)):null;}
let modalType='',editId=null,editIdx=null;
function toast(msg,type='success'){const t=document.getElementById('toast'),dot=document.getElementById('toast-dot');document.getElementById('toast-msg').textContent=msg;dot.style.background=type==='error'?'var(--red)':type==='warn'?'var(--amber)':'var(--teal)';t.classList.add('show');setTimeout(()=>t.classList.remove('show'),3000);}
function showPage(name,el){document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));document.querySelectorAll('.nav-item').forEach(n=>n.classList.remove('active'));document.getElementById('page-'+name).classList.add('active');if(el)el.classList.add('active');({dashboard:renderDashboard,risks:renderRisks,heatmap:renderHeatmap,controls:renderControls,policies:renderPolicies,compliance:renderCompliance,issues:renderIssues,assets:renderAssets,reports:()=>{},email:renderEmail})[name]?.();}

function renderDashboard(){
  const open=data.risks.filter(r=>r.status!=='Closed');
  const crit=open.filter(r=>severity(sc(r))==='Critical');
  const breaches=open.filter(r=>r.appetiteBreach==='Yes');
  document.getElementById('stat-grid').innerHTML=`
    <div class="stat-card"><div class="stat-top"><span class="stat-label">Total Risks</span><div class="stat-icon" style="background:#1e1a3a">🔢</div></div><div class="stat-value" style="color:var(--purple)">${data.risks.length}</div><div class="stat-sub">${open.length} open</div></div>
    <div class="stat-card"><div class="stat-top"><span class="stat-label">Critical Risks</span><div class="stat-icon" style="background:var(--red-bg)">🔴</div></div><div class="stat-value" style="color:var(--red)">${crit.length}</div><div class="stat-sub">Immediate action</div></div>
    <div class="stat-card"><div class="stat-top"><span class="stat-label">Appetite Breaches</span><div class="stat-icon" style="background:var(--amber-bg)">🎯</div></div><div class="stat-value" style="color:var(--amber)">${breaches.length}</div><div class="stat-sub">Exceeding tolerance</div></div>
    <div class="stat-card"><div class="stat-top"><span class="stat-label">Assets Tracked</span><div class="stat-icon" style="background:var(--teal-bg)">🖥️</div></div><div class="stat-value" style="color:var(--teal)">${data.assets.length}</div><div class="stat-sub">${data.assets.filter(a=>a.criticality==='Critical').length} critical</div></div>`;
  const avgEff=data.controls.length?Math.round(data.controls.reduce((a,c)=>a+c.effectiveness,0)/data.controls.length):0;
  const compRate=data.compliance.length?Math.round(data.compliance.filter(c=>c.status==='Compliant').length/data.compliance.length*100):0;
  const closeRate=data.risks.length?Math.round(data.risks.filter(r=>r.status==='Closed').length/data.risks.length*100):0;
  document.getElementById('kri-grid').innerHTML=`
    <div class="kri-card"><div class="kri-title">Control Effectiveness</div><div class="kri-value" style="color:${avgEff>=70?'var(--teal)':avgEff>=50?'var(--amber)':'var(--red)'}">${avgEff}%</div><div class="kri-bar-wrap"><div class="progress-bar"><div class="progress-fill" style="width:${avgEff}%;background:${avgEff>=70?'var(--teal)':avgEff>=50?'var(--amber)':'var(--red)'}"></div></div></div><div class="kri-threshold">Target: ≥70%</div></div>
    <div class="kri-card"><div class="kri-title">Compliance Rate</div><div class="kri-value" style="color:${compRate>=80?'var(--teal)':compRate>=60?'var(--amber)':'var(--red)'}">${compRate}%</div><div class="kri-bar-wrap"><div class="progress-bar"><div class="progress-fill" style="width:${compRate}%;background:${compRate>=80?'var(--teal)':compRate>=60?'var(--amber)':'var(--red)'}"></div></div></div><div class="kri-threshold">Target: ≥80%</div></div>
    <div class="kri-card"><div class="kri-title">Risk Closure Rate</div><div class="kri-value" style="color:var(--purple)">${closeRate}%</div><div class="kri-bar-wrap"><div class="progress-bar"><div class="progress-fill" style="width:${closeRate}%;background:var(--purple)"></div></div></div><div class="kri-threshold">Closed vs total</div></div>`;

  // KPIs
  const overdue=open.filter(r=>r.dueDate&&daysUntil(r.dueDate)<0);
  const dueSoon=open.filter(r=>r.dueDate&&daysUntil(r.dueDate)>=0&&daysUntil(r.dueDate)<=7);
  const onTrack=open.length?Math.round(open.filter(r=>!r.dueDate||daysUntil(r.dueDate)>=0).length/open.length*100):100;
  const trendingUp=open.filter(r=>r.trend==='Up').length;
  document.getElementById('kpi-grid').innerHTML=`
    <div class="kri-card"><div class="kri-title">Risks On Track</div><div class="kri-value" style="color:${onTrack>=80?'var(--teal)':onTrack>=50?'var(--amber)':'var(--red)'}">${onTrack}%</div><div class="kri-bar-wrap"><div class="progress-bar"><div class="progress-fill" style="width:${onTrack}%;background:${onTrack>=80?'var(--teal)':onTrack>=50?'var(--amber)':'var(--red)'}"></div></div></div><div class="kri-threshold">${overdue.length} overdue</div></div>
    <div class="kri-card"><div class="kri-title">Avg Residual Reduction</div><div class="kri-value" style="color:var(--teal)">${(()=>{const diffs=data.risks.filter(r=>r.residualScore!=null).map(r=>sc(r)-r.residualScore);return diffs.length?Math.round(diffs.reduce((a,b)=>a+b,0)/diffs.length*10)/10:0;})()}</div><div class="kri-bar-wrap"><div class="kri-threshold" style="margin-top:8px">Inherent → Residual score drop</div></div></div>
    <div class="kri-card"><div class="kri-title">Risks Trending Up</div><div class="kri-value" style="color:${trendingUp>0?'var(--red)':'var(--teal)'}">${trendingUp}</div><div class="kri-bar-wrap"><div class="kri-threshold" style="margin-top:8px">${trendingUp>0?'⚠️ Worsening risk exposure':'✅ No worsening risks'}</div></div></div>`;

  // Overdue panel
  if(overdue.length){
    document.getElementById('overdue-section').style.display='block';
    document.getElementById('overdue-count').textContent=`${overdue.length} risk(s) past due date`;
    document.getElementById('overdue-table').innerHTML=overdue.map(r=>`<tr><td><b>${r.id}</b></td><td>${r.name}</td><td><div class="risk-score" style="background:${scoreColor(sc(r))}">${sc(r)}</div></td><td><span class="badge ${sevClass(severity(sc(r)))}">${severity(sc(r))}</span></td><td><span class="avatar">${initials(r.owner)}</span>${r.owner.split(' ')[0]}</td><td style="color:var(--red);font-size:12px">${r.dueDate}</td><td style="color:var(--red);font-weight:600">${Math.abs(daysUntil(r.dueDate))}d</td></tr>`).join('');
  }else document.getElementById('overdue-section').style.display='none';

  // Due soon panel
  if(dueSoon.length){
    document.getElementById('duesoon-section').style.display='block';
    document.getElementById('duesoon-count').textContent=`${dueSoon.length} risk(s) due within 7 days`;
    document.getElementById('duesoon-table').innerHTML=dueSoon.map(r=>`<tr><td><b>${r.id}</b></td><td>${r.name}</td><td><div class="risk-score" style="background:${scoreColor(sc(r))}">${sc(r)}</div></td><td><span class="avatar">${initials(r.owner)}</span>${r.owner.split(' ')[0]}</td><td style="font-size:12px;color:var(--text3)">${r.treatmentStatus||r.treatment||'—'}</td><td style="color:var(--amber);font-size:12px">${r.dueDate} (${daysUntil(r.dueDate)}d)</td></tr>`).join('');
  }else document.getElementById('duesoon-section').style.display='none';

  const top=[...data.risks].sort((a,b)=>sc(b)-sc(a)).slice(0,6);
  document.getElementById('top-risks-table').innerHTML=top.map(r=>`
    <tr><td><b>${r.id}</b></td><td>${r.name}</td>
    <td><div class="risk-score" style="background:${scoreColor(sc(r))}">${sc(r)}</div></td>
    <td><div class="risk-score" style="background:${scoreColor(r.residualScore||0)}">${r.residualScore||'—'}</div></td>
    <td><span class="badge ${sevClass(severity(sc(r)))}">${severity(sc(r))}</span></td>
    <td>${trendIcon(r.trend)}</td>
    <td><span class="badge badge-${r.appetiteBreach==='Yes'?'yes':'no'}">${r.appetiteBreach||'No'}</span></td>
    <td><span class="avatar">${initials(r.owner)}</span>${r.owner.split(' ')[0]}</td>
    <td style="font-size:11px;color:var(--text3)">${r.dueDate||'—'}</td></tr>`).join('');
  updateBadge();
}

function renderRisks(list){
  list=list||data.risks;
  document.getElementById('risk-table').innerHTML=list.length?list.map(r=>`
    <tr><td><b style="font-size:11px">${r.id}</b></td><td style="max-width:160px;font-size:12px">${r.name}</td><td style="font-size:11px">${r.category}</td>
    <td>${r.likelihood}</td><td>${r.impact}</td>
    <td><div class="risk-score" style="background:${scoreColor(sc(r))}">${sc(r)}</div></td>
    <td><div class="risk-score" style="background:${scoreColor(r.residualScore||0)};font-size:11px">${r.residualScore||'—'}</div></td>
    <td><span class="badge ${sevClass(severity(sc(r)))}" style="font-size:10px">${severity(sc(r))}</span></td>
    <td><span class="badge badge-${r.appetiteBreach==='Yes'?'yes':'no'}" style="font-size:10px">${r.appetiteBreach||'No'}</span></td>
    <td>${trendIcon(r.trend)}</td>
    <td style="font-size:12px"><span class="avatar">${initials(r.owner)}</span>${r.owner.split(' ')[0]}</td>
    <td style="font-size:11px;color:var(--text3)">${r.treatmentStatus||r.treatment||'—'}</td>
    <td style="font-size:11px;color:var(--text3)">${r.dueDate||'—'}</td>
    <td style="font-size:11px;color:var(--text3)">${r.lastReview||'—'}</td>
    <td><span class="badge badge-${r.status==='Open'?'open':r.status==='In Progress'?'progress':'closed'}" style="font-size:10px">${r.status}</span></td>
    <td style="white-space:nowrap"><button class="btn btn-ghost" style="padding:3px 8px;font-size:11px" onclick="openModal('risk',data.risks.find(x=>x.id==='${r.id}'))">Edit</button> <button class="btn btn-danger" style="padding:3px 8px;font-size:11px" onclick="deleteItem('risks','${r.id}')">Del</button></td></tr>`).join('')
    :`<tr><td colspan="16"><div class="empty"><div class="empty-icon">🛡️</div><div class="empty-text">No risks found.</div></div></td></tr>`;
  updateBadge();
}
function filterRisks(){const q=document.getElementById('risk-search').value.toLowerCase();const cat=document.getElementById('risk-filter-cat').value;const sev=document.getElementById('risk-filter-sev').value;const breach=document.getElementById('risk-filter-breach').value;renderRisks(data.risks.filter(r=>(!q||r.name.toLowerCase().includes(q)||r.id.toLowerCase().includes(q))&&(!cat||r.category===cat)&&(!sev||severity(sc(r))===sev)&&(!breach||r.appetiteBreach===breach)));}
function deleteItem(type,id){if(!confirm('Delete?'))return;data[type]=data[type].filter(x=>x.id!==id);save();({risks:renderRisks,controls:renderControls,issues:renderIssues,policies:renderPolicies,assets:renderAssets})[type]?.();toast('Deleted');}
function updateBadge(){document.getElementById('risk-badge').textContent=data.risks.filter(r=>r.status!=='Closed').length;}

function renderHeatmap(){
  const labels=['Very Low','Low','Medium','High','Very High'];let html='';
  for(let imp=5;imp>=1;imp--){
    html+=`<div class="hm-label" style="font-size:9px;text-align:right;padding-right:4px">${labels[imp-1]}</div>`;
    for(let lik=1;lik<=5;lik++){const s=lik*imp,sev=severity(s),risks=data.risks.filter(r=>r.likelihood===lik&&r.impact===imp);const cls=sev==='Critical'?'hm-critical':sev==='High'?'hm-high':sev==='Medium'?'hm-medium':'hm-low';html+=`<div class="hm-cell ${cls}" onclick="showHeatmapRisks(${lik},${imp})" title="L${lik}xI${imp}=${s}">${risks.length||''}</div>`;}
  }
  html+='<div></div>';labels.forEach(l=>html+=`<div class="hm-label" style="font-size:9px;text-align:center">${l}</div>`);
  document.getElementById('heatmap-container').innerHTML=`<div style="margin-bottom:8px;font-size:11px;color:var(--text3)">↑ Impact</div><div class="heatmap-grid">${html}</div><div style="margin-top:6px;font-size:11px;color:var(--text3)">Likelihood →</div>`;
}
function showHeatmapRisks(lik,imp){const risks=data.risks.filter(r=>r.likelihood===lik&&r.impact===imp);const sec=document.getElementById('heatmap-risks-section');if(!risks.length){sec.style.display='none';return;}document.getElementById('heatmap-risks-title').textContent=`Risks at L${lik}×I${imp}`;document.getElementById('heatmap-risks-table').innerHTML=risks.map(r=>`<tr><td><b>${r.id}</b></td><td>${r.name}</td><td><div class="risk-score" style="background:${scoreColor(r.residualScore||0)};font-size:11px">${r.residualScore||'—'}</div></td><td>${trendIcon(r.trend)}</td><td>${r.owner}</td><td><span class="badge badge-${r.status==='Open'?'open':r.status==='In Progress'?'progress':'closed'}">${r.status}</span></td></tr>`).join('');sec.style.display='block';}

function renderControls(){
  const eff=e=>e>=70?'effective':e>=40?'partial':'ineffective';const counts={effective:0,partial:0,ineffective:0};data.controls.forEach(c=>counts[eff(c.effectiveness)]++);
  document.getElementById('control-stats').innerHTML=`<div class="stat-card"><div class="stat-top"><span class="stat-label">Effective</span><div class="stat-icon" style="background:var(--teal-bg)">✅</div></div><div class="stat-value" style="color:var(--teal)">${counts.effective}</div></div><div class="stat-card"><div class="stat-top"><span class="stat-label">Partial</span><div class="stat-icon" style="background:var(--amber-bg)">⚠️</div></div><div class="stat-value" style="color:var(--amber)">${counts.partial}</div></div><div class="stat-card"><div class="stat-top"><span class="stat-label">Ineffective</span><div class="stat-icon" style="background:var(--red-bg)">❌</div></div><div class="stat-value" style="color:var(--red)">${counts.ineffective}</div></div><div class="stat-card"><div class="stat-top"><span class="stat-label">Total</span><div class="stat-icon" style="background:#1e1a3a">🛡️</div></div><div class="stat-value" style="color:var(--purple)">${data.controls.length}</div></div>`;
  document.getElementById('controls-table').innerHTML=data.controls.map(c=>`<tr><td><b>${c.id}</b></td><td>${c.name}</td><td>${c.type}</td><td><div class="progress-wrap"><div class="progress-bar"><div class="progress-fill" style="width:${c.effectiveness}%;background:${c.effectiveness>=70?'var(--teal)':c.effectiveness>=40?'var(--amber)':'var(--red)'}"></div></div><span style="font-size:11px;min-width:30px">${c.effectiveness}%</span></div></td><td><span class="avatar">${initials(c.owner)}</span>${c.owner.split(' ')[0]}</td><td style="font-size:12px;color:var(--text3)">${c.lastTested}</td><td>${c.mitigates.map(m=>`<span class="badge badge-medium" style="margin-right:2px;font-size:10px">${m}</span>`).join('')}</td><td style="white-space:nowrap"><button class="btn btn-ghost" style="padding:3px 8px;font-size:11px" onclick="openModal('control',data.controls.find(x=>x.id==='${c.id}'))">Edit</button> <button class="btn btn-danger" style="padding:3px 8px;font-size:11px" onclick="deleteItem('controls','${c.id}')">Del</button></td></tr>`).join('');}

function renderPolicies(list){
  list=list||data.policies;const counts={Active:0,Draft:0,'Under Review':0,Expired:0};data.policies.forEach(p=>counts[p.status]=(counts[p.status]||0)+1);
  document.getElementById('policy-stats').innerHTML=`<div class="stat-card"><div class="stat-top"><span class="stat-label">Active</span><div class="stat-icon" style="background:var(--teal-bg)">✅</div></div><div class="stat-value" style="color:var(--teal)">${counts.Active||0}</div></div><div class="stat-card"><div class="stat-top"><span class="stat-label">Draft</span><div class="stat-icon" style="background:var(--bg3)">📝</div></div><div class="stat-value" style="color:var(--text2)">${counts.Draft||0}</div></div><div class="stat-card"><div class="stat-top"><span class="stat-label">Under Review</span><div class="stat-icon" style="background:var(--amber-bg)">🔍</div></div><div class="stat-value" style="color:var(--amber)">${counts['Under Review']||0}</div></div><div class="stat-card"><div class="stat-top"><span class="stat-label">Expired</span><div class="stat-icon" style="background:var(--red-bg)">⏰</div></div><div class="stat-value" style="color:var(--red)">${counts.Expired||0}</div></div>`;
  if(!list.length){document.getElementById('policy-grid').innerHTML=`<div class="empty" style="grid-column:1/-1"><div class="empty-icon">📋</div><div class="empty-text">No policies found.</div></div>`;return;}
  document.getElementById('policy-grid').innerHTML=list.map(p=>{const days=p.reviewDate?daysUntil(p.reviewDate):null;const due=days!==null&&days<=30?`<span style="color:var(--amber);font-size:10px"> ⚠️ ${days}d</span>`:'';return`<div class="policy-card"><div class="policy-card-top"><div class="policy-card-title">${p.title}</div><span class="badge badge-${p.status==='Active'?'active':p.status==='Draft'?'draft':p.status==='Under Review'?'review':'expired'}">${p.status}</span></div><div class="policy-card-meta"><b>${p.id}</b> · v${p.version} · ${p.category}<br><b>Framework:</b> ${p.framework}<br><b>Owner:</b> ${p.owner}<br><b>Review:</b> ${p.reviewDate||'—'}${due}</div><div style="font-size:12px;color:var(--text3);margin-bottom:9px">${p.description}</div><div style="display:flex;gap:6px"><button class="btn btn-ghost" style="padding:3px 8px;font-size:11px" onclick="openModal('policy',data.policies.find(x=>x.id==='${p.id}'))">Edit</button><button class="btn btn-danger" style="padding:3px 8px;font-size:11px" onclick="deleteItem('policies','${p.id}')">Delete</button></div></div>`;}).join('');}
function filterPolicies(){const q=document.getElementById('policy-search').value.toLowerCase();const st=document.getElementById('policy-filter-status').value;renderPolicies(data.policies.filter(p=>(!q||p.title.toLowerCase().includes(q))&&(!st||p.status===st)));}

function renderCompliance(){document.getElementById('compliance-table').innerHTML=data.compliance.map((c,i)=>`<tr><td><b>${c.framework}</b></td><td>${c.requirement}</td><td><span class="badge ${c.status==='Compliant'?'badge-compliant':c.status==='Non-Compliant'?'badge-noncompliant':'badge-partial-c'}">${c.status}</span></td><td><span class="avatar">${initials(c.owner)}</span>${c.owner.split(' ')[0]}</td><td style="font-size:12px;color:var(--text3)">${c.dueDate}</td><td><div class="progress-wrap"><div class="progress-bar"><div class="progress-fill" style="width:${c.progress}%;background:${c.progress>=80?'var(--teal)':c.progress>=50?'var(--amber)':'var(--red)'}"></div></div><span style="font-size:11px;min-width:30px">${c.progress}%</span></div></td><td style="white-space:nowrap"><button class="btn btn-ghost" style="padding:3px 8px;font-size:11px" onclick="openModal('compliance',data.compliance[${i}],${i})">Edit</button> <button class="btn btn-danger" style="padding:3px 8px;font-size:11px" onclick="deleteCompliance(${i})">Del</button></td></tr>`).join('');}
function deleteCompliance(i){if(!confirm('Delete?'))return;data.compliance.splice(i,1);save();renderCompliance();toast('Deleted');}

function renderIssues(){document.getElementById('issues-table').innerHTML=data.issues.map(iss=>`<tr><td><b>${iss.id}</b></td><td>${iss.issue}</td><td><span class="badge badge-medium" style="font-size:10px">${iss.linkedRisk}</span></td><td><span class="badge ${sevClass(iss.priority)}">${iss.priority}</span></td><td><span class="avatar">${initials(iss.owner)}</span>${iss.owner.split(' ')[0]}</td><td style="font-size:12px;color:var(--text3)">${iss.dueDate}</td><td><span class="badge badge-${iss.status==='Open'?'open':iss.status==='In Progress'?'progress':'closed'}">${iss.status}</span></td><td style="white-space:nowrap"><button class="btn btn-ghost" style="padding:3px 8px;font-size:11px" onclick="openModal('issue',data.issues.find(x=>x.id==='${iss.id}'))">Edit</button> <button class="btn btn-danger" style="padding:3px 8px;font-size:11px" onclick="deleteItem('issues','${iss.id}')">Del</button></td></tr>`).join('');}

function renderAssets(list){
  list=list||data.assets;
  const typeIcon={Hardware:'🖥️',Software:'💻',Data:'🗄️',People:'👤',Facility:'🏢','Cloud Service':'☁️'};
  const counts={Critical:0,High:0,Medium:0,Low:0};data.assets.forEach(a=>counts[a.criticality]=(counts[a.criticality]||0)+1);
  document.getElementById('asset-stats').innerHTML=`<div class="stat-card"><div class="stat-top"><span class="stat-label">Total Assets</span><div class="stat-icon" style="background:#1e1a3a">🖥️</div></div><div class="stat-value" style="color:var(--purple)">${data.assets.length}</div></div><div class="stat-card"><div class="stat-top"><span class="stat-label">Critical</span><div class="stat-icon" style="background:var(--red-bg)">🔴</div></div><div class="stat-value" style="color:var(--red)">${counts.Critical||0}</div></div><div class="stat-card"><div class="stat-top"><span class="stat-label">High</span><div class="stat-icon" style="background:var(--amber-bg)">🟡</div></div><div class="stat-value" style="color:var(--amber)">${counts.High||0}</div></div><div class="stat-card"><div class="stat-top"><span class="stat-label">Asset Types</span><div class="stat-icon" style="background:var(--teal-bg)">📦</div></div><div class="stat-value" style="color:var(--teal)">${new Set(data.assets.map(a=>a.type)).size}</div></div>`;
  document.getElementById('assets-table').innerHTML=list.length?list.map(a=>`<tr><td><b>${a.id}</b></td><td><span class="asset-type-icon" style="background:var(--bg3)">${typeIcon[a.type]||'📦'}</span>${a.name}</td><td>${a.type}</td><td><span class="avatar">${initials(a.owner)}</span>${a.owner.split(' ')[0]}</td><td><span class="badge ${sevClass(a.criticality)}">${a.criticality}</span></td><td style="font-size:12px;color:var(--text3)">${a.location}</td><td>${(a.linkedRisks||[]).map(r=>`<span class="badge badge-medium" style="margin-right:2px;font-size:10px">${r}</span>`).join('')}</td><td style="font-size:12px;color:var(--text3)">${a.lastReviewed||'—'}</td><td style="white-space:nowrap"><button class="btn btn-ghost" style="padding:3px 8px;font-size:11px" onclick="openModal('asset',data.assets.find(x=>x.id==='${a.id}'))">Edit</button> <button class="btn btn-danger" style="padding:3px 8px;font-size:11px" onclick="deleteItem('assets','${a.id}')">Del</button></td></tr>`).join(''):`<tr><td colspan="9"><div class="empty"><div class="empty-icon">🖥️</div><div class="empty-text">No assets found.</div></div></td></tr>`;}
function filterAssets(){const q=document.getElementById('asset-search').value.toLowerCase();const type=document.getElementById('asset-filter-type').value;const crit=document.getElementById('asset-filter-crit').value;renderAssets(data.assets.filter(a=>(!q||a.name.toLowerCase().includes(q)||a.id.toLowerCase().includes(q))&&(!type||a.type===type)&&(!crit||a.criticality===crit)));}

// ── REPORTS ──────────────────────────────────────────────────
function generateReport(type){
  const out=document.getElementById('report-output');const body=document.getElementById('report-body');const title=document.getElementById('report-title');
  const now=new Date().toLocaleDateString('en-GB',{day:'2-digit',month:'short',year:'numeric'});
  const open=data.risks.filter(r=>r.status!=='Closed');
  const breaches=open.filter(r=>r.appetiteBreach==='Yes');
  const ts=s=>`<span class="badge ${sevClass(severity(s))}">${severity(s)}</span>`;
  const row=(cells)=>`<tr>${cells.map(c=>`<td style="padding:8px 12px;border-bottom:1px solid rgba(42,51,82,.4);font-size:12px">${c}</td>`).join('')}</tr>`;
  const thead=(cols)=>`<thead><tr>${cols.map(c=>`<th style="padding:8px 12px;font-size:11px;font-weight:600;color:var(--text3);text-transform:uppercase;border-bottom:1px solid var(--border)">${c}</th>`).join('')}</tr></thead>`;
  const tbl=(cols,rows)=>`<table style="width:100%;border-collapse:collapse">${thead(cols)}<tbody>${rows.join('')}</tbody></table>`;
  const stat=(label,val,color)=>`<div style="background:var(--bg3);border:1px solid var(--border);border-radius:8px;padding:14px;text-align:center"><div style="font-size:11px;color:var(--text3);margin-bottom:4px">${label}</div><div style="font-size:24px;font-weight:700;color:${color}">${val}</div></div>`;
  const avgEff=data.controls.length?Math.round(data.controls.reduce((a,c)=>a+c.effectiveness,0)/data.controls.length):0;
  const compRate=data.compliance.length?Math.round(data.compliance.filter(c=>c.status==='Compliant').length/data.compliance.length*100):0;

  const reports={
    executive:{
      t:'Executive Risk Summary',
      b:`<div style="color:var(--text3);font-size:12px;margin-bottom:16px">Generated: ${now}</div>
      <div style="display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin-bottom:20px">
        ${stat('Total Risks',data.risks.length,'var(--purple)')}${stat('Open Risks',open.length,'var(--blue)')}${stat('Critical',open.filter(r=>severity(sc(r))==='Critical').length,'var(--red)')}${stat('Appetite Breaches',breaches.length,'var(--amber)')}
      </div>
      <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:20px">
        ${stat('Control Effectiveness',avgEff+'%',avgEff>=70?'var(--teal)':avgEff>=50?'var(--amber)':'var(--red)')}${stat('Compliance Rate',compRate+'%',compRate>=80?'var(--teal)':compRate>=60?'var(--amber)':'var(--red)')}${stat('Risks Trending Up',open.filter(r=>r.trend==='Up').length,'var(--red)')}
      </div>
      <h3 style="font-size:13px;margin-bottom:10px;color:var(--text2)">Top Risks by Score</h3>
      ${tbl(['ID','Risk','Score','Residual','Rating','Appetite Breach','Trend','Owner'],
        [...data.risks].sort((a,b)=>sc(b)-sc(a)).slice(0,8).map(r=>row([`<b>${r.id}</b>`,r.name,`<b style="color:${sc(r)>=16?'#f87171':sc(r)>=9?'#fbbf24':'#60a5fa'}">${sc(r)}</b>`,r.residualScore||'—',ts(sc(r)),`<span style="color:${r.appetiteBreach==='Yes'?'#f87171':'#4ade80'};font-weight:600">${r.appetiteBreach||'No'}</span>`,r.trend==='Up'?'↑ Up':r.trend==='Down'?'↓ Down':'→ Flat',r.owner])))}`,
    },
    register:{
      t:'Full Risk Register',
      b:`<div style="color:var(--text3);font-size:12px;margin-bottom:16px">Generated: ${now} · ${data.risks.length} risks total</div>
      ${tbl(['ID','Risk','Category','Score','Residual','Rating','Appetite','Trend','Treatment','Due Date','Last Review','Status'],
        data.risks.map(r=>row([`<b>${r.id}</b>`,r.name,r.category,`<b>${sc(r)}</b>`,r.residualScore||'—',ts(sc(r)),`<span style="color:${r.appetiteBreach==='Yes'?'#f87171':'#4ade80'}">${r.appetiteBreach||'No'}</span>`,r.trend||'—',r.treatmentStatus||r.treatment||'—',r.dueDate||'—',r.lastReview||'—',r.status])))}`,
    },
    appetite:{
      t:'Risk Appetite Report',
      b:`<div style="color:var(--text3);font-size:12px;margin-bottom:16px">Generated: ${now} · ${breaches.length} breach(es) identified</div>
      ${breaches.length?tbl(['ID','Risk','Category','Score','Residual','Severity','Owner','Due Date'],
        breaches.map(r=>row([`<b>${r.id}</b>`,r.name,r.category,`<b style="color:#f87171">${sc(r)}</b>`,r.residualScore||'—',ts(sc(r)),r.owner,r.dueDate||'—'])))
        :`<div style="text-align:center;padding:30px;color:var(--teal)">✅ No appetite breaches detected</div>`}`,
    },
    residual:{
      t:'Residual Risk Report',
      b:`<div style="color:var(--text3);font-size:12px;margin-bottom:16px">Generated: ${now}</div>
      ${tbl(['ID','Risk','Inherent Score','Residual Score','Reduction','Rating','Treatment Status'],
        data.risks.map(r=>{const inh=sc(r);const res=r.residualScore||inh;const red=inh-res;return row([`<b>${r.id}</b>`,r.name,`<b style="color:${scoreColor(inh).replace(/,.*/,'').replace('rgba(','').split(',').join(',')}}">${inh}</b>`,`<b>${res}</b>`,`<span style="color:${red>0?'#4ade80':'#f87171'}">${red>0?'-'+red:red===0?'0':'+'+Math.abs(red)}</span>`,ts(inh),r.treatmentStatus||r.treatment||'—']);}))}`,
    },
    compliance:{
      t:'Compliance Status Report',
      b:`<div style="color:var(--text3);font-size:12px;margin-bottom:16px">Generated: ${now}</div>
      <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:18px">
        ${stat('Compliant',data.compliance.filter(c=>c.status==='Compliant').length,'var(--teal)')}${stat('Partial',data.compliance.filter(c=>c.status==='Partial').length,'var(--amber)')}${stat('Non-Compliant',data.compliance.filter(c=>c.status==='Non-Compliant').length,'var(--red)')}
      </div>
      ${tbl(['Framework','Requirement','Status','Progress','Owner','Due Date'],
        data.compliance.map(c=>row([`<b>${c.framework}</b>`,c.requirement,`<span class="badge ${c.status==='Compliant'?'badge-compliant':c.status==='Non-Compliant'?'badge-noncompliant':'badge-partial-c'}">${c.status}</span>`,`<div class="progress-wrap"><div class="progress-bar" style="flex:1"><div class="progress-fill" style="width:${c.progress}%;background:${c.progress>=80?'var(--teal)':c.progress>=50?'var(--amber)':'var(--red)'}"></div></div><span style="font-size:11px">${c.progress}%</span></div>`,c.owner,c.dueDate||'—'])))}`,
    },
    assets:{
      t:'Asset Risk Report',
      b:`<div style="color:var(--text3);font-size:12px;margin-bottom:16px">Generated: ${now} · ${data.assets.length} assets tracked</div>
      ${tbl(['ID','Asset','Type','Criticality','Owner','Location','Linked Risks','Last Reviewed'],
        data.assets.map(a=>row([`<b>${a.id}</b>`,a.name,a.type,`<span class="badge ${sevClass(a.criticality)}">${a.criticality}</span>`,a.owner,a.location,(a.linkedRisks||[]).join(', ')||'—',a.lastReviewed||'—'])))}`,
    }
  };
  title.textContent=reports[type].t;body.innerHTML=reports[type].b;out.style.display='block';
  out.scrollIntoView({behavior:'smooth'});
}
function printReport(){const content=document.getElementById('report-body').innerHTML;const w=window.open('','_blank');w.document.write(`<html><head><title>GRC Report</title><style>body{font-family:Arial,sans-serif;padding:20px;color:#000}table{width:100%;border-collapse:collapse}th,td{padding:8px;border:1px solid #ddd;font-size:12px}th{background:#f0f0f0;font-weight:600}.badge{padding:2px 8px;border-radius:10px;font-size:11px;font-weight:600}</style></head><body>${content}</body></html>`);w.document.close();w.print();}

// ── EMAIL ────────────────────────────────────────────────────
function renderEmail(){const c=data.emailConfig;['pubKey','serviceId','templateId','email'].forEach(k=>{const el=document.getElementById('ejs-'+k.replace('Key','key').replace('Id','').toLowerCase().replace('pubkey','pubkey').replace('serviceid','service').replace('templateid','template'));if(el&&c[k])el.value=c[k];});document.getElementById('ejs-pubkey').value=c.pubKey||'';document.getElementById('ejs-service').value=c.serviceId||'';document.getElementById('ejs-template').value=c.templateId||'';document.getElementById('ejs-email').value=c.email||'';const p=data.alertPrefs;['critical','high','appetite','overdue','policy'].forEach(k=>{const el=document.getElementById('alert-'+k);if(el)el.checked=p[k];});}
function saveEmailConfig(){data.emailConfig={pubKey:document.getElementById('ejs-pubkey').value,serviceId:document.getElementById('ejs-service').value,templateId:document.getElementById('ejs-template').value,email:document.getElementById('ejs-email').value};save();toast('Config saved');}
function saveAlertPrefs(){['critical','high','appetite','overdue','policy'].forEach(k=>{data.alertPrefs[k]=document.getElementById('alert-'+k).checked;});save();toast('Preferences saved');}
function testEmail(){const c=data.emailConfig;if(!c.pubKey||!c.serviceId||!c.templateId||!c.email){toast('Fill all EmailJS fields','warn');return;}emailjs.init(c.pubKey);emailjs.send(c.serviceId,c.templateId,{to_email:c.email,subject:'GRC-Control Test',message:'Email alerts working!'}).then(()=>toast('Test sent!')).catch(e=>toast('Failed: '+e.text,'error'));}
function sendAlert(subject,message){const c=data.emailConfig;if(!c.pubKey||!c.serviceId||!c.templateId||!c.email)return;emailjs.init(c.pubKey);emailjs.send(c.serviceId,c.templateId,{to_email:c.email,subject,message}).catch(()=>{});}

// ── MODALS ────────────────────────────────────────────────────
function openModal(type,item,idx){
  modalType=type;editId=item?.id||null;editIdx=idx!==undefined?idx:null;
  const F={
    risk:`<div class="form-row"><div class="form-group"><label>Risk Name *</label><input id="f-name" value="${item?.name||''}" placeholder="Describe the risk"/></div><div class="form-group"><label>Category</label><select id="f-cat"><option>Operational</option><option>Financial</option><option>Strategic</option><option>Compliance</option><option>Technology</option><option>Reputational</option></select></div></div>
    <div class="form-group"><label>Description</label><textarea id="f-desc">${item?.description||''}</textarea></div>
    <div class="form-row-3"><div class="form-group"><label>Likelihood (1-5)</label><input id="f-lik" type="number" min="1" max="5" value="${item?.likelihood||3}"/></div><div class="form-group"><label>Impact (1-5)</label><input id="f-imp" type="number" min="1" max="5" value="${item?.impact||3}"/></div><div class="form-group"><label>Residual Score</label><input id="f-res" type="number" min="0" max="25" value="${item?.residualScore||''}" placeholder="After controls"/></div></div>
    <div class="form-row"><div class="form-group"><label>Risk Appetite Breach</label><select id="f-appetite"><option>No</option><option>Yes</option></select></div><div class="form-group"><label>Trend</label><select id="f-trend"><option>Flat</option><option>Up</option><option>Down</option></select></div></div>
    <div class="form-row"><div class="form-group"><label>Owner</label><input id="f-owner" value="${item?.owner||''}" placeholder="Full name"/></div><div class="form-group"><label>Status</label><select id="f-status"><option>Open</option><option>In Progress</option><option>Closed</option></select></div></div>
    <div class="form-row"><div class="form-group"><label>Treatment</label><select id="f-treat"><option>Mitigate</option><option>Accept</option><option>Transfer</option><option>Avoid</option></select></div><div class="form-group"><label>Treatment Status</label><select id="f-tstat"><option>Planned</option><option>In Progress</option><option>Completed</option><option>Accepted</option></select></div></div>
    <div class="form-row"><div class="form-group"><label>Due Date</label><input id="f-due" type="date" value="${item?.dueDate||''}"/></div><div class="form-group"><label>Last Review Date</label><input id="f-review" type="date" value="${item?.lastReview||''}"/></div></div>`,
    control:`<div class="form-row"><div class="form-group"><label>Control Name *</label><input id="f-name" value="${item?.name||''}"/></div><div class="form-group"><label>Type</label><select id="f-type"><option>Preventive</option><option>Detective</option><option>Corrective</option></select></div></div>
    <div class="form-row"><div class="form-group"><label>Effectiveness (%)</label><input id="f-eff" type="number" min="0" max="100" value="${item?.effectiveness||50}"/></div><div class="form-group"><label>Owner</label><input id="f-owner" value="${item?.owner||''}"/></div></div>
    <div class="form-row"><div class="form-group"><label>Last Tested</label><input id="f-tested" type="date" value="${item?.lastTested||''}"/></div><div class="form-group"><label>Mitigates (comma IDs)</label><input id="f-mit" value="${item?.mitigates?.join(',')||''}"/></div></div>`,
    policy:`<div class="form-row"><div class="form-group"><label>Policy Title *</label><input id="f-name" value="${item?.title||''}"/></div><div class="form-group"><label>Category</label><select id="f-pcat"><option>Information Security</option><option>Data Privacy</option><option>Operational</option><option>HR & Conduct</option><option>Financial</option><option>IT & Technology</option></select></div></div>
    <div class="form-group"><label>Description</label><textarea id="f-desc">${item?.description||''}</textarea></div>
    <div class="form-row"><div class="form-group"><label>Owner</label><input id="f-owner" value="${item?.owner||''}"/></div><div class="form-group"><label>Status</label><select id="f-pstatus"><option>Active</option><option>Draft</option><option>Under Review</option><option>Expired</option></select></div></div>
    <div class="form-row"><div class="form-group"><label>Version</label><input id="f-ver" value="${item?.version||'1.0'}"/></div><div class="form-group"><label>Review Date</label><input id="f-review" type="date" value="${item?.reviewDate||''}"/></div></div>
    <div class="form-group"><label>Framework</label><select id="f-fw"><option>ISO 27001</option><option>SOC 2</option><option>GDPR</option><option>NIST CSF</option><option>PCI DSS</option><option>ISO 31000</option><option>ISO 22301</option><option>Other</option></select></div>`,
    compliance:`<div class="form-row"><div class="form-group"><label>Framework</label><select id="f-fw"><option>ISO 27001</option><option>SOC 2</option><option>GDPR</option><option>NIST CSF</option><option>PCI DSS</option><option>ISO 31000</option></select></div><div class="form-group"><label>Status</label><select id="f-status"><option>Compliant</option><option>Non-Compliant</option><option>Partial</option></select></div></div>
    <div class="form-group"><label>Requirement *</label><input id="f-req" value="${item?.requirement||''}"/></div>
    <div class="form-row"><div class="form-group"><label>Owner</label><input id="f-owner" value="${item?.owner||''}"/></div><div class="form-group"><label>Due Date</label><input id="f-due" type="date" value="${item?.dueDate||''}"/></div></div>
    <div class="form-group"><label>Progress (%)</label><input id="f-prog" type="number" min="0" max="100" value="${item?.progress||0}"/></div>`,
    issue:`<div class="form-group"><label>Issue Description *</label><input id="f-iss" value="${item?.issue||''}"/></div>
    <div class="form-row"><div class="form-group"><label>Linked Risk ID</label><input id="f-risk" value="${item?.linkedRisk||''}" placeholder="RSK-001"/></div><div class="form-group"><label>Priority</label><select id="f-pri"><option>Critical</option><option>High</option><option>Medium</option><option>Low</option></select></div></div>
    <div class="form-row"><div class="form-group"><label>Owner</label><input id="f-owner" value="${item?.owner||''}"/></div><div class="form-group"><label>Due Date</label><input id="f-due" type="date" value="${item?.dueDate||''}"/></div></div>
    <div class="form-group"><label>Status</label><select id="f-st"><option>Open</option><option>In Progress</option><option>Closed</option></select></div>`,
    asset:`<div class="form-row"><div class="form-group"><label>Asset Name *</label><input id="f-name" value="${item?.name||''}" placeholder="e.g. Core Banking System"/></div><div class="form-group"><label>Type</label><select id="f-atype"><option>Hardware</option><option>Software</option><option>Data</option><option>People</option><option>Facility</option><option>Cloud Service</option></select></div></div>
    <div class="form-group"><label>Description</label><textarea id="f-desc">${item?.description||''}</textarea></div>
    <div class="form-row"><div class="form-group"><label>Owner</label><input id="f-owner" value="${item?.owner||''}"/></div><div class="form-group"><label>Criticality</label><select id="f-crit"><option>Critical</option><option>High</option><option>Medium</option><option>Low</option></select></div></div>
    <div class="form-row"><div class="form-group"><label>Location</label><input id="f-loc" value="${item?.location||''}" placeholder="e.g. AWS us-east-1, On-Premise"/></div><div class="form-group"><label>Last Reviewed</label><input id="f-reviewed" type="date" value="${item?.lastReviewed||''}"/></div></div>
    <div class="form-group"><label>Linked Risk IDs (comma separated)</label><input id="f-risks" value="${item?.linkedRisks?.join(',')||''}" placeholder="RSK-001, RSK-002"/></div>`
  };
  document.getElementById('modal-title').textContent=(item?'Edit ':'Add ')+{risk:'Risk',control:'Control',policy:'Policy',compliance:'Compliance Item',issue:'Issue',asset:'Asset'}[type];
  document.getElementById('modal-body').innerHTML=F[type];
  document.getElementById('modal').style.display='flex';
  setTimeout(()=>{if(item){
    if(type==='risk'){sv('f-cat',item.category);sv('f-status',item.status);sv('f-treat',item.treatment);sv('f-tstat',item.treatmentStatus);sv('f-appetite',item.appetiteBreach||'No');sv('f-trend',item.trend||'Flat');}
    if(type==='control')sv('f-type',item.type);
    if(type==='policy'){sv('f-pcat',item.category);sv('f-pstatus',item.status);sv('f-fw',item.framework);}
    if(type==='compliance'){sv('f-fw',item.framework);sv('f-status',item.status);}
    if(type==='issue'){sv('f-pri',item.priority);sv('f-st',item.status);}
    if(type==='asset'){sv('f-atype',item.type);sv('f-crit',item.criticality);}
  }},10);
}
function sv(id,val){const el=document.getElementById(id);if(el&&val!==undefined)el.value=val;}
function closeModal(){document.getElementById('modal').style.display='none';editId=null;editIdx=null;}
function g(id){return document.getElementById(id)?.value||'';}

function saveModal(){
  if(modalType==='risk'){
    const name=g('f-name');if(!name){alert('Risk name required');return;}
    const obj={id:editId||`RSK-${String(data.risks.length+1).padStart(3,'0')}`,name,category:g('f-cat'),description:g('f-desc'),likelihood:Math.min(5,Math.max(1,parseInt(g('f-lik'))||3)),impact:Math.min(5,Math.max(1,parseInt(g('f-imp'))||3)),residualScore:parseInt(g('f-res'))||null,appetiteBreach:g('f-appetite')||'No',trend:g('f-trend')||'Flat',owner:g('f-owner')||'Unassigned',status:g('f-status'),treatment:g('f-treat'),treatmentStatus:g('f-tstat'),dueDate:g('f-due'),lastReview:g('f-review')};
    const isNew=!editId;
    if(editId){const i=data.risks.findIndex(r=>r.id===editId);data.risks[i]=obj;}else data.risks.push(obj);
    save();renderRisks();
    if(isNew){const sev=severity(sc(obj));if(sev==='Critical'&&data.alertPrefs.critical)sendAlert(`Critical Risk: ${obj.name}`,`New Critical risk.\nID: ${obj.id}\nScore: ${sc(obj)}\nOwner: ${obj.owner}\nDue: ${obj.dueDate||'—'}`);else if(sev==='High'&&data.alertPrefs.high)sendAlert(`High Risk: ${obj.name}`,`New High risk.\nID: ${obj.id}\nScore: ${sc(obj)}`);if(obj.appetiteBreach==='Yes'&&data.alertPrefs.appetite)sendAlert(`Appetite Breach: ${obj.name}`,`Risk ${obj.id} is breaching risk appetite.\nScore: ${sc(obj)}\nOwner: ${obj.owner}`);}
  }else if(modalType==='control'){
    const name=g('f-name');if(!name)return;
    const obj={id:editId||`CTL-${String(data.controls.length+1).padStart(3,'0')}`,name,type:g('f-type'),effectiveness:parseInt(g('f-eff'))||50,owner:g('f-owner')||'Unassigned',lastTested:g('f-tested')||new Date().toISOString().slice(0,10),mitigates:g('f-mit').split(',').map(s=>s.trim()).filter(Boolean)};
    if(editId){const i=data.controls.findIndex(c=>c.id===editId);data.controls[i]=obj;}else data.controls.push(obj);
    save();renderControls();
  }else if(modalType==='policy'){
    const name=g('f-name');if(!name)return;
    const obj={id:editId||`POL-${String(data.policies.length+1).padStart(3,'0')}`,title:name,category:g('f-pcat'),description:g('f-desc'),owner:g('f-owner')||'Unassigned',status:g('f-pstatus'),version:g('f-ver')||'1.0',reviewDate:g('f-review'),framework:g('f-fw')};
    if(editId){const i=data.policies.findIndex(p=>p.id===editId);data.policies[i]=obj;}else data.policies.push(obj);
    save();renderPolicies();
    const days=obj.reviewDate?daysUntil(obj.reviewDate):null;
    if(days!==null&&days<=30&&data.alertPrefs.policy)sendAlert(`Policy Review Due: ${obj.title}`,`Due in ${days} days.\nOwner: ${obj.owner}`);
  }else if(modalType==='compliance'){
    const req=g('f-req');if(!req)return;
    const obj={framework:g('f-fw'),requirement:req,status:g('f-status'),owner:g('f-owner')||'Unassigned',dueDate:g('f-due')||'',progress:parseInt(g('f-prog'))||0};
    if(editIdx!==null)data.compliance[editIdx]=obj;else data.compliance.push(obj);
    save();renderCompliance();
  }else if(modalType==='issue'){
    const iss=g('f-iss');if(!iss)return;
    const obj={id:editId||`ISS-${String(data.issues.length+1).padStart(3,'0')}`,issue:iss,linkedRisk:g('f-risk'),priority:g('f-pri'),owner:g('f-owner')||'Unassigned',dueDate:g('f-due')||'',status:g('f-st')};
    if(editId){const i=data.issues.findIndex(x=>x.id===editId);data.issues[i]=obj;}else data.issues.push(obj);
    save();renderIssues();
  }else if(modalType==='asset'){
    const name=g('f-name');if(!name)return;
    const obj={id:editId||`AST-${String(data.assets.length+1).padStart(3,'0')}`,name,type:g('f-atype'),description:g('f-desc'),owner:g('f-owner')||'Unassigned',criticality:g('f-crit'),location:g('f-loc'),linkedRisks:g('f-risks').split(',').map(s=>s.trim()).filter(Boolean),lastReviewed:g('f-reviewed')};
    if(editId){const i=data.assets.findIndex(a=>a.id===editId);data.assets[i]=obj;}else data.assets.push(obj);
    save();renderAssets();
  }
  closeModal();toast('Saved successfully ✓');
}

function exportCSV(){
  const rows=[['ID','Risk','Category','Likelihood','Impact','Score','Residual','Severity','Appetite Breach','Trend','Owner','Treatment','Treatment Status','Due Date','Last Review','Status'],...data.risks.map(r=>[r.id,r.name,r.category,r.likelihood,r.impact,sc(r),r.residualScore||'',severity(sc(r)),r.appetiteBreach||'No',r.trend||'Flat',r.owner,r.treatment,r.treatmentStatus||'',r.dueDate||'',r.lastReview||'',r.status])];
  const csv=rows.map(r=>r.map(c=>`"${c}"`).join(',')).join('\n');
  const a=document.createElement('a');a.href='data:text/csv;charset=utf-8,'+encodeURIComponent(csv);a.download='grc-risk-register.csv';a.click();toast('CSV exported ✓');
}
renderDashboard();
</script>
</body>
</html>
