<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Planilha de Controle Financeiro | Investidor da Roça</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Sora:wght@300;400;600;700;800&family=DM+Serif+Display:ital@0;1&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
<style>
/* ─── TOKENS ──────────────────────────────────────────────────── */
:root {
  --ink:       #0C1A0E;
  --leaf:      #1B5E20;
  --lime:      #2ECC71;
  --lime-dim:  #A5D6A7;
  --soil:      #3E2723;
  --cream:     #F5F2EB;
  --fog:       #C8D5CA;
  --red:       #C62828;
  --gold:      #F9A825;
  --paper:     #FAFAF7;

  --f-display: 'DM Serif Display', Georgia, serif;
  --f-body:    'Sora', system-ui, sans-serif;
  --f-mono:    'JetBrains Mono', monospace;
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { scroll-behavior: smooth; }

body {
  font-family: var(--f-body);
  background: var(--paper);
  color: var(--ink);
  overflow-x: hidden;
  -webkit-font-smoothing: antialiased;
}

/* ─── SHARED ──────────────────────────────────────────────────── */
.container { max-width: 960px; margin: 0 auto; padding: 0 24px; }

.tag {
  display: inline-block;
  font-family: var(--f-mono);
  font-size: 11px;
  letter-spacing: .12em;
  text-transform: uppercase;
  padding: 5px 14px;
  border-radius: 2px;
  font-weight: 700;
}

.btn-primary {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  background: var(--lime);
  color: var(--ink);
  font-family: var(--f-body);
  font-weight: 700;
  font-size: 16px;
  padding: 18px 40px;
  border-radius: 4px;
  border: none;
  cursor: pointer;
  text-decoration: none;
  transition: background .18s, transform .14s, box-shadow .18s;
  letter-spacing: .02em;
}
.btn-primary:hover {
  background: #27ae60;
  transform: translateY(-2px);
  box-shadow: 0 12px 32px rgba(46,204,113,.35);
}
.btn-ghost {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  color: var(--lime);
  font-family: var(--f-body);
  font-weight: 600;
  font-size: 14px;
  text-decoration: none;
  border-bottom: 1px solid currentColor;
  padding-bottom: 2px;
  transition: opacity .15s;
}
.btn-ghost:hover { opacity: .7; }

/* ─── NAV ─────────────────────────────────────────────────────── */
nav {
  position: fixed; top: 0; left: 0; right: 0; z-index: 100;
  background: rgba(12,26,14,.96);
  backdrop-filter: blur(8px);
  border-bottom: 1px solid rgba(46,204,113,.12);
  padding: 14px 0;
}
.nav-inner {
  max-width: 960px; margin: 0 auto; padding: 0 24px;
  display: flex; align-items: center; justify-content: space-between;
}
.nav-logo {
  font-family: var(--f-mono);
  font-size: 13px;
  color: var(--lime);
  text-decoration: none;
  letter-spacing: .08em;
}
.nav-cta { font-size: 13px; padding: 10px 22px; }

/* ─── HERO ────────────────────────────────────────────────────── */
#hero {
  background: var(--ink);
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 120px 0 80px;
  position: relative;
  overflow: hidden;
}

/* Assinatura visual: grade de linhas verdes tipo planilha */
#hero::before {
  content: '';
  position: absolute; inset: 0;
  background-image:
    linear-gradient(rgba(46,204,113,.04) 1px, transparent 1px),
    linear-gradient(90deg, rgba(46,204,113,.04) 1px, transparent 1px);
  background-size: 48px 48px;
  pointer-events: none;
}
#hero::after {
  content: '';
  position: absolute;
  bottom: -1px; left: 0; right: 0; height: 80px;
  background: linear-gradient(to bottom, transparent, var(--paper));
}

.hero-eyebrow {
  background: rgba(46,204,113,.12);
  color: var(--lime);
  margin-bottom: 32px;
}

.hero-headline {
  font-family: var(--f-display);
  font-size: clamp(48px, 7vw, 82px);
  line-height: 1.05;
  color: #fff;
  max-width: 780px;
  margin-bottom: 28px;
}
.hero-headline em {
  color: var(--lime);
  font-style: italic;
}

.hero-sub {
  font-size: 18px;
  line-height: 1.65;
  color: var(--fog);
  max-width: 560px;
  margin-bottom: 44px;
}

.hero-cta-row {
  display: flex;
  align-items: center;
  gap: 28px;
  flex-wrap: wrap;
}

.hero-proof {
  font-family: var(--f-mono);
  font-size: 12px;
  color: rgba(165,214,167,.6);
  letter-spacing: .06em;
}

/* Ticker de números flutuando no hero */
.hero-stat-belt {
  position: absolute;
  bottom: 90px; right: 0;
  display: flex;
  flex-direction: column;
  gap: 12px;
  padding-right: 40px;
  opacity: .55;
}
.hero-stat {
  font-family: var(--f-mono);
  font-size: 11px;
  color: var(--lime);
  letter-spacing: .06em;
  text-align: right;
}
.hero-stat span {
  display: block;
  font-size: 22px;
  font-weight: 700;
  color: #fff;
}

/* ─── PAIN (dor) ──────────────────────────────────────────────── */
#pain {
  padding: 100px 0;
  background: var(--paper);
}
.pain-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 0;
}
.pain-left {
  padding-right: 64px;
  border-right: 1px solid var(--fog);
}
.pain-headline {
  font-family: var(--f-display);
  font-size: clamp(36px, 4.5vw, 54px);
  line-height: 1.1;
  margin-bottom: 28px;
  color: var(--ink);
}
.pain-headline em { color: var(--red); font-style: normal; }
.pain-body {
  font-size: 17px;
  line-height: 1.7;
  color: #4A5568;
  margin-bottom: 20px;
}
.pain-right {
  padding-left: 64px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 20px;
}
.pain-item {
  display: flex;
  gap: 16px;
  align-items: flex-start;
}
.pain-dot {
  flex-shrink: 0;
  width: 32px; height: 32px;
  border-radius: 50%;
  background: #FFEBEE;
  display: flex; align-items: center; justify-content: center;
  font-size: 14px;
  margin-top: 2px;
}
.pain-item-text strong {
  display: block;
  font-size: 15px;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 4px;
}
.pain-item-text p {
  font-size: 14px;
  color: #718096;
  line-height: 1.5;
}

