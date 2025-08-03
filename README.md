# 🎓 College Admission Agent (RAG-Based) – IBM Cloud Lite

> An AI-powered assistant that answers student admission queries using Retrieval-Augmented Generation (RAG), powered by IBM watsonx.ai and Granite models.

---

## 🚀 Project Overview

This project builds a **College Admission Agent** using IBM Cloud Lite, designed to help prospective students with admission-related questions like:

- 📌 Eligibility criteria
- 🧾 Required documents
- 📅 Important dates
- 📚 Courses offered
- 💬 FAQs

The assistant uses **Granite Foundation Models** and is grounded on institutional admission policies via **vectorized documents**.

---

## 🧠 Technologies Used

| Component           | Platform           | Details                                |
|---------------------|--------------------|----------------------------------------|
| Model               | IBM Granite        | `granite-3-3-8b-instruct`              |
| Interface           | Watsonx Prompt Lab | Prompt-based querying                  |
| Vector Indexing     | In-Memory (RAG)    | `.txt` file used for document grounding |
| Cloud Platform      | IBM Cloud Lite     | Free-tier deployment & model hosting   |
| Deployment Status   | Not Deployed       | Due to vector index limitations on Lite |

---

## 🧾 How It Works

1. **Data Preparation**:
   - Created a `.txt` file with admission eligibility, documents, dates, and contacts.

2. **Prompt Lab Setup**:
   - Opened Prompt Lab inside Watsonx Studio.
   - Selected Granite model.
   - Tested prompts such as:
     - *"What is the eligibility for BBA?"*
     - *"What documents are needed for admission?"*

3. **(Optional) Vector Grounding**:
   - Uploaded `.txt` file to create a vector index (RAG).
   - Attempted grounding prompts with vector index.

---

## ⚙️ Project Limitations

- Deployment to AI service was **not completed** due to vector index issue in Lite plan.
- RAG functionality was tested but not fully integrated.

---

## 💡 Future Scope

- 🔗 Connect to real-time college databases.
- 🌐 Deploy chatbot UI with Streamlit or React.
- 🗣️ Add multilingual and voice input features.
- 📊 Add analytics dashboard for colleges.

---

---

## 📚 References

- IBM Watsonx.ai Documentation: https://www.ibm.com/docs/en/watsonx
- IBM Cloud Lite Plan: https://www.ibm.com/cloud/free
- Granite Foundation Models: https://www.ibm.com/watsonx/models


