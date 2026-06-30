# Caglar Oksuz

Welcome to my personal academic webpage! 

I am a Ph.D. candidate and Callahan Fellow in Computer Science at Case Western Reserve University specializing in the security and privacy of machine learning. My research evaluates how models behave after deployment, especially through realistic black-box interfaces that expose only limited outputs, and studies privacy leakage and adversarial vulnerabilities via explainable AI, model extraction, membership inference, model inversion, and privacy risk quantification. 

My work focuses on:
- **Privacy**
- **Explainable AI (XAI)**
- **Adversarial Machine Learning**
- **Artificial Intelligence and Machine Learning (AI/ML)**


## 🎓 Education

Ph.D. in	Computer Science @ Case Western Reserve University (_Present_)

M.S.  in Computer Engineering @ Bilkent University (_August 2020_)   

B.S.  in Computer Engineering @ Bilkent University (_June 2017_) (_Minor in Psychology_)

Erasmus+ Exchange Student @ Roskilde University (_June 2015_)


## 💼 Experience

**Graduate Researcher @ Case Western Reserve University (_Aug 2021 – present_)**  

- Developing a **model inversion framework** to reconstruct sensitive training data from face recognition models (e.g., FaceNet) for privacy risk quantification, leveraging generative AI techniques including diffusion models (e.g., DDPM, conditional diffusion) built with PyTorch and Hugging Face, and gradient-based explanation methods (e.g., layer-wise relevance propagation, class activation maps). Pipeline is containerized and runs on GPU-accelerated HPC clusters (SLURM, Tesla V100).
- Developed a query-efficient, black-box, label-only **membership inference framework** using active and transfer learning. Reduced per-sample query cost from hundreds of online queries to a single query by training a surrogate under a fixed budget (active + transfer learning). Achieved up to a 1000x reduction in query overhead compared to prior label-only membership inference attacks, with models tuned via grid search, applied defenses (DP-SGD, L2 regularization), and networks trained in PyTorch. [GitHub Repo](https://github.com/acoksuz/LoMime) (Private, will be public after publication)
- Developed a **model extraction framework** on Python by exploiting LIME and SHAP to steal black-box MLaaS models (in Google Cloud, Amazon SageMaker, IBM Watson) under restrictive threat models and reduced query overhead by up to 240x. Built Dockerized pipeline for containerization with unit/integration tests and deployed it on GitHub. [GitHub Repo](https://github.com/acoksuz/AUTOLYCUS)
- Applied extensive prompt engineering and LLM-assisted workflows (e.g., Anthropic and OpenAI models) to write, reproduce, and edit research artifacts, experiment scripts, and paper figures, accelerating the research and engineering cycle. The developed frameworks are integrated into an NSF-funded cyberinfrastructure project, deployed across supercomputer and HPC systems as privacy quantification tools.

**Graduate Researcher @ Bilkent University (_Sep 2017 – Aug 2020_)**  
- Developed a privacy-preserving **genomic watermarking framework** on MATLAB using local differential privacy and belief propagation for GDPR/HIPAA compliant data sharing, and achieved 80% detection with under 5% utility loss against collusion attacks. [GitHub Repo](https://github.com/acoksuz/PPRW_SGD_BPLDP)

**Software Engineering Intern @ ASELSAN (_Jul 2015 – Aug 2015_)**  
- Developed a prototype responsive **UI and control panel** for a telecommunication hardware using ASP.NET MVC 5 and C#.
 
**Software Engineering Intern @ Nokta Medya (_Aug 2014- Sep 2014_)** 
- Assisted SEO workshops and B2C field studies; analyzed web traffic and user behavior on hosted video sharing platforms using Google Analytics, Excel, and SQL. Conducted competitive analysis on major video streaming platforms to identify strategies for improving organic search visibility and on-site engagement. Presented data-driven findings through data storytelling to stakeholders from diverse backgrounds, including upper management and the CEO, contributing to the adoption of three product features.


## 🔬 Publications

Find my latest research at: [Google Scholar](https://scholar.google.com/citations?user=bu1zAmcAAAAJ)

### LoMime: Query-Efficient Membership Inference using Model Extraction in Label-Only Settings (2026)

This study proposes a query-efficient membership inferfence attack that leverages surrogate models and active learning. ([GitHub Repo](https://github.com/acoksuz/LoMime)) ([doi](https://doi.org/10.48550/arXiv.2602.18934))

### AUTOLYCUS: Exploiting Explainable Artificial Intelligence (XAI) for Model Extraction Attacks against Interpretable Models (2024)

This study proposes a model extraction attack that leverages explainable AI (XAI) techniques to compromise and steal interpretable models. ([GitHub Repo](https://github.com/acoksuz/AUTOLYCUS)) ([doi](https://doi.org/10.56553/popets-2024-0137))

### Privacy-preserving and robust watermarking on sequential genome data using belief propagation and local differential privacy (2021)

This study proposes a robust and privacy-preserving genomic watermarking scheme that embeds identifiable markers into sequential genome data using belief propagation and local differential privacy to resist collusion and inference attacks. ([GitHub Repo](https://github.com/acoksuz/PPRW_SGD_BPLDP)) ([doi](https://doi.org/10.1093/bioinformatics/btab128))



## 🔍 Projects

### Essay Grading (NLP)

A supervised NLP system that grades short essays based on writing style, trained on existing essays and their grades using **WordNet**-based lexical features. Built during graduate NLP coursework.

### Follower Analyzer

A graph-based data analyzer on **Matlab** to extract, evaluate and visualize follower interactions on Instagram. Utilized for keeping track of followers, follower interactions, and notify users for followers who quit following.    

### Family Linker

A **Python** application that automates web scraping and ETL pipelines to extract structured social and familial relationship data of Northeast Ohio residents from voter registration and people finding web sites. Utilized **Jupyter**, and libraries **BeautifulSoup**, **selenium**, **chromium**, **pandas** and **numpy** to automate linkage and analysis. ([GitHub Repo](https://github.com/acoksuz/LOV))

### Spoiler Blocker

A Chrome extension designed to block spoiler content annotated by users on websites. Developed using **React**, **Django**, **MySQL**, and **JavaScript**, deployed via **Google Cloud**, with version control managed through **Git**. ([GitHub Repo](https://github.com/acoksuz/SpoilerBlocker))



## 📬 Contact
If you'd like to collaborate or have any questions, feel free to reach out:
- 📧 Email:    [acoksuz0@gmail.com](mailto:acoksuz0@gmail.com)
- 🌐 Website:  [acoksuz.github.io](https://acoksuz.github.io)
- 💼 LinkedIn: [https://www.linkedin.com/in/acoksuz/](https://www.linkedin.com/in/acoksuz/)
- 🧑‍💻 GitHub:   [https://github.com/acoksuz/](https://github.com/acoksuz)

  

Thank you for visiting! • Powered by [GitHub Pages](https://pages.github.com/)