/* ─── PROVA (gráfico) ─────────────────────────────────────────── */
#proof {
  padding: 100px 0;
  background: var(--ink);
  position: relative;
  overflow: hidden;
}
#proof::before {
  content: '';
  position: absolute; inset: 0;
  background-image:
    linear-gradient(rgba(46,204,113,.03) 1px, transparent 1px),
    linear-gradient(90deg, rgba(46,204,113,.03) 1px, transparent 1px);
  background-size: 48px 48px;
}
.proof-tag { background: rgba(46,204,113,.12); color: var(--lime); margin-bottom: 20px; }
.proof-headline {
  font-family: var(--f-display);
  font-size: clamp(36px, 4.5vw, 56px);
  color: #fff;
  line-height: 1.1;
  margin-bottom: 16px;
  max-width: 640px;
}
.proof-headline em { color: var(--lime); font-style: italic; }
.proof-sub { font-size: 16px; color: var(--fog); margin-bottom: 64px; max-width: 520px; }

/* Gráfico de patrimônio */
.chart-wrap {
  background: rgba(255,255,255,.03);
  border: 1px solid rgba(46,204,113,.12);
  border-radius: 8px;
  padding: 40px;
  position: relative;
}
.chart-label-y {
  position: absolute;
  left: 12px; top: 50%;
  transform: translateY(-50%) rotate(-90deg);
  font-family: var(--f-mono);
  font-size: 10px;
  color: rgba(165,214,167,.4);
  letter-spacing: .08em;
  white-space: nowrap;
}
.chart-area {
  width: 100%;
  height: 220px;
  position: relative;
  margin-bottom: 12px;
}
.chart-svg { width: 100%; height: 100%; }

.chart-x-labels {
  display: flex;
  justify-content: space-between;
  padding: 0 4px;
}
.chart-x-labels span {
  font-family: var(--f-mono);
  font-size: 10px;
  color: rgba(165,214,167,.4);
  letter-spacing: .04em;
}
.chart-x-labels span.highlight { color: var(--lime); font-weight: 700; }

.chart-callout {
  position: absolute;
  right: 0; top: -8px;
  background: var(--lime);
  color: var(--ink);
  font-family: var(--f-mono);
  font-size: 11px;
  font-weight: 700;
  padding: 6px 14px;
  border-radius: 3px;
  white-space: nowrap;
}
.chart-start-note {
  position: absolute;
  left: 0; bottom: 28px;
  font-family: var(--f-mono);
  font-size: 10px;
  color: rgba(200,213,202,.4);
}

.proof-stats {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1px;
  background: rgba(46,204,113,.1);
  border: 1px solid rgba(46,204,113,.1);
  border-radius: 4px;
  margin-top: 40px;
  overflow: hidden;
}
.proof-stat {
  background: rgba(12,26,14,.8);
  padding: 28px 24px;
  text-align: center;
}
.proof-stat-num {
  font-family: var(--f-display);
  font-size: 40px;
  color: var(--lime);
  display: block;
  line-height: 1;
  margin-bottom: 8px;
}
.proof-stat-label {
  font-family: var(--f-mono);
  font-size: 10px;
  color: var(--fog);
  letter-spacing: .08em;
  text-transform: uppercase;
}

/* ─── FEATURES ────────────────────────────────────────────────── */
#features {
  padding: 100px 0;
  background: var(--cream);
}
.features-header { margin-bottom: 60px; }
.features-tag { background: #E8F5E9; color: var(--leaf); margin-bottom: 20px; }
.features-headline {
  font-family: var(--f-display);
  font-size: clamp(36px, 4.5vw, 52px);
  line-height: 1.1;
  color: var(--ink);
  max-width: 600px;
}
.features-headline em { color: var(--leaf); font-style: italic; }

.features-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2px;
  background: var(--fog);
  border: 2px solid var(--fog);
  border-radius: 6px;
  overflow: hidden;
}
.feature-card {
  background: var(--cream);
  padding: 36px 28px;
  transition: background .2s;
}
.feature-card:hover { background: #fff; }
.feature-icon {
  font-size: 28px;
  margin-bottom: 16px;
  display: block;
}
.feature-name {
  font-family: var(--f-body);
  font-size: 15px;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 10px;
}
.feature-desc {
  font-size: 13px;
  line-height: 1.6;
  color: #607D8B;
}
.feature-badge {
  display: inline-block;
  margin-top: 14px;
  font-family: var(--f-mono);
  font-size: 10px;
  color: var(--leaf);
  background: #E8F5E9;
  padding: 3px 8px;
  border-radius: 2px;
  letter-spacing: .06em;
}

/* ─── COMO FUNCIONA ───────────────────────────────────────────── */
#how {
  padding: 100px 0;
  background: var(--paper);
}
.how-tag { background: #EDE7F6; color: #4A148C; margin-bottom: 20px; }
.how-headline {
  font-family: var(--f-display);
  font-size: clamp(36px, 4vw, 50px);
  line-height: 1.1;
  margin-bottom: 60px;
  max-width: 560px;
}
.how-steps {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px 80px;
}
.how-step { position: relative; }
.how-step-num {
  font-family: var(--f-display);
  font-size: 72px;
  color: #E8F5E9;
  line-height: 1;
  margin-bottom: -16px;
  display: block;
}
.how-step-title {
  font-size: 17px;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 10px;
}
.how-step-body {
  font-size: 14px;
  line-height: 1.65;
  color: #607D8B;
}
.how-step-mono {
  display: inline-block;
  margin-top: 10px;
  font-family: var(--f-mono);
  font-size: 11px;
  color: var(--leaf);
  background: #E8F5E9;
  padding: 4px 10px;
  border-radius: 2px;
}

/* ─── METAS SEMÁFORO ──────────────────────────────────────────── */
#goals {
  padding: 100px 0;
  background: var(--ink);
  position: relative;
  overflow: hidden;
}
#goals::before {
  content: '';
  position: absolute; inset: 0;
  background: radial-gradient(ellipse at 80% 50%, rgba(46,204,113,.06) 0%, transparent 60%);
}
.goals-tag { background: rgba(249,168,37,.15); color: var(--gold); margin-bottom: 20px; }
.goals-headline {
  font-family: var(--f-display);
  font-size: clamp(36px, 4.5vw, 54px);
  color: #fff;
  line-height: 1.1;
  margin-bottom: 16px;
  max-width: 580px;
}
.goals-headline em { color: var(--gold); font-style: italic; }
.goals-sub { font-size: 16px; color: var(--fog); margin-bottom: 56px; max-width: 480px; }

