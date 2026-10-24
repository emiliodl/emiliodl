<h1 align="center">Emiliano Dias</h1>

<p align="center">
<b>M.Sc. student in Electrical Engineering @ University of São Paulo (EESC-USP)</b><br>
Machine learning for energy time series · Non-Intrusive Load Monitoring · Applied AI automation
</p>

<p align="center">
<a href="https://www.linkedin.com/in/emilianodias/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:emiliods79@gmail.com"><img src="https://img.shields.io/badge/Email-emiliods79%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
<img src="https://img.shields.io/badge/Location-Brazil-009C3B?style=flat-square" alt="Location: Brazil">
</p>

---

## About me

I am a Master's student in Signal Processing & Instrumentation at the São Carlos School of
Engineering (EESC), University of São Paulo. My research is on **Non-Intrusive Load
Monitoring (NILM)**: recognizing which household appliances are running from a single
smart-meter reading, with a focus on the low sampling rates (5–15 min) that real meters
record and on models that still work in houses they were not trained on.

I also work in industry as an **Integrated Operations Analyst at Méliuz**, where I build
AI-powered automation: LLM agents and n8n workflows for fraud detection, contract
compliance review and IT support, on Google Cloud.

I care about results that hold up: pre-registered evaluations, statistical tests, honest
baselines and reproducible code.

## Research

| Repository | Summary | Stack |
|---|---|---|
| [**CRAFT**](https://github.com/emiliodl/CRAFT) | Appliance on/off detection from 5- and 15-min smart-meter data. Trains on *recomposed* aggregates (real appliance activations over other days' background) so the model cannot rely on usage-habit shortcuts; ensemble of 1D ResNets plus a sign-constrained edge detector. Compared with a published low-rate NILM benchmark under a pre-registered protocol with day-block bootstrap and Holm correction. | PyTorch · NumPy · pandas |
| [**FastMV-NILM**](https://github.com/emiliodl/FastMV-NILM) | Fast feature extraction for image-based NILM. Shrinking the encoded image to 56×56 before a frozen MobileNetV3 cuts extractor latency by 72% without losing F1, and the saved time pays for fusing several time-series image encodings (TBG, GASF, GADF, RP, MTF). | TensorFlow/Keras · XGBoost · scikit-learn |
| [nilm_dft](https://github.com/emiliodl/nilm_dft) | Exploratory notebooks (DFT, FIR and wavelet front-ends for MobileNet features) that led to FastMV-NILM. | Jupyter |

## Other projects

| Repository | Summary |
|---|---|
| [CEREIA6](https://github.com/emiliodl/CEREIA6) | MVP that matches oncology patients to open clinical trials by biomarkers, staging and MeSH terms (CRIA project). Streamlit. |
| [trab-final-visao](https://github.com/emiliodl/trab-final-visao) | Parking-space occupancy detection from video with OpenCV. |
| [trab01-seg](https://github.com/emiliodl/trab01-seg) | OpenSSL-compatible key management and file encryption tool. |

## Publications

- K. P. de Lima, **E. D. S. C. Lima**, C. A. L. de Campos, V. A. C. C. Almeida, R. A. L. Rabêlo.
  *Clinic Match: Facilitating Clinical Trials with Text Mining.* ERCEMAPI, SBC.
  [[paper]](https://sol.sbc.org.br/index.php/ercemapi/article/view/30193)

Manuscripts in preparation: CRAFT and FastMV-NILM (see the repositories above).

## Education

- **M.Sc., Electrical Engineering** (Signal Processing & Instrumentation): University of São Paulo, EESC-USP, 2026–2028
- **B.Sc., Computer Science**: Federal University of Piauí, UFPI, 2022–2026
  - CNPq/PIBITI undergraduate research fellow
  - Teaching assistant: Distributed Systems, Relational Databases, Graph Theory & Applications

## Tech stack

| Area | Tools |
|---|---|
| Machine learning | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) |
| Data & signal processing | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) |
| Cloud, data & apps | ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) |
| Automation & agents | ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square) |
| Tooling | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Conda](https://img.shields.io/badge/Conda-44A833?style=flat-square&logo=anaconda&logoColor=white) ![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white) |

## Currently

- Writing up CRAFT and FastMV-NILM for publication.
- Fine-tuning Distil-Whisper for Brazilian Portuguese speech recognition (WER reduction with VAD, LM rescoring and text normalization).
- Building MCP-based integrations that give LLM agents safe, structured access to internal APIs.
