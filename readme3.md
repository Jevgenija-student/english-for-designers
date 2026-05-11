# English for Designers – Winter 2025

## About This Course
This repository documents my work for the course *English for Designers*.
The focus of the course is clear, accessible writing about design, process, and identity.

This work is created by a student of graphic design.

---

## Table of Contents
- [Content First](#content-first)
- First Impressions
- Process & Iterations
- Reflection

---

## Content First

### Drop Cap / Letter Design
**Chosen letter:** A

**Why I chose this letter:**  
I chose the letter A because it is simple and strong, but now I wanted to give it a playful twist. Turning it into a 3D purple balloon adds volume, fun, and a unique character while keeping it recognizable.

**Process:**  
I started by sketching the letter A in a standard font. Then, I added rounded, inflated edges to make it look like a balloon. I used gradients of purple to create a 3D effect, with highlights and soft shadows to simulate light reflecting off the surface. Finally, I refined the contours to keep the shape clean and readable, even with the playful, bouncy style.

![Drop cap letter A](img/letter.jpg)

---

### Alt Text Writing

**Alt text version 1:**  
A 3D purple balloon letter A with soft, rounded edges and glossy highlights.

**Alt text version 2:**  
A playful drop cap letter A shaped like a purple balloon, with light reflections creating a three-dimensional effect.

**Alt text version 3 (AI-assisted, edited):**  
A stylized purple balloon letter A, 3D with shiny surfaces and smooth curves, resembling a party balloon.

**Final alt text:**  
A 3D purple balloon letter A with soft curves, glossy highlights, and a playful, inflated look.

---

### Type Specimen

**Original text:**  
Typography plays an important role in visual communication. It helps guide the reader, creates hierarchy, and influences how content is perceived. In this design, the letter A is presented as a playful 3D purple balloon, adding a fun and eye-catching element while remaining readable. Good typography is not only decorative but also functional and accessible.

**Design notes:**  
I focused on readability, spacing, and hierarchy, while giving the initial letter a playful twist. The 3D purple balloon A adds volume, highlights, and a tactile feel, creating a visual focal point without sacrificing clarity. I maintained contrast between headings and body text and avoided unnecessary decoration.

![Type specimen layout](img/type-specimen.png)

---

## First Impressions

### Handshake
Hi, I’m Jevgenija, a graphic design student living in Prague with a focus on social media content, digital design and visual communication. I speak Czech, Russian and English. 

---

### About Me
I am a design student interested in visual communication, social marketing, and identity. I focus on visual communication, illustrattion, and social media.

---

## Process & Iterations
This section documents my design process, including sketches, experiments, mistakes, and revisions. I focused on testing different approaches and learning from each iteration.

---

## Reflection

**What I learned:**  
- Writing clearly about design is part of the design process  
- Accessibility and readability are essential  
- Simple solutions are often the strongest  

**What I want to improve:**  
- Writing confidence  
- Explaining my process in more detail

---

## Vas praktik

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Váš praktik — Rebranding Case Study | Jevgenija Diděnko</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300..900;1,9..144,300..900&family=Nunito:wght@300;400;600;700;800;900&display=swap" rel="stylesheet">
<style>
:root {
  --bg: #f5f1ec;
  --ink: #1a1a1a;
  --ink-soft: #3a3a3a;
  --paper: #faf7f3;
  --white: #ffffff;
  --rose: #f7bdc7;
  --rose-deep: #ec9b9f;
  --lavender: #d5bfd6;
  --terra: #c98777;
  --muted: #babec1;
  --line: rgba(26, 26, 26, 0.12);
}

* { box-sizing: border-box; margin: 0; padding: 0; }
html { scroll-behavior: smooth; }

body {
  font-family: 'Nunito', sans-serif;
  background: var(--bg);
  color: var(--ink);
  font-weight: 400;
  line-height: 1.55;
  overflow-x: hidden;
  position: relative;
}

body::before {
  content: "";
  position: fixed;
  inset: 0;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='2' stitchTiles='stitch'/%3E%3CfeColorMatrix values='0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.18 0'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
  opacity: 0.45;
  pointer-events: none;
  z-index: 1;
  mix-blend-mode: multiply;
}

main, header, nav { position: relative; z-index: 2; }

/* === NAV === */
nav {
  position: fixed;
  top: 0; left: 0; right: 0;
  padding: 20px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  z-index: 100;
  background: rgba(245, 241, 236, 0.85);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  border-bottom: 1px solid var(--line);
}

.nav-logo {
  font-family: 'Fraunces', serif;
  font-weight: 600;
  font-style: italic;
  font-size: 18px;
  letter-spacing: -0.01em;
}
.nav-logo span { color: var(--rose-deep); }

.nav-links { display: flex; gap: 32px; list-style: none; }
.nav-links a {
  color: var(--ink-soft);
  text-decoration: none;
  font-size: 13px;
  font-weight: 600;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  transition: color 0.3s;
  position: relative;
}
.nav-links a::after {
  content: "";
  position: absolute;
  bottom: -4px; left: 0; right: 0;
  height: 1px;
  background: var(--rose-deep);
  transform: scaleX(0);
  transform-origin: right;
  transition: transform 0.4s cubic-bezier(0.86, 0, 0.07, 1);
}
.nav-links a:hover { color: var(--ink); }
.nav-links a:hover::after { transform: scaleX(1); transform-origin: left; }

/* === HERO === */
.hero {
  min-height: 100vh;
  padding: 140px 40px 80px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 60px;
  align-items: center;
}

.hero-meta {
  display: flex;
  flex-direction: column;
  gap: 16px;
  font-size: 12px;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: var(--ink-soft);
  font-weight: 700;
}
.hero-meta .divider { width: 40px; height: 1px; background: var(--ink); }

.hero h1 {
  font-family: 'Fraunces', serif;
  font-size: clamp(60px, 9vw, 140px);
  font-weight: 300;
  line-height: 0.95;
  letter-spacing: -0.04em;
  margin: 32px 0 28px;
  font-variation-settings: "opsz" 144;
}
.hero h1 em { font-style: italic; font-weight: 400; color: var(--rose-deep); }

.hero-intro {
  font-size: 17px;
  line-height: 1.65;
  color: var(--ink-soft);
  max-width: 460px;
  margin-bottom: 40px;
}

.hero-tags { display: flex; flex-wrap: wrap; gap: 10px; }
.tag {
  font-size: 11px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  padding: 8px 14px;
  border: 1px solid var(--ink);
  border-radius: 100px;
  font-weight: 600;
}
.tag.filled { background: var(--ink); color: var(--paper); }

.hero-visual {
  position: relative;
  aspect-ratio: 1;
  display: flex;
  align-items: center;
  justify-content: center;
}

/* Logo na bílém pozadí pro maximální čitelnost */
.logo-stage {
  position: relative;
  width: 100%;
  aspect-ratio: 1;
  background: var(--white);
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 30px 80px -30px rgba(26,26,26,0.2),
              0 8px 20px -8px rgba(26,26,26,0.08);
  border: 1px solid var(--line);
}

.logo-stage::before {
  content: "";
  position: absolute;
  inset: 18%;
  background: radial-gradient(circle, rgba(247,189,199,0.25) 0%, transparent 70%);
  animation: pulse 6s ease-in-out infinite;
  pointer-events: none;
}

@keyframes pulse {
  0%, 100% { transform: scale(1); opacity: 0.7; }
  50% { transform: scale(1.15); opacity: 1; }
}

.vp-logo-img {
  width: 55%;
  height: auto;
  position: relative;
  z-index: 2;
}

.hero-visual .logo-caption {
  position: absolute;
  bottom: -28px;
  left: 0; right: 0;
  text-align: center;
  font-size: 11px;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--ink-soft);
}

