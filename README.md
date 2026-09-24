<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Biraj Thapa — Accounting Assistant / Bookkeeper / AP-AR Specialist</title>
<meta name="description" content="Detail-oriented accounting professional with 3+ years of experience. QuickBooks ProAdvisor + Xero Certified + NetSuite. US Permanent Resident.">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700&family=Inter:wght@400;500;700;800;900&display=swap">

<script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/lenis@1.3.13/dist/lenis.min.js"></script>

<style>
:root {
  --bg: #080808;
  --bg-soft: #0e0e0e;
  --text: #ffffff;
  --text-soft: #dadada;
  --text-mute: #888888;
  --accent: #a3c47a;
  --accent-soft: rgba(163, 196, 122, 0.15);
  --accent-line: rgba(163, 196, 122, 0.35);
  --line: rgba(255, 255, 255, 0.10);
  --line-soft: rgba(255, 255, 255, 0.06);
  --ease-quiet: cubic-bezier(.22, 1, .36, 1);
  --ease-precise: cubic-bezier(.4, 0, .2, 1);
  --ease-emphasis: cubic-bezier(.16, 1, .3, 1);
}

* { margin: 0; padding: 0; box-sizing: border-box; }
html { scroll-behavior: smooth; }
body {
  background: var(--bg);
  color: var(--text);
  font-family: 'Inter', sans-serif;
  font-weight: 400;
  -webkit-font-smoothing: antialiased;
  overflow-x: hidden;
  cursor: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 28 28"><text x="5" y="20" font-family="monospace" font-size="18" font-weight="bold" fill="%23a3c47a">%24</text></svg>') 4 2, auto;
}

a, button, .btn, .row, .project-card, .contact-item, .tool-tag {
  cursor: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 28 28"><text x="5" y="20" font-family="monospace" font-size="18" font-weight="bold" fill="%23ffffff">%24</text></svg>') 4 2, pointer;
}

a { color: inherit; }
::selection { background: var(--accent); color: var(--bg); }

.label {
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  font-weight: 400;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--text-mute);
  display: inline-block;
}
.label-accent { color: var(--accent); }

.glyph-rain {
  position: fixed; inset: 0; z-index: -1;
  opacity: 0.05;
  pointer-events: none;
}

nav.top {
  position: fixed; top: 0; left: 0; right: 0; z-index: 100;
  padding: 1.25rem 2rem;
  display: flex; justify-content: space-between; align-items: center;
  background: rgba(8, 8, 8, 0.78);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  border-bottom: 1px solid var(--line-soft);
}
nav.top .brand {
  font-family: 'JetBrains Mono', monospace;
  font-weight: 700;
  font-size: 13px;
  letter-spacing: 0.05em;
}
nav.top .brand .accent { color: var(--accent); }
nav.top .brand .sub { color: var(--text-mute); margin-left: 0.5rem; font-weight: 400; }
nav.top ul {
  list-style: none;
  display: flex;
  gap: 2rem;
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
}
nav.top ul a {
  color: var(--text-soft);
  text-decoration: none;
  transition: color 300ms var(--ease-quiet);
  position: relative;
}
nav.top ul a:hover { color: var(--accent); }
@media (max-width: 768px) { nav.top ul { display: none; } }

section {
  padding: 8rem 2rem;
  position: relative;
}
@media (max-width: 768px) { section { padding: 5rem 1.5rem; } }

.container { max-width: 1400px; margin: 0 auto; }
.container-narrow { max-width: 860px; margin: 0 auto; }

.section-label {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin-bottom: 2rem;
}
.section-label::before {
  content: '';
  display: inline-block;
  width: 2rem;
  height: 1px;
  background: var(--accent);
}

.section-headline {
  font-family: 'Inter', sans-serif;
  font-weight: 800;
  font-size: clamp(2.25rem, 4.5vw, 3.75rem);
  letter-spacing: -0.025em;
  line-height: 1.05;
  margin-bottom: 4rem;
  max-width: 1100px;
}

.prose-block p {
  font-size: 1.0625rem;
  line-height: 1.65;
  color: var(--text-soft);
  margin-bottom: 1.5rem;
}
.prose-block p:last-child { margin-bottom: 0; }

.reveal {
  opacity: 0;
  transform: translateY(40px);
  transition: opacity 1200ms var(--ease-quiet), transform 1200ms var(--ease-quiet);
}
.reveal.is-in {
  opacity: 1;
  transform: none;
}

/* ========================================
   HERO SECTION
   ======================================== */
.hero {
  min-height: 100vh;
  padding: 9rem 2rem 4rem;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  align-items: start;
  position: relative;
  border-bottom: 1px solid var(--line);
}
@media (max-width: 900px) {
  .hero { grid-template-columns: 1fr; padding: 7rem 1.5rem 3rem; gap: 2rem; }
}

.hero-left {
  position: sticky;
  top: 0;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 4rem 0;
}
@media (max-width: 900px) {
  .hero-left { position: static; height: auto; padding: 0; }
}

.hero-eyebrow {
  display: flex;
  gap: 1.5rem;
  margin-bottom: 2.5rem;
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--text-mute);
  flex-wrap: wrap;
}
.hero-eyebrow .dot {
  width: 6px; height: 6px; border-radius: 50%;
  background: var(--accent);
  display: inline-block;
  margin-right: 0.5rem;
  vertical-align: middle;
}

.hero-title {
  font-family: 'JetBrains Mono', monospace;
  font-weight: 700;
  font-size: clamp(2.75rem, 6.5vw, 5.25rem);
  letter-spacing: -0.04em;
  line-height: 0.95;
  margin-bottom: 2rem;
}
.hero-title .accent { color: var(--accent); }

.hero-role {
  font-family: 'JetBrains Mono', monospace;
  font-size: 12px;
  letter-spacing: 0.25em;
  text-transform: uppercase;
  color: var(--accent);
  margin-bottom: 2rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid var(--line);
  max-width: 480px;
}

.hero-sub {
  font-size: 1.0625rem;
  line-height: 1.6;
  color: var(--text-soft);
  max-width: 480px;
  margin-bottom: 3rem;
}

.hero-cta {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.btn {
  display: inline-flex;
  align-items: center;
  gap: 0.6rem;
  padding: 1rem 1.5rem;
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  text-decoration: none;
  color: var(--text);
  border: 1px solid var(--line);
  background: transparent;
  transition: all 400ms var(--ease-quiet);
}
.btn:hover {
  border-color: var(--accent);
  color: var(--accent);
}
.btn-primary {
  background: var(--accent);
  color: var(--bg);
  border-color: var(--accent);
  font-weight: 700;
}
.btn-primary:hover {
  background: transparent;
  color: var(--accent);
}

/* ========================================
   HERO RIGHT — FINANCIAL OPERATIONS DASHBOARD
   ======================================== */
.hero-right {
  position: sticky;
  top: 0;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 4rem 0;
  overflow: hidden;
}

/* Grid texture overlay */
.hero-right::before {
  content: '';
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(to right, rgba(255,255,255,0.015) 1px, transparent 1px),
    linear-gradient(to bottom, rgba(255,255,255,0.015) 1px, transparent 1px);
  background-size: 36px 36px;
  pointer-events: none;
  z-index: 0;
}

/* Scan line texture */
.hero-right::after {
  content: '';
  position: absolute;
  inset: 0;
  background: repeating-linear-gradient(
    0deg,
    transparent 0px,
    transparent 3px,
    rgba(255,255,255,0.008) 3px,
    rgba(255,255,255,0.008) 4px
  );
  pointer-events: none;
  z-index: 0;
}

/* Dashboard base container */
.fin-dashboard {
  position: relative;
  z-index: 1;
  width: 100%;
  max-width: 560px;
  margin: 0 auto;
}

/* Dashboard header */
.dash-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 0.5rem;
}

.dash-title {
  font-family: 'JetBrains Mono', monospace;
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--text);
}

.dash-sub {
  font-family: 'JetBrains Mono', monospace;
  font-size: 9px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--text-mute);
  margin-top: 0.4rem;
}

.dash-status {
  display: flex;
  align-items: center;
  gap: 0.4rem;
  font-family: 'JetBrains Mono', monospace;
  font-size: 9px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--accent);
}

.status-dot {
  width: 6px;
  height: 6px;
  border-radius: 50%;
  background: var(--accent);
  animation: pulseDot 2.5s ease-in-out infinite;
}

@keyframes pulseDot {
  0%, 100% { opacity: 1; box-shadow: 0 0 6px var(--accent); }
  50% { opacity: 0.3; box-shadow: 0 0 12px var(--accent); }
}

.dash-timestamp {
  font-family: 'JetBrains Mono', monospace;
  font-size: 8px;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--text-mute);
  opacity: 0.5;
  margin-bottom: 1.5rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid rgba(255,255,255,0.03);
}

/* Chart section */
.dash-chart-section {
  margin-bottom: 1.5rem;
}

.chart-section-label {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  margin-bottom: 0.75rem;
}

.chart-section-label .label-main {
  font-family: 'JetBrains Mono', monospace;
  font-size: 9px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--text-mute);
}

.chart-section-label .label-ref {
  font-family: 'JetBrains Mono', monospace;
  font-size: 8px;
  letter-spacing: 0.15em;
  color: var(--text-mute);
  opacity: 0.5;
}

/* Chart wrapper with corner brackets */
.dash-chart-wrap {
  position: relative;
  width: 100%;
  height: 140px;
}

.dash-chart-wrap::before,
.dash-chart-wrap::after {
  content: '';
  position: absolute;
  width: 10px;
  height: 10px;
  border: 1px solid rgba(163, 196, 122, 0.2);
  z-index: 3;
}
.dash-chart-wrap::before {
  top: 0; left: 0;
  border-right: none;
  border-bottom: none;
}
.dash-chart-wrap::after {
  bottom: 0; right: 0;
  border-left: none;
  border-top: none;
}

.cash-flow-chart {
  width: 100%;
  height: 140px;
  display: block;
}

.chart-grid line {
  stroke: rgba(255,255,255,0.03);
  stroke-width: 1;
}

.revenue-area {
  fill: rgba(163,196,122,0.04);
  opacity: 0;
  animation: fadeIn 1.5s var(--ease-quiet) 1.5s forwards;
}

.expense-line {
  fill: none;
  stroke: rgba(255,255,255,0.12);
  stroke-width: 1;
  stroke-dasharray: 500;
  stroke-dashoffset: 500;
  animation: drawLine 2.5s var(--ease-quiet) 0.6s forwards;
}

.revenue-line {
  fill: none;
  stroke: var(--accent);
  stroke-width: 1.5;
  stroke-dasharray: 500;
  stroke-dashoffset: 500;
  animation: drawLine 2.5s var(--ease-quiet) 0.3s forwards;
  filter: drop-shadow(0 0 3px rgba(163,196,122,0.2));
}

.current-month-line {
  stroke: rgba(163,196,122,0.15);
  stroke-width: 1;
  stroke-dasharray: 2 4;
  opacity: 0;
  animation: fadeIn 0.8s var(--ease-quiet) 2.5s forwards;
}

@keyframes drawLine {
  to { stroke-dashoffset: 0; }
}