.goals-table {
  background: rgba(255,255,255,.03);
  border: 1px solid rgba(255,255,255,.07);
  border-radius: 6px;
  overflow: hidden;
}
.goals-table-head {
  display: grid;
  grid-template-columns: 2fr 1.2fr 1.2fr 1fr 1.2fr;
  padding: 12px 24px;
  background: rgba(255,255,255,.04);
  border-bottom: 1px solid rgba(255,255,255,.06);
}
.goals-table-head span {
  font-family: var(--f-mono);
  font-size: 10px;
  color: rgba(200,213,202,.4);
  letter-spacing: .08em;
  text-transform: uppercase;
}
.goals-row {
  display: grid;
  grid-template-columns: 2fr 1.2fr 1.2fr 1fr 1.2fr;
  padding: 14px 24px;
  border-bottom: 1px solid rgba(255,255,255,.04);
  align-items: center;
  transition: background .15s;
}
.goals-row:last-child { border-bottom: none; }
.goals-row:hover { background: rgba(255,255,255,.025); }
.goals-cat { font-size: 14px; color: #fff; font-weight: 500; }
.goals-val { font-family: var(--f-mono); font-size: 13px; color: var(--fog); }
.goals-spent { font-family: var(--f-mono); font-size: 13px; color: #fff; font-weight: 700; }
.goals-bar-wrap { height: 6px; background: rgba(255,255,255,.1); border-radius: 3px; overflow: hidden; }
.goals-bar { height: 100%; border-radius: 3px; }
.status-ok    { display: inline-flex; align-items: center; gap: 6px; font-size: 12px; font-weight: 600; color: #A5D6A7; font-family: var(--f-mono); }
.status-warn  { display: inline-flex; align-items: center; gap: 6px; font-size: 12px; font-weight: 600; color: var(--gold); font-family: var(--f-mono); }
.status-over  { display: inline-flex; align-items: center; gap: 6px; font-size: 12px; font-weight: 600; color: #EF9A9A; font-family: var(--f-mono); }

/* ─── OFERTA ──────────────────────────────────────────────────── */
#offer {
  padding: 100px 0;
  background: var(--paper);
  position: relative;
}
.offer-tag { background: #E8F5E9; color: var(--leaf); margin-bottom: 24px; }
.offer-headline {
  font-family: var(--f-display);
  font-size: clamp(40px, 5.5vw, 64px);
  line-height: 1.05;
  margin-bottom: 12px;
  color: var(--ink);
}
.offer-headline em { color: var(--leaf); font-style: italic; }

.offer-layout {
  display: grid;
  grid-template-columns: 1fr 380px;
  gap: 64px;
  align-items: start;
  margin-top: 56px;
}

/* Lista de entregáveis */
.deliverables { list-style: none; }
.deliverable {
  display: flex;
  gap: 16px;
  align-items: flex-start;
  padding: 18px 0;
  border-bottom: 1px solid var(--fog);
}
.deliverable:first-child { border-top: 1px solid var(--fog); }
.del-icon {
  flex-shrink: 0;
  width: 36px; height: 36px;
  background: #E8F5E9;
  border-radius: 4px;
  display: flex; align-items: center; justify-content: center;
  font-size: 16px;
}
.del-text strong {
  display: block;
  font-size: 15px;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 4px;
}
.del-text p { font-size: 13px; color: #718096; line-height: 1.5; }

/* Card de preço */
.price-card {
  background: var(--ink);
  border-radius: 8px;
  padding: 40px 32px;
  position: sticky;
  top: 88px;
  text-align: center;
}
.price-eyebrow {
  font-family: var(--f-mono);
  font-size: 11px;
  letter-spacing: .1em;
  color: var(--lime-dim);
  text-transform: uppercase;
  margin-bottom: 24px;
  display: block;
}
.price-value {
  font-family: var(--f-display);
  font-size: 80px;
  color: var(--lime);
  line-height: 1;
  margin-bottom: 6px;
}
.price-value sup {
  font-size: 32px;
  vertical-align: super;
  font-family: var(--f-body);
  font-weight: 700;
}
.price-note {
  font-family: var(--f-mono);
  font-size: 11px;
  color: rgba(165,214,167,.5);
  letter-spacing: .06em;
  margin-bottom: 32px;
  display: block;
}
.price-cta {
  width: 100%;
  font-size: 15px;
  padding: 18px 24px;
  border-radius: 4px;
  margin-bottom: 20px;
}
.price-guarantee {
  font-size: 12px;
  color: rgba(200,213,202,.5);
  line-height: 1.5;
}
.price-divider {
  border: none;
  border-top: 1px solid rgba(255,255,255,.06);
  margin: 24px 0;
}
.price-perks { list-style: none; text-align: left; }
.price-perk {
  font-size: 13px;
  color: var(--fog);
  padding: 7px 0;
  display: flex;
  gap: 10px;
  align-items: center;
}
.price-perk::before {
  content: '✓';
  color: var(--lime);
  font-weight: 700;
  flex-shrink: 0;
}

/* ─── URGÊNCIA / BANNER ───────────────────────────────────────── */
.urgency-banner {
  background: var(--lime);
  padding: 16px 0;
  text-align: center;
}
.urgency-banner p {
  font-family: var(--f-mono);
  font-size: 13px;
  font-weight: 700;
  color: var(--ink);
  letter-spacing: .04em;
}
.urgency-banner span { text-decoration: underline; }

/* ─── DEPOIMENTOS ─────────────────────────────────────────────── */
#testimonials {
  padding: 100px 0;
  background: var(--cream);
}
.test-tag { background: #EDE7F6; color: #4A148C; margin-bottom: 20px; }
.test-headline {
  font-family: var(--f-display);
  font-size: clamp(32px, 4vw, 46px);
  line-height: 1.1;
  margin-bottom: 56px;
  max-width: 500px;
}
.testimonials-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
.testimonial {
  background: #fff;
  border-radius: 6px;
  padding: 28px;
  border-left: 3px solid var(--lime);
}
.test-quote {
  font-size: 15px;
  line-height: 1.65;
  color: #4A5568;
  margin-bottom: 20px;
  font-style: italic;
}
.test-quote::before { content: '"'; color: var(--lime); font-size: 20px; font-family: var(--f-display); }
.test-author {
  display: flex;
  align-items: center;
  gap: 12px;
}
.test-avatar {
  width: 36px; height: 36px;
  border-radius: 50%;
  background: var(--leaf);
  display: flex; align-items: center; justify-content: center;
  font-size: 14px;
  font-weight: 700;
  color: #fff;
  flex-shrink: 0;
}
.test-name { font-size: 13px; font-weight: 700; color: var(--ink); }
.test-role { font-size: 12px; color: #90A4AE; }
.test-stars { color: var(--gold); font-size: 12px; margin-bottom: 4px; }

/* ─── FAQ ─────────────────────────────────────────────────────── */
#faq {
  padding: 100px 0;
  background: var(--paper);
}
.faq-tag { background: #E3F2FD; color: #0D47A1; margin-bottom: 20px; }
.faq-headline {
  font-family: var(--f-display);
  font-size: clamp(32px, 4vw, 46px);
  margin-bottom: 48px;
  max-width: 480px;
}
.faq-list { max-width: 680px; }
.faq-item {
  border-bottom: 1px solid var(--fog);
  padding: 24px 0;
}
.faq-q {
  font-size: 16px;
  font-weight: 700;
  color: var(--ink);
  cursor: pointer;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 16px;
  user-select: none;
}
.faq-q::after {
  content: '+';
  font-size: 22px;
  color: var(--leaf);
  font-weight: 300;
  flex-shrink: 0;
  transition: transform .2s;
}
.faq-item.open .faq-q::after { transform: rotate(45deg); }
.faq-a {
  font-size: 15px;
  line-height: 1.7;
  color: #607D8B;
  margin-top: 12px;
  display: none;
}
.faq-item.open .faq-a { display: block; }

/* ─── CTA FINAL ───────────────────────────────────────────────── */
#final-cta {
  padding: 120px 0;
  background: var(--leaf);
  text-align: center;
  position: relative;
  overflow: hidden;
}
#final-cta::before {
  content: '';
  position: absolute; inset: 0;
  background-image:
    linear-gradient(rgba(255,255,255,.04) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,.04) 1px, transparent 1px);
  background-size: 48px 48px;
}
.final-headline {
  font-family: var(--f-display);
  font-size: clamp(40px, 6vw, 72px);
  color: #fff;
  line-height: 1.05;
  margin-bottom: 20px;
  position: relative;
}
.final-sub {
  font-size: 18px;
  color: var(--lime-dim);
  margin-bottom: 48px;
  max-width: 500px;
  margin-left: auto;
  margin-right: auto;
  position: relative;
}
.final-btn {
  position: relative;
  font-size: 18px;
  padding: 22px 56px;
  border-radius: 4px;
  background: #fff;
  color: var(--leaf);
}
.final-btn:hover {
  background: #F0FFF4;
  box-shadow: 0 16px 48px rgba(0,0,0,.2);
}
.final-note {
  margin-top: 20px;
  font-family: var(--f-mono);
  font-size: 12px;
  color: rgba(165,214,167,.6);
  position: relative;
  letter-spacing: .06em;
}

/* ─── FOOTER ──────────────────────────────────────────────────── */
footer {
  background: var(--ink);
  padding: 40px 0;
  text-align: center;
}
footer p {
  font-family: var(--f-mono);
  font-size: 12px;
  color: rgba(200,213,202,.3);
  letter-spacing: .06em;
}

/* ─── ANIMAÇÕES ───────────────────────────────────────────────── */
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(24px); }
  to   { opacity: 1; transform: translateY(0); }
}
.fade-up { opacity: 0; }
.fade-up.visible { animation: fadeUp .6s ease forwards; }
.fade-up:nth-child(2) { animation-delay: .1s; }
.fade-up:nth-child(3) { animation-delay: .2s; }

@keyframes pulse-dot {
  0%,100% { opacity: 1; transform: scale(1); }
  50%      { opacity: .6; transform: scale(1.3); }
}
.live-dot {
  display: inline-block;
  width: 7px; height: 7px;
  background: var(--lime);
  border-radius: 50%;
  animation: pulse-dot 2s ease-in-out infinite;
  margin-right: 6px;
  vertical-align: middle;
}

/* ─── RESPONSIVE ──────────────────────────────────────────────── */
@media (max-width: 768px) {
  .pain-grid,
  .how-steps,
  .offer-layout,
  .testimonials-grid { grid-template-columns: 1fr; }
  .pain-left { border-right: none; border-bottom: 1px solid var(--fog); padding-right: 0; padding-bottom: 48px; margin-bottom: 48px; }
  .pain-right { padding-left: 0; }
  .features-grid { grid-template-columns: 1fr 1fr; }
  .proof-stats { grid-template-columns: 1fr; }
  .hero-stat-belt { display: none; }
  .price-card { position: static; }
  .goals-table-head span:nth-child(4),
  .goals-row > *:nth-child(4) { display: none; }
}

@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after { animation: none !important; transition: none !important; }
}
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-inner">
    <a href="#" class="nav-logo">@investidordaroca</a>
    <a href="#offer" class="btn-primary nav-cta">Quero a planilha — R$67</a>
  </div>