.scroll-down {
  position: absolute;
  bottom: 40px;
  left: 40px;
  font-size: 10px;
  letter-spacing: 0.25em;
  text-transform: uppercase;
  color: var(--ink-soft);
  display: flex;
  align-items: center;
  gap: 12px;
  writing-mode: vertical-rl;
  transform: rotate(180deg);
}
.scroll-down::before {
  content: "";
  display: block;
  width: 1px;
  height: 60px;
  background: var(--ink);
  animation: scrollLine 2s ease-in-out infinite;
}
@keyframes scrollLine {
  0%, 100% { transform: scaleY(1); transform-origin: top; }
  50% { transform: scaleY(0.3); transform-origin: bottom; }
}

/* === SECTIONS === */
section { padding: 120px 40px; position: relative; }

.section-label {
  display: flex;
  align-items: center;
  gap: 16px;
  font-size: 12px;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  font-weight: 700;
  margin-bottom: 40px;
  color: var(--ink-soft);
}
.section-label .num {
  font-family: 'Fraunces', serif;
  font-style: italic;
  color: var(--rose-deep);
  font-weight: 400;
}
.section-label .line { flex: 1; height: 1px; background: var(--line); }

h2 {
  font-family: 'Fraunces', serif;
  font-size: clamp(40px, 5.5vw, 76px);
  font-weight: 300;
  line-height: 1.0;
  letter-spacing: -0.03em;
  margin-bottom: 40px;
  max-width: 1000px;
}
h2 em { font-style: italic; color: var(--rose-deep); font-weight: 400; }