@keyframes fadeIn {
  to { opacity: 1; }
}

/* Chart endpoint dot with glow */
.chart-endpoint {
  position: absolute;
  right: 0;
  top: 20.7%;
  transform: translate(50%, -50%);
  width: 8px;
  height: 8px;
  z-index: 3;
}

.chart-endpoint::before {
  content: '';
  position: absolute;
  inset: 0;
  border-radius: 50%;
  background: var(--accent);
  box-shadow: 0 0 6px rgba(163,196,122,0.5);
}

.chart-endpoint::after {
  content: '';
  position: absolute;
  inset: -5px;
  border-radius: 50%;
  border: 1px solid var(--accent);
  opacity: 0.3;
  animation: ringPulse 2.5s ease-in-out infinite;
}

@keyframes ringPulse {
  0%, 100% { transform: scale(1); opacity: 0.3; }
  50% { transform: scale(1.6); opacity: 0; }
}

/* X-axis labels */
.chart-x-labels {
  display: flex;
  justify-content: space-between;
  margin-top: 0.5rem;
  padding: 0 1px;
}

.chart-x-labels span {
  font-family: 'JetBrains Mono', monospace;
  font-size: 7px;
  color: var(--text-mute);
  opacity: 0.35;
  letter-spacing: 0.1em;
}

/* Chart legend / stats row */
.chart-legend {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 0;
  margin-top: 1rem;
  padding-top: 0.75rem;
  border-top: 1px solid rgba(255,255,255,0.03);
}

.legend-item {
  display: flex;
  flex-direction: column;
  gap: 0.2rem;
}

.legend-item:not(:last-child) {
  border-right: 1px solid rgba(255,255,255,0.03);
  padding-right: 0.75rem;
}

.legend-item:not(:first-child) {
  padding-left: 0.75rem;
}

.legend-line {
  display: inline-block;
  width: 12px;
  height: 1px;
  margin-right: 0.4rem;
  vertical-align: middle;
}

.legend-line.revenue { background: var(--accent); }
.legend-line.expense { background: rgba(255,255,255,0.2); }

.legend-label {
  font-family: 'JetBrains Mono', monospace;
  font-size: 8px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--text-mute);
  opacity: 0.6;
}

.legend-value {
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  font-weight: 700;
  color: var(--text-soft);
  font-variant-numeric: tabular-nums;
}

/* General Ledger */
.dash-ledger {
  margin-top: 1.25rem;
  opacity: 0.3;
  transition: opacity 400ms var(--ease-quiet);
}

.dash-ledger:hover { opacity: 0.5; }

.ledger-header-row {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  margin-bottom: 0.5rem;
  padding-bottom: 0.5rem;
  border-bottom: 1px solid rgba(255,255,255,0.03);
}

.ledger-header-row .hdr {
  font-family: 'JetBrains Mono', monospace;
  font-size: 9px;
  letter-spacing: 0.25em;
  text-transform: uppercase;
  color: var(--text-mute);
}

.ledger-header-row .ref {
  font-family: 'JetBrains Mono', monospace;
  font-size: 8px;
  letter-spacing: 0.15em;
  color: var(--text-mute);
  opacity: 0.5;
}

.ledger-row {
  display: grid;
  grid-template-columns: 24px 1fr auto;
  gap: 0.75rem;
  font-family: 'JetBrains Mono', monospace;
  font-size: 10px;
  padding: 0.3rem 0;
  border-bottom: 1px solid rgba(255,255,255,0.015);
}

.ledger-acct { color: var(--accent); opacity: 0.6; }
.ledger-name { color: var(--text-mute); }
.ledger-amt { color: var(--text-mute); text-align: right; font-variant-numeric: tabular-nums; }

/* Software stack */
.dash-software {
  margin-top: 1.25rem;
  padding-top: 0.75rem;
  border-top: 1px solid rgba(255,255,255,0.03);
}

.software-row {
  font-family: 'JetBrains Mono', monospace;
  font-size: 9px;
  letter-spacing: 0.22em;
  color: var(--text-mute);
  opacity: 0.5;
}

.software-sub {
  font-family: 'JetBrains Mono', monospace;
  font-size: 8px;
  letter-spacing: 0.22em;
  color: var(--text-mute);
  opacity: 0.35;
  margin-top: 0.3rem;
}

/* Floating metric cards */
.metric-card {
  position: absolute;
  background: rgba(10, 10, 10, 0.88);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  border: 1px solid rgba(255,255,255,0.07);
  padding: 0.875rem 1.125rem;
  min-width: 148px;
  z-index: 4;
  transition: transform 500ms var(--ease-quiet), border-color 400ms var(--ease-quiet);
}

.metric-card::before {
  content: '';
  position: absolute;
  left: 0; top: 0;
  width: 2px;
  height: 100%;
  background: var(--accent);
  opacity: 0.4;
  transition: opacity 400ms var(--ease-quiet);
}

.metric-card:hover {
  border-color: rgba(163,196,122,0.2);
}

.metric-card:hover::before {
  opacity: 0.8;
}

.metric-card-inner {
  opacity: 0;
  transform: translateY(8px);
  animation: cardSlideIn 0.8s var(--ease-quiet) forwards;
  animation-delay: var(--card-delay, 0.5s);
}

@keyframes cardSlideIn {
  to { opacity: 1; transform: none; }
}

.metric-label {
  font-family: 'JetBrains Mono', monospace;
  font-size: 8px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--text-mute);
  margin-bottom: 0.4rem;
}

.metric-value {
  font-family: 'JetBrains Mono', monospace;
  font-size: 1.125rem;
  font-weight: 700;
  color: var(--text);
  letter-spacing: -0.02em;
  margin-bottom: 0.2rem;
  font-variant-numeric: tabular-nums;
}

.metric-change {
  font-family: 'JetBrains Mono', monospace;
  font-size: 9px;
  color: var(--accent);
  letter-spacing: 0.05em;
}

.metric-timestamp {
  font-family: 'JetBrains Mono', monospace;
  font-size: 7px;
  color: var(--text-mute);
  opacity: 0.4;
  margin-top: 0.4rem;
  padding-top: 0.3rem;
  border-top: 1px solid rgba(255,255,255,0.03);
  letter-spacing: 0.1em;
}

/* Card positions — desktop */
.card-1 { top: 6%; right: 0; }
.card-2 { top: 34%; left: -8px; }
.card-3 { top: 55%; right: 6%; }
.card-4 { bottom: 8%; left: 4%; }

/* Hero right responsive */
@media (max-width: 900px) {
  .hero-right {
    position: static;
    height: auto;
    padding: 0;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1px;
    background: var(--line);
    border: 1px solid var(--line);
    overflow: visible;
  }

  .hero-right::before,
  .hero-right::after { display: none; }

  .fin-dashboard { display: none; }

  .metric-card {
    position: relative;
    top: auto !important;
    left: auto !important;
    right: auto !important;
    bottom: auto !important;
    margin: 0 !important;
    background: var(--bg);
    border: none;
    padding: 1.5rem 1.25rem;
    transform: none !important;
    min-width: 0;
  }

  .metric-card::before {
    display: block;
    opacity: 0.3;
  }

  .metric-card-inner {
    animation: none;
    opacity: 1;
    transform: none;
  }
}

@media (max-width: 480px) {
  .hero-right {
    grid-template-columns: 1fr;
  }
}

/* ========================================
   REMAINING SECTIONS (unchanged)
   ======================================== */
.sticky-pair {
  display: grid;
  grid-template-columns: 5fr 7fr;
  gap: 4rem;
  align-items: start;
}
.sticky-pair .left {
  position: sticky;
  top: 100px;
  align-self: start;
}
.sticky-pair .left .section-headline {
  margin-bottom: 2rem;
}
.sticky-pair .left .prose-side {
  color: var(--text-soft);
  font-size: 1rem;
  line-height: 1.65;
  max-width: 380px;
}
@media (max-width: 900px) {
  .sticky-pair { grid-template-columns: 1fr; gap: 2rem; }
  .sticky-pair .left { position: static; }
}
.sticky-pair .right { display: flex; flex-direction: column; gap: 0; }

.sub-headline {
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  font-weight: 400;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--text-mute);
  margin-bottom: 1.5rem;
  padding-top: 2rem;
  border-top: 1px solid var(--line-soft);
}
.sub-headline.no-border {
  border-top: none;
  padding-top: 0;
}

.competency-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2px;
  background: var(--line);
  border: 1px solid var(--line);
}
.competency {
  background: var(--bg);
  padding: 2.25rem 2rem;
  transition: background 400ms var(--ease-quiet);
}
.competency:hover { background: rgba(163, 196, 122, 0.04); }
.competency h4 {
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--accent);
  margin-bottom: 1.5rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid var(--line-soft);
}
.competency ul {
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 0.6rem;
}
.competency ul li {
  font-size: 0.9375rem;
  color: var(--text-soft);
  line-height: 1.45;
  padding-left: 1.25rem;
  position: relative;
}
.competency ul li::before {
  content: '$';
  position: absolute;
  left: 0;
  color: var(--accent);
  opacity: 0.55;
  font-family: 'JetBrains Mono', monospace;
  font-weight: 700;
}

.timeline-item {
  padding: 2.5rem 0;
  border-top: 1px solid var(--line);
  position: relative;
}
.timeline-item:last-child { border-bottom: 1px solid var(--line); }
.timeline-meta {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  margin-bottom: 1rem;
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  flex-wrap: wrap;
  gap: 0.5rem;
}
.timeline-meta .date { color: var(--accent); }
.timeline-meta .location { color: var(--text-mute); }
.timeline-item h3 {
  font-family: 'Inter', sans-serif;
  font-weight: 800;
  font-size: 1.5rem;
  letter-spacing: -0.02em;
  margin-bottom: 1rem;
  line-height: 1.25;
}
.timeline-item ul.bullets {
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
  margin-top: 1.5rem;
}
.timeline-item ul.bullets li {
  font-size: 0.9375rem;
  line-height: 1.55;
  color: var(--text-soft);
  padding-left: 1.5rem;
  position: relative;
}
.timeline-item ul.bullets li::before {
  content: '$';
  position: absolute;
  left: 0;
  color: var(--accent);
  font-family: 'JetBrains Mono', monospace;
  font-weight: 700;
}

