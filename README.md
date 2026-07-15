# <img src="figs/teachmaster_logo.png" alt="TeachMaster logo" width="52" style="vertical-align: middle; transform: translateY(2px);"> TeachMaster: Generative Teaching via Code

**TeachMaster** is a code-centric multi-agent framework for **Generative Teaching**, turning pedagogical intent into curriculum-ready educational videos.

<p>
  <a href="https://www.teachmaster.cn"><strong>🌐 Project Website</strong></a>
  ·
  <a href="#-highlights">Highlights</a>
  ·
  <a href="#-framework">Framework</a>
  ·
  <a href="#-results">Results</a>
</p>

**Paper:** *TeachMaster: Generative Teaching via Code*  
**Website:** [www.teachmaster.cn](https://www.teachmaster.cn)

TeachMaster introduces **Generative Teaching**, a new paradigm where educators act as high-level directors while AI agents handle lesson planning, visual design, animation rendering, narration, and quality validation.

Unlike end-to-end pixel-level video generation, TeachMaster uses **executable code as an intermediate semantic medium**. This makes generated teaching videos more interpretable, editable, controllable, and suitable for scalable educational content production.

## ✨ Highlights

- **Intent-driven course creation**: transforms lecture outlines and pedagogical goals into complete multimodal teaching videos.
- **Code-centric generation**: uses executable visual code to preserve structure, timing, layout, and editability.
- **Multi-agent workflow**: coordinates content planning, visual synthesis, narration, TTS, debugging, synchronization, and layout optimization.
- **Human-in-the-loop refinement**: supports both natural-language editing and direct code-level intervention.
- **Cross-modal alignment**: keeps narration, visuals, and instructional logic semantically consistent.
- **Broad applicability**: supports bilingual and cross-disciplinary course generation across STEM, humanities, and professional education.

## 🧩 Framework

TeachMaster decomposes educational video production into three main stages:

1. **Content Planning**  
   Converts raw teaching intents into coherent manuscripts and page-level instructional blueprints.

2. **Presentation Generation**  
   Transforms each blueprint into code-driven visual animations, narration scripts, and synthesized speech.

3. **Quality Validation**  
   Improves rendering reliability, audio-visual synchronization, and layout clarity through iterative debugging and refinement.

## 📊 Results

Experiments show that TeachMaster approaches the quality of human-crafted educational videos while offering a substantial efficiency advantage over traditional production workflows and end-to-end video generation baselines.

TeachMaster demonstrates strong performance in:

- video generation quality,
- educational script quality,
- cross-modal semantic alignment,
- production efficiency,
- real-world educator and student feedback.

In practical deployment, TeachMaster has served **1,000+ educators**, generated **30,000+ minutes** of educational content, and covered **40+ disciplines**. Producing a standard 45-hour semester-long course costs approximately **0.3%** of traditional online course production expenses.

## 📁 Repository Contents

This repository contains the paper source and related assets for TeachMaster, including the ACL-style LaTeX manuscript, bibliography, style files, and figures used in the paper.

## 📌 Citation

If you find TeachMaster useful, please consider citing the paper once the official citation information is available.
