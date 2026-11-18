<p align="center">
  <img src="banner.svg" width="100%" alt="Lakshmi Tripura, AI/ML Engineer. Generative AI, LLMs, RAG, AI Agents, MLOps.">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tripura-kanagala-a17942241"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:tripurakanagala21@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/Tripura21?tab=repositories"><img src="https://img.shields.io/badge/Projects-Browse-8B5CF6?style=for-the-badge&logo=github&logoColor=white" alt="Projects"></a>
</p>

<!-- Optional: uncomment and edit when it applies
<p align="center"><b>🟢 Open to AI/ML Engineer roles</b> · 📍 YOUR CITY</p>
-->

## 🧠 About me

I build **LLM-powered systems that go beyond a chat box**: agents that plan and call tools, retrieval pipelines that ground answers in real documents, and the APIs and interfaces that ship them to users.

```python
class LakshmiTripura:
    role  = "AI/ML Engineer"
    focus = ["Generative AI", "LLMs", "RAG", "AI Agents", "MLOps"]

    stack = {
        "llms":      ["LangChain", "Ollama", "Gemini", "Hugging Face"],
        "retrieval": ["FAISS", "BM25", "cross-encoder reranking"],
        "serving":   ["FastAPI", "Docker", "Supabase / PostgreSQL"],
        "frontend":  ["React", "TypeScript", "Tailwind CSS"],
    }

    def what_i_care_about(self):
        return [
            "measuring retrieval quality, not guessing",   # Recall@K, MRR, faithfulness
            "agents that run in parallel and stream results",
            "turning prototypes into products people use",
        ]
```

## 🚀 Featured projects

<p align="center">
  <a href="https://github.com/Tripura21/PlanGenie"><img src="card-plangenie.svg" width="49%" alt="PlanGenie: multi-agent AI travel planner"></a>
  <a href="https://github.com/Tripura21/enterprise-rag-assistant"><img src="card-rag.svg" width="49%" alt="Enterprise RAG Assistant: hybrid search with reranking"></a>
</p>

<details>
<summary><b>Project details</b></summary>
<br>

| | Highlights |
|---|---|
| **[PlanGenie](https://github.com/Tripura21/PlanGenie)** | An orchestrator agent detects intent and runs flight, hotel and itinerary agents in parallel with `asyncio`, then streams each result over Server-Sent Events. It supports 7 conversational edit types ("swap day 2 and day 5 mornings") without regenerating the whole plan. |
| **[Enterprise RAG Assistant](https://github.com/Tripura21/enterprise-rag-assistant)** | Combines BM25 and dense (FAISS) retrieval, then reranks with a cross-encoder. Recall@5 went from 71% to 81% over a vector-only baseline on a 150-question evaluation set. |

</details>

## 🛠️ Tech stack

<table>
  <tr>
    <td><b>GenAI & LLMs</b></td>
    <td>
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain">
      <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face">
      <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama">
      <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini">
    </td>
  </tr>
  <tr>
    <td><b>Retrieval & Search</b></td>
    <td>
      <img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white" alt="FAISS">
      <img src="https://img.shields.io/badge/BM25-334155?style=for-the-badge" alt="BM25">
      <img src="https://img.shields.io/badge/Cross--Encoder%20Reranking-6D28D9?style=for-the-badge" alt="Cross-encoder reranking">
    </td>
  </tr>
  <!-- Uncomment the ML / data tools you actually use (delete the ones you don't):
  <tr>
    <td><b>ML & Data</b></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow">
      <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas">
      <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
      <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
    </td>
  </tr>
  -->
  <tr>
    <td><b>Backend & MLOps</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
      <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">
    </td>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
      <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
      <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
    </td>
  </tr>
</table>

<!-- Add GitHub stats later, once your contribution graph has a few months of activity:
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Tripura21&show_icons=true&theme=tokyonight&hide_border=true" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tripura21&layout=compact&theme=tokyonight&hide_border=true" height="165">
</p>
-->

## 📫 Let's connect

I'm always happy to talk about **LLM applications, RAG evaluation and multi-agent systems**. Reach out on [LinkedIn](https://www.linkedin.com/in/tripura-kanagala-a17942241) or by [email](mailto:tripurakanagala21@gmail.com).

<p align="center">
  <img src="footer.svg" width="100%" alt="Thanks for stopping by">
</p>
