---
permalink: /
#title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am **Ruoyu Chen**, a recent graduate with a Master's degree from **the University of Edinburgh**, School of Biological Sciences. My research focuses on **Computational Biology**, particularly on 
**protein tagging site prediction using computational methods**.

I am **actively seeking a PhD position**, with a particular interest in **bioinformatics** and **drug discovery**. I am passionate about using computational tools to address biological questions and translational research challenges.

For more details, please view 
<a href="/files/Ruoyu_Chen_CV_07_21.pdf" class="btn btn-primary" target="_blank">My CV</a>


<div id="publications"></div>
<div class="project-block" style="display: flex; align-items: center; gap: 30px; margin-bottom: 2em; flex-wrap: wrap;">
<h2>📑 Publications</h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
</div>

<div id="research-interest"></div>
## 💕 Research Interest

1. My research interests lie in the **computational analysis of molecular biology**, with a focus on uncovering the mechanisms of genes, proteins, and their interactions. I am particularly interested in developing predictive models to gain insights into complex biological systems.

2. I am also interested in applying these models to **biomedical problems**, such as **genetic variant interpretation**, **target identification**, and **early-stage drug discovery**, by integrating sequence- and structure-based information in a data-driven framework.


<div id="research-experience"></div>
## 🔬 Research Experience
<div class="project-block" style="display: flex; align-items: center; gap: 30px; margin-bottom: 2em; flex-wrap: wrap;">

<!--project1-->
<div style="display: flex; align-items: center; gap: 30px; margin: 2em 0; flex-wrap: wrap;">
  <div style="flex: 1; text-align: center;">
    <img src="/images/proteintagging.png" 
        alt="Protein Tagging Image"
        style="width: 320px; height: 200px; object-fit: contain; border-radius: 12px; box-shadow: 0 6px 20px rgba(0,0,0,0.25); border: 1px solid #ccc;">
  </div>

  <div style="flex: 2;">
  <b>Project 1: Computational prediction of optimal protein tagging sites</b>
  <ul><li>Description: R & Python</li></ul>
  <ol>
    <li>
    In-house computational prediction method TagScore was assessed through benchmarking using DMS data and human clinial insertion data by correlation analysis and ROC/PR analysis, comparing with existing used tolerance metrics pLDDT and RSA.
    </li>
    <li>
    Properties of the proteins predicted by TagScore to prefer N-terminal, C-terminal or internal tagging were explored by the gene enrichment analysis. GTPase-associated proteins were found to possibly prefer internal tagging.
    </li>
  </ol>
  </div> 
</div>

<!--project2-->
<div style="display: flex; align-items: center; gap: 30px; margin: 2em 0; flex-wrap: wrap;">
  <div style="flex: 1; text-align: center;">
    <img src="/images/Project2.png" 
        alt="Protein Tagging Image"
        style="width: 320px; height: 200px; object-fit: contain; border-radius: 12px; box-shadow: 0 6px 20px rgba(0,0,0,0.25); border: 1px solid #ccc;">
  </div>

  <div style="flex: 2;">
  <b>Project 2: Screening of the Protein Phosphatase PPM1B Inhibitors</b>
  <ul><li>Description: PCR & Western Blot & Cell Culture & Inhibitor Screening</li></ul>
  <ol>
    <li>
    Plasmids containting 2p8e mutant were extracted and subjected to PCR validation. Phosphatase PPM1B protein was extracted and purified.
    </li>
    <li>
    39 compunds with preliminary inhibitory effects on PPM1B were confirmed.
    </li>
    <li>
    Compound h3-41f1 with relatively effective inhibition was screened and identified with an IC50 value of 0.38 μM.
    </li>
  </ol>
  </div> 
</div>
</div>

<div id="education"></div>
## 🎓 Educations
- 2023.9-2024.11, **Master of science**

  School of Biological Science, the University of Edinburgh, UK

  Drug Discovery and Translational Biology, 2:1 (Merit)

- 2018.9-2022.6, **Bachelor of Science**

  School of Pharmaceutical Sciences, Shandong University (985 Project), China

  Pharmacy, GPA: 83.37



<div id="professional-experience"></div>
## 🥼 Professional Experience

- Lecturer (Part-time), AI-Driven Protein Design, China (04/2025-Now)

- Drug Inspection (Intern), Comprehensive Business Department and Chemical Office, China (07/2022-09/2022)

- Clinical Pharmacists (Intern), Jinan Central Hospital, China (07/2021-08/2021)

<div id="skills"></div>
## 🧪 Skills
- Programming and Scripting Languages: R, Python, Bash, HTML, JavaScript, SQL

- Biotechnological and Chemical Techniques: Western blot, PCR, Basic anatomy and drug administration in mice and rabbits, Organic synthesis, HPLC, Column Chromatography, Thin Layer Chromatography (TLC)

- Software: PyMol, Chem Draw, Alphafold2/3, ESM-fold, RFdiffusion, GraphPad Prism

- Language: Mandarin (Native), English (IELTS 7.0 overall, Listening 7.5, Speaking 7.5, Reading 7.5)

<div id="honors-and-awards"></div>
## 🏆 Honors and Awards
- Third Class of Academic Scholarship, Shandong University

- Second Class of Artistic Expertise Scholarship, Shandong University

- Excellence Award of "Internet +" Innovation & Entrepreneurship Competition, Shandong University

- First Prize of National College Student Career Development Competition, Shandong University
