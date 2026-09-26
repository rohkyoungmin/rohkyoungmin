<h1 align="center">Kyoungmin Roh</h1>

<p align="center"><strong>Cybersecurity Researcher &amp; Engineer</strong><br>
Trustworthy AI · Confidential Computing · Embedded and CPS Security</p>

<p align="center">
  <a href="mailto:imsie1@dankook.ac.kr">Email</a> |
  <a href="https://scholar.google.com/citations?user=6O2OMlwAAAAJ">Google Scholar</a> |
  <a href="https://www.linkedin.com/in/kyoungmin-roh-88bb09343/">LinkedIn</a> |
  <a href="https://orcid.org/0009-0005-5060-1255">ORCID</a>
</p>

I am a cybersecurity researcher and a B.E. candidate at Dankook University in South Korea. My work spans **Android malware detection under concept drift**, **trusted execution environments**, and **security for embedded and cyber-physical systems**. I am currently a research intern at Seoul National University, where I study confidential computing for software-defined vehicles and the security of robot foundation models.

## Research experience

### Seoul National University · Security Optimization Research Lab
*Research Intern | Jun 2026 – Present · Seoul, South Korea*

- Designing a Zephyr-in-Realm architecture for software-defined vehicles, with a virtualized ECU isolated using Arm Confidential Compute Architecture (CCA) and Automotive Grade Linux in the IVI domain.
- Developing threat models for hypervisor behavior, shared-memory communication, and trust consistency in virtualized automotive systems.
- Mapping attack surfaces in robot foundation models and vision-language-action systems, from multimodal inputs to closed-loop control.

### Dankook University · Computer Security and Operating Systems Lab
*Undergraduate Research Assistant | Mar 2025 – Jul 2026 · Yongin, South Korea*

- Built temporally separated Android malware evaluation pipelines using API co-occurrence graphs, Louvain/Leiden communities, mixture models, and adaptive thresholds. This work led to first-author journal and conference papers, a patent application, and paper awards.
- Designed and implemented split execution for ML-KEM on Arm TrustZone-A, keeping secret-dependent operations in the Secure World while moving public computation to the Normal World. Evaluated trusted-code size, secure-monitor-call overhead, and latency.

### Indiana University Bloomington · CPS Security Lab
*Research Intern | Oct 2025 – Jan 2026 · Remote*

- Collected and normalized vulnerability reports from OSV, GitHub Issues, and security forums; classified affected components, failure modes, attack surfaces, and security impact for systematic CPS software analysis.

## Publications

**International journal**