.row {
  display: grid;
  grid-template-columns: 180px 1fr;
  gap: 3rem;
  padding: 2.5rem 0;
  border-top: 1px solid var(--line);
  position: relative;
  transition: background 400ms var(--ease-quiet);
}
.row:last-child { border-bottom: 1px solid var(--line); }
.row::before {
  content: '';
  position: absolute;
  left: 0; top: 0;
  width: 2px; height: 0;
  background: var(--accent);
  transition: height 600ms var(--ease-quiet);
}
.row:hover::before { height: 100%; }
.row .row-label {
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--text-mute);
  padding-left: 1.5rem;
  transition: color 400ms var(--ease-quiet);
}
.row:hover .row-label { color: var(--accent); }
.row .row-content { transition: color 400ms var(--ease-quiet); }
.row .row-content h3 {
  font-family: 'Inter', sans-serif;
  font-weight: 800;
  font-size: 1.25rem;
  letter-spacing: -0.015em;
  margin-bottom: 0.75rem;
  line-height: 1.3;
}
.row .row-content p {
  font-size: 0.95rem;
  line-height: 1.6;
  color: var(--text-soft);
}
@media (max-width: 768px) {
  .row { grid-template-columns: 1fr; gap: 0.75rem; padding: 2rem 0; }
  .row .row-label { padding-left: 1rem; }
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 2px;
  background: var(--line);
  border: 1px solid var(--line);
}
.project-card {
  background: var(--bg);
  padding: 2.5rem 2rem;
  display: flex;
  flex-direction: column;
  gap: 1.25rem;
  position: relative;
  transition: background 400ms var(--ease-quiet);
  min-height: 320px;
  text-decoration: none;
  color: var(--text);
}
.project-card::before {
  content: '';
  position: absolute;
  left: 0; top: 0;
  width: 2px; height: 0;
  background: var(--accent);
  transition: height 600ms var(--ease-quiet);
}
.project-card:hover::before { height: 100%; }
.project-card:hover { background: rgba(163, 196, 122, 0.03); }
.project-card .num {
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.22em;
  color: var(--accent);
}
.project-card h3 {
  font-family: 'Inter', sans-serif;
  font-weight: 800;
  font-size: 1.4rem;
  line-height: 1.25;
  letter-spacing: -0.02em;
}
.project-card p {
  font-size: 0.9375rem;
  line-height: 1.55;
  color: var(--text-soft);
  flex: 1;
}
.project-card .arrow {
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--text-mute);
  transition: color 400ms var(--ease-quiet);
  display: flex;
  align-items: center;
  gap: 0.5rem;
}
.project-card:hover .arrow { color: var(--accent); }

.method {
  padding: 10rem 2rem;
  border-top: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
  background: var(--bg-soft);
}
.method-quote {
  max-width: 1000px;
  margin: 0 auto;
  text-align: left;
}
.method-quote .quote-mark {
  font-family: 'JetBrains Mono', monospace;
  font-size: 4rem;
  color: var(--accent);
  line-height: 0.8;
  margin-bottom: 2rem;
}
.method-quote blockquote {
  font-family: 'Inter', sans-serif;
  font-weight: 800;
  font-size: clamp(1.75rem, 3.5vw, 2.75rem);
  letter-spacing: -0.025em;
  line-height: 1.2;
  margin-bottom: 2rem;
}
.method-quote blockquote .accent { color: var(--accent); }
.method-quote cite {
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--text-mute);
  font-style: normal;
}

.case-study {
  padding: 8rem 2rem;
  border-top: 1px solid var(--line);
}

.case-header {
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 4rem;
  margin-bottom: 4rem;
  align-items: end;
  padding-bottom: 3rem;
  border-bottom: 1px solid var(--line);
}
@media (max-width: 768px) {
  .case-header { grid-template-columns: 1fr; gap: 1.5rem; }
}

.case-number {
  font-family: 'JetBrains Mono', monospace;
  font-size: 0.9375rem;
  letter-spacing: 0.22em;
  color: var(--accent);
  text-transform: uppercase;
}
.case-title {
  font-family: 'Inter', sans-serif;
  font-weight: 900;
  font-size: clamp(2rem, 4vw, 3.25rem);
  letter-spacing: -0.025em;
  line-height: 1.05;
}

.case-intro {
  max-width: 760px;
  margin-bottom: 4rem;
}
.case-intro > p {
  font-size: 1.0625rem;
  line-height: 1.65;
  color: var(--text-soft);
  margin-bottom: 1.5rem;
}
.case-meta {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 1.5rem;
  padding: 1.5rem 0;
  border-top: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
  margin-bottom: 1.5rem;
}
.case-meta > div .label { display: block; margin-bottom: 0.5rem; }
.case-meta > div .val {
  font-family: 'JetBrains Mono', monospace;
  font-size: 0.9375rem;
  color: var(--text);
}

.tool-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}
.tool-tag {
  padding: 0.4rem 0.75rem;
  border: 1px solid var(--line);
  font-family: 'JetBrains Mono', monospace;
  font-size: 10px;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: var(--text-soft);
  transition: border-color 300ms var(--ease-quiet), color 300ms var(--ease-quiet);
}
.tool-tag:hover { border-color: var(--accent-line); color: var(--accent); }

.kpi-strip {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  border: 1px solid var(--line);
  margin-bottom: 4rem;
}
@media (max-width: 768px) {
  .kpi-strip { grid-template-columns: repeat(2, 1fr); }
}
.kpi {
  padding: 1.75rem 1.5rem;
  border-right: 1px solid var(--line);
}
.kpi:nth-child(2n) { border-right: none; }
@media (min-width: 769px) {
  .kpi:nth-child(2n) { border-right: 1px solid var(--line); }
  .kpi:last-child { border-right: none; }
}
@media (max-width: 768px) {
  .kpi:nth-child(3), .kpi:nth-child(4) { border-top: 1px solid var(--line); }
}
.kpi .val {
  font-family: 'JetBrains Mono', monospace;
  font-size: 1.75rem;
  font-weight: 700;
  color: var(--accent);
  letter-spacing: -0.02em;
  margin-bottom: 0.5rem;
  font-variant-numeric: tabular-nums;
}
.kpi .lbl {
  font-family: 'JetBrains Mono', monospace;
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--text-mute);
}

.charts-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2px;
  background: var(--line);
  border: 1px solid var(--line);
  margin-bottom: 4rem;
}
@media (max-width: 768px) {
  .charts-grid { grid-template-columns: 1fr; }
}
.chart-panel {
  background: var(--bg);
  padding: 2rem;
}
.chart-panel-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  margin-bottom: 1.5rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid var(--line-soft);
}
.chart-panel-header h4 {
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--text);
  font-weight: 400;
}
.chart-panel-header .meta {
  font-family: 'JetBrains Mono', monospace;
  font-size: 10px;
  letter-spacing: 0.15em;
  color: var(--text-mute);
  text-transform: uppercase;
}
.chart-canvas-wrap {
  height: 280px;
  position: relative;
}

.block-title {
  font-family: 'Inter', sans-serif;
  font-weight: 800;
  font-size: 1.4rem;
  letter-spacing: -0.02em;
  margin-bottom: 1.5rem;
  padding-bottom: 0.75rem;
  border-bottom: 1px solid var(--line-soft);
}

.ledger-wrap {
  overflow-x: auto;
  margin-bottom: 4rem;
}
.ledger-table {
  width: 100%;
  border-collapse: collapse;
  font-family: 'JetBrains Mono', monospace;
  font-size: 0.8125rem;
  min-width: 600px;
}
.ledger-table th, .ledger-table td {
  padding: 0.75rem 1rem;
  text-align: left;
  border-bottom: 1px solid var(--line-soft);
  vertical-align: top;
}
.ledger-table th {
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--text-mute);
  font-weight: 400;
  border-bottom: 1px solid var(--line);
  text-align: left;
}
.ledger-table td.amount, .ledger-table th.amount {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
.ledger-table tr:hover td { background: rgba(163, 196, 122, 0.03); }
.ledger-table tr.total td {
  border-top: 1px solid var(--accent-line);
  border-bottom: 1px solid var(--accent-line);
  font-weight: 700;
  color: var(--accent);
}
.ledger-table tr.subtotal td {
  border-top: 1px solid var(--line);
  font-weight: 700;
  color: var(--text);
}

.bank-rec-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2px;
  background: var(--line);
  border: 1px solid var(--line);
  margin-bottom: 4rem;
}
@media (max-width: 768px) { .bank-rec-grid { grid-template-columns: 1fr; } }
.bank-rec-side {
  background: var(--bg);
  padding: 2rem;
}
.bank-rec-side h4 {
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--accent);
  margin-bottom: 1.5rem;
  padding-bottom: 0.75rem;
  border-bottom: 1px solid var(--line-soft);
}

.close-memo {
  padding: 3rem;
  border: 1px solid var(--accent-line);
  background: rgba(163, 196, 122, 0.03);
  margin-bottom: 4rem;
}
@media (max-width: 768px) { .close-memo { padding: 2rem 1.5rem; } }
.close-memo .label { margin-bottom: 1rem; }
.close-memo p {
  font-size: 1.0625rem;
  line-height: 1.65;
  color: var(--text-soft);
  margin-bottom: 1.5rem;
}
.close-memo .memo-footer {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 1rem;
  padding-top: 1.5rem;
  border-top: 1px solid var(--accent-line);
}
.close-memo .memo-footer > div .label { display: block; margin-bottom: 0.4rem; }
.close-memo .memo-footer > div .val {
  font-family: 'JetBrains Mono', monospace;
  font-size: 0.9rem;
  color: var(--text-soft);
}

.lang-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2px;
  background: var(--line);
  border: 1px solid var(--line);
}
@media (max-width: 768px) { .lang-grid { grid-template-columns: 1fr; } }
.lang-cell {
  background: var(--bg);
  padding: 2.5rem 2rem;
}
.lang-cell .label { color: var(--accent); margin-bottom: 1.25rem; }
.lang-cell .lang-name {
  font-family: 'JetBrains Mono', monospace;
  font-size: 2rem;
  font-weight: 700;
  letter-spacing: -0.02em;
  margin-bottom: 1rem;
}
.lang-cell p {
  color: var(--text-soft);
  font-size: 0.9375rem;
  line-height: 1.55;
}

.contact {
  padding: 10rem 2rem;
  border-top: 1px solid var(--line);
  text-align: center;
}
.contact .label { margin-bottom: 2rem; }
.contact h2 {
  font-family: 'JetBrains Mono', monospace;
  font-weight: 700;
  font-size: clamp(2.75rem, 6vw, 5rem);
  letter-spacing: -0.04em;
  line-height: 0.95;
  margin-bottom: 2rem;
}
.contact h2 .accent { color: var(--accent); }
.contact .lead {
  max-width: 600px;
  margin: 0 auto 4rem;
  font-size: 1.0625rem;
  line-height: 1.6;
  color: var(--text-soft);
}
.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 0;
  max-width: 1000px;
  margin: 0 auto;
  text-align: left;
  border: 1px solid var(--line);
}
.contact-item {
  padding: 2rem;
  border-right: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
  text-decoration: none;
  color: var(--text);
  transition: background 400ms var(--ease-quiet);
  display: block;
}
.contact-item:nth-child(2n) { border-right: none; }
.contact-item:nth-last-child(-n+2) { border-bottom: none; }
@media (max-width: 768px) {
  .contact-item { border-right: none; }
  .contact-item:last-child { border-bottom: none; }
}
.contact-item:hover { background: rgba(163, 196, 122, 0.04); }
.contact-item .lbl {
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--text-mute);
  margin-bottom: 0.75rem;
}
.contact-item .val {
  font-family: 'JetBrains Mono', monospace;
  font-size: 0.9375rem;
  color: var(--text);
  transition: color 300ms var(--ease-quiet);
}
.contact-item:hover .val { color: var(--accent); }