h3 {
  font-family: 'Fraunces', serif;
  font-size: 28px;
  font-weight: 500;
  line-height: 1.2;
  letter-spacing: -0.02em;
  margin-bottom: 16px;
}

p {
  font-size: 16px;
  line-height: 1.7;
  color: var(--ink-soft);
  max-width: 65ch;
}

/* === ABOUT === */
.about {
  display: grid;
  grid-template-columns: 1fr 1.4fr;
  gap: 80px;
  align-items: start;
}

.about-stats {
  display: flex;
  flex-direction: column;
  gap: 32px;
  position: sticky;
  top: 120px;
}

.stat { border-top: 1px solid var(--line); padding-top: 16px; }
.stat-label {
  font-size: 11px;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--ink-soft);
  font-weight: 700;
  margin-bottom: 8px;
}
.stat-value {
  font-family: 'Fraunces', serif;
  font-size: 22px;
  font-weight: 400;
  line-height: 1.3;
}

.about-text p + p { margin-top: 20px; }

.pullquote {
  font-family: 'Fraunces', serif;
  font-size: 32px;
  font-style: italic;
  font-weight: 300;
  line-height: 1.25;
  color: var(--ink);
  margin: 48px 0;
  padding-left: 24px;
  border-left: 2px solid var(--rose-deep);
  max-width: none;
}

/* === COMPARE === */
.compare {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1px;
  background: var(--line);
  border: 1px solid var(--line);
  border-radius: 4px;
  overflow: hidden;
}
.compare-col { padding: 48px; background: var(--paper); }
.compare-col.before {
  background: linear-gradient(180deg, rgba(186,190,193,0.15) 0%, var(--paper) 100%);
}
.compare-col.after {
  background: linear-gradient(180deg, rgba(247,189,199,0.18) 0%, var(--paper) 100%);
}
.compare-label {
  display: inline-block;
  font-size: 10px;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  font-weight: 800;
  padding: 6px 12px;
  border-radius: 100px;
  margin-bottom: 24px;
}
.compare-label.bad { background: var(--muted); color: var(--ink); }
.compare-label.good { background: var(--rose-deep); color: var(--paper); }
.compare h3 { margin-bottom: 16px; }
.compare ul { list-style: none; margin-top: 20px; }
.compare li {
  font-size: 14px;
  line-height: 1.6;
  padding: 12px 0;
  border-top: 1px dashed var(--line);
  color: var(--ink-soft);
  display: flex;
  gap: 12px;
}
.compare li::before {
  content: attr(data-mark);
  font-family: 'Fraunces', serif;
  font-style: italic;
  color: var(--rose-deep);
  font-weight: 600;
  flex-shrink: 0;
}

/* === IDENTITY === */
.identity-grid {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 24px;
  margin-top: 60px;
}

.identity-card {
  background: var(--paper);
  border: 1px solid var(--line);
  border-radius: 4px;
  padding: 36px;
  position: relative;
  overflow: hidden;
  transition: transform 0.4s cubic-bezier(0.16, 1, 0.3, 1), box-shadow 0.4s;
}
.identity-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 20px 40px -20px rgba(0,0,0,0.15);
}

.identity-card.logo { grid-column: span 7; min-height: 380px; display: flex; flex-direction: column; }
.identity-card.colors { grid-column: span 5; }
.identity-card.type { grid-column: span 5; }
.identity-card.mascot { grid-column: span 7; min-height: 360px; }

.card-meta {
  font-size: 10px;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--ink-soft);
  font-weight: 700;
  margin-bottom: 16px;
  display: flex;
  align-items: center;
  gap: 8px;
}
.card-meta::before {
  content: "";
  width: 6px;
  height: 6px;
  background: var(--rose-deep);
  border-radius: 50%;
}

.card-title {
  font-family: 'Fraunces', serif;
  font-size: 26px;
  font-weight: 400;
  line-height: 1.15;
  letter-spacing: -0.02em;
  margin-bottom: 20px;
}

.card-text { font-size: 14px; line-height: 1.65; color: var(--ink-soft); }

/* Logo card — bílé pozadí pro logotyp */
.logo-showcase {
  flex: 1;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 20px 0;
  background: var(--white);
  border: 1px solid var(--line);
  border-radius: 4px;
  padding: 40px 24px;
  min-height: 180px;
}
.logo-full-img { width: 100%; max-width: 320px; height: auto; }

