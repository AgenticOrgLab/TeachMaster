# <img src="figs/teachmaster_logo.png" alt="TeachMaster logo" width="52" style="vertical-align: middle; transform: translateY(2px);"> TeachMaster: Generative Teaching via Code

**TeachMaster** is a code-centric multi-agent framework for **Generative Teaching**, turning pedagogical intent into curriculum-ready educational videos.

<p>
  <a href="https://www.teachmaster.cn"><strong>🌐 Project Website</strong></a>
  ·
  <a href="#-english">English</a>
  ·
  <a href="#-中文">中文</a>
</p>

**Paper:** *TeachMaster: Generative Teaching via Code*  
**Affiliation:** School of Artificial Intelligence, Shanghai Jiao Tong University  
**Website:** [www.teachmaster.cn](https://www.teachmaster.cn)

---

## 🇬🇧 English

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

---

## 🇨🇳 中文

TeachMaster 提出了 **Generative Teaching（生成式教学）** 这一新范式：教师不再需要手动完成课程视频制作中的每一个细节，而是以“教学导演”的方式给出教学目标、课程大纲和内容意图，由多智能体系统自动完成内容规划、视觉生成、语音合成、同步校验和质量优化。

与直接生成像素级视频的黑盒方法不同，TeachMaster 使用 **可执行代码作为中间语义媒介**。这种方式让生成结果具备更好的可解释性、可编辑性和可控性，更适合严肃教学场景中的规模化内容生产。

## 🌟 项目亮点

- **面向教学意图的生成**：将课程大纲和教学目标转化为完整的多模态教学视频。
- **以代码为语义中介**：通过可执行视觉代码控制结构、节奏、布局和动画逻辑。
- **多智能体协作流程**：覆盖内容规划、视觉合成、旁白生成、语音合成、调试、同步和布局优化。
- **人在回路的精修能力**：支持自然语言修改，也支持直接进行代码级精细编辑。
- **跨模态语义对齐**：保持画面、旁白和教学逻辑之间的一致性。
- **跨语言、跨学科适用**：支持中英文课程内容生成，并可覆盖理工、人文和职业教育等多个领域。

## 🏗️ 系统框架

TeachMaster 将教学视频生产拆解为三个主要阶段：

1. **内容规划**  
   将原始教学意图转化为连贯的讲稿和页面级教学蓝图。

2. **演示生成**  
   将每个页面蓝图转化为代码驱动的视觉动画、旁白文本和语音内容。

3. **质量校验**  
   通过迭代式调试、音画同步和布局优化，提高视频生成的稳定性和教学可读性。

## 📈 实验与部署

实验结果表明，TeachMaster 在保持接近人工制作教学视频质量的同时，显著提升了生产效率，并优于端到端视频生成基线在教学结构、可控性和跨模态一致性方面的表现。

TeachMaster 在以下方面表现突出：

- 视频生成质量，
- 教学讲稿质量，
- 跨模态语义对齐，
- 内容生产效率，
- 真实教学场景中的教师和学生反馈。

在实际部署中，TeachMaster 已服务 **1,000+ 名教师**，生成 **30,000+ 分钟**教学内容，覆盖 **40+ 个学科方向**。制作一门标准 45 小时学期课程的成本约为传统在线课程制作成本的 **0.3%**。

## 🗂️ 仓库内容

本仓库包含 TeachMaster 论文相关的源文件和素材，包括 ACL 风格 LaTeX 稿件、参考文献、样式文件以及论文中使用的图表资源。

## 📝 引用

如果 TeachMaster 对你的研究或项目有帮助，欢迎在官方引用信息发布后引用我们的论文。