footer.bottom {
  padding: 3rem 2rem;
  border-top: 1px solid var(--line);
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-family: 'JetBrains Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--text-mute);
  flex-wrap: wrap;
  gap: 1rem;
}
footer.bottom .accent { color: var(--accent); }
@media (max-width: 768px) {
  footer.bottom { flex-direction: column; text-align: center; }
}

@media (prefers-reduced-motion: reduce) {
  .reveal { opacity: 1; transform: none; transition: none; }
  .revenue-line, .expense-line { stroke-dashoffset: 0 !important; animation: none !important; }
  .revenue-area, .current-month-line { opacity: 1 !important; animation: none !important; }
  .metric-card-inner { opacity: 1 !important; transform: none !important; animation: none !important; }
  .status-dot, .chart-endpoint::after { animation: none !important; }
  * { animation-duration: 0.01ms !important; transition-duration: 0.01ms !important; }
}
</style>
</head>
<body>

<canvas class="glyph-rain"></canvas>

<nav class="top">
  <div class="brand">BIRAJ<span class="accent">.</span>THAPA<span class="sub">/ ACCT · BOOKKEEPER</span></div>
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#education">Education</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- ========================================
     HERO SECTION
     ======================================== -->
<section class="hero" id="hero">
  <!-- LEFT SIDE (unchanged) -->
  <div class="hero-left">
    <div class="hero-eyebrow">
      <span><span class="dot"></span>MORRISVILLE · NC</span>
      <span>EST. 2022</span>
      <span>US PERMANENT RESIDENT</span>
    </div>
    <h1 class="hero-title">BIRAJ<br>THAPA<span class="accent">.</span></h1>
    <div class="hero-role">Accounting Assistant · Bookkeeper · AP / AR</div>
    <p class="hero-sub">
      Detail-oriented accounting professional with 3+ years of experience in AP/AR, bank reconciliation, journal entries, payroll support, and full-cycle bookkeeping. Proficient in QuickBooks Online, Xero, NetSuite, Tally, and advanced Excel, with working knowledge of U.S. GAAP and accrual-basis accounting.
    </p>
    <div class="hero-cta">
      <a href="#projects" class="btn btn-primary">View portfolio →</a>
      <a href="mailto:biraj0864@gmail.com" class="btn">biraj0864@gmail.com</a>
    </div>
  </div>

  <!-- RIGHT SIDE — FINANCIAL OPERATIONS DASHBOARD -->
  <div class="hero-right">
    <!-- Dashboard base layer -->
    <div class="fin-dashboard">
      <!-- Header -->
      <div class="dash-header">
        <div>
          <div class="dash-title">FINANCIAL OPERATIONS</div>
          <div class="dash-sub">2026 · MONTHLY OVERVIEW</div>
        </div>
        <div class="dash-status">
          <span class="status-dot"></span>
          <span>LIVE</span>
        </div>
      </div>
      <div class="dash-timestamp">LAST SYNC: 08:42 UTC · AUTO-SYNC: ON · SYS: FIN-OPS-01</div>

      <!-- Chart section -->
      <div class="dash-chart-section">
        <div class="chart-section-label">
          <span class="label-main">CASH FLOW · 12 MONTHS</span>
          <span class="label-ref">T-12M</span>
        </div>
        <div class="dash-chart-wrap">
          <svg class="cash-flow-chart" viewBox="0 0 400 160" preserveAspectRatio="none">
            <!-- Grid lines -->
            <g class="chart-grid">
              <line x1="0" y1="10" x2="400" y2="10" />
              <line x1="0" y1="50" x2="400" y2="50" />
              <line x1="0" y1="90" x2="400" y2="90" />
              <line x1="0" y1="130" x2="400" y2="130" />
              <line x1="0" y1="160" x2="400" y2="160" />
            </g>
            <!-- Revenue area fill -->
            <path class="revenue-area" d="M 0,62.5 L 36,58 L 73,53.5 L 109,55 L 145,50.5 L 182,47.5 L 218,52 L 255,43 L 291,40 L 327,41.5 L 364,37 L 400,33.1 L 400,160 L 0,160 Z" />
            <!-- Expense line -->
            <path class="expense-line" d="M 0,97 L 36,95.5 L 73,94 L 109,92.5 L 145,95.5 L 182,91 L 218,89.5 L 255,88 L 291,85 L 327,86.5 L 364,83.5 L 400,81.73" />
            <!-- Revenue line -->
            <path class="revenue-line" d="M 0,62.5 L 36,58 L 73,53.5 L 109,55 L 145,50.5 L 182,47.5 L 218,52 L 255,43 L 291,40 L 327,41.5 L 364,37 L 400,33.1" />
            <!-- Current month indicator -->
            <line class="current-month-line" x1="400" y1="10" x2="400" y2="160" />
          </svg>
          <!-- Endpoint dot -->
          <div class="chart-endpoint"></div>
        </div>
        <!-- X-axis labels -->
        <div class="chart-x-labels">
          <span>J</span><span>F</span><span>M</span><span>A</span><span>M</span><span>J</span><span>J</span><span>A</span><span>S</span><span>O</span><span>N</span><span>D</span>
        </div>
        <!-- Legend / stats row -->
        <div class="chart-legend">
          <div class="legend-item">
            <span class="legend-label"><span class="legend-line revenue"></span>REVENUE</span>
            <span class="legend-value">$84,620</span>
          </div>
          <div class="legend-item">
            <span class="legend-label"><span class="legend-line expense"></span>EXPENSES</span>
            <span class="legend-value">$52,180</span>
          </div>
          <div class="legend-item">
            <span class="legend-label">NET INCOME</span>
            <span class="legend-value">$32,440</span>
          </div>
        </div>
      </div>

      <!-- General Ledger -->
      <div class="dash-ledger">
        <div class="ledger-header-row">
          <span class="hdr">GENERAL LEDGER</span>
          <span class="ref">REF: GL-2026-08</span>
        </div>
        <div class="ledger-rows">
          <div class="ledger-row">
            <span class="ledger-acct">01</span>
            <span class="ledger-name">CASH</span>
            <span class="ledger-amt">$12,450</span>
          </div>
          <div class="ledger-row">
            <span class="ledger-acct">02</span>
            <span class="ledger-name">ACCOUNTS RECEIVABLE</span>
            <span class="ledger-amt">$28,920</span>
          </div>
          <div class="ledger-row">
            <span class="ledger-acct">03</span>
            <span class="ledger-name">ACCOUNTS PAYABLE</span>
            <span class="ledger-amt">$16,340</span>
          </div>
          <div class="ledger-row">
            <span class="ledger-acct">04</span>
            <span class="ledger-name">REVENUE</span>
            <span class="ledger-amt">$84,620</span>
          </div>
          <div class="ledger-row">
            <span class="ledger-acct">05</span>
            <span class="ledger-name">OPERATING EXPENSES</span>
            <span class="ledger-amt">$52,180</span>
          </div>
        </div>
      </div>

      <!-- Software stack -->
      <div class="dash-software">
        <div class="software-row">QBO · XERO · NETSUITE · EXCEL</div>
        <div class="software-sub">US GAAP · ACCRUAL ACCOUNTING</div>
      </div>
    </div>

    <!-- Floating metric cards -->
    <div class="metric-card card-1" data-depth="1">
      <div class="metric-card-inner" style="--card-delay: 0.6s">
        <div class="metric-label">ACCOUNTS PAYABLE</div>
        <div class="metric-value">$42,680</div>
        <div class="metric-change">+8.4%</div>
        <div class="metric-timestamp">AS OF 08/31</div>
      </div>
    </div>

    <div class="metric-card card-2" data-depth="2">
      <div class="metric-card-inner" style="--card-delay: 0.8s">
        <div class="metric-label">ACCOUNTS RECEIVABLE</div>
        <div class="metric-value">$31,240</div>
        <div class="metric-change">+5.2%</div>
        <div class="metric-timestamp">AS OF 08/31</div>
      </div>
    </div>

    <div class="metric-card card-3" data-depth="1.5">
      <div class="metric-card-inner" style="--card-delay: 1.0s">
        <div class="metric-label">BANK RECONCILIATION</div>
        <div class="metric-value">99.8%</div>
        <div class="metric-change">RECONCILED</div>
        <div class="metric-timestamp">08/31/2026</div>
      </div>
    </div>

    <div class="metric-card card-4" data-depth="2.5">
      <div class="metric-card-inner" style="--card-delay: 1.2s">
        <div class="metric-label">MONTHLY REVENUE</div>
        <div class="metric-value">$84,620</div>
        <div class="metric-change">+12.6%</div>
        <div class="metric-timestamp">AUGUST 2026</div>
      </div>
    </div>
  </div>
</section>

<!-- ========================================
     REMAINING SECTIONS (unchanged)
     ======================================== -->

<section id="about">
  <div class="container-narrow">
    <div class="section-label">
      <span class="label">01 / About</span>
    </div>
    <h2 class="section-headline reveal">A bookkeeper who treats every ledger like it's getting audited next quarter.</h2>
    <div class="prose-block reveal">
      <p>I'm a detail-oriented accounting professional based in Morrisville, North Carolina, with 3+ years of experience in AP/AR, bank reconciliation, journal entries, payroll support, and full-cycle bookkeeping across insurance, education, and multi-entity corporate environments. I've maintained multi-entity ledgers in Xero, managed international collections, and supported month-end and year-end closing accuracy.</p>
      <p>I'm a certified QuickBooks Online ProAdvisor, Xero Level 3 Specialist, and Oracle NetSuite Financial Associate, proficient in Tally, advanced Excel (XLOOKUP, PivotTables, SUMIFS, Power Query), and basic Power BI. I bring working knowledge of U.S. GAAP and accrual-basis accounting, with hands-on experience in month-end close, adjusting entries, payroll management, and financial statement preparation.</p>
      <p>I'm currently seeking an Accounting Assistant, Bookkeeper, Accounting Associate, or AP/AR role where accuracy and audit-ready recordkeeping are genuinely valued. The portfolio below is built from two self-directed Excel systems: a U.S. small business bookkeeping and month-end close build, and a U.S. payroll processing system.</p>
    </div>
  </div>
</section>