</nav>

<!-- URGÊNCIA TOPO -->
<div class="urgency-banner" style="margin-top:57px;">
  <p><span class="live-dot"></span> Oferta de lançamento ativa — <span>preço sobe em breve</span></p>
</div>

<!-- ═══ HERO ═══ -->
<section id="hero">
  <div class="container">
    <span class="tag hero-eyebrow">Controle Financeiro Pessoal</span>
    <h1 class="hero-headline fade-up">
      O seu dinheiro some<br>porque você não<br><em>enxerga para onde vai.</em>
    </h1>
    <p class="hero-sub fade-up">
      Uma planilha feita com 8 anos de dados financeiros reais — do zero a
      R$&nbsp;312 mil acumulados. Automática, visual e fácil de usar.
    </p>
    <div class="hero-cta-row fade-up">
      <a href="#offer" class="btn-primary" style="font-size:17px;padding:20px 44px;">
        Quero organizar meu dinheiro →
      </a>
      <a href="#proof" class="btn-ghost">Ver o histórico real</a>
    </div>
    <p class="hero-proof" style="margin-top:32px;">
      <span class="live-dot"></span>
      Compatível com Excel e Google Sheets · Acesso imediato
    </p>
  </div>

  <div class="hero-stat-belt">
    <div class="hero-stat">PATRIMÔNIO 2026<span>R$ 312.352</span></div>
    <div class="hero-stat">ANOS DE DADOS<span>8 anos</span></div>
    <div class="hero-stat">LANÇAMENTOS<span>158+</span></div>
    <div class="hero-stat">ABAS<span>6</span></div>
  </div>
