# Hi, I'm Chia-Hsiang Chen 👋

**Data Science · Machine Learning · LLM Applications**　｜　資料科學 · 機器學習 · LLM 應用

---

🎓 碩士論文（代表作）— 多代理 LLM「專利 FTO 初篩」系統 × 行為評估方法論
核心問題：在沒有標準答案（no ground truth）的 FTO 場景，如何嚴謹評估一個多代理 LLM 系統「可不可靠」？

學術核心貢獻——可遷移的 LLM 行為評估方法論：三層漸進式框架（穩定性 → 行為模式 → 因子探索），以探索性資料分析取代假設檢驗；結合非監督式學習（K-means／PCA）、Bootstrap BCa 與效應量處理小樣本與高隨機性。核心邏輯「先立穩定性、再探行為」可移轉至其他無標準答案的 LLM 系統——並以誠實報告負面結果（R²=0.039、統計效力不足）展現方法論紀律。

量化結果：200 次受控執行——Layer 1 穩定性 n=50（自洽性 92.5%）、Layer 2 行為模式 n=120（PCA 揭示四代理二維結構、K-means 四群）、Layer 3 資訊完整度 n=30（探索性、不做因果推論）。結論：系統達可接受的行為穩定性，92.5% 可作為企業導入的穩定性基準線。

支撐系統（工程）：四代理並行（保守／技術／商業／法律）+ Meta-Evaluator 三層推理；FAISS 向量檢索 + 跨語言查詢 + CPC 重排序 + RAG；FastAPI + React 全端；10,000 筆 USPTO ICT 專利。

全端獨立開發。原始碼非公開，可於面談完整展示系統與程式碼。

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