<section id="competencies">
  <div class="container">
    <div class="section-label">
      <span class="label">02 / Core competencies</span>
    </div>
    <h2 class="section-headline reveal">Six categories. Twenty-three tools. Zero spreadsheets I'm afraid of.</h2>
    <div class="competency-grid">
      <div class="competency">
        <h4>Accounting software</h4>
        <ul>
          <li>QuickBooks Online ProAdvisor</li>
          <li>Xero Certified Specialist L3</li>
          <li>Tally ERP / Prime</li>
          <li>Oracle NetSuite Financial Associate</li>
          <li>General ERP Systems</li>
        </ul>
      </div>
      <div class="competency">
        <h4>Finance & accounting</h4>
        <ul>
          <li>Accounts Payable & Receivable</li>
          <li>Bank Reconciliation</li>
          <li>Journal Entries & Ledger Maintenance</li>
          <li>Balance Confirmations</li>
          <li>Invoice / Payment / Purchase Vouchers</li>
          <li>Collections & Payroll Support</li>
        </ul>
      </div>
      <div class="competency">
        <h4>Banking & cash ops</h4>
        <ul>
          <li>Cheque Processing & Deposits</li>
          <li>Cash Withdrawals & Handling</li>
          <li>Fund Transfers</li>
          <li>Vendor Payment Coordination</li>
          <li>AR Collections & Follow-Up</li>
          <li>Bank Reconciliation</li>
        </ul>
      </div>
      <div class="competency">
        <h4>Document management</h4>
        <ul>
          <li>Financial Filing Systems</li>
          <li>Document Indexing & Organization</li>
          <li>Physical & Digital Recordkeeping</li>
          <li>Audit-Ready Documentation</li>
          <li>Records Retrieval for Audits</li>
        </ul>
      </div>
      <div class="competency">
        <h4>Data & productivity</h4>
        <ul>
          <li>Advanced Excel (XLOOKUP, SUMIFS)</li>
          <li>PivotTables & Power Query</li>
          <li>Basic Power BI</li>
          <li>Microsoft Office Suite</li>
          <li>Google Workspace</li>
        </ul>
      </div>
      <div class="competency">
        <h4>Professional & soft</h4>
        <ul>
          <li>Stakeholder Communication</li>
          <li>Confidentiality & Ethics</li>
          <li>Attention to Detail & Multitasking</li>
          <li>Deadline-Driven & Cross-Functional</li>
          <li>Adaptability</li>
          <li>English Communication (IELTS 7.5)</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="experience">
  <div class="container">
    <div class="section-label">
      <span class="label">03 / Professional experience</span>
    </div>
    <div class="sticky-pair">
      <div class="left">
        <h2 class="section-headline">Two roles. Multi-entity ledgers. One consistent record. Zero-discrepancy books and on-time closes.</h2>
        <p class="prose-side">From a college cashier window processing 1,500+ students to multi-entity Xero ledgers across Japan-facing operations and cross-border client accounts. Every position pushed accuracy further. The bullets on the right are the highlights; the supporting documentation is what I build as a matter of habit.</p>
      </div>
      <div class="right">
        <article class="timeline-item">
          <div class="timeline-meta">
            <span class="date">Mar 2025 to Jun 2026</span>
            <span class="location">IGC Business Holding · Kathmandu, Nepal</span>
          </div>
          <h3>Account Assistant</h3>
          <ul class="bullets">
            <li>Reconciled multi-entity ledgers in Xero across business verticals, including Japan-facing operations and cross-border client accounts, ensuring accurate monthly close.</li>
            <li>Managed AP/AR and international collections, recording and reconciling invoices and payments across subsidiary/brand units to keep balances current.</li>
            <li>Processed payroll and statutory deductions for over 50+ staff in coordination with the HR department, while managing VAT/TDS filings and supporting external auditors during periodic reviews.</li>
            <li>Consolidated financial data across business units into periodic summaries for management, supporting month-end and year-end closing accuracy.</li>
          </ul>
        </article>
        <article class="timeline-item">
          <div class="timeline-meta">
            <span class="date">Aug 2023 to Feb 2025</span>
            <span class="location">Trinity SS College · Kathmandu, Nepal</span>
          </div>
          <h3>Account Assistant</h3>
          <ul class="bullets">
            <li>Processed daily fee collections and billing for 1,500+ student accounts, issuing receipts and invoices through an institutional ERP system.</li>
            <li>Performed end-of-day cash balancing and reconciliation against ledger entries, maintaining zero-discrepancy records.</li>
            <li>Maintained audit-ready filing systems for fee ledgers and payment histories across 500+ active accounts.</li>
            <li>Assisted in payroll processing and statutory deductions for staff, coordinating closely with the HR department to ensure accurate, on-time disbursement.</li>
            <li>Coordinated front-office operations and drafted official correspondence, serving as liaison between students, faculty, and the finance office.</li>
          </ul>
        </article>
      </div>
    </div>
  </div>
</section>

<section id="projects">
  <div class="container">
    <div class="section-label">
      <span class="label">04 / Portfolio projects</span>
    </div>
    <h2 class="section-headline reveal">Two self-directed Excel systems. Each one could be opened by an auditor tomorrow morning.</h2>
    <div class="projects-grid">
      <a href="#case-payroll" class="project-card">
        <div class="num">PROJECT 01</div>
        <h3>U.S. Payroll Processing System</h3>
        <p>Built a bi-weekly U.S. payroll system covering employee setup, time tracking, and pay calculation with FICA, Medicare, and NC state tax withholding. Automated overtime, deductions, and benefits calculations, structuring the workbook for compliance and a clear audit trail.</p>
        <div class="arrow">View case study →</div>
      </a>
      <a href="#case-bookkeeping" class="project-card">
        <div class="num">PROJECT 02</div>
        <h3>U.S. Small Business Bookkeeping & Month-End Close System</h3>
        <p>Built a full-cycle small-business bookkeeping system covering chart of accounts, customer/vendor records, invoicing, AP/AR tracking, aging schedules, and cash transactions. Completed a simulated month-end close under accrual-basis U.S. GAAP.</p>
        <div class="arrow">View case study →</div>
      </a>
    </div>
  </div>
</section>

<section class="method">
  <div class="method-quote">
    <div class="quote-mark">"</div>
    <blockquote>
      Books should be quiet until they're asked a question. Then they should answer in <span class="accent">one number</span>, with a trail back to the source document.
    </blockquote>
    <cite>Working principle · every workbook in this portfolio</cite>
  </div>
</section>

<!-- CASE STUDY 01 — PAYROLL -->
<section class="case-study" id="case-payroll">
  <div class="container">
    <div class="case-header">
      <div><div class="case-number">CASE STUDY 01</div></div>
      <div><h2 class="case-title">U.S. Payroll Processing System</h2></div>
    </div>

    <div class="case-intro">
      <p>A bi-weekly U.S. payroll system built in a single Excel workbook, covering employee setup, time tracking, and pay calculation with FICA, Medicare, and North Carolina state tax withholding. The build reflects North Carolina state rules and automates overtime, deductions, and benefits calculations, structuring the workbook for compliance and a clear audit trail.</p>
      <div class="case-meta">
        <div><span class="label">Entity</span><span class="val">Riverstone Bookkeeping Demo LLC</span></div>
        <div><span class="label">Pay period</span><span class="val">08/03 to 08/16/2026</span></div>
        <div><span class="label">Pay date</span><span class="val">08/21/2026</span></div>
        <div><span class="label">Headcount</span><span class="val">8 active</span></div>
        <div><span class="label">Frequency</span><span class="val">Bi-weekly · 26 periods</span></div>
        <div><span class="label">State</span><span class="val">North Carolina</span></div>
      </div>
      <div class="tool-tags">
        <span class="tool-tag">Excel</span>
        <span class="tool-tag">FICA</span>
        <span class="tool-tag">Medicare</span>
        <span class="tool-tag">NC State Tax</span>
        <span class="tool-tag">SUTA</span>
        <span class="tool-tag">401(k)</span>
        <span class="tool-tag">Direct Deposit</span>
        <span class="tool-tag">Audit Trail</span>
      </div>
    </div>

    <div class="kpi-strip">
      <div class="kpi"><div class="val">$14,814</div><div class="lbl">Total gross payroll</div></div>
      <div class="kpi"><div class="val">$11,226</div><div class="lbl">Total net pay</div></div>
      <div class="kpi"><div class="val">$2,425</div><div class="lbl">Taxes withheld</div></div>
      <div class="kpi"><div class="val">$16,134</div><div class="lbl">Total employer cost</div></div>
    </div>

    <div class="charts-grid">
      <div class="chart-panel">
        <div class="chart-panel-header">
          <h4>Payroll cost breakdown</h4>
          <span class="meta">CURRENT PERIOD · USD</span>
        </div>
        <div class="chart-canvas-wrap"><canvas id="chart-payroll-breakdown"></canvas></div>
      </div>
      <div class="chart-panel">
        <div class="chart-panel-header">
          <h4>Gross pay by department</h4>
          <span class="meta">USD · 4 DEPARTMENTS</span>
        </div>
        <div class="chart-canvas-wrap"><canvas id="chart-payroll-dept"></canvas></div>
      </div>
      <div class="chart-panel">
        <div class="chart-panel-header">
          <h4>Top earners gross pay</h4>
          <span class="meta">TOP 5 · CURRENT PERIOD</span>
        </div>
        <div class="chart-canvas-wrap"><canvas id="chart-payroll-earners"></canvas></div>
      </div>
      <div class="chart-panel">
        <div class="chart-panel-header">
          <h4>Headcount composition</h4>
          <span class="meta">8 EMPLOYEES · 2 TYPES</span>
        </div>
        <div class="chart-canvas-wrap"><canvas id="chart-payroll-headcount"></canvas></div>
      </div>
    </div>

    <div class="ledger-wrap">
      <h3 class="block-title">Tax withholding current pay period</h3>
      <table class="ledger-table">
        <thead>
          <tr>
            <th>Emp ID</th><th>Employee</th><th class="amount">Gross</th><th class="amount">Fed Income Tax</th><th class="amount">Soc. Sec. (6.2%)</th><th class="amount">Medicare (1.45%)</th><th class="amount">NC State (4.25%)</th><th class="amount">Total Withheld</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>EMP-001</td><td>Maria Gonzalez</td><td class="amount">$2,400.00</td><td class="amount">$214.19</td><td class="amount">$148.80</td><td class="amount">$34.80</td><td class="amount">$102.00</td><td class="amount">$499.79</td></tr>
          <tr><td>EMP-002</td><td>David Chen</td><td class="amount">$2,000.00</td><td class="amount">$10.77</td><td class="amount">$124.00</td><td class="amount">$29.00</td><td class="amount">$85.00</td><td class="amount">$248.77</td></tr>
          <tr><td>EMP-003</td><td>Angela Brooks</td><td class="amount">$1,845.00</td><td class="amount">$170.09</td><td class="amount">$114.39</td><td class="amount">$26.75</td><td class="amount">$78.41</td><td class="amount">$389.65</td></tr>
          <tr><td>EMP-004</td><td>Marcus Reed</td><td class="amount">$2,158.00</td><td class="amount">$29.42</td><td class="amount">$133.80</td><td class="amount">$31.29</td><td class="amount">$91.72</td><td class="amount">$286.22</td></tr>
          <tr><td>EMP-005</td><td>Priya Nair</td><td class="amount">$1,200.00</td><td class="amount">$67.69</td><td class="amount">$74.40</td><td class="amount">$17.40</td><td class="amount">$51.00</td><td class="amount">$210.49</td></tr>
          <tr><td>EMP-006</td><td>Samuel Osei</td><td class="amount">$2,615.38</td><td class="amount">$7.38</td><td class="amount">$162.15</td><td class="amount">$37.92</td><td class="amount">$111.15</td><td class="amount">$318.62</td></tr>
          <tr><td>EMP-007</td><td>Rachel Kim</td><td class="amount">$1,782.00</td><td class="amount">$137.53</td><td class="amount">$110.48</td><td class="amount">$25.84</td><td class="amount">$75.74</td><td class="amount">$349.59</td></tr>
          <tr><td>EMP-008</td><td>Tyler Brooks</td><td class="amount">$814.00</td><td class="amount">$25.25</td><td class="amount">$50.47</td><td class="amount">$11.80</td><td class="amount">$34.60</td><td class="amount">$122.11</td></tr>
          <tr class="total"><td colspan="2">TOTALS</td><td class="amount">$14,814.38</td><td class="amount">$662.33</td><td class="amount">$918.49</td><td class="amount">$214.81</td><td class="amount">$629.61</td><td class="amount">$2,425.24</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</section>