1. **Kyoungmin Roh**, Seungmin Lee, Seong-je Cho, Youngsup Hwang, and Dongjae Kim. “[SCAN: Structural Clustering with Adaptive Thresholds for Intelligent and Robust Android Malware Detection under Concept Drift](https://www.sciencedirect.com/org/science/article/pii/S1526149226001244).” *Computer Modeling in Engineering & Sciences*, 2026.

**International conferences**

1. **Kyoungmin Roh**, Seungmin Lee, Seong-je Cho, and Youngsup Hwang. “[ALARM: Android Malware Detection with Leiden API Communities and Robust Mixture of Experts](https://dl.acm.org/doi/10.1145/3748522.3779797).” *ACM/SIGAPP Symposium on Applied Computing (SAC)*, 2026.
2. Nahee Kwon, **Kyoungmin Roh**, Youngsup Hwang, Seong-je Cho, and Boojoong Kang. “C-STAR: Cost-Aware Adaptive Learning under Concept Drift for Android Malware Detection.” *International Conference on Security and Cryptography (SECRYPT)*, 2026.

**Domestic journal and conferences**

1. **Kyoungmin Roh** and Seong-je Cho. “[Concept Drift-Resilient Android Malware Detection via API Co-occurrence Graphs and Louvain Communities](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12586205).” *KIISE Transactions on Computing Practices*, 2026. Invited article.
2. **Kyoungmin Roh**<sup>†</sup>, Nahee Kwon<sup>†</sup>, Suhyeon Park, and Seong-je Cho. “A Lightweight ML-KEM Architecture via Secret-Dependency-Based Partitioning for Embedded TrustZone-A Systems.” *Korea Computer Congress (KCC)*, 2026. **Distinguished Paper Award.**
3. Nahee Kwon, **Kyoungmin Roh**, Suhyeon Park, and Seong-je Cho. “SCA: A Security Descriptor-Guided Logit Calibration Module for Concept Drift Adaptation in Android Malware Detection.” *KCC*, 2026.
4. **Kyoungmin Roh**, Suhyeon Park, and Seong-je Cho. “[Drift-Aware Security Module Based on Louvain Communities for Retraining-Free Android Malware Detection](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12577588).” *Korea Software Congress (KSC)*, 2025. **Best Paper Award.**
5. **Kyoungmin Roh**, Seungmin Lee, Yudam Kim, Seokhyun Ahn, and Seong-je Cho. “Android Malware Detection Using Co-occurrence Graphs of APIs and Louvain Method for Community Detection.” *Workshop on Dependable and Secure Computing (WDSC)*, 2025. **Best Paper Award.**
6. Seungmin Lee, **Kyoungmin Roh**, Jiheon Jung, Suhyeon Park, and Seong-je Cho. “Classifying File Fragment Types for IVI System Forensics.” *WDSC*, 2025.

<sup>†</sup> Co-first authors. See [Google Scholar](https://scholar.google.com/citations?user=6O2OMlwAAAAJ) and the [research papers repository](https://github.com/rohkyoungmin/Research-Papers) for more details.

## Patent application

- **Kyoungmin Roh**, Seungmin Lee, Seong-je Cho, and Yoonho Choi. “A Malware Detection Method Combining Clustering and Supervised Learning Models.” Korean Patent Application **10-2025-0098855**, filed 2025.

## Selected projects

| Project | What I built |
| --- | --- |
| [Safe LiDAR-IVI Embedded Vehicle System](https://github.com/rohkyoungmin/lidar_car_project) | Integrated ROS 2 LiDAR visualization, obstacle indicators, browser-based driving, and motor diagnostics on a Raspberry Pi and Arduino vehicle platform. |
| [Multi-Agent C/C++ Vulnerability Analysis](https://github.com/rohkyoungmin/AISECApp) | Built an LLM-assisted source auditing pipeline that grounds findings in NVD candidates and source evidence; evaluated it on 139 Magma cases and 27 robustness tests. |
| [Split-Kyber for Arm TrustZone-A](https://github.com/Cyber-Security-Contest/Kyber-Split) | Implemented a split-execution ML-KEM prototype to isolate secret-dependent operations while measuring security and performance tradeoffs. |
| [ASX: Android API Sequence Extractor](https://github.com/rohkyoungmin/api-sequence-extractor-gui) | Created a DEX static-analysis pipeline and Electron GUI for repeatable API call-sequence extraction. |
| QRust ([backend](https://github.com/dku-capstone/QRust-BE), [AI](https://github.com/dku-capstone/QRust-AI)) | Built HMAC-signed QR generation and a URL phishing classifier for a mobile detection workflow; undergraduate thesis project. |
| [Post-Quantum Signature System](https://github.com/rohkyoungmin/Post-Quantum-Signature-System) | Implemented Lamport one-time signatures with Merkle-tree aggregation in Python; first place in a cryptography application competition. |

## Selected honors

- **KCC Distinguished Paper Award** (2026), **KSC Best Paper Award** (2025), and **WDSC Best Paper Award** (2025).
- **First place**, Dankook University Cyber Security Contest research-paper track (2025), for split ML-KEM on TrustZone-A.
- **Danwoo Academic Merit Scholarship** (2026), awarded for academic performance in the top 6% of the department.
- **Army Commendation Medal** (2024) and **Best KATUSA Award** (2024) for service with the U.S. Eighth Army.

## Education and service

- **Dankook University** — B.E. candidate in Cybersecurity, expected Feb 2027. GPA: 3.20/4.50. Coursework includes calculus, linear algebra, numerical analysis, probability and statistics, and discrete mathematics.
- **KATUSA, U.S. Eighth Army, 35th Air Defense Artillery Brigade** — Aug 2023 – Feb 2025. Served in supply, environmental, and interpretation roles in a bilingual U.S.–ROK unit; member of the winning Best Warrior Squad.

---

<p align="center"><a href="mailto:imsie1@dankook.ac.kr">imsie1@dankook.ac.kr</a></p>