</section>

<!-- ═══ DOR ═══ -->
<section id="pain">
  <div class="container">
    <div class="pain-grid">
      <div class="pain-left">
        <h2 class="pain-headline">
          No fim do mês,<br>o dinheiro acabou<br>e você não sabe<br><em>por quê.</em>
        </h2>
        <p class="pain-body">
          Não é falta de disciplina. É falta de visibilidade. Sem saber exatamente onde o dinheiro vai, é impossível tomar decisões melhores.
        </p>
        <p class="pain-body">
          Você tenta lembrar dos gastos, faz conta de cabeça, promete se organizar no mês que vem. E o ciclo se repete.
        </p>
      </div>
      <div class="pain-right">
        <div class="pain-item">
          <div class="pain-dot">💸</div>
          <div class="pain-item-text">
            <strong>Gasta sem saber o total</strong>
            <p>Sem controle por categoria, qualquer valor parece normal — até não sobrar nada.</p>
          </div>
        </div>
        <div class="pain-item">
          <div class="pain-dot">🤯</div>
          <div class="pain-item-text">
            <strong>Planilha complica demais</strong>
            <p>A maioria desiste porque cria algo difícil de manter. Precisa ser simples para funcionar.</p>
          </div>
        </div>
        <div class="pain-item">
          <div class="pain-dot">📉</div>
          <div class="pain-item-text">
            <strong>Não vê evolução ao longo do tempo</strong>
            <p>Sem histórico, você não sabe se está melhorando ou se está na mesma há anos.</p>
          </div>
        </div>
        <div class="pain-item">
          <div class="pain-dot">🎯</div>
          <div class="pain-item-text">
            <strong>Nunca sabe se vai atingir suas metas</strong>
            <p>Sem limite definido por categoria, qualquer gasto parece cabível.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ═══ PROVA ═══ -->
<section id="proof">
  <div class="container">
    <span class="tag proof-tag">Histórico Real</span>
    <h2 class="proof-headline">
      Em 2018 eu tinha<br><em>R$&nbsp;5.900</em> acumulados.<br>Hoje são R$&nbsp;312 mil.
    </h2>
    <p class="proof-sub">
      Não mudei de emprego. Não herdei nada. Só aprendi a anotar — e usar os dados para tomar decisões melhores.
    </p>

    <div class="chart-wrap">
      <div class="chart-label-y">PATRIMÔNIO ACUMULADO (R$)</div>
      <div class="chart-area">
        <div class="chart-callout">R$ 312.352 →</div>
        <svg class="chart-svg" viewBox="0 0 800 200" preserveAspectRatio="none">
          <defs>
            <linearGradient id="chartGrad" x1="0" y1="0" x2="0" y2="1">
              <stop offset="0%" stop-color="#2ECC71" stop-opacity="0.25"/>
              <stop offset="100%" stop-color="#2ECC71" stop-opacity="0.01"/>
            </linearGradient>
            <linearGradient id="lineGrad" x1="0" y1="0" x2="1" y2="0">
              <stop offset="0%" stop-color="#1B5E20"/>
              <stop offset="100%" stop-color="#2ECC71"/>
            </linearGradient>
          </defs>
          <!-- grid lines -->
          <line x1="0" y1="50"  x2="800" y2="50"  stroke="rgba(46,204,113,.06)" stroke-width="1"/>
          <line x1="0" y1="100" x2="800" y2="100" stroke="rgba(46,204,113,.06)" stroke-width="1"/>
          <line x1="0" y1="150" x2="800" y2="150" stroke="rgba(46,204,113,.06)" stroke-width="1"/>
          <line x1="0" y1="190" x2="800" y2="190" stroke="rgba(46,204,113,.12)" stroke-width="1"/>
          <!-- Área -->
          <!-- Pontos: 2018=5.9k,2019=15.5k,2020=20.7k,2021=42.9k,2022=59.6k,2023=115k,2024=180.5k,2025=283.4k,2026=312.4k -->
          <!-- Escala: max=312k→y=10, 0→y=190. Range=180. x: 0 a 800 / 8 passos = 0,100,200,300,400,500,600,700,800 -->
          <!-- y = 190 - (val/312000)*180 -->
          <!-- 5.9→187, 15.5→181, 20.7→178, 42.9→165, 59.6→156, 115→123, 180.5→86, 283.4→27, 312.4→10 -->
          <path d="M0,187 C30,185 60,183 100,181 C140,179 170,178 200,178 C230,173 260,168 300,165 C335,160 365,158 400,156 C435,140 460,130 500,123 C540,105 565,94 600,86 C645,57 670,40 700,27 C740,18 770,13 800,10 L800,190 L0,190 Z"
            fill="url(#chartGrad)"/>
          <!-- Linha -->
          <path d="M0,187 C30,185 60,183 100,181 C140,179 170,178 200,178 C230,173 260,168 300,165 C335,160 365,158 400,156 C435,140 460,130 500,123 C540,105 565,94 600,86 C645,57 670,40 700,27 C740,18 770,13 800,10"
            fill="none" stroke="url(#lineGrad)" stroke-width="2.5" stroke-linecap="round"/>
          <!-- Ponto inicial -->
          <circle cx="0" cy="187" r="4" fill="#1B5E20"/>
          <!-- Ponto final com pulso -->
          <circle cx="800" cy="10" r="6" fill="#2ECC71"/>
          <circle cx="800" cy="10" r="12" fill="#2ECC71" opacity=".2"/>
        </svg>
        <div class="chart-start-note">2018 · R$ 5.900</div>
      </div>
      <div class="chart-x-labels">
        <span>2018</span><span>2019</span><span>2020</span><span>2021</span>
        <span>2022</span><span>2023</span><span>2024</span><span>2025</span>
        <span class="highlight">2026</span>
      </div>
    </div>

    <div class="proof-stats">
      <div class="proof-stat">
        <span class="proof-stat-num">R$399k</span>
        <span class="proof-stat-label">Receita em 2025</span>
      </div>
      <div class="proof-stat">
        <span class="proof-stat-num">8 anos</span>
        <span class="proof-stat-label">de histórico real</span>
      </div>
      <div class="proof-stat">
        <span class="proof-stat-num">+5.200%</span>
        <span class="proof-stat-label">crescimento acumulado</span>
      </div>
    </div>

    <div style="text-align:center;margin-top:48px;">
      <a href="#offer" class="btn-primary" style="font-size:16px;padding:18px 44px;">
        Quero essa planilha → R$ 67
      </a>
    </div>
  </div>