.logo-variants {
  display: flex;
  gap: 16px;
  justify-content: center;
  margin-top: 12px;
}
.logo-mini {
  width: 56px;
  height: 56px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 1px solid var(--line);
  overflow: hidden;
}
.logo-mini.dark { background: var(--ink); }
.logo-mini.rose { background: var(--rose); }
.logo-mini.paper { background: var(--white); }
.logo-mini.paper img { filter: invert(78%) sepia(20%) saturate(700%) hue-rotate(305deg) brightness(95%) contrast(95%); }
.logo-mini img { width: 65%; height: auto; }
.logo-mini.dark img { filter: brightness(0) invert(1); }
.logo-mini.rose img { filter: brightness(0); }

/* Colors */
.color-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
  margin-top: 20px;
}
.swatch {
  aspect-ratio: 1.2;
  border-radius: 4px;
  padding: 14px;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  font-size: 11px;
  letter-spacing: 0.05em;
  font-weight: 700;
  position: relative;
  overflow: hidden;
}
.swatch-name { text-transform: uppercase; opacity: 0.6; font-size: 9px; letter-spacing: 0.15em; }
.swatch-hex { font-family: 'Fraunces', serif; font-style: italic; font-weight: 400; font-size: 14px; margin-top: 4px; }
.swatch.gray { background: #BABEC1; color: #2a2a2a; }
.swatch.rose { background: #F7BDC7; color: #5a2a30; }
.swatch.lav { background: #D5BFD6; color: #3d2a40; }
.swatch.terra { background: #EC9B9F; color: #5a1f24; }

/* Typography */
.type-display {
  font-family: 'Nunito', sans-serif;
  font-size: 64px;
  font-weight: 900;
  line-height: 0.95;
  letter-spacing: -0.04em;
  margin: 20px 0;
}
.type-display .small {
  font-size: 24px;
  font-weight: 600;
  opacity: 0.5;
  display: block;
  margin-top: 4px;
}
.type-meta {
  display: flex;
  gap: 20px;
  font-size: 11px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: var(--ink-soft);
  font-weight: 700;
  padding-top: 16px;
  border-top: 1px solid var(--line);
}

/* Mascot */
.identity-card.mascot {
  background: linear-gradient(135deg, var(--lavender) 0%, var(--rose) 100%);
  color: var(--ink);
}
.identity-card.mascot .card-meta::before { background: var(--ink); }
.identity-card.mascot .card-meta { color: var(--ink); }
.identity-card.mascot .card-text { color: var(--ink-soft); }
.mascot-illustration {
  position: absolute;
  right: -30px;
  bottom: -20px;
  width: 280px;
  height: auto;
  opacity: 0.95;
  pointer-events: none;
}

/* === PROCESS === */
.process {
  background: var(--ink);
  color: var(--paper);
  margin: 60px -40px 0;
  padding: 120px 40px;
}
.process .section-label { color: rgba(250,247,243,0.6); }
.process .section-label .line { background: rgba(250,247,243,0.2); }
.process h2 { color: var(--paper); }
.process h2 em { color: var(--rose); }

.process-steps {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 32px;
  margin-top: 60px;
}
.step { border-top: 1px solid rgba(250,247,243,0.2); padding-top: 24px; }
.step-num {
  font-family: 'Fraunces', serif;
  font-style: italic;
  font-size: 48px;
  font-weight: 300;
  color: var(--rose);
  line-height: 1;
  margin-bottom: 16px;
}
.step h4 {
  font-family: 'Fraunces', serif;
  font-size: 22px;
  font-weight: 500;
  margin-bottom: 12px;
  color: var(--paper);
}
.step p { font-size: 14px; color: rgba(250,247,243,0.7); line-height: 1.6; }

/* === APPLICATIONS — reálné obrázky z BP === */
.apps-intro { margin-bottom: 32px; }

.apps-gallery {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  gap: 24px;
  margin-top: 40px;
}

.app-tile {
  background: var(--paper);
  border: 1px solid var(--line);
  border-radius: 4px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  transition: transform 0.4s cubic-bezier(0.16,1,0.3,1), box-shadow 0.4s;
}
.app-tile:hover {
  transform: translateY(-6px);
  box-shadow: 0 24px 50px -20px rgba(0,0,0,0.18);
}

.app-tile.wide { grid-column: span 4; }
.app-tile.normal { grid-column: span 2; }
.app-tile.half { grid-column: span 3; }
.app-tile.full { grid-column: span 6; }

.app-image {
  width: 100%;
  aspect-ratio: 16/9;
  overflow: hidden;
  background: var(--white);
  position: relative;
}
.app-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center;
  display: block;
  transition: transform 0.6s cubic-bezier(0.16,1,0.3,1);
}
.app-tile:hover .app-image img { transform: scale(1.03); }

.app-tile.tall .app-image { aspect-ratio: 3/4; background: #f5f1ec; }
.app-tile.tall .app-image img { object-fit: contain; padding: 16px; }
.app-tile.full .app-image { aspect-ratio: 21/9; }

.app-content { padding: 24px 28px 28px; }
.app-meta-label {
  font-size: 10px;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  font-weight: 800;
  color: var(--ink-soft);
  margin-bottom: 8px;
}
.app-title {
  font-family: 'Fraunces', serif;
  font-size: 22px;
  font-weight: 500;
  line-height: 1.2;
  letter-spacing: -0.02em;
  margin-bottom: 8px;
}
.app-desc {
  font-size: 13px;
  line-height: 1.55;
  color: var(--ink-soft);
}

/* === OUTRO === */
.outro { text-align: center; padding: 160px 40px; }
.outro h2 {
  font-size: clamp(48px, 8vw, 120px);
  margin: 0 auto 32px;
  max-width: 900px;
}
.outro p { margin: 0 auto 48px; font-size: 18px; }
.signature {
  display: inline-flex;
  align-items: center;
  gap: 16px;
  padding: 16px 28px;
  border: 1px solid var(--ink);
  border-radius: 100px;
  font-size: 13px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  font-weight: 700;
  transition: all 0.3s;
  text-decoration: none;
  color: var(--ink);
}
.signature:hover { background: var(--ink); color: var(--paper); }
.signature span {
  font-family: 'Fraunces', serif;
  font-style: italic;
  font-weight: 400;
  text-transform: none;
  letter-spacing: 0;
}

footer {
  border-top: 1px solid var(--line);
  padding: 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 12px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: var(--ink-soft);
  font-weight: 600;
  position: relative;
  z-index: 2;
}

/* Reveal */
.reveal {
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 0.9s cubic-bezier(0.16,1,0.3,1), transform 0.9s cubic-bezier(0.16,1,0.3,1);
}
.reveal.visible { opacity: 1; transform: translateY(0); }

@media (max-width: 980px) {
  .hero { grid-template-columns: 1fr; padding: 120px 24px 60px; gap: 40px; }
  .hero-visual { aspect-ratio: 1; max-width: 380px; }
  .scroll-down { display: none; }
  section { padding: 80px 24px; }
  .about { grid-template-columns: 1fr; gap: 40px; }
  .about-stats { position: static; flex-direction: row; flex-wrap: wrap; }
  .about-stats .stat { flex: 1; min-width: 140px; }
  .compare { grid-template-columns: 1fr; }
  .identity-grid { grid-template-columns: 1fr; }
  .identity-card.logo, .identity-card.colors,
  .identity-card.type, .identity-card.mascot { grid-column: span 1; }
  .process { margin: 60px -24px 0; padding: 80px 24px; }
  .process-steps { grid-template-columns: 1fr 1fr; gap: 24px; }
  .apps-gallery { grid-template-columns: 1fr 1fr; }
  .app-tile.wide, .app-tile.normal, .app-tile.half, .app-tile.full { grid-column: span 2; }
  nav { padding: 16px 20px; }
  .nav-links { display: none; }
  footer { flex-direction: column; gap: 16px; padding: 30px 24px; text-align: center; }
  .mascot-illustration { width: 200px; right: -20px; bottom: -10px; }
}
@media (max-width: 560px) {
  .apps-gallery { grid-template-columns: 1fr; }
  .app-tile.wide, .app-tile.normal, .app-tile.half, .app-tile.full { grid-column: span 1; }
  .process-steps { grid-template-columns: 1fr; }
  .pullquote { font-size: 24px; padding-left: 16px; }
  .type-display { font-size: 44px; }
}
</style>
</head>
<body>

<nav>
  <div class="nav-logo">Váš<span>/</span>praktik <em style="font-style:italic; font-weight:400; opacity:0.5; margin-left:8px;">rebrand</em></div>
  <ul class="nav-links">
    <li><a href="#problem">Problem</a></li>
    <li><a href="#identity">Identity</a></li>
    <li><a href="#process">Process</a></li>
    <li><a href="#applications">Applications</a></li>
  </ul>
</nav>

<main>

<!-- HERO -->
<section class="hero">
  <div class="hero-content reveal visible">
    <div class="hero-meta">
      <span>Bachelor's thesis · 2026</span>
      <div class="divider"></div>
      <span>Rebranding · Visual identity · Healthcare</span>
    </div>
    <h1>A clinic that's not <em>afraid</em><br>to be human.</h1>
    <p class="hero-intro">
      Case study of the rebranding for <strong>Váš praktik</strong> — from a scattered collection of animal illustrations to a coherent visual system built for adult patients of the digital generation.
    </p>
    <div class="hero-tags">
      <span class="tag filled">Visual identity</span>
      <span class="tag">Logo</span>
      <span class="tag">Mascot</span>
      <span class="tag">Web · Print · Outdoor</span>
    </div>
  </div>

  <div class="hero-visual reveal visible">
    <div class="logo-stage">
      <img class="vp-logo-img" src="images/sym.png" alt="Váš praktik monogram">
    </div>
    <div class="logo-caption">V·P monogram — original construction</div>
  </div>

  <div class="scroll-down">Scroll</div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="section-label">
    <span class="num">01</span>
    <span>About the project</span>
    <div class="line"></div>
  </div>

  <div class="about">
    <div class="about-stats">
      <div class="stat">
        <div class="stat-label">Client</div>
        <div class="stat-value">Váš praktik<br>network of general practice clinics</div>
      </div>
      <div class="stat">
        <div class="stat-label">Target audience</div>
        <div class="stat-value">Adults 20–40<br>the digital generation</div>
      </div>
      <div class="stat">
        <div class="stat-label">Role</div>
        <div class="stat-value">Analysis, concept, visual system, applications</div>
      </div>
      <div class="stat">
        <div class="stat-label">Year</div>
        <div class="stat-value">2026</div>
      </div>
    </div>

    <div class="about-text">
      <h2>A clinic for adults that looked like a <em>pediatric office</em>.</h2>
      <p>
        Váš praktik is a network of modern general practice clinics. The ambulances run CRP, ECG, and blood pressure holter — technologically everything is up to standard. The problem was elsewhere: in the visual communication.
      </p>
      <p>
        The Instagram feed looked like a gallery of fairy-tale animals: a fly in a nurse's cap, a cat for home care, a hippo in the shower. For a patient in their productive years — the primary target group — this generated visual noise that weakened the professionalism and credibility of the brand.
      </p>
      <div class="pullquote">
        „Between the sterile big network and the traditional doctor's office, fill the space for a <em>young clinic for young people</em>."
      </div>
      <p>
        The goal of the rebranding wasn't to "repaint the logo". It was to redefine the relationship between doctor and patient — to create an identity that communicates both stability and humanity, technology and empathy. A safe place that doesn't have a tendency to alienate the patient.
      </p>
    </div>
  </div>
</section>

<!-- PROBLEM / SOLUTION -->
<section id="problem">
  <div class="section-label">
    <span class="num">02</span>
    <span>Before / After</span>
    <div class="line"></div>
  </div>

  <h2 class="reveal">Diagnosis of the old identity.</h2>

  <div class="compare reveal">
    <div class="compare-col before">
      <span class="compare-label bad">Before</span>
      <h3>Fragmented communication</h3>
      <p>The old identity lacked a visual anchor. Each social media post used a different style, different illustrations, different typography.</p>
      <ul>
        <li data-mark="—">Poppins logotype + illustrative stethoscope — blurs when scaled down</li>
        <li data-mark="—">A plurality of animal illustrations without a unifying anchor</li>
        <li data-mark="—">"Praha" in the logo — limits expansion beyond the capital</li>
        <li data-mark="—">Visuals evoke pediatrics despite the focus on adults</li>
        <li data-mark="—">Inconsistency between web ↔ Instagram ↔ print</li>
      </ul>
    </div>

    <div class="compare-col after">
      <span class="compare-label good">After</span>
      <h3>A system, not a collection</h3>
      <p>The new identity stands on one concept — bridging tradition and technology. Everything else flows from it.</p>
      <ul>
        <li data-mark="+">V·P monogram drawn in one continuous line; the cross emerges at the intersection</li>
        <li data-mark="+">Robot mascot as a modular visual system</li>
        <li data-mark="+">Pastel palette humanizes the clinical space</li>
        <li data-mark="+">Nunito — legible, friendly, digitally competent</li>
        <li data-mark="+">Tone of voice: „We're in this with you."</li>
      </ul>
    </div>
  </div>
</section>

<!-- IDENTITY -->
<section id="identity">
  <div class="section-label">
    <span class="num">03</span>
    <span>Visual identity</span>
    <div class="line"></div>
  </div>

  <h2 class="reveal">Four building blocks of a <em>new language</em>.</h2>

  <div class="identity-grid">

    <div class="identity-card logo reveal">
      <div class="card-meta">Logo · Monogram</div>
      <h3 class="card-title">One line. Two letters. A cross within.</h3>
      <p class="card-text">The V·P monogram is drawn as a single continuous curve — softness, fluidity, a human touch. At the intersection of the lines a cross naturally emerges, a clinical symbol that isn't stuck on, but is the result of the geometry itself.</p>

      <div class="logo-showcase">
        <img class="logo-full-img" src="images/logotyp-dark.png" alt="Váš praktik logo">
      </div>

      <div class="logo-variants">
        <div class="logo-mini dark"><img src="images/sym.png" alt=""></div>
        <div class="logo-mini rose"><img src="images/sym.png" alt=""></div>
        <div class="logo-mini paper"><img src="images/sym.png" alt=""></div>
      </div>
    </div>

    <div class="identity-card colors reveal">
      <div class="card-meta">Palette</div>
      <h3 class="card-title">Calm without sterility.</h3>
      <p class="card-text">Grey as the technological backbone, balanced by emotional tones. No saturated blue. No hospital white. Pastels that humanize.</p>
      <div class="color-grid">
        <div class="swatch gray">
          <div class="swatch-name">Steel</div>
          <div class="swatch-hex">#BABEC1</div>
        </div>
        <div class="swatch rose">
          <div class="swatch-name">Rose</div>
          <div class="swatch-hex">#F7BDC7</div>
        </div>
        <div class="swatch lav">
          <div class="swatch-name">Lavender</div>
          <div class="swatch-hex">#D5BFD6</div>
        </div>
        <div class="swatch terra">
          <div class="swatch-name">Terra</div>
          <div class="swatch-hex">#EC9B9F</div>
        </div>
      </div>
    </div>

    <div class="identity-card type reveal">
      <div class="card-meta">Typography</div>
      <h3 class="card-title">Nunito — round, clear, friendly.</h3>
      <div class="type-display">
        Aa
        <span class="small">Nunito ExtraBold / SemiBold</span>
      </div>
      <p class="card-text">Rounded terminals harmonize with the organic line of the logo. High legibility at small formats and in internal documentation.</p>
      <div class="type-meta">
        <span>Display · 900</span>
        <span>Body · 600/400</span>
      </div>
    </div>

    <div class="identity-card mascot reveal">
      <div class="card-meta">Mascot</div>
      <h3 class="card-title">A robot with a hand-drawn line.</h3>
      <p class="card-text">A humanoid figure at the boundary of technology and empathy. A heart with a pulse on the chest, an organic illustrative line — a machine that bears a human imprint. Modular system: doctor, nurse, educator, in-app guide.</p>
      <img class="mascot-illustration" src="images/robot-family.png" alt="Mascot family — robot with variants">
    </div>

  </div>
</section>

<!-- PROCESS -->
<section id="process" class="process">
  <div class="section-label">
    <span class="num">04</span>
    <span>Process</span>
    <div class="line"></div>
  </div>

  <h2 class="reveal">From analysis to <em>system</em>.</h2>

  <div class="process-steps">
    <div class="step reveal">
      <div class="step-num">01</div>
      <h4>Audit</h4>
      <p>An in-depth analysis of current communication across all channels. Identifying the gap between the service offered and how it presents itself visually.</p>
    </div>
    <div class="step reveal">
      <div class="step-num">02</div>
      <h4>Competition</h4>
      <p>A comparison of five players — from small clinics (PrahaMed, Salubrita) to networks (EUC, AGEL) and premium care (Canadian Medical). Looking for the white space.</p>
    </div>
    <div class="step reveal">
      <div class="step-num">03</div>
      <h4>Persona</h4>
      <p>Eliška, 24, student. Prefers digital over phone. Looking for a clinic that feels like a safe place, not a government office.</p>
    </div>
    <div class="step reveal">
      <div class="step-num">04</div>
      <h4>System</h4>
      <p>Logo, palette, typography, mascot, tone of voice. Applied to every touchpoint — print, web, interior, social.</p>
    </div>
  </div>
</section>

<!-- APPLICATIONS -->
<section id="applications">
  <div class="section-label">
    <span class="num">05</span>
    <span>Applications</span>
    <div class="line"></div>
  </div>

  <h2 class="reveal">One system. <em>Many touchpoints</em>.</h2>
  <p class="reveal apps-intro">
    The identity lives on posters in the waiting room, in Instagram posts, on the doctors' business cards, on the 3D logo above the entrance, and in a guerrilla campaign at a trade fair. The same voice everywhere.
  </p>

  <div class="apps-gallery">

    <div class="app-tile wide reveal">
      <div class="app-image">
        <img src="images/business-cards.jpg" alt="Business cards — Váš praktik">
      </div>
      <div class="app-content">
        <div class="app-meta-label">01 · Business cards</div>
        <div class="app-title">Rose on rose.</div>
        <div class="app-desc">A monochromatic palette derived from the brand's signature color. The front carries the bold mark; the back keeps contact information clean and scannable.</div>
      </div>
    </div>

    <div class="app-tile normal tall reveal">
      <div class="app-image">
        <img src="images/robot-main.jpg" alt="Robot mascot — main character">
      </div>
      <div class="app-content">
        <div class="app-meta-label">02 · Plush mascot</div>
        <div class="app-title">A robot you can hug.</div>
        <div class="app-desc">A physical version of the mascot for the waiting room — a humanizing object that softens the clinical environment.</div>
      </div>
    </div>

    <div class="app-tile half reveal">
      <div class="app-image">
        <img src="images/instagram.jpg" alt="Instagram feed — Váš praktik">
      </div>
      <div class="app-content">
        <div class="app-meta-label">03 · Instagram</div>
        <div class="app-title">Education, not noise.</div>
        <div class="app-desc">Templates combine real photos from the clinic with mascot illustrations. Topics like prevention, modern diagnostics, and lifestyle tips delivered with visual consistency.</div>
      </div>
    </div>

    <div class="app-tile half reveal">
      <div class="app-image">
        <img src="images/indoor.jpg" alt="Uniforms, notebooks, mugs, masks">
      </div>
      <div class="app-content">
        <div class="app-meta-label">04 · Indoor marketing</div>
        <div class="app-title">Uniforms. Notebooks. Mugs.</div>
        <div class="app-desc">Discreetly branded interior elements that improve both the patient's stay and the staff's daily routine — a coherent ecosystem of small, considered details.</div>
      </div>
    </div>

    <div class="app-tile half reveal">
      <div class="app-image">
        <img src="images/exterior.jpg" alt="Clinic exterior visualization">
      </div>
      <div class="app-content">
        <div class="app-meta-label">05 · Exterior / 3D signage</div>
        <div class="app-title">A storefront that breathes.</div>
        <div class="app-desc">A 3D logo above the entrance, large-format glazing, soft material palette — a "healing environment" that signals trust at first contact.</div>
      </div>
    </div>

    <div class="app-tile half reveal">
      <div class="app-image">
        <img src="images/guerilla.jpg" alt="Guerrilla marketing at a trade fair">
      </div>
      <div class="app-content">
        <div class="app-meta-label">06 · Guerrilla campaign</div>
        <div class="app-title">Branded glucose at a trade fair.</div>
        <div class="app-desc">Free dextrose tabs distributed during peak fatigue hours. Each wrapper carries a QR code leading directly to the booking system. Slogan: "At the fair, sugar saves you. In life, Váš praktik."</div>
      </div>
    </div>

  </div>
</section>

<!-- OUTRO -->
<section class="outro">
  <div class="section-label" style="justify-content:center;">
    <span class="num">06</span>
    <span>Outcome</span>
  </div>
  <h2 class="reveal">Rebranding isn't <em>a new logo</em>.<br>It's a new relationship.</h2>
  <p class="reveal">
    Today Váš praktik speaks with one voice — online, in the waiting room, and in stories. A patient meets the brand at home on their phone or at the reception desk and, in either place, recognizes that they're home.
  </p>
  <a href="#" class="signature reveal">
    <span>Jevgenija Diděnko</span>
    · BA · VŠKK 2026
  </a>
</section>

</main>

<footer>
  <div>Váš praktik · Rebranding case study</div>
  <div>Bachelor's thesis · VŠKK 2026 · J. Diděnko</div>
</footer>

<script>
const observer = new IntersectionObserver((entries) => {
  entries.forEach((entry, i) => {
    if (entry.isIntersecting) {
      setTimeout(() => entry.target.classList.add('visible'), i * 80);
      observer.unobserve(entry.target);
    }
  });
}, { threshold: 0.15, rootMargin: '0px 0px -80px 0px' });

document.querySelectorAll('.reveal').forEach(el => {
  if (!el.classList.contains('visible')) observer.observe(el);
});

const stage = document.querySelector('.logo-stage');
if (stage && window.matchMedia('(min-width: 980px)').matches) {
  document.addEventListener('mousemove', (e) => {
    const x = (e.clientX / window.innerWidth - 0.5) * 10;
    const y = (e.clientY / window.innerHeight - 0.5) * 10;
    stage.style.transform = `translate(${x}px, ${y}px)`;
  });
}
</script>

</body>
</html>
