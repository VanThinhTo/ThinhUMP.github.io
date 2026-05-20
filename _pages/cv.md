---
layout: archive
title: "Curriculum vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download the latest PDF CV [here](/cv/CV_summer_intern.pdf).

Education
======
* **2025 - expected 2027:** Erasmus Mundus Scholar, Double Degree Master's Program
  * Master of Bioinformatics, [University Paris Cite](https://u-paris.fr/en/), France. GPA: 18.05 / 20.00.
  * Master of Chemistry, [University of Milan](https://www.unimi.it/it), Italy. GPA: 18.05 / 20.00.
* **2019 - 2024:** Bachelor of Pharmacy, [University of Medicine and Pharmacy at Ho Chi Minh City](https://ump.edu.vn/), Vietnam. GPA: 3.31 / 4.00; ranking: Top 4%.
  * Thesis: "A Knowledge-Guided Graph Self-Supervised Learning for Molecular Property Predictions." Grade: 10 / 10.

Research Experience
======
* **Sep 2025 - present: Master researcher, University Paris Cite, France**
  * Supervisors: Prof. Olivier Taboureau and Assistant Prof. Viet-Khoa Tran-Nguyen.
  * **PubChem and ChEMBL benchmarking data sets**
    * Automating large-scale retrieval of bioactivity data for all protein targets from PubChem and ChEMBL.
    * Identifying dark chemical matter compounds for use as assumed inactives.
    * Conducting virtual screening benchmarking studies across selected protein targets.
  * **Jan 2026: Target-specific machine learning scoring functions for cystathionine beta-synthase inhibitors**
    * Curated data sets from PubChem and ChEMBL.

* **Jun 2022 - Aug 2025: Undergraduate researcher, University of Medicine and Pharmacy at Ho Chi Minh City, Vietnam**
  * Supervisors: [Assoc. Prof. Tuyen Ngoc Truong](http://uphcm.edu.vn/emplinfo.aspx?EmplCode=truongngoctuyen) and [PhD Researcher Tieu-Long Phan](https://tieulongphan.github.io/).
  * **May 2024 - Aug 2025: Generative AI for dual targets of EGFR and VEGFR**
    * Developed a knowledge-guided graph-based scoring function to evaluate generated molecules.
  * **Dec 2023 - Jul 2024: Knowledge-guided graph for molecular representation**
    * Introduced pre-text tasks for self-supervised learning guided by orbital information.
    * Proposed a knowledge-guided graph using hierarchical molecular graphs, defragmentation, and two orbital-information knowledge vectors for molecular representation.
    * Improved ROC-AUC by 2.4% for classification and reduced RMSE and MAE by 39% and 14% for regression compared with a state-of-the-art MoleculeNet model.
  * **Jun 2022 - Jan 2024: Machine learning in virtual screening of HIV integrase inhibitors**
    * Identified applicability domains of machine learning models using Principal Component Analysis and convex hull techniques.
  * **Jun 2023 - Dec 2023: Molecular similarity, neural network, and GNINA docking for PD-L1 inhibitors**
    * Proposed an artificial neural network model and molecular similarity assessment with GNINA 1.0 molecular docking.
    * Developed an automated pipeline for the molecular similarity model.
    * Screened 15,235 DrugBank repurposing compounds and identified 22 hit compounds.
  * **Dec 2022 - Jun 2023: Machine learning, deep neural networks, and consensus molecular docking for ALK inhibitors**
    * Trained an ensemble model including a graph neural network, artificial neural network, and XGBoost model to predict potential Anaplastic Lymphoma Kinase inhibitors.

Teaching Experience
======
* **Aug 2024 - Aug 2025: Contracted teaching assistant and research mentoring, Department of Organic Chemistry, Faculty of Pharmacy, University of Medicine and Pharmacy at Ho Chi Minh City**
  * Wrote research proposals for four university-funded projects, each awarded 1200 USD.
  * Prepared computer-aided drug design training materials for undergraduate students, including RDKit, fingerprints, molecular descriptors, ANN, and GNN.
  * Mentored one undergraduate thesis student on self-supervised learning.
  * Taught practical organic chemistry, including laboratory equipment proficiency, ChemDraw, lab techniques, and synthesis skills.

Skills
======
* **Cheminformatics:** RDKit; machine learning (Scikit-learn); deep learning (TensorFlow, PyTorch); molecular docking (GNINA); generative diffusion model (IRDiff); property-matched decoy generation (DeepCoy); databases (PDB, PubChem, ChEMBL); visualization (PyMOL).
* **Programming:** Python, R, C, Linux terminal, Pytest, Git, package management, deployment.
* **Languages:** Vietnamese (native); English (IELTS Academic Overall 7.0, Nov 2024).

Training
======
* **Sep 2023: Vienna Summer School on Drug Design, Austria**
  * Gained foundational training in drug discovery using docking, pharmacophore, and molecular simulation tools including LigandScout, KNIME, and OpenEye.
  * Learned drug discovery concepts including generative models.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
* **2025:** To, V.-T. et al. KGG: Knowledge-Guided Graph Self-Supervised Learning to Enhance Molecular Property Predictions. 41st Scientific and Technical Conference of Pharmacy. Oral presenter.
* **2023:** To, V.-T., Phan, T.-L. & Ngoc Doan, B.-V. Application of Molecular Similarity and Artificial Neural Networks for PD-L1 inhibitors Virtual Screening. ECMC2023: 9th International Electronic Conference on Medicinal Chemistry. Poster presenter.
  
Selected Awards
======
* **2019 - 2024:** Pharmacy Scholarship for Elite Students. Awarded a 5000 USD stipend over 5 years, covering full tuition (acceptance rate: 10%).
* **2018, 2019:** Second prize in the nationwide Vietnamese Chemistry Olympiad. Ranked 42 overall among 400+ participants in Vietnam's largest chemistry competition.
* **2019, 2024:** Odon Vallet Scholarship. Awarded to outstanding high school, university, and graduate students in Vietnam, among over 1,000 recipients nationwide.

References
======
* [**Assoc. Prof. Tuyen Ngoc Truong**](http://uphcm.edu.vn/emplinfo.aspx?EmplCode=truongngoctuyen)
  * University of Medicine and Pharmacy at Ho Chi Minh City, Vietnam
  * Email: [truongtuyen@ump.edu.vn](mailto:truongtuyen@ump.edu.vn)

* [**PhD Researcher Tieu-Long Phan**](https://tieulongphan.github.io/)
  * University Leipzig, Germany
  * Email: [tieu@bioinf.uni-leipzig.de](mailto:tieu@bioinf.uni-leipzig.de)