</section>

<!-- ═══ FEATURES ═══ -->
<section id="features">
  <div class="container">
    <div class="features-header">
      <span class="tag features-tag">O Que Está Incluso</span>
      <h2 class="features-headline">
        6 abas. Tudo<br><em>automático.</em><br>Você só preenche uma coluna.
      </h2>
    </div>

    <div class="features-grid">
      <div class="feature-card">
        <span class="feature-icon">📝</span>
        <div class="feature-name">Lançamentos</div>
        <p class="feature-desc">A única aba que você preenche. Data, valor e categoria com menu suspenso. Mês calculado automaticamente.</p>
        <span class="feature-badge">ENTRADA DE DADOS</span>
      </div>
      <div class="feature-card">
        <span class="feature-icon">📊</span>
        <div class="feature-name">Resumo Mensal</div>
        <p class="feature-desc">Entradas, saídas e saldo de cada mês calculados e exibidos automaticamente. Com indicador de status.</p>
        <span class="feature-badge">AUTOMÁTICO</span>
      </div>
      <div class="feature-card">
        <span class="feature-icon">🏷️</span>
        <div class="feature-name">Por Categoria</div>
        <p class="feature-desc">Moradia, alimentação, saúde, beleza, lazer e mais 7 categorias — com total anual e % de cada uma.</p>
        <span class="feature-badge">12 CATEGORIAS</span>
      </div>
      <div class="feature-card">
        <span class="feature-icon">📈</span>
        <div class="feature-name">Dashboard</div>
        <p class="feature-desc">3 gráficos automáticos: barras de entradas vs saídas, pizza por categoria e linha de evolução do saldo.</p>
        <span class="feature-badge">3 GRÁFICOS</span>
      </div>
      <div class="feature-card">
        <span class="feature-icon">🎯</span>
        <div class="feature-name">Metas e Limites</div>
        <p class="feature-desc">Defina um teto mensal por categoria. Semáforo automático: ✅ OK, ⚠️ Atenção, 🔴 Excedeu.</p>
        <span class="feature-badge">SEMÁFORO</span>
      </div>
      <div class="feature-card">
        <span class="feature-icon">💰</span>
        <div class="feature-name">Patrimônio Histórico</div>
        <p class="feature-desc">Veja sua evolução financeira ano a ano. Gráfico de curva patrimonial com dados de 2018 a 2026.</p>
        <span class="feature-badge">EXCLUSIVO</span>
      </div>
    </div>
  </div>
</section>

<!-- ═══ COMO FUNCIONA ═══ -->
<section id="how">
  <div class="container">
    <span class="tag how-tag" style="background:#EDE7F6;color:#4A148C;">Como Usar</span>
    <h2 class="how-headline">
      Em 5 minutos você já<br>está no controle.
    </h2>

    <div class="how-steps">
      <div class="how-step">
        <span class="how-step-num">01</span>
        <div class="how-step-title">Baixa e abre no Excel</div>
        <p class="how-step-body">Compatível com Microsoft Excel e Google Sheets. Funciona no celular e no computador. Sem instalação, sem conta, sem mensalidade.</p>
        <span class="how-step-mono">ACESSO IMEDIATO</span>
      </div>
      <div class="how-step">
        <span class="how-step-num">02</span>
        <div class="how-step-title">Lança seus gastos</div>
        <p class="how-step-body">Só na aba "Lançamentos". Data, seleciona a categoria no menu, coloca o valor. Menos de 30 segundos por lançamento.</p>
        <span class="how-step-mono">DROPDOWNS PRONTOS</span>
      </div>
      <div class="how-step">
        <span class="how-step-num">03</span>
        <div class="how-step-title">A planilha faz o resto</div>
        <p class="how-step-body">Resumo mensal, gráficos, totais por categoria, semáforo de metas — tudo calculado e atualizado automaticamente.</p>
        <span class="how-step-mono">100% AUTOMÁTICO</span>
      </div>
      <div class="how-step">
        <span class="how-step-num">04</span>
        <div class="how-step-title">Toma decisões com dados</div>
        <p class="how-step-body">Visualize onde está gastando mais, defina metas realistas por categoria e acompanhe seu patrimônio crescer mês a mês.</p>
        <span class="how-step-mono">VISÃO COMPLETA</span>
      </div>
    </div>

    <div style="text-align:center;margin-top:60px;">
      <a href="#offer" class="btn-primary" style="font-size:16px;padding:18px 44px;">
        Começar agora — R$ 67 →
      </a>
    </div>
  </div>
