---
title: 健康与运动
url: /sport/
summary: 最近一周的健康概况与接下来七天的运动计划
hideMeta: true
ShowBreadCrumbs: false
ShowReadingTime: false
ShowShareButtons: false
ShowPostNavLinks: false
ShowToc: false
disableShare: true
---

<style>/* Page-specific theme overrides and a self-contained light palette. */
body:has(.sport-dashboard) {
  margin: 0;
  background: #f8fafc;
  background-image:
    radial-gradient(ellipse at 35% 5%, #e9f6ef 0, transparent 43%),
    radial-gradient(ellipse at 77% 18%, #fcf0e7 0, transparent 41%),
    radial-gradient(ellipse at 76% 58%, #faeef4 0, transparent 43%),
    radial-gradient(ellipse at 15% 78%, #edf5fc 0, transparent 46%),
    radial-gradient(ellipse at 95% 85%, #f1eefb 0, transparent 48%);
  background-attachment: scroll;
  color-scheme: light;
}
body:has(.sport-dashboard) .main { max-width: 1392px; padding: 0 24px; }
body:has(.sport-dashboard) :is(.post-header, .post-footer, .breadcrumbs, .toc) { display: none; }
body:has(.sport-dashboard) .post-content { margin: 0; }
.sport-dashboard {
  --ink: #252932;
  --muted: #747b84;
  --line: #58657718;
  box-sizing: border-box; width: 100%; max-width: 1376px; margin: 0 auto; padding: 38px 28px 24px;
  font: 14px/1.6 -apple-system, BlinkMacSystemFont, "Segoe UI", "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", sans-serif;
  color: var(--ink); -webkit-font-smoothing: antialiased; text-align: left;
}
.sport-dashboard *, .sport-dashboard *::before, .sport-dashboard *::after { box-sizing: border-box; }
.sport-dashboard :is(h1, h2, h3, p, ul, li, figure, table) { margin: 0; padding: 0; color: inherit; }
.sport-dashboard :is(h1, h2, h3) { line-height: 1.35; border: 0; }
.sport-dashboard .icon { display: inline-block; flex: 0 0 auto; width: 20px; height: 20px; margin: 0; vertical-align: middle; }
.sport-dashboard .dashboard-header { display: flex; align-items: center; justify-content: space-between; gap: 24px; margin-bottom: 31px; }
.sport-dashboard .greeting > p:first-of-type { margin-bottom: 4px; font-size: 20px; font-weight: 300; color: #626771; }
.sport-dashboard .greeting h1 { font-size: clamp(27px, 3vw, 39px); font-weight: 650; letter-spacing: -1.5px; }
.sport-dashboard .greeting h1 > span { color: #6da48b; }
.sport-dashboard .greeting .header-description { margin-top: 11px; color: var(--muted); font-size: 13px; letter-spacing: .5px; }
.sport-dashboard .header-meta { display: flex; flex-direction: column; align-items: flex-end; gap: 13px; padding-top: 32px; }
.sport-dashboard .today-label { color: #606771; font-size: 12px; }
.sport-dashboard .period-pill { display: flex; align-items: center; gap: 13px; padding: 11px 18px; border: 1px solid #ffffffb8; border-radius: 16px; background: #ffffff52; color: #535e65; font-size: 13px; font-variant-numeric: tabular-nums; }
.sport-dashboard .period-pill > .icon { color: #7b8e83; width: 21px; height: 21px; }
.sport-dashboard .period-pill small { display: block; color: var(--muted); font-size: 10px; margin-top: 1px; }
.sport-dashboard .sync-status { display: flex; align-items: center; gap: 6px; color: #77817b; font-size: 10px; }
.sport-dashboard .sync-status i { width: 5px; height: 5px; border-radius: 50%; background: #7caf91; box-shadow: 0 0 0 3px #7caf9112; }
.sport-dashboard .dashboard-grid { display: grid; grid-template-columns: minmax(300px, .93fr) minmax(0, 1.55fr); gap: 20px; align-items: start; }
.sport-dashboard :is(.glass, .metric) {
  position: relative;
  isolation: isolate;
  border: 1px solid #ffffffd9;
  border-radius: 25px;
  background: linear-gradient(135deg, #ffffffb8, #ffffff61);
  box-shadow: inset 0 1px 0 #fffffff0, inset 0 -1px 0 #ffffff70, 0 12px 32px -18px #51607928, 0 2px 6px -3px #6572870d;
  backdrop-filter: blur(32px) saturate(135%);
  -webkit-backdrop-filter: blur(32px) saturate(135%);
}
.sport-dashboard :is(.glass, .metric)::before {
  content: "";
  position: absolute;
  inset: 0;
  z-index: -1;
  border-radius: inherit;
  pointer-events: none;
  opacity: .045;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='180' height='180'%3E%3Cfilter id='grain'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.8' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' opacity='.7' filter='url(%23grain)'/%3E%3C/svg%3E");
}
.sport-dashboard .glass { padding: 24px; }
.sport-dashboard .panel-heading { display: flex; align-items: center; justify-content: space-between; gap: 10px; }
.sport-dashboard .panel-heading > .icon { color: #7b8582; width: 19px; height: 19px; }
.sport-dashboard .eyebrow { display: block; margin-bottom: 6px; font-size: 8px; font-weight: 500; color: #7c8883; letter-spacing: 1.6px; }
.sport-dashboard h2 { font-size: 18px; font-weight: 600; letter-spacing: -.3px; }
.sport-dashboard .plan-panel { min-height: 100%; background: linear-gradient(145deg, #ffffffa3, #f1f7ff69); }
.sport-dashboard .plan-count { font-size: 27px; font-weight: 300; color: #6c8b7b; line-height: 1; }
.sport-dashboard .plan-count small { display: block; font-size: 7px; letter-spacing: 1.8px; margin-top: 5px; }
.sport-dashboard .plan-period { margin: 12px 0 15px; color: #717d77; font-size: 11px; font-variant-numeric: tabular-nums; }
.sport-dashboard .plan-period > span { color: #8a928e; margin-left: 7px; font-size: 10px; }
.sport-dashboard .session { border: 0; border-bottom: 1px solid #697d7310; border-radius: 0; background: transparent; }
.sport-dashboard .session:last-child { border-bottom: 0; }
.sport-dashboard .session > summary, .sport-dashboard .unscheduled { display: flex; align-items: center; gap: 12px; min-height: 60px; padding: 9px 1px; list-style: none; }
.sport-dashboard summary { cursor: pointer; -webkit-tap-highlight-color: transparent; }
.sport-dashboard summary::-webkit-details-marker { display: none; }
.sport-dashboard :is(.session, .metric) > summary::marker { content: ""; }
.sport-dashboard .session-date { display: flex; flex: 0 0 39px; flex-direction: column; color: #8a9291; font-size: 9px; line-height: 1.7; }
.sport-dashboard .session-date strong { color: #5c6665; font-size: 12px; font-weight: 500; font-variant-numeric: tabular-nums; }
.sport-dashboard :is(.session-symbol, .activity-symbol, .insight-symbol) { display: grid; flex: 0 0 34px; width: 34px; height: 34px; place-items: center; border-radius: 12px; background: #e9eaf3a8; color: #8b91a3; }
.sport-dashboard .session-symbol .icon { width: 17px; height: 17px; }
.sport-dashboard .tennis .session-symbol, .sport-dashboard .activity-symbol.tennis { background: #e7eed6b5; color: #83945d; }
.sport-dashboard :is(.run, .walk) .session-symbol, .sport-dashboard .activity-symbol:is(.run, .walk) { background: #d9efe3a3; color: #69a386; }
.sport-dashboard .strength .session-symbol, .sport-dashboard .activity-symbol.strength { background: #e6e2f6b5; color: #9586bd; }
.sport-dashboard .session-copy { flex: 1; min-width: 0; }
.sport-dashboard .session-copy strong { display: block; font-size: 12px; font-weight: 550; overflow-wrap: anywhere; }
.sport-dashboard .session-copy small { display: block; margin-top: 2px; color: #858d90; font-size: 10px; }
.sport-dashboard .session-chevron { color: #a0aaa5; width: 12px; height: 12px; transition: transform .18s; }
.sport-dashboard .session[open] .session-chevron { transform: rotate(90deg); }
.sport-dashboard .is-today { position: relative; }
.sport-dashboard .is-today::before { position: absolute; content: ""; width: 3px; height: 24px; top: 18px; left: -13px; border-radius: 3px; background: #8db59b; }
.sport-dashboard .is-today .session-date span { color: #50886c; font-weight: 600; }
.sport-dashboard .session-body { padding: 0 6px 14px 52px; font-size: 11px; color: #69756e; line-height: 1.9; }
.sport-dashboard .session-body small { display: block; margin-top: 7px; font-size: 9px; color: #8b948e; }
.sport-dashboard .unscheduled { opacity: .65; }
.sport-dashboard .sleep-target { display: flex; align-items: center; gap: 11px; margin-top: 17px; padding: 14px; border: 1px solid #ffffffb5; border-radius: 14px; background: #ffffff4d; color: #8881ad; }
.sport-dashboard .sleep-target strong { display: block; color: #6d7182; font-size: 10px; font-weight: 500; }
.sport-dashboard .sleep-target small { display: block; margin-top: 3px; color: #8a8a98; font-size: 10px; }
.sport-dashboard .panel-note { margin-top: 17px; color: #8c939b; font-size: 10px; line-height: 1.8; }
.sport-dashboard .metrics-grid { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 19px; align-items: start; }
.sport-dashboard .metric { overflow: hidden; min-width: 0; color: var(--ink); }
.sport-dashboard .mint { --chart-color: #6da58a; background: linear-gradient(145deg, #ffffffad, #e2f1df66); }
.sport-dashboard .peach { --chart-color: #c49872; background: linear-gradient(145deg, #ffffffad, #ffe8d866); }
.sport-dashboard .lavender { --chart-color: #9696b0; background: linear-gradient(145deg, #ffffffb8, #efedff66); }
.sport-dashboard .lilac { --chart-color: #a096db; background: linear-gradient(145deg, #ffffffb8, #f0e8f566); }
.sport-dashboard .rose { --chart-color: #d887a2; background: linear-gradient(145deg, #ffffffb8, #ffe4ef66); }
.sport-dashboard .ice { --chart-color: #9b9cac; background: linear-gradient(145deg, #ffffffb8, #eeedf766); }
.sport-dashboard .metric > summary { display: flex; flex-direction: column; min-height: 330px; padding: 20px 19px 17px; list-style: none; }
.sport-dashboard .metric-heading { display: flex; align-items: center; justify-content: space-between; gap: 4px; margin-bottom: 17px; font-size: 12px; font-weight: 550; }
.sport-dashboard .metric-heading > span { display: flex; align-items: center; gap: 6px; }
.sport-dashboard .metric-heading > span .icon { width: 14px; height: 14px; color: #707b789c; }
.sport-dashboard .metric-arrow { width: 13px; height: 13px; color: #7e8586; transition: transform .18s; }
.sport-dashboard .metric[open] .metric-arrow { transform: rotate(90deg); }
.sport-dashboard .metric-value { display: block; font-size: clamp(36px, 4.2vw, 49px); font-weight: 550; letter-spacing: -2px; font-variant-numeric: tabular-nums; line-height: 1.15; color: #23252d; }
.sport-dashboard .metric-value.compact { font-size: clamp(29px, 3.5vw, 42px); }
.sport-dashboard .metric-description { display: block; margin-top: 5px; color: #8a8a91; font-size: 10px; }
.sport-dashboard .metric-visual { display: flex; align-items: flex-end; justify-content: center; flex: 1; min-height: 108px; padding-top: 15px; }
.sport-dashboard :is(.trend-chart, .stress-gauge) { display: block; width: 100%; height: auto; max-height: 100px; overflow: visible; color: var(--chart-color); }
.sport-dashboard :is(.trend-chart, .stress-gauge) text { font: 9px -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; fill: #9697a1; stroke: none; }
.sport-dashboard .chart-guide { stroke: #88919a15; stroke-width: 1; fill: none; }
.sport-dashboard .chart-line { fill: none; stroke: currentColor; stroke-width: 2; stroke-linecap: round; stroke-linejoin: round; }
.sport-dashboard .chart-dot { fill: currentColor; stroke: #ffffffc4; stroke-width: 1.5; }
.sport-dashboard .chart-bar { fill: currentColor; opacity: .55; }
.sport-dashboard .chart-bar:nth-last-of-type(1) { opacity: .9; }
.sport-dashboard .chart-missing { stroke: #a6a7b263; stroke-width: 2; stroke-dasharray: 2 2; }
.sport-dashboard .metric-footer { display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 4px; margin-top: 10px; color: #777a80; font-size: 9px; }
.sport-dashboard .metric-footer > small { color: #96939c; font-size: 9px; white-space: nowrap; }
.sport-dashboard .chart-empty { display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 4px; min-height: 94px; width: 100%; color: #b49c8b; font-size: 10px; }
.sport-dashboard .chart-empty > .icon { width: 23px; height: 23px; margin-bottom: 3px; opacity: .65; }
.sport-dashboard .chart-empty small { font-size: 8px; opacity: .8; }
.sport-dashboard :is(.gauge-track, .gauge-value) { fill: none; stroke: currentColor; stroke-width: 10; stroke-linecap: round; }
.sport-dashboard .gauge-track { opacity: .16; }
.sport-dashboard .gauge-dot { fill: #fff4f8; stroke: currentColor; stroke-width: 2; }
.sport-dashboard .metric-detail { padding: 4px 18px 16px; border-top: 1px solid #ffffff80; font-size: 10px; }
.sport-dashboard .metric-detail table { display: table; width: 100%; border-collapse: collapse; overflow: visible; font-size: 10px; }
.sport-dashboard .metric-detail caption { padding: 9px 0; text-align: left; color: #6b6c78; font-size: 9px; }
.sport-dashboard .metric-detail :is(th, td) { padding: 4px 0; border: 0; border-bottom: 1px solid #ffffff5c; font-size: 10px; font-weight: 400; background: transparent; text-align: left; }
.sport-dashboard .metric-detail td { text-align: right; font-variant-numeric: tabular-nums; }
.sport-dashboard .metric-detail p { margin-top: 8px; color: #8b8793; font-size: 8px; }
.sport-dashboard .activity-panel { background: linear-gradient(145deg, #ffffffad, #eff7ff75); min-height: 365px; }
.sport-dashboard .activity-totals { display: flex; align-items: baseline; gap: 25px; margin: 20px 0 14px; }
.sport-dashboard .activity-totals > strong { font-size: 25px; font-weight: 500; }
.sport-dashboard .activity-totals > span { font-size: 19px; color: #78848e; }
.sport-dashboard .activity-totals small { font-size: 10px; font-weight: 400; color: #939ca4; margin-left: 5px; }
.sport-dashboard .activity-chart { display: flex; gap: 10px; padding-bottom: 13px; border-bottom: 1px solid #788b9e15; }
.sport-dashboard .activity-day { flex: 1; min-width: 0; text-align: center; font-size: 8px; color: #929caa; }
.sport-dashboard .activity-track { display: flex; align-items: flex-end; height: 38px; margin-bottom: 6px; border-bottom: 2px solid #b2bbce29; }
.sport-dashboard .activity-fill { display: block; width: 100%; height: var(--bar-height); border-radius: 4px 4px 1px 1px; background: linear-gradient(0deg, #a6aee08c, #b4bdebba); }
.sport-dashboard .activity-records { display: grid; gap: 13px; margin-top: 17px; list-style: none; }
.sport-dashboard .activity-records li { display: flex; align-items: center; gap: 10px; list-style: none; }
.sport-dashboard .activity-symbol { flex-basis: 28px; width: 28px; height: 28px; border-radius: 10px; }
.sport-dashboard .activity-symbol .icon { width: 14px; height: 14px; }
.sport-dashboard .activity-records strong { display: block; font-size: 11px; font-weight: 500; }
.sport-dashboard .activity-records small { display: block; margin-top: 2px; color: #8f98a4; font-size: 9px; }
.sport-dashboard .record-label { margin-left: auto; color: #97a19a; font-size: 9px; white-space: nowrap; }
.sport-dashboard :is(.empty-record, .empty-insights) { padding: 20px 0; color: #858e98; font-size: 12px; }
.sport-dashboard .insights-panel { min-height: 365px; background: linear-gradient(145deg, #ffffffb3, #faf7ff75); }
.sport-dashboard .insight-list { display: grid; gap: 20px; margin-top: 27px; list-style: none; }
.sport-dashboard .insight-list li { display: flex; align-items: center; gap: 14px; list-style: none; }
.sport-dashboard .insight-symbol { flex-basis: 33px; width: 33px; height: 33px; border: 1px solid #ffffff5e; border-radius: 12px; color: var(--chart-color); }
.sport-dashboard .insight-symbol .icon { width: 16px; height: 16px; }
.sport-dashboard .insight-list strong { display: block; font-size: 12px; font-weight: 400; line-height: 1.5; }
.sport-dashboard .insight-list small { display: block; margin-top: 4px; color: #92929c; font-size: 10px; }
.sport-dashboard .dashboard-footer { display: flex; justify-content: space-between; flex-wrap: wrap; gap: 12px; padding: 24px 3px 4px; color: #939da2; font-size: 10px; }
.sport-dashboard .dashboard-footer > span:first-child { display: flex; align-items: center; gap: 7px; color: #85968b; }
.sport-dashboard .dashboard-footer .icon { width: 13px; height: 13px; }
.sport-dashboard summary:hover { background: #ffffff1a; }
.sport-dashboard summary:focus-visible, .sport-dashboard a:focus-visible { outline: 2px solid #63977d; outline-offset: -3px; border-radius: 12px; }
@media (min-width: 1400px) {
  .sport-dashboard { padding-top: 45px; }
  .sport-dashboard .dashboard-header { margin-bottom: 38px; }
}
@media (max-width: 1080px) {
  .sport-dashboard { padding: 28px 20px 20px; }
  .sport-dashboard .dashboard-grid { grid-template-columns: minmax(270px, .9fr) minmax(0, 1.55fr); gap: 15px; }
  .sport-dashboard .glass { padding: 19px; }
  .sport-dashboard .metrics-grid { gap: 13px; }
  .sport-dashboard .metric > summary { padding: 18px 13px 15px; min-height: 330px; }
  .sport-dashboard .metric-value.compact { font-size: 30px; }
  .sport-dashboard .metric-heading > span .icon { display: none; }
  .sport-dashboard .session > summary { gap: 9px; }
  .sport-dashboard .plan-period > span { display: block; margin: 3px 0 0; }
}
@media (max-width: 800px) {
  body:has(.sport-dashboard) .main { padding: 0 12px; }
  .sport-dashboard { padding: 26px 15px 18px; }
  .sport-dashboard .dashboard-grid { grid-template-columns: 1fr; gap: 18px; }
  .sport-dashboard .plan-panel { min-height: auto; }
  .sport-dashboard .metrics-grid { grid-row: 2; gap: 15px; }
  .sport-dashboard .metric > summary { min-height: 260px; padding: 20px 17px 16px; }
  .sport-dashboard .metric-value { font-size: 43px; }
  .sport-dashboard .metric-value.compact { font-size: 34px; }
  .sport-dashboard .sessions { display: grid; grid-template-columns: 1fr 1fr; column-gap: 25px; align-items: start; }
  .sport-dashboard .plan-period > span { display: inline; margin-left: 7px; }
  .sport-dashboard .glass { padding: 23px; }
  .sport-dashboard .sleep-target { margin-top: 12px; }
  .sport-dashboard :is(.activity-panel, .insights-panel) { min-height: 0; }
}
@media (max-width: 520px) {
  .sport-dashboard { padding: 25px 15px 15px; }
  .sport-dashboard .dashboard-header { display: block; margin-bottom: 21px; }
  .sport-dashboard .greeting > p:first-of-type { font-size: 17px; }
  .sport-dashboard .greeting h1 { font-size: 30px; letter-spacing: -1px; }
  .sport-dashboard .greeting .header-description { margin-top: 9px; font-size: 12px; }
  .sport-dashboard .header-meta { display: grid; grid-template-columns: 1fr auto; justify-items: start; align-items: center; padding-top: 20px; gap: 11px; }
  .sport-dashboard .today-label { grid-column: 1 / -1; font-size: 10px; }
  .sport-dashboard .period-pill { padding: 9px 12px; gap: 8px; border-radius: 12px; font-size: 11px; }
  .sport-dashboard .period-pill > .icon { width: 17px; height: 17px; }
  .sport-dashboard .period-pill small { font-size: 8px; }
  .sport-dashboard .sync-status { font-size: 9px; }
  .sport-dashboard .metrics-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 12px; }
  .sport-dashboard :is(.metric, .glass) { border-radius: 21px; }
  .sport-dashboard .metric > summary { min-height: 258px; padding: 18px 15px 15px; }
  .sport-dashboard .metric-heading { margin-bottom: 14px; }
  .sport-dashboard .metric-description { font-size: 9px; }
  .sport-dashboard .metric-footer, .sport-dashboard .metric-footer > small { font-size: 8px; }
  .sport-dashboard .metric-value { font-size: 43px; }
  .sport-dashboard .metric-value.compact { font-size: 34px; }
  .sport-dashboard .metric-visual { min-height: 93px; }
  .sport-dashboard .sessions { display: block; }
  .sport-dashboard .glass { padding: 22px; }
  .sport-dashboard .session > summary { min-height: 62px; gap: 13px; }
  .sport-dashboard .session-copy strong { font-size: 13px; }
  .sport-dashboard .plan-period { margin-top: 13px; }
  .sport-dashboard .sleep-target { padding: 12px; }
  .sport-dashboard .insight-list { gap: 21px; }
  .sport-dashboard .insight-list strong { font-size: 11px; }
  .sport-dashboard .insight-list small { font-size: 9px; }
  .sport-dashboard .dashboard-footer { font-size: 9px; padding-top: 20px; }
}
@media (max-width: 360px) {
  .sport-dashboard { padding-right: 11px; padding-left: 11px; }
  .sport-dashboard .metric > summary { padding-right: 11px; padding-left: 11px; }
  .sport-dashboard .metric-value.compact { font-size: 29px; }
  .sport-dashboard .session > summary { gap: 9px; }
  .sport-dashboard .plan-period > span { display: block; margin-left: 0; }
}
@media (prefers-reduced-motion: reduce) {
  .sport-dashboard * { transition: none !important; }
}
</style>
<div class="sport-dashboard" role="region" aria-label="个人健康周报">
  <header class="dashboard-header">
    <div class="greeting"><p>你好，</p><h1>保持自己的节奏<span>。</span></h1><p class="header-description">这里是你最近一周的健康概况</p></div>
    <div class="header-meta"><span class="today-label">2026 年 10 月 26 日 · 周一</span><span class="period-pill"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="4" y="5" width="16" height="16" rx="4"/><path d="M8 3v4m8-4v4M4 11h16m-11 4h.01m6 0h.01"/></svg><span>2026.10.19 — 10.25<small>最近 7 个完整日 · 上海时间</small></span></span><span class="sync-status"><i></i>本周数据已同步</span></div>
  </header>
  <div class="dashboard-grid">
    <section class="plan-panel glass" id="plan" aria-labelledby="plan-title">
      <div class="panel-heading"><div><span class="eyebrow">A LITTLE EVERY DAY</span><h2 id="plan-title">接下来 7 天</h2></div><span class="plan-count">7 <small>DAYS</small></span></div>
      <p class="plan-period">10.26 — 11.01 <span>· 点击查看训练内容</span></p>
      <div class="sessions"><details class="session run is-today"><summary><span class="session-date"><span>今天</span><strong>10.26</strong></span><span class="session-symbol"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="15" cy="4" r="1.5"/><path d="m10 10 3-4 3 5 4 1M4 10l5 1 4 5-3 6M13 12l-5 5H3"/></svg></span><span class="session-copy"><strong>连续轻松跑</strong><small>户外 · RPE 3-4</small></span><svg class="icon session-chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m9 5 7 7-7 7"/></svg></summary><div class="session-body"><p>热身5分钟＋跑15分钟＋放松5分钟</p><small>七日计划 · 计划</small></div></details><details class="session strength"><summary><span class="session-date"><span>周二</span><strong>10.27</strong></span><span class="session-symbol"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m6 6 12 12M4 9l5-5M15 20l5-5M2 7l5-5M17 22l5-5"/></svg></span><span class="session-copy"><strong>上肢与核心</strong><small>健身房 · RPE 4-5</small></span><svg class="icon session-chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m9 5 7 7-7 7"/></svg></summary><div class="session-body"><p>热身8分钟；哑铃卧推、高位下拉各2×10-12，单臂哑铃划船每侧2×10-12；平板支撑2×20-30秒；放松5分钟。共35-45分钟</p><small>七日计划 · 计划</small></div></details><details class="session strength"><summary><span class="session-date"><span>周三</span><strong>10.28</strong></span><span class="session-symbol"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m6 6 12 12M4 9l5-5M15 20l5-5M2 7l5-5M17 22l5-5"/></svg></span><span class="session-copy"><strong>上背与核心B</strong><small>健身房 · RPE 4-5</small></span><svg class="icon session-chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m9 5 7 7-7 7"/></svg></summary><div class="session-body"><p>肩部环绕、肩胛活动及各主动作轻重量热身共8分钟；宽握高位下拉2×10-12、单臂支撑哑铃划船每侧2×10-12、轻哑铃肩上推举2×8-10、俯卧W抬臂2×8；仰卧交替伸手伸腿（死虫式）每侧2×6-8；肩胸舒展5分钟，共40-50分钟；肩肘疲劳时取消推举</p><small>月度安排 · 计划</small></div></details><details class="session run"><summary><span class="session-date"><span>周四</span><strong>10.29</strong></span><span class="session-symbol"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="15" cy="4" r="1.5"/><path d="m10 10 3-4 3 5 4 1M4 10l5 1 4 5-3 6M13 12l-5 5H3"/></svg></span><span class="session-copy"><strong>连续轻松跑</strong><small>户外平坦路线 · RPE 3-4</small></span><svg class="icon session-chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m9 5 7 7-7 7"/></svg></summary><div class="session-body"><p>热身5分钟＋连续轻松跑20分钟＋放松5分钟，共30分钟；全程能说完整句子</p><small>月度安排 · 计划</small></div></details><details class="session rest"><summary><span class="session-date"><span>周五</span><strong>10.30</strong></span><span class="session-symbol"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M20 15.5A8.5 8.5 0 0 1 8.5 4a8.5 8.5 0 1 0 11.5 11.5Z"/></svg></span><span class="session-copy"><strong>周五晚休息</strong><small>不限</small></span><svg class="icon session-chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m9 5 7 7-7 7"/></svg></summary><div class="session-body"><p>晚上不安排运动；白天只保留日常活动</p><small>月度安排 · 休息</small></div></details><details class="session tennis"><summary><span class="session-date"><span>周六</span><strong>10.31</strong></span><span class="session-symbol"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="8.5"/><path d="M5 6c6 1 6 11 14 12M5 18c7-1 6-11 14-12"/></svg></span><span class="session-copy"><strong>固定网球</strong><small>球场 · RPE 4-6</small></span><svg class="icon session-chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m9 5 7 7-7 7"/></svg></summary><div class="session-body"><p>10:00—11:00：热身10分钟、对打/技术练习40分钟、放松10分钟；不另加跑步</p><small>月度安排 · 计划</small></div></details><details class="session rest"><summary><span class="session-date"><span>周日</span><strong>11.01</strong></span><span class="session-symbol"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M20 15.5A8.5 8.5 0 0 1 8.5 4a8.5 8.5 0 1 0 11.5 11.5Z"/></svg></span><span class="session-copy"><strong>周日恢复</strong><small>户外 · RPE 2</small></span><svg class="icon session-chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m9 5 7 7-7 7"/></svg></summary><div class="session-body"><p>轻松散步20-30分钟，可加肩胸髋舒展5-10分钟；也可完全休息；健身房周日不开门</p><small>月度安排 · 休息</small></div></details></div>
      <div class="sleep-target"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M20 15.5A8.5 8.5 0 0 1 8.5 4a8.5 8.5 0 1 0 11.5 11.5Z"/></svg><span><strong>本阶段作息目标</strong><small>7:30 起床 · 23:15—23:30 关灯</small></span></div>
      <p class="panel-note">以已制定的计划为准，随恢复状态调整。</p>
    </section>
    <section class="metrics-grid" aria-label="最近七日健康指标"><details class="metric mint" id="metric-battery_high"><summary><span class="metric-heading"><span><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="6" width="17" height="12" rx="3"/><path d="M23 10v4M7 10v4m4-4v4m4-4v4"/></svg>身体电量</span><svg class="icon metric-arrow" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M7 17 17 7M7 7h10v10"/></svg></span><span class="metric-value">76</span><span class="metric-description">/ 100 · 每日最高值的周均值</span><span class="metric-visual"><svg class="trend-chart" viewBox="0 0 204 96" role="img" aria-label="身体电量七日趋势；横轴为日期，缺失数据留空"><title>身体电量 · 最近七日，点击卡片查看每日数值</title><path class="chart-guide" d="M3 70h198M3 38h198"/><polyline class="chart-line" points="12,35.21 42,36.84 72,22.71 102,28.69 132,28.69 162,30.32 192,61.29"/><circle class="chart-dot" cx="12" cy="35.21" r="3"><title>2026-10-19 · 身体电量 75.0 / 100</title></circle><text x="12" y="91" text-anchor="middle">19</text><circle class="chart-dot" cx="42" cy="36.84" r="3"><title>2026-10-20 · 身体电量 72.0 / 100</title></circle><text x="42" y="91" text-anchor="middle">20</text><circle class="chart-dot" cx="72" cy="22.71" r="3"><title>2026-10-21 · 身体电量 98.0 / 100</title></circle><text x="72" y="91" text-anchor="middle">21</text><circle class="chart-dot" cx="102" cy="28.69" r="3"><title>2026-10-22 · 身体电量 87.0 / 100</title></circle><text x="102" y="91" text-anchor="middle">22</text><circle class="chart-dot" cx="132" cy="28.69" r="3"><title>2026-10-23 · 身体电量 87.0 / 100</title></circle><text x="132" y="91" text-anchor="middle">23</text><circle class="chart-dot" cx="162" cy="30.32" r="3"><title>2026-10-24 · 身体电量 84.0 / 100</title></circle><text x="162" y="91" text-anchor="middle">24</text><circle class="chart-dot" cx="192" cy="61.29" r="3"><title>2026-10-25 · 身体电量 27.0 / 100</title></circle><text x="192" y="91" text-anchor="middle">25</text></svg></span><span class="metric-footer"><span>最低值均值 20</span><small>7/7 天</small></span></summary><div class="metric-detail"><table><caption>身体电量 · 每日记录（/ 100）</caption><thead><tr><th scope="col">日期</th><th scope="col">数值</th></tr></thead><tbody><tr><th scope="row">10-19</th><td>75 / 100</td></tr><tr><th scope="row">10-20</th><td>72 / 100</td></tr><tr><th scope="row">10-21</th><td>98 / 100</td></tr><tr><th scope="row">10-22</th><td>87 / 100</td></tr><tr><th scope="row">10-23</th><td>87 / 100</td></tr><tr><th scope="row">10-24</th><td>84 / 100</td></tr><tr><th scope="row">10-25</th><td>27 / 100</td></tr></tbody></table><p>仅统计有记录的日期；— 表示缺失。</p></div></details><details class="metric peach" id="metric-respiration"><summary><span class="metric-heading"><span><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 8h11a3 3 0 1 0-3-3M3 12h15a3 3 0 1 1-3 3M3 16h5a2 2 0 1 1-2 2"/></svg>呼吸</span><svg class="icon metric-arrow" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M7 17 17 7M7 7h10v10"/></svg></span><span class="metric-value">17.0</span><span class="metric-description">次/分 · 清醒呼吸均值的周均值</span><span class="metric-visual"><svg class="trend-chart" viewBox="0 0 204 96" role="img" aria-label="呼吸七日趋势；横轴为日期，缺失数据留空"><title>呼吸 · 最近七日，点击卡片查看每日数值</title><path class="chart-guide" d="M3 70h198M3 38h198"/><polyline class="chart-line" points="12,51.64 42,61.29 72,51.64 102,61.29 132,61.29 162,51.64 192,22.71"/><circle class="chart-dot" cx="12" cy="51.64" r="3"><title>2026-10-19 · 呼吸 17.0 次/分</title></circle><text x="12" y="91" text-anchor="middle">19</text><circle class="chart-dot" cx="42" cy="61.29" r="3"><title>2026-10-20 · 呼吸 16.0 次/分</title></circle><text x="42" y="91" text-anchor="middle">20</text><circle class="chart-dot" cx="72" cy="51.64" r="3"><title>2026-10-21 · 呼吸 17.0 次/分</title></circle><text x="72" y="91" text-anchor="middle">21</text><circle class="chart-dot" cx="102" cy="61.29" r="3"><title>2026-10-22 · 呼吸 16.0 次/分</title></circle><text x="102" y="91" text-anchor="middle">22</text><circle class="chart-dot" cx="132" cy="61.29" r="3"><title>2026-10-23 · 呼吸 16.0 次/分</title></circle><text x="132" y="91" text-anchor="middle">23</text><circle class="chart-dot" cx="162" cy="51.64" r="3"><title>2026-10-24 · 呼吸 17.0 次/分</title></circle><text x="162" y="91" text-anchor="middle">24</text><circle class="chart-dot" cx="192" cy="22.71" r="3"><title>2026-10-25 · 呼吸 20.0 次/分</title></circle><text x="192" y="91" text-anchor="middle">25</text></svg></span><span class="metric-footer"><span>睡眠均值 18.4 次/分</span><small>7/7 天</small></span></summary><div class="metric-detail"><table><caption>呼吸 · 每日记录（次/分）</caption><thead><tr><th scope="col">日期</th><th scope="col">数值</th></tr></thead><tbody><tr><th scope="row">10-19</th><td>17.0 次/分</td></tr><tr><th scope="row">10-20</th><td>16.0 次/分</td></tr><tr><th scope="row">10-21</th><td>17.0 次/分</td></tr><tr><th scope="row">10-22</th><td>16.0 次/分</td></tr><tr><th scope="row">10-23</th><td>16.0 次/分</td></tr><tr><th scope="row">10-24</th><td>17.0 次/分</td></tr><tr><th scope="row">10-25</th><td>20.0 次/分</td></tr></tbody></table><p>仅统计有记录的日期；— 表示缺失。</p></div></details><details class="metric lavender" id="metric-hrv"><summary><span class="metric-heading"><span><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M2 12h5l3-8 4 16 3-8h5"/></svg>HRV</span><svg class="icon metric-arrow" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M7 17 17 7M7 7h10v10"/></svg></span><span class="metric-value">49</span><span class="metric-description">ms · 夜间均值的周均值</span><span class="metric-visual"><svg class="trend-chart" viewBox="0 0 204 96" role="img" aria-label="HRV七日趋势；横轴为日期，缺失数据留空"><title>HRV · 最近七日，点击卡片查看每日数值</title><path class="chart-guide" d="M3 70h198M3 38h198"/><rect class="chart-bar" x="3" y="23.15" width="18" height="46.85" rx="4"><title>2026-10-19 · HRV 45.0 ms</title></rect><text x="12" y="91" text-anchor="middle">19</text><rect class="chart-bar" x="33" y="20.09" width="18" height="49.91" rx="4"><title>2026-10-20 · HRV 48.0 ms</title></rect><text x="42" y="91" text-anchor="middle">20</text><rect class="chart-bar" x="63" y="16.02" width="18" height="53.98" rx="4"><title>2026-10-21 · HRV 52.0 ms</title></rect><text x="72" y="91" text-anchor="middle">21</text><rect class="chart-bar" x="93" y="15.00" width="18" height="55.00" rx="4"><title>2026-10-22 · HRV 53.0 ms</title></rect><text x="102" y="91" text-anchor="middle">22</text><rect class="chart-bar" x="123" y="20.09" width="18" height="49.91" rx="4"><title>2026-10-23 · HRV 48.0 ms</title></rect><text x="132" y="91" text-anchor="middle">23</text><path class="chart-missing" d="M158 69h8"><title>2026-10-24 · 暂无记录</title></path><text x="162" y="91" text-anchor="middle">24</text><path class="chart-missing" d="M188 69h8"><title>2026-10-25 · 暂无记录</title></path><text x="192" y="91" text-anchor="middle">25</text></svg></span><span class="metric-footer"><span>平衡 5 天</span><small>5/7 天</small></span></summary><div class="metric-detail"><table><caption>HRV · 每日记录（ms）</caption><thead><tr><th scope="col">日期</th><th scope="col">数值</th></tr></thead><tbody><tr><th scope="row">10-19</th><td>45 ms</td></tr><tr><th scope="row">10-20</th><td>48 ms</td></tr><tr><th scope="row">10-21</th><td>52 ms</td></tr><tr><th scope="row">10-22</th><td>53 ms</td></tr><tr><th scope="row">10-23</th><td>48 ms</td></tr><tr><th scope="row">10-24</th><td>— ms</td></tr><tr><th scope="row">10-25</th><td>— ms</td></tr></tbody></table><p>仅统计有记录的日期；— 表示缺失。</p></div></details><details class="metric lilac" id="metric-sleep_hours"><summary><span class="metric-heading"><span><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M20 15.5A8.5 8.5 0 0 1 8.5 4a8.5 8.5 0 1 0 11.5 11.5Z"/></svg>睡眠</span><svg class="icon metric-arrow" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M7 17 17 7M7 7h10v10"/></svg></span><span class="metric-value">6.4</span><span class="metric-description">小时 · 每晚平均睡眠</span><span class="metric-visual"><svg class="trend-chart" viewBox="0 0 204 96" role="img" aria-label="睡眠七日趋势；横轴为日期，缺失数据留空"><title>睡眠 · 最近七日，点击卡片查看每日数值</title><path class="chart-guide" d="M3 70h198M3 38h198"/><rect class="chart-bar" x="3" y="38.59" width="18" height="31.41" rx="4"><title>2026-10-19 · 睡眠 4.3 小时</title></rect><text x="12" y="91" text-anchor="middle">19</text><rect class="chart-bar" x="33" y="22.10" width="18" height="47.90" rx="4"><title>2026-10-20 · 睡眠 6.7 小时</title></rect><text x="42" y="91" text-anchor="middle">20</text><rect class="chart-bar" x="63" y="15.00" width="18" height="55.00" rx="4"><title>2026-10-21 · 睡眠 7.7 小时</title></rect><text x="72" y="91" text-anchor="middle">21</text><rect class="chart-bar" x="93" y="19.43" width="18" height="50.57" rx="4"><title>2026-10-22 · 睡眠 7.1 小时</title></rect><text x="102" y="91" text-anchor="middle">22</text><rect class="chart-bar" x="123" y="26.43" width="18" height="43.57" rx="4"><title>2026-10-23 · 睡眠 6.1 小时</title></rect><text x="132" y="91" text-anchor="middle">23</text><path class="chart-missing" d="M158 69h8"><title>2026-10-24 · 暂无记录</title></path><text x="162" y="91" text-anchor="middle">24</text><path class="chart-missing" d="M188 69h8"><title>2026-10-25 · 暂无记录</title></path><text x="192" y="91" text-anchor="middle">25</text></svg></span><span class="metric-footer"><span>平均评分 74</span><small>5/7 天</small></span></summary><div class="metric-detail"><table><caption>睡眠 · 每日记录（小时）</caption><thead><tr><th scope="col">日期</th><th scope="col">数值</th></tr></thead><tbody><tr><th scope="row">10-19</th><td>4.3 小时</td></tr><tr><th scope="row">10-20</th><td>6.7 小时</td></tr><tr><th scope="row">10-21</th><td>7.7 小时</td></tr><tr><th scope="row">10-22</th><td>7.1 小时</td></tr><tr><th scope="row">10-23</th><td>6.1 小时</td></tr><tr><th scope="row">10-24</th><td>— 小时</td></tr><tr><th scope="row">10-25</th><td>— 小时</td></tr></tbody></table><p>仅统计有记录的日期；— 表示缺失。</p></div></details><details class="metric rose" id="metric-stress"><summary><span class="metric-heading"><span><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M4 18a8 8 0 1 1 16 0M12 15l4-6"/><circle cx="12" cy="16" r="1"/></svg>压力</span><svg class="icon metric-arrow" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M7 17 17 7M7 7h10v10"/></svg></span><span class="metric-value">32</span><span class="metric-description">/ 100 · 每日平均压力的周均值</span><span class="metric-visual"><svg class="stress-gauge" viewBox="0 0 204 100" role="img" aria-label="周平均压力 32，量表 0 至 100"><path class="gauge-track" d="M34 78a68 68 0 0 1 136 0" pathLength="100"/><path class="gauge-value" d="M34 78a68 68 0 0 1 136 0" pathLength="100" stroke-dasharray="32.43 100"/><circle class="gauge-dot" cx="66.34" cy="20.10" r="5"/><text x="24" y="98">0</text><text x="160" y="98">100</text></svg></span><span class="metric-footer"><span>静息心率均值 55 bpm</span><small>7/7 天</small></span></summary><div class="metric-detail"><table><caption>压力 · 每日记录（/ 100）</caption><thead><tr><th scope="col">日期</th><th scope="col">数值</th></tr></thead><tbody><tr><th scope="row">10-19</th><td>43 / 100</td></tr><tr><th scope="row">10-20</th><td>27 / 100</td></tr><tr><th scope="row">10-21</th><td>25 / 100</td></tr><tr><th scope="row">10-22</th><td>27 / 100</td></tr><tr><th scope="row">10-23</th><td>23 / 100</td></tr><tr><th scope="row">10-24</th><td>60 / 100</td></tr><tr><th scope="row">10-25</th><td>22 / 100</td></tr></tbody></table><p>仅统计有记录的日期；— 表示缺失。</p></div></details><details class="metric ice" id="metric-steps"><summary><span class="metric-heading"><span><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M8 3c3 0 4 5 3 8s-5 3-6 0S5 3 8 3Zm8 8c3 0 4 5 3 8s-5 3-6 0 0-8 3-8Z"/></svg>活动</span><svg class="icon metric-arrow" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M7 17 17 7M7 7h10v10"/></svg></span><span class="metric-value compact">71,301</span><span class="metric-description">步 · 本周累计步数</span><span class="metric-visual"><svg class="trend-chart" viewBox="0 0 204 96" role="img" aria-label="活动七日趋势；横轴为日期，缺失数据留空"><title>活动 · 最近七日，点击卡片查看每日数值</title><path class="chart-guide" d="M3 70h198M3 38h198"/><rect class="chart-bar" x="3" y="15.00" width="18" height="55.00" rx="4"><title>2026-10-19 · 活动 18,194.0 步</title></rect><text x="12" y="91" text-anchor="middle">19</text><rect class="chart-bar" x="33" y="49.94" width="18" height="20.06" rx="4"><title>2026-10-20 · 活动 6,423.0 步</title></rect><text x="42" y="91" text-anchor="middle">20</text><rect class="chart-bar" x="63" y="32.72" width="18" height="37.28" rx="4"><title>2026-10-21 · 活动 12,224.0 步</title></rect><text x="72" y="91" text-anchor="middle">21</text><rect class="chart-bar" x="93" y="36.62" width="18" height="33.38" rx="4"><title>2026-10-22 · 活动 10,911.0 步</title></rect><text x="102" y="91" text-anchor="middle">22</text><rect class="chart-bar" x="123" y="44.00" width="18" height="26.00" rx="4"><title>2026-10-23 · 活动 8,424.0 步</title></rect><text x="132" y="91" text-anchor="middle">23</text><rect class="chart-bar" x="153" y="24.24" width="18" height="45.76" rx="4"><title>2026-10-24 · 活动 15,081.0 步</title></rect><text x="162" y="91" text-anchor="middle">24</text><rect class="chart-bar" x="183" y="68.87" width="18" height="1.13" rx="4"><title>2026-10-25 · 活动 44.0 步</title></rect><text x="192" y="91" text-anchor="middle">25</text></svg></span><span class="metric-footer"><span>日均 10,186 步</span><small>7/7 天</small></span></summary><div class="metric-detail"><table><caption>活动 · 每日记录（步）</caption><thead><tr><th scope="col">日期</th><th scope="col">数值</th></tr></thead><tbody><tr><th scope="row">10-19</th><td>18,194 步</td></tr><tr><th scope="row">10-20</th><td>6,423 步</td></tr><tr><th scope="row">10-21</th><td>12,224 步</td></tr><tr><th scope="row">10-22</th><td>10,911 步</td></tr><tr><th scope="row">10-23</th><td>8,424 步</td></tr><tr><th scope="row">10-24</th><td>15,081 步</td></tr><tr><th scope="row">10-25</th><td>44 步</td></tr></tbody></table><p>仅统计有记录的日期；— 表示缺失。</p></div></details></section>
    <section class="activity-panel glass" aria-label="最近七日运动记录"><div class="panel-heading"><div><span class="eyebrow">YOUR WEEK IN MOTION</span><h2>这一周的活动</h2></div><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m4 16 6-6 4 4 6-9m-6 0h6v6"/></svg></div><div class="activity-totals"><strong>3<small>次运动</small></strong><span>3.9<small>小时记录时长</small></span></div><div class="activity-chart" role="group" aria-label="最近七日运动记录时长"><div class="activity-day" title="2026-10-19 · 129 分钟运动记录"><span class="activity-track"><span class="activity-fill" style="--bar-height:100.00%"></span></span><span>10.19</span></div><div class="activity-day" title="2026-10-20 · 0 分钟运动记录"><span class="activity-track"><span class="activity-fill" style="--bar-height:0.00%"></span></span><span>10.20</span></div><div class="activity-day" title="2026-10-21 · 61 分钟运动记录"><span class="activity-track"><span class="activity-fill" style="--bar-height:47.69%"></span></span><span>10.21</span></div><div class="activity-day" title="2026-10-22 · 0 分钟运动记录"><span class="activity-track"><span class="activity-fill" style="--bar-height:0.00%"></span></span><span>10.22</span></div><div class="activity-day" title="2026-10-23 · 0 分钟运动记录"><span class="activity-track"><span class="activity-fill" style="--bar-height:0.00%"></span></span><span>10.23</span></div><div class="activity-day" title="2026-10-24 · 45 分钟运动记录"><span class="activity-track"><span class="activity-fill" style="--bar-height:35.02%"></span></span><span>10.24</span></div><div class="activity-day" title="2026-10-25 · 0 分钟运动记录"><span class="activity-track"><span class="activity-fill" style="--bar-height:0.00%"></span></span><span>10.25</span></div></div><ul class="activity-records"><li><span class="activity-symbol tennis"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="8.5"/><path d="M5 6c6 1 6 11 14 12M5 18c7-1 6-11 14-12"/></svg></span><span><strong>网球</strong><small>10-24 10:19 · 45 分钟 · 1.73 km</small></span><span class="record-label">已记录</span></li><li><span class="activity-symbol tennis"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="8.5"/><path d="M5 6c6 1 6 11 14 12M5 18c7-1 6-11 14-12"/></svg></span><span><strong>网球</strong><small>10-21 18:59 · 61 分钟 · 0.06 km</small></span><span class="record-label">已记录</span></li><li><span class="activity-symbol tennis"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="8.5"/><path d="M5 6c6 1 6 11 14 12M5 18c7-1 6-11 14-12"/></svg></span><span><strong>网球</strong><small>10-19 10:14 · 129 分钟 · 2.92 km</small></span><span class="record-label">已记录</span></li></ul><p class="panel-note">记录时长可能含休息；无记录不代表没有活动。</p></section>
    <section class="insights-panel glass" aria-labelledby="insights-title"><div class="panel-heading"><div><span class="eyebrow">SMALL SIGNS, BIG PICTURE</span><h2 id="insights-title">一周里的小变化</h2></div><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m12 3 2.5 6.5L21 12l-6.5 2.5L12 21l-2.5-6.5L3 12l6.5-2.5Z"/></svg></div><ul class="insight-list"><li><span class="insight-symbol mint"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m4 16 6-6 4 4 6-9m-6 0h6v6"/></svg></span><span><strong>3 天达到当日步数目标</strong><small>共 7 天有步数与目标记录</small></span></li><li><span class="insight-symbol lilac"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M20 15.5A8.5 8.5 0 0 1 8.5 4a8.5 8.5 0 1 0 11.5 11.5Z"/></svg></span><span><strong>每晚平均睡眠 6.4 小时</strong><small>共 5 晚 · 最短 4.3 / 最长 7.7 小时</small></span></li><li><span class="insight-symbol mint"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M20 5c-3-3-7-1-8 1-1-2-5-4-8-1s-1 7 8 14c9-7 11-11 8-14Z"/></svg></span><span><strong>夜间 HRV 平均 49 ms</strong><small>共 5 晚有记录 · Garmin 标记平衡 5 天</small></span></li><li><span class="insight-symbol peach"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M2 12h5l3-8 4 16 3-8h5"/></svg></span><span><strong>静息心率平均 55 bpm</strong><small>每日静息心率范围 50—58 bpm</small></span></li><li><span class="insight-symbol lavender"><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="4" y="5" width="16" height="16" rx="4"/><path d="M8 3v4m8-4v4M4 11h16m-11 4h.01m6 0h.01"/></svg></span><span><strong>2 晚睡眠记录缺失</strong><small>周均值只计算有记录的夜晚</small></span></li></ul><p class="panel-note">来自这一周的真实记录，留意长期的节奏。</p></section>
  </div>
  <footer class="dashboard-footer"><span><svg class="icon " viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M20 4c-8-2-16 3-14 10s13 6 14-10Z"/><path d="M4 21 15 10"/></svg> 好好运动，也好好休息。</span><span>Garmin 数据 · 同步于 10.26 13:07 · 上海时间</span></footer>
</div>