<!-- CASE STUDY 02 — BOOKKEEPING & CLOSE -->
<section class="case-study" id="case-bookkeeping">
  <div class="container">
    <div class="case-header">
      <div><div class="case-number">CASE STUDY 02</div></div>
      <div><h2 class="case-title">U.S. Small Business Bookkeeping & Month-End Close System</h2></div>
    </div>

    <div class="case-intro">
      <p>A full-cycle bookkeeping system for a single-member LLC providing outsourced bookkeeping services. The workbook covers chart of accounts setup, customer and vendor master lists, sales invoicing, vendor bill entry, AP/AR subledgers, bank reconciliation, aging reports, and a YTD P&L. It also completes a full simulated month-end close under accrual-basis U.S. GAAP including adjusted trial balance, income statement, balance sheet, close checklist, and management close report.</p>
      <div class="case-meta">
        <div><span class="label">Entity</span><span class="val">Riverstone Bookkeeping Demo LLC</span></div>
        <div><span class="label">Period</span><span class="val">06/01 to 08/31/2026</span></div>
        <div><span class="label">Method</span><span class="val">Accrual / U.S. GAAP</span></div>
        <div><span class="label">Currency</span><span class="val">USD</span></div>
        <div><span class="label">Customers</span><span class="val">8</span></div>
        <div><span class="label">Vendors</span><span class="val">8</span></div>
      </div>
      <div class="tool-tags">
        <span class="tool-tag">Excel</span>
        <span class="tool-tag">Chart of Accounts</span>
        <span class="tool-tag">Invoicing</span>
        <span class="tool-tag">AP / AR</span>
        <span class="tool-tag">Aging</span>
        <span class="tool-tag">Bank Rec</span>
        <span class="tool-tag">Adjusting JEs</span>
        <span class="tool-tag">U.S. GAAP</span>
      </div>
    </div>

    <div class="kpi-strip">
      <div class="kpi"><div class="val">$25,235</div><div class="lbl">Total revenue YTD</div></div>
      <div class="kpi"><div class="val">$14,872</div><div class="lbl">Net income YTD</div></div>
      <div class="kpi"><div class="val">$17,141</div><div class="lbl">AR outstanding</div></div>
      <div class="kpi"><div class="val">$4,574</div><div class="lbl">AP outstanding</div></div>
    </div>

    <div class="charts-grid">
      <div class="chart-panel">
        <div class="chart-panel-header">
          <h4>Revenue vs expenses (YTD)</h4>
          <span class="meta">JUN to AUG 2026 · USD</span>
        </div>
        <div class="chart-canvas-wrap"><canvas id="chart-bookkeeping-pl"></canvas></div>
      </div>
      <div class="chart-panel">
        <div class="chart-panel-header">
          <h4>AR aging by bucket</h4>
          <span class="meta">AS OF 08/15/2026</span>
        </div>
        <div class="chart-canvas-wrap"><canvas id="chart-ar-aging"></canvas></div>
      </div>
      <div class="chart-panel">
        <div class="chart-panel-header">
          <h4>AP aging by bucket</h4>
          <span class="meta">AS OF 08/15/2026</span>
        </div>
        <div class="chart-canvas-wrap"><canvas id="chart-ap-aging"></canvas></div>
      </div>
      <div class="chart-panel">
        <div class="chart-panel-header">
          <h4>Bank reconciliation summary</h4>
          <span class="meta">OPERATING · 08/15/2026</span>
        </div>
        <div class="chart-canvas-wrap"><canvas id="chart-bank-rec"></canvas></div>
      </div>
    </div>

    <div class="ledger-wrap">
      <h3 class="block-title">Top customers by balance due</h3>
      <table class="ledger-table">
        <thead>
          <tr><th>Customer</th><th class="amount">Total Invoiced</th><th class="amount">Total Paid</th><th class="amount">Balance Due</th><th class="amount">Open Inv.</th><th>Oldest Due</th></tr>
        </thead>
        <tbody>
          <tr><td>Northgate Retail Group</td><td class="amount">$7,668.38</td><td class="amount">$2,000.00</td><td class="amount">$5,668.38</td><td class="amount">2</td><td>08/15/2026</td></tr>
          <tr><td>Summit Ridge Contractors</td><td class="amount">$6,756.75</td><td class="amount">$3,500.00</td><td class="amount">$3,256.75</td><td class="amount">2</td><td>06/25/2026</td></tr>
          <tr><td>Ironworks Fitness Studio</td><td class="amount">$3,432.00</td><td class="amount">$—</td><td class="amount">$3,432.00</td><td class="amount">1</td><td>07/18/2026</td></tr>
          <tr><td>GreenLeaf Landscaping</td><td class="amount">$2,788.50</td><td class="amount">$950.00</td><td class="amount">$1,838.50</td><td class="amount">2</td><td>07/20/2026</td></tr>
          <tr><td>Bluebird Cafe & Bakery</td><td class="amount">$2,400.00</td><td class="amount">$1,200.00</td><td class="amount">$1,200.00</td><td class="amount">1</td><td>08/07/2026</td></tr>
          <tr><td>Coastal Wellness Spa</td><td class="amount">$2,252.25</td><td class="amount">$2,100.00</td><td class="amount">$152.25</td><td class="amount">1</td><td>08/11/2026</td></tr>
          <tr><td>Willow Creek Realty</td><td class="amount">$938.44</td><td class="amount">$—</td><td class="amount">$938.44</td><td class="amount">1</td><td>08/24/2026</td></tr>
          <tr><td>Pinecrest Veterinary Clinic</td><td class="amount">$654.23</td><td class="amount">$—</td><td class="amount">$654.23</td><td class="amount">1</td><td>08/16/2026</td></tr>
          <tr class="total"><td colspan="3">TOTAL AR</td><td class="amount">$17,140.54</td><td class="amount">11</td><td>—</td></tr>
        </tbody>
      </table>
    </div>

    <div class="ledger-wrap">
      <h3 class="block-title">Profit & Loss YTD (06/01 to 08/15/2026)</h3>
      <table class="ledger-table">
        <thead><tr><th>Account</th><th class="amount">Amount</th></tr></thead>
        <tbody>
          <tr><td>Sales Income</td><td class="amount">$13,560.00</td></tr>
          <tr><td>Service Income</td><td class="amount">$11,675.00</td></tr>
          <tr class="subtotal"><td>Total Revenue</td><td class="amount">$25,235.00</td></tr>
          <tr><td>Cost of Goods Sold</td><td class="amount">$—</td></tr>
          <tr class="subtotal"><td>Gross Profit</td><td class="amount">$25,235.00</td></tr>
          <tr><td>Rent Expense</td><td class="amount">$6,600.00</td></tr>
          <tr><td>Marketing & Advertising</td><td class="amount">$1,500.00</td></tr>
          <tr><td>Insurance Expense</td><td class="amount">$675.00</td></tr>
          <tr><td>Utilities Expense</td><td class="amount">$705.00</td></tr>
          <tr><td>Professional Fees</td><td class="amount">$450.00</td></tr>
          <tr><td>Office Supplies Expense</td><td class="amount">$210.00</td></tr>
          <tr><td>Software Subscriptions</td><td class="amount">$178.00</td></tr>
          <tr><td>Bank Fees & Charges</td><td class="amount">$45.00</td></tr>
          <tr class="subtotal"><td>Total Operating Expenses</td><td class="amount">$10,363.00</td></tr>
          <tr class="total"><td>NET INCOME</td><td class="amount">$14,872.00</td></tr>
        </tbody>
      </table>
    </div>

    <div class="kpi-strip">
      <div class="kpi"><div class="val">$55,500</div><div class="lbl">Total revenue (Aug)</div></div>
      <div class="kpi"><div class="val">$34,005</div><div class="lbl">Operating expenses</div></div>
      <div class="kpi"><div class="val">$21,495</div><div class="lbl">Net income</div></div>
      <div class="kpi"><div class="val">$111,230</div><div class="lbl">Total assets</div></div>
    </div>

    <div class="charts-grid">
      <div class="chart-panel">
        <div class="chart-panel-header">
          <h4>Income statement composition</h4>
          <span class="meta">AUG 2026 · USD</span>
        </div>
        <div class="chart-canvas-wrap"><canvas id="chart-close-is"></canvas></div>
      </div>
      <div class="chart-panel">
        <div class="chart-panel-header">
          <h4>Adjusting journal entries by amount</h4>
          <span class="meta">8 ENTRIES · $10,580 TOTAL</span>
        </div>
        <div class="chart-canvas-wrap"><canvas id="chart-close-aje"></canvas></div>
      </div>
      <div class="chart-panel">
        <div class="chart-panel-header">
          <h4>Balance sheet composition</h4>
          <span class="meta">AS OF 08/31/2026</span>
        </div>
        <div class="chart-canvas-wrap"><canvas id="chart-close-bs"></canvas></div>
      </div>
      <div class="chart-panel">
        <div class="chart-panel-header">
          <h4>Operating expense breakdown</h4>
          <span class="meta">USD · 9 ACCOUNTS</span>
        </div>
        <div class="chart-canvas-wrap"><canvas id="chart-close-opex"></canvas></div>
      </div>
    </div>

    <div class="ledger-wrap">
      <h3 class="block-title">Adjusting journal entries August 31, 2026</h3>
      <table class="ledger-table">
        <thead>
          <tr><th>JE #</th><th>Acct #</th><th>Account</th><th class="amount">Debit</th><th class="amount">Credit</th><th>Description</th></tr>
        </thead>
        <tbody>
          <tr><td>AJE-1</td><td>5600</td><td>Bank Fees Expense</td><td class="amount">$45.00</td><td class="amount">—</td><td>Bank service charges per August statement</td></tr>
          <tr><td>AJE-1</td><td>1010</td><td>Cash Operating Checking</td><td class="amount">—</td><td class="amount">$45.00</td><td>Bank service charges per August statement</td></tr>
          <tr><td>AJE-2</td><td>5000</td><td>Salaries & Wages Expense</td><td class="amount">$3,850.00</td><td class="amount">—</td><td>Accrue wages Aug 26 to 31, paid Sept 5</td></tr>
          <tr><td>AJE-2</td><td>2300</td><td>Wages Payable</td><td class="amount">—</td><td class="amount">$3,850.00</td><td>Accrue wages Aug 26 to 31, paid Sept 5</td></tr>
          <tr><td>AJE-3</td><td>5200</td><td>Utilities Expense</td><td class="amount">$610.00</td><td class="amount">—</td><td>Accrue August electricity/internet</td></tr>
          <tr><td>AJE-3</td><td>2310</td><td>Utilities Payable (Accrued Liab.)</td><td class="amount">—</td><td class="amount">$610.00</td><td>Accrue August electricity/internet</td></tr>
          <tr><td>AJE-4</td><td>5400</td><td>Insurance Expense</td><td class="amount">$600.00</td><td class="amount">—</td><td>Amortize 1 of 12 months, $7,200 policy</td></tr>
          <tr><td>AJE-4</td><td>1410</td><td>Prepaid Insurance</td><td class="amount">—</td><td class="amount">$600.00</td><td>Amortize 1 of 12 months, $7,200 policy</td></tr>
          <tr><td>AJE-5</td><td>5500</td><td>Depreciation Expense</td><td class="amount">$600.00</td><td class="amount">—</td><td>Straight-line, $36k / 5yr / 12mo</td></tr>
          <tr><td>AJE-5</td><td>1510</td><td>Accum. Depreciation Equipment</td><td class="amount">—</td><td class="amount">$600.00</td><td>Straight-line, $36k / 5yr / 12mo</td></tr>
          <tr><td>AJE-6</td><td>2200</td><td>Unearned Revenue</td><td class="amount">$3,200.00</td><td class="amount">—</td><td>Recognize August retainer earned</td></tr>
          <tr><td>AJE-6</td><td>4000</td><td>Bookkeeping Service Revenue</td><td class="amount">—</td><td class="amount">$3,200.00</td><td>Recognize August retainer earned</td></tr>
          <tr><td>AJE-7</td><td>2010</td><td>Accounts Payable</td><td class="amount">$475.00</td><td class="amount">—</td><td>Correct duplicate Office Depot posting</td></tr>
          <tr><td>AJE-7</td><td>5300</td><td>Office Supplies Expense</td><td class="amount">—</td><td class="amount">$475.00</td><td>Correct duplicate Office Depot posting</td></tr>
          <tr><td>AJE-8</td><td>5800</td><td>Bad Debt Expense</td><td class="amount">$1,200.00</td><td class="amount">—</td><td>Write off Cedar Grove Cafe Inv #1042</td></tr>
          <tr><td>AJE-8</td><td>1200</td><td>Accounts Receivable</td><td class="amount">—</td><td class="amount">$1,200.00</td><td>Write off Cedar Grove Cafe Inv #1042</td></tr>
          <tr class="total"><td colspan="3">TOTALS</td><td class="amount">$10,580.00</td><td class="amount">$10,580.00</td><td>8 entries · 16 posting lines</td></tr>
        </tbody>
      </table>
    </div>

    <div>
      <h3 class="block-title">Bank reconciliation Operating Checking, 08/31/2026</h3>
      <div class="bank-rec-grid">
        <div class="bank-rec-side">
          <h4>Bank side</h4>
          <table class="ledger-table" style="border: none;">
            <tbody>
              <tr><td>Balance per bank statement, 8/31</td><td class="amount">$45,780.00</td></tr>
              <tr><td>Add: Deposits in transit (2)</td><td class="amount">$3,200.00</td></tr>
              <tr><td>Less: Outstanding checks (3)</td><td class="amount">($2,150.00)</td></tr>
              <tr class="total"><td>Adjusted bank balance</td><td class="amount">$46,830.00</td></tr>
            </tbody>
          </table>
        </div>
        <div class="bank-rec-side">
          <h4>Book side</h4>
          <table class="ledger-table" style="border: none;">
            <tbody>
              <tr><td>Balance per general ledger, 8/31</td><td class="amount">$46,875.00</td></tr>
              <tr><td>Less: Bank service charges</td><td class="amount">($45.00)</td></tr>
              <tr class="total"><td>Adjusted book balance</td><td class="amount">$46,830.00</td></tr>
              <tr class="total"><td>Difference (reconciled)</td><td class="amount">$0.00</td></tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>

    <div class="close-memo">
      <span class="label label-accent">CLOSE REPORT EXCERPT · SEPTEMBER 5, 2026</span>
      <p>August was a clean, on-time close. The bank reconciliation tied out with no unexplained variances; eight adjusting entries totaling $10,580.00 were booked to properly match revenue and expenses to the period. Two exceptions surfaced during subledger review: a duplicate AP invoice and one uncollectible AR balance. Both were investigated, corrected, and are documented below.</p>
      <div class="memo-footer">
        <div><span class="label">Bank</span><span class="val">Reconciled · $0.00 variance</span></div>
        <div><span class="label">AP</span><span class="val">Corrected $475 duplicate invoice</span></div>
        <div><span class="label">AR</span><span class="val">Wrote off $1,200 uncollectible</span></div>
        <div><span class="label">Status</span><span class="val">Complete · Approved</span></div>
      </div>
    </div>
  </div>
