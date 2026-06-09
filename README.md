# Hi, I'm Chia-Hsiang Chen 👋

**Data Science · Machine Learning · LLM Applications**　｜　資料科學 · 機器學習 · LLM 應用

---

## 🎓 碩士論文（代表作）— LLM 多代理「專利 FTO 初篩」全端系統

讓技術人員以 **中文描述技術** → **跨語言檢索美國專利** → 進行 **FTO（Freedom to Operate）風險初篩**。在缺乏標準答案的情境下，以非監督式學習與統計驗證行為評估，把 LLM 系統的量化評估。

- **系統架構**：前端 React + TypeScript + Vite + Zustand；後端 FastAPI + WebSocket；核心引擎 FAISS 向量檢索（all-MiniLM-L6-v2）+ Multi-Agent + Meta-Evaluator + RAG，LLM 為 GPT-4o-mini；資料規模 10,000 筆美國 ICT 專利（2023–2025）。
- **多代理設計**：四個差異化視角代理並行（保守風險 / 技術比較 / 商業可行 / 法律風險），Meta-Evaluator 以三層推理整合代理間分歧。
- **評估方法論（學術核心貢獻）**：三層漸進式行為評估，共 **200 次受控執行**——Layer 1 穩定性（n=50，**系統自洽性 92.5%**）、Layer 2 行為模式（n=120，K-means + PCA + Bootstrap BCa，辨識四種代理共識群組）、Layer 3 資訊完整度影響（n=30，探索性、不做因果推論）。
- 全端系統獨立開發。**原始碼非公開，可於面談完整展示系統與程式碼。**

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![SAS](https://img.shields.io/badge/SAS-0766D1?style=flat&logo=sas&logoColor=white)

**ML / DL / LLM**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006600?style=flat)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

LLM · RAG · Multi-Agent · Prompt Engineering · FAISS

**Data / Viz**

![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat&logo=polars&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![NetworkX](https://img.shields.io/badge/NetworkX-2C5BB4?style=flat&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)

**Web / Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

---

> 👇 其他公開專案見下方 **Pinned**。