</section>

<!-- ═══ METAS ═══ -->
<section id="goals">
  <div class="container">
    <span class="tag goals-tag">Metas por Categoria</span>
    <h2 class="goals-headline">
      Defina um limite.<br>Receba um alerta<br>antes de <em>estourar.</em>
    </h2>
    <p class="goals-sub">Você escolhe quanto quer gastar em cada categoria. A planilha monitora e avisa quando chegar perto do teto.</p>

    <div class="goals-table">
      <div class="goals-table-head">
        <span>Categoria</span>
        <span>Meta mensal</span>
        <span>Gasto no mês</span>
        <span>% usado</span>
        <span>Status</span>
      </div>

      <div class="goals-row">
        <span class="goals-cat">🏠 Moradia</span>
        <span class="goals-val">R$ 1.500</span>
        <span class="goals-spent">R$ 1.350</span>
        <div><div class="goals-bar-wrap"><div class="goals-bar" style="width:90%;background:#66BB6A;"></div></div></div>
        <span class="status-ok">✅ OK</span>
      </div>
      <div class="goals-row">
        <span class="goals-cat">🍽️ Alimentação</span>
        <span class="goals-val">R$ 1.200</span>
        <span class="goals-spent">R$ 890</span>
        <div><div class="goals-bar-wrap"><div class="goals-bar" style="width:74%;background:#66BB6A;"></div></div></div>
        <span class="status-ok">✅ OK</span>
      </div>
      <div class="goals-row">
        <span class="goals-cat">💊 Saúde</span>
        <span class="goals-val">R$ 300</span>
        <span class="goals-spent" style="color:var(--gold);">R$ 268</span>
        <div><div class="goals-bar-wrap"><div class="goals-bar" style="width:89%;background:#F9A825;"></div></div></div>
        <span class="status-warn">⚠️ Atenção</span>
      </div>
      <div class="goals-row">
        <span class="goals-cat">🚗 Transporte</span>
        <span class="goals-val">R$ 500</span>
        <span class="goals-spent">R$ 380</span>
        <div><div class="goals-bar-wrap"><div class="goals-bar" style="width:76%;background:#66BB6A;"></div></div></div>
        <span class="status-ok">✅ OK</span>
      </div>
      <div class="goals-row">
        <span class="goals-cat">🛍️ Compras</span>
        <span class="goals-val">R$ 600</span>
        <span class="goals-spent" style="color:#EF9A9A;">R$ 874</span>
        <div><div class="goals-bar-wrap"><div class="goals-bar" style="width:100%;background:#C62828;"></div></div></div>
        <span class="status-over">🔴 Excedeu</span>
      </div>
      <div class="goals-row">
        <span class="goals-cat">💆 Beleza</span>
        <span class="goals-val">R$ 150</span>
        <span class="goals-spent">R$ 110</span>
        <div><div class="goals-bar-wrap"><div class="goals-bar" style="width:73%;background:#66BB6A;"></div></div></div>
        <span class="status-ok">✅ OK</span>
      </div>
    </div>

    <p style="margin-top:20px;font-family:var(--f-mono);font-size:11px;color:rgba(200,213,202,.35);letter-spacing:.06em;">
      SELECIONE O MÊS DE ANÁLISE COM UM CLIQUE — DADOS ATUALIZAM AUTOMATICAMENTE
    </p>
  </div>
</section>

<!-- ═══ OFERTA ═══ -->
<section id="offer">
  <div class="container">
    <span class="tag offer-tag">A Oferta</span>
    <h2 class="offer-headline">
      Tudo que você precisa<br>para <em>organizar, controlar</em><br>e crescer financeiramente.
    </h2>

    <div class="offer-layout">
      <div>
        <ul class="deliverables">
          <li class="deliverable">
            <div class="del-icon">📝</div>
            <div class="del-text">
              <strong>Aba de Lançamentos completa</strong>
              <p>200 linhas, menus suspensos para categoria, conta e tipo, mês automático e status de conferência.</p>
            </div>
          </li>
          <li class="deliverable">
            <div class="del-icon">📊</div>
            <div class="del-text">
              <strong>Resumo Mensal automático</strong>
              <p>Entradas, saídas, saldo e % gasto de cada mês — com indicador de resultado e total anual.</p>
            </div>
          </li>
          <li class="deliverable">
            <div class="del-icon">🏷️</div>
            <div class="del-text">
              <strong>Análise por Categoria</strong>
              <p>12 categorias pré-definidas. Total por mês, total anual e % de participação em cada uma.</p>
            </div>
          </li>
          <li class="deliverable">
            <div class="del-icon">📈</div>
            <div class="del-text">
              <strong>Dashboard com 3 gráficos automáticos</strong>
              <p>Barras de entradas vs saídas, pizza de categorias e linha de evolução do saldo. Sem configurar nada.</p>
            </div>
          </li>
          <li class="deliverable">
            <div class="del-icon">🎯</div>
            <div class="del-text">
              <strong>Metas e semáforo de gastos</strong>
              <p>Defina seu teto mensal por categoria. Semáforo automático mostra o que está OK, em atenção ou excedido.</p>
            </div>
          </li>
          <li class="deliverable">
            <div class="del-icon">💰</div>
            <div class="del-text">
              <strong>Histórico patrimonial (2018–2026)</strong>
              <p>Veja a evolução do patrimônio acumulado ano a ano com gráfico de curva. Único no mercado.</p>
            </div>
          </li>
          <li class="deliverable">
            <div class="del-icon">ℹ️</div>
            <div class="del-text">
              <strong>Guia de uso completo</strong>
              <p>Passo a passo dentro da própria planilha. Sem precisar de suporte ou tutorial externo.</p>
            </div>
          </li>
        </ul>
      </div>

      <!-- CARD DE PREÇO -->
      <div class="price-card">
        <span class="price-eyebrow">Pagamento único</span>
        <div class="price-value"><sup>R$</sup>67</div>
        <span class="price-note">sem mensalidade · sem renovação</span>

        <a href="#" class="btn-primary price-cta">
          Comprar agora →
        </a>
        <p class="price-guarantee">
          🔒 Pagamento seguro · Acesso imediato após confirmação
        </p>

        <hr class="price-divider">

        <ul class="price-perks">
          <li class="price-perk">6 abas completas e funcionais</li>
          <li class="price-perk">Fórmulas automáticas prontas</li>
          <li class="price-perk">3 gráficos dinâmicos</li>
          <li class="price-perk">Semáforo de metas mensais</li>
          <li class="price-perk">Histórico patrimonial 8 anos</li>
          <li class="price-perk">Compatível com Excel e Sheets</li>
          <li class="price-perk">Guia de uso incluído</li>
          <li class="price-perk">Acesso vitalício</li>
        </ul>

        <hr class="price-divider">

        <p style="font-family:var(--f-mono);font-size:12px;color:rgba(165,214,167,.5);letter-spacing:.04em;line-height:1.6;">
          "Você gasta R$ 67 num jantar.<br>Aqui você compra controle<br>financeiro pra vida."
        </p>
      </div>
    </div>
  </div>