</section>

<section id="education">
  <div class="container">
    <div class="section-label">
      <span class="label">05 / Education & Certifications</span>
    </div>
    <div class="sticky-pair">
      <div class="left">
        <h2 class="section-headline">Trained on the fundamentals. Certified on the tools that pay.</h2>
        <p class="prose-side">A high school management diploma and three current accounting certifications. The academic foundation plus the credentials that let an employer hand over the books without a long ramp up.</p>
      </div>
      <div class="right">
        <div class="sub-headline no-border">Certifications</div>
        <article class="row">
          <div class="row-label">2026 · INTUIT</div>
          <div class="row-content">
            <h3>QuickBooks Online Accountant ProAdvisor Certification</h3>
            <p>Issued June 2026. Full QuickBooks Online Accountant suite, including chart of accounts setup, bank feeds, AP/AR workflows, payroll, reconciliation, and reporting.</p>
          </div>
        </article>
        <article class="row">
          <div class="row-label">2026 · XERO</div>
          <div class="row-content">
            <h3>Xero Certified Specialist Level 3 (Score: 96)</h3>
            <p>Issued August 2026. Highest Xero certification tier covering advanced bank reconciliation, foreign currency, fixed assets, projects, and advisor reporting.</p>
          </div>
        </article>
        <article class="row">
          <div class="row-label">2026 · ORACLE</div>
          <div class="row-content">
            <h3>Oracle NetSuite Certified Financial Associate</h3>
            <p>Issued August 2026. Foundational NetSuite financials including GL, AP, AR, multi-subsidiary, and period-close workflows.</p>
          </div>
        </article>
        <article class="row">
          <div class="row-label">2022 · IELTS</div>
          <div class="row-content">
            <h3>IELTS Academic Band 7.5</h3>
            <p>Overall band 7.5 on the academic module. Fluent professional English across written, spoken, and audit correspondence contexts.</p>
          </div>
        </article>
        <div class="sub-headline">Education</div>
        <article class="row">
          <div class="row-label">2019 to 2021 · HIGH SCHOOL</div>
          <div class="row-content">
            <h3>High School Diploma in Management (GPA 3.46 / 4.0)</h3>
            <p>Chanakya College of Management, Bhaktapur. Main subjects: Accounting, Economics, Business Mathematics, and Computer Science.</p>
          </div>
        </article>
      </div>
    </div>
  </div>
</section>

<section id="languages">
  <div class="container">
    <div class="section-label">
      <span class="label">06 / Languages</span>
    </div>
    <div class="sticky-pair">
      <div class="left">
        <h2 class="section-headline">Two languages. One native, one fluent at academic band 7.5.</h2>
        <p class="prose-side">Vendor correspondence, audit follow-up, and management reporting all happen in English; local stakeholder coordination happens in Nepali. Both are working languages, not line items on a CV.</p>
      </div>
      <div class="right">
        <div class="lang-grid">
          <div class="lang-cell">
            <div class="label">NATIVE</div>
            <div class="lang-name">Nepali</div>
            <p>First language. Used in all local stakeholder communication across college finance, multi-entity corporate operations, and remote coordination.</p>
          </div>
          <div class="lang-cell">
            <div class="label">FLUENT · IELTS 7.5</div>
            <div class="lang-name">English</div>
            <p>Overall band 7.5 on IELTS Academic. Comfortable in vendor correspondence, audit follow-up, and management reporting.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="contact" id="contact">
  <div class="container">
    <div class="label">07 / Get in touch</div>
    <h2>Let's talk<br>about your<span class="accent"> books.</span></h2>
    <p class="lead">Seeking an Accounting Assistant, Bookkeeper, Accounting Associate, or AP/AR role. The fastest reply is email; I usually respond within a working day.</p>
    <div class="contact-grid">
      <a href="mailto:biraj0864@gmail.com" class="contact-item">
        <div class="lbl">Email</div>
        <div class="val">biraj0864@gmail.com</div>
      </a>
      <a href="tel:+9779749840852" class="contact-item">
        <div class="lbl">Phone</div>
        <div class="val">+977 9749840852</div>
      </a>
      <div class="contact-item">
        <div class="lbl">Location</div>
        <div class="val">Morrisville, NC</div>
      </div>
      <div class="contact-item">
        <div class="lbl">Work Authorization</div>
        <div class="val">US Permanent Resident</div>
      </div>
    </div>
  </div>
</section>

<footer class="bottom">
  <div>© 2026 BIRAJ THAPA<span class="accent">.</span> MORRISVILLE, NC</div>
  <div>BUILT IN EXCEL · QUICKBOOKS · XERO · NETSUITE</div>
</footer>

<script>
// ---------- Lenis smooth scroll ----------
const lenis = new Lenis({
  duration: 1.1,
  easing: t => Math.min(1, 1.001 - Math.pow(2, -10 * t))
});
function raf(time) { lenis.raf(time); requestAnimationFrame(raf); }
requestAnimationFrame(raf);

// ---------- Reveal observer ----------
const revealObs = new IntersectionObserver((entries) => {
  entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('is-in'); revealObs.unobserve(e.target); } });
}, { threshold: 0.15 });
document.querySelectorAll('.reveal').forEach(el => revealObs.observe(el));

// ---------- Glyph rain background ----------
const rain = document.querySelector('.glyph-rain');
const rainCtx = rain.getContext('2d');
let cols, drops;
const CHARS = '$0123456789$%+-.';
function resizeRain() {
  rain.width = innerWidth;
  rain.height = innerHeight;
  cols = Math.floor(rain.width / 18);
  drops = Array.from({ length: cols }, () => Math.random() * -rain.height);
}
resizeRain();
addEventListener('resize', resizeRain);

const reduceMotion = matchMedia('(prefers-reduced-motion: reduce)').matches;
function rainFrame() {
  if (reduceMotion) return;
  rainCtx.fillStyle = 'rgba(8,8,8,0.08)';
  rainCtx.fillRect(0, 0, rain.width, rain.height);
  rainCtx.font = '12px "JetBrains Mono", monospace';
  drops.forEach((y, i) => {
    const x = i * 18;
    const bright = Math.random() < 0.015;
    rainCtx.fillStyle = bright ? 'rgba(163,196,122,0.6)' : 'rgba(163,196,122,0.2)';
    rainCtx.fillText(CHARS[Math.floor(Math.random() * CHARS.length)], x, y);
    drops[i] = y > rain.height && Math.random() > 0.975 ? 0 : y + 11;
  });
  requestAnimationFrame(rainFrame);
}
if (!reduceMotion) rainFrame();

// ---------- Hero dashboard parallax ----------
const hero = document.querySelector('.hero');
const metricCards = document.querySelectorAll('.metric-card');
let parallaxEnabled = false;

function checkParallax() {
  parallaxEnabled = window.innerWidth > 900 && !reduceMotion;
}
checkParallax();
window.addEventListener('resize', checkParallax);

hero.addEventListener('mousemove', (e) => {
  if (!parallaxEnabled) return;
  const rect = hero.getBoundingClientRect();
  const x = (e.clientX - rect.left) / rect.width - 0.5;
  const y = (e.clientY - rect.top) / rect.height - 0.5;

  metricCards.forEach(card => {
    const depth = parseFloat(card.dataset.depth) || 1;
    card.style.transform = `translate(${x * depth * 5}px, ${y * depth * 5}px)`;
  });
});

hero.addEventListener('mouseleave', () => {
  metricCards.forEach(card => { card.style.transform = ''; });
});

// ---------- Case study charts ----------
Chart.defaults.color = '#888';
Chart.defaults.font.family = '"JetBrains Mono", monospace';
Chart.defaults.font.size = 10;
Chart.defaults.borderColor = 'rgba(255,255,255,0.06)';

const ACCENT = '#a3c47a';
const ACCENT_TRANS = 'rgba(163,196,122,0.6)';
const PALETTE = [
  ACCENT,
  'rgba(163,196,122,0.7)',
  'rgba(163,196,122,0.45)',
  'rgba(163,196,122,0.25)',
  'rgba(163,196,122,0.12)'
];

function chartOpts(extra = {}) {
  return Object.assign({
    responsive: true,
    maintainAspectRatio: false,
    plugins: { legend: { display: false }, tooltip: { enabled: false } },
    animation: { duration: 900, easing: 'easeOutQuart' },
    scales: {
      x: { grid: { color: 'rgba(255,255,255,0.04)', drawBorder: false }, ticks: { color: '#888', font: { size: 9 } } },
      y: { grid: { color: 'rgba(255,255,255,0.04)', drawBorder: false }, ticks: { color: '#888', font: { size: 9 } } }
    }
  }, extra);
}

// Payroll charts
new Chart(document.getElementById('chart-payroll-breakdown'), {
  type: 'doughnut',
  data: {
    labels: ['Net Pay $11,226', 'Emp. Taxes $2,425', 'Emp. Deductions $1,163', 'Employer FICA+SUTA $1,320'],
    datasets: [{
      data: [11226, 2425, 1163, 1320],
      backgroundColor: [ACCENT, 'rgba(163,196,122,0.65)', 'rgba(163,196,122,0.4)', 'rgba(163,196,122,0.22)'],
      borderColor: '#080808',
      borderWidth: 2
    }]
  },
  options: chartOpts({
    cutout: '58%',
    plugins: {
      legend: { display: true, position: 'bottom', labels: { color: '#dadada', font: { size: 10, family: 'JetBrains Mono' }, padding: 14, boxWidth: 10 } },
      tooltip: { enabled: true, backgroundColor: '#080808', borderColor: '#a3c47a', borderWidth: 1 }
    },
    scales: {}
  })
});

new Chart(document.getElementById('chart-payroll-dept'), {
  type: 'bar',
  data: {
    labels: ['Operations', 'Accounting', 'Client Services', 'Administration'],
    datasets: [{ data: [3214, 4615, 5785, 1200], backgroundColor: ACCENT_TRANS, borderColor: ACCENT, borderWidth: 1 }]
  },
  options: chartOpts({
    scales: {
      x: { grid: { display: false }, ticks: { color: '#888' } },
      y: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#888', callback: v => '$' + v.toLocaleString() } }
    }
  })
});

new Chart(document.getElementById('chart-payroll-earners'), {
  type: 'bar',
  data: {
    labels: ['Samuel Osei', 'Maria Gonzalez', 'Marcus Reed', 'David Chen', 'Angela Brooks'],
    datasets: [{ data: [2615, 2400, 2158, 2000, 1845], backgroundColor: ACCENT_TRANS, borderColor: ACCENT, borderWidth: 1 }]
  },
  options: chartOpts({
    indexAxis: 'y',
    scales: {
      x: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#888', callback: v => '$' + v.toLocaleString() } },
      y: { grid: { display: false }, ticks: { color: '#888' } }
    }
  })
});

new Chart(document.getElementById('chart-payroll-headcount'), {
  type: 'bar',
  data: {
    labels: ['Salary', 'Hourly'],
    datasets: [{ data: [3, 5], backgroundColor: [ACCENT, 'rgba(163,196,122,0.4)'], borderColor: ACCENT, borderWidth: 1 }]
  },
  options: chartOpts({
    scales: {
      x: { grid: { display: false }, ticks: { color: '#888' } },
      y: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#888', stepSize: 1 } }
    }
  })
});

// Bookkeeping & Close charts
new Chart(document.getElementById('chart-bookkeeping-pl'), {
  type: 'bar',
  data: {
    labels: ['Total Revenue', 'COGS', 'Operating Exp.', 'Net Income'],
    datasets: [{ data: [25235, 0, 10363, 14872], backgroundColor: [ACCENT, 'rgba(163,196,122,0.1)', 'rgba(163,196,122,0.4)', 'rgba(163,196,122,0.7)'], borderColor: ACCENT, borderWidth: 1 }]
  },
  options: chartOpts({
    scales: {
      x: { grid: { display: false }, ticks: { color: '#888' } },
      y: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#888', callback: v => '$' + (v / 1000) + 'k' } }
    }
  })
});

new Chart(document.getElementById('chart-ar-aging'), {
  type: 'bar',
  data: {
    labels: ['Current', '1 to 30 Days', '31 to 60 Days', '61 to 90 Days', '90+ Days'],
    datasets: [{ data: [12034, 4853, 254, 0, 0], backgroundColor: PALETTE, borderColor: ACCENT, borderWidth: 1 }]
  },
  options: chartOpts({
    scales: {
      x: { grid: { display: false }, ticks: { color: '#888' } },
      y: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#888', callback: v => '$' + (v / 1000) + 'k' } }
    }
  })
});

new Chart(document.getElementById('chart-ap-aging'), {
  type: 'bar',
  data: {
    labels: ['Current', '1 to 30 Days', '31 to 60 Days', '61 to 90 Days', '90+ Days'],
    datasets: [{ data: [675, 3899, 0, 0, 0], backgroundColor: PALETTE, borderColor: ACCENT, borderWidth: 1 }]
  },
  options: chartOpts({
    scales: {
      x: { grid: { display: false }, ticks: { color: '#888' } },
      y: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#888', callback: v => '$' + (v / 1000) + 'k' } }
    }
  })
});

new Chart(document.getElementById('chart-bank-rec'), {
  type: 'bar',
  data: {
    labels: ['Bank Bal.', '+ Deposits', '− Checks', 'Adj. Bank', 'Book Bal.', '− Fees', 'Adj. Book', 'Diff.'],
    datasets: [{
      data: [24850, 2800, -1450, 26200, 26233, -45, 26200, 0],
      backgroundColor: ['rgba(163,196,122,0.3)', 'rgba(163,196,122,0.5)', 'rgba(163,196,122,0.18)', ACCENT, 'rgba(163,196,122,0.3)', 'rgba(163,196,122,0.18)', ACCENT, ACCENT],
      borderColor: ACCENT, borderWidth: 1
    }]
  },
  options: chartOpts({
    scales: {
      x: { grid: { display: false }, ticks: { color: '#888', font: { size: 8 }, maxRotation: 0, autoSkip: false } },
      y: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#888', callback: v => '$' + (v / 1000) + 'k' } }
    }
  })
});

new Chart(document.getElementById('chart-close-is'), {
  type: 'doughnut',
  data: {
    labels: ['Net Income $21,495', 'Operating Expenses $34,005'],
    datasets: [{
      data: [21495, 34005],
      backgroundColor: [ACCENT, 'rgba(163,196,122,0.3)'],
      borderColor: '#080808',
      borderWidth: 2
    }]
  },
  options: chartOpts({
    cutout: '58%',
    plugins: { legend: { display: true, position: 'bottom', labels: { color: '#dadada', font: { size: 10, family: 'JetBrains Mono' }, padding: 14, boxWidth: 10 } } },
    scales: {}
  })
});

new Chart(document.getElementById('chart-close-aje'), {
  type: 'bar',
  data: {
    labels: ['AJE 1 Bank Fees', 'AJE 2 Wages', 'AJE 3 Utilities', 'AJE 4 Insurance', 'AJE 5 Deprec.', 'AJE 6 Unearned Rev.', 'AJE 7 AP Corr.', 'AJE 8 Bad Debt'],
    datasets: [{ data: [45, 3850, 610, 600, 600, 3200, 475, 1200], backgroundColor: ACCENT_TRANS, borderColor: ACCENT, borderWidth: 1 }]
  },
  options: chartOpts({
    scales: {
      x: { grid: { display: false }, ticks: { color: '#888', font: { size: 8 }, maxRotation: 45, minRotation: 45, autoSkip: false } },
      y: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#888', callback: v => '$' + v.toLocaleString() } }
    }
  })
});

new Chart(document.getElementById('chart-close-bs'), {
  type: 'doughnut',
  data: {
    labels: ['Liabilities $24,635', 'Common Stock $25,000', 'Retained Earnings $40,100', 'Net Income $21,495'],
    datasets: [{
      data: [24635, 25000, 40100, 21495],
      backgroundColor: ['rgba(163,196,122,0.22)', ACCENT, 'rgba(163,196,122,0.5)', 'rgba(163,196,122,0.7)'],
      borderColor: '#080808',
      borderWidth: 2
    }]
  },
  options: chartOpts({
    cutout: '58%',
    plugins: { legend: { display: true, position: 'bottom', labels: { color: '#dadada', font: { size: 10, family: 'JetBrains Mono' }, padding: 14, boxWidth: 10 } } },
    scales: {}
  })
});

new Chart(document.getElementById('chart-close-opex'), {
  type: 'bar',
  data: {
    labels: ['Salaries & Wages', 'Rent', 'Bad Debt', 'Misc.', 'Office Supplies', 'Utilities', 'Insurance', 'Depreciation', 'Bank Fees'],
    datasets: [{ data: [25250, 4200, 1200, 825, 675, 610, 600, 600, 45], backgroundColor: ACCENT_TRANS, borderColor: ACCENT, borderWidth: 1 }]
  },
  options: chartOpts({
    indexAxis: 'y',
    scales: {
      x: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#888', callback: v => '$' + (v / 1000) + 'k' } },
      y: { grid: { display: false }, ticks: { color: '#888', font: { size: 9 } } }
    }
  })
});

// ---------- Smooth anchor scrolling ----------
document.querySelectorAll('a[href^="#"]').forEach(a => {
  a.addEventListener('click', (e) => {
    const id = a.getAttribute('href');
    if (id.length > 1) {
      const el = document.querySelector(id);
      if (el) {
        e.preventDefault();
        lenis.scrollTo(el, { offset: -80, duration: 1.2 });
      }
    }
  });
});
</script>
</body>
</html>