</section>

<!-- BANNER URGÊNCIA MEIO -->
<div class="urgency-banner">
  <p>⚡ Preço de lançamento · <span>R$&nbsp;67 — pagamento único</span> · Link na bio</p>
</div>

<!-- ═══ DEPOIMENTOS ═══ -->
<section id="testimonials">
  <div class="container">
    <span class="tag test-tag">Resultados Reais</span>
    <h2 class="test-headline">
      Quem organizou<br>o dinheiro mudou<br>de vida.
    </h2>

    <div class="testimonials-grid">
      <div class="testimonial">
        <div class="test-stars">★★★★★</div>
        <p class="test-quote">Nunca soube para onde ia meu dinheiro. Com a planilha descobri que gastava R$&nbsp;900 por mês em compras desnecessárias. Cortei na metade em 30 dias.</p>
        <div class="test-author">
          <div class="test-avatar">M</div>
          <div>
            <div class="test-name">Mariana S.</div>
            <div class="test-role">Professora, MG</div>
          </div>
        </div>
      </div>
      <div class="testimonial">
        <div class="test-stars">★★★★★</div>
        <p class="test-quote">O gráfico de patrimônio foi o que me fez encarar a situação de verdade. Ver que estava acumulando quase zero em 3 anos me deu um susto necessário.</p>
        <div class="test-author">
          <div class="test-avatar">R</div>
          <div>
            <div class="test-name">Ricardo A.</div>
            <div class="test-role">Autônomo, SP</div>
          </div>
        </div>
      </div>
      <div class="testimonial">
        <div class="test-stars">★★★★★</div>
        <p class="test-quote">Tentei várias planilhas prontas mas desistia porque eram complicadas. Essa aqui é diferente — preencho só uma coluna e já tenho tudo na tela.</p>
        <div class="test-author">
          <div class="test-avatar">J</div>
          <div>
            <div class="test-name">Juliana C.</div>
            <div class="test-role">Empreendedora, PR</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ═══ FAQ ═══ -->
<section id="faq">
  <div class="container">
    <span class="tag faq-tag">Dúvidas Frequentes</span>
    <h2 class="faq-headline">Antes de comprar,<br>tire suas dúvidas.</h2>

    <div class="faq-list">
      <div class="faq-item">
        <div class="faq-q">Precisa saber usar Excel?</div>
        <div class="faq-a">Não. Você só preenche a aba de Lançamentos com data, categoria (menu suspenso) e valor. Todas as fórmulas e gráficos já estão prontos e funcionam automaticamente.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q">Funciona no Google Sheets ou só no Excel?</div>
        <div class="faq-a">Funciona nos dois. Você recebe o arquivo .xlsx que abre normalmente no Microsoft Excel (qualquer versão a partir do 2016) e no Google Sheets, inclusive pelo celular.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q">Como recebo após o pagamento?</div>
        <div class="faq-a">O acesso é imediato. Após a confirmação do pagamento você recebe o arquivo por e-mail ou link de download direto — sem espera.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q">É pagamento único ou tem mensalidade?</div>
        <div class="faq-a">Pagamento único de R$&nbsp;67. Sem assinatura, sem renovação, sem cobrança recorrente. Você paga uma vez e usa para sempre.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q">Posso adaptar para minha realidade?</div>
        <div class="faq-a">Sim. As categorias, metas e contas já vêm com sugestões realistas, mas tudo pode ser ajustado para a sua realidade. As fórmulas se adaptam automaticamente.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q">O que é o histórico patrimonial?</div>
        <div class="faq-a">É uma aba exclusiva com dados reais de 8 anos (2018–2026) mostrando como o patrimônio cresceu de R$&nbsp;5.900 para R$&nbsp;312 mil. Serve como referência e motivação — e você pode adicionar seu próprio histórico.</div>
      </div>
    </div>
  </div>
</section>

<!-- ═══ CTA FINAL ═══ -->
<section id="final-cta">
  <div class="container">
    <h2 class="final-headline">
      O melhor momento<br>de se organizar<br>foi ontem.<br>O segundo melhor<br>é agora.
    </h2>
    <p class="final-sub">
      R$&nbsp;67. Pagamento único. Acesso imediato. Controle financeiro pelo resto da vida.
    </p>
    <a href="#offer" class="btn-primary final-btn">
      Quero a planilha agora →
    </a>
    <p class="final-note">
      🔒 Pagamento seguro · Acesso imediato · Sem mensalidade
    </p>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2026 @investidordaroca · Todos os direitos reservados · Feito com dados reais</p>
</footer>

<script>
// FAQ toggle
document.querySelectorAll('.faq-q').forEach(q => {
  q.addEventListener('click', () => {
    const item = q.parentElement;
    const isOpen = item.classList.contains('open');
    document.querySelectorAll('.faq-item').forEach(i => i.classList.remove('open'));
    if (!isOpen) item.classList.add('open');
  });
});

// Scroll fade-up
const observer = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      e.target.classList.add('visible');
      observer.unobserve(e.target);
    }
  });
}, { threshold: 0.15 });
document.querySelectorAll('.fade-up').forEach(el => observer.observe(el));
</script>
</body>
</html>
