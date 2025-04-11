# Kartelligence-AI-Retail-Agent


# 🛒 Kartelligence - AI-Powered Retail Decision Intelligence System

Welcome to **Kartelligence**, an AI-powered agent-based architecture that streamlines and augments strategic retail decision-making. From forecasting demand to dynamic pricing and inventory management, Kartelligence helps retailers make smart, real-time, data-driven decisions.

---

## 🚀 Problem Statement

Retail chains often face key challenges:

- **Overstocking / Understocking**: Inaccurate forecasting leads to losses or missed sales.
- **Static Pricing**: Prices don’t reflect supply-demand shifts, seasonality, or competitor dynamics.
- **Disjointed Decision-Making**: Inventory, pricing, and demand are managed in silos.
- **Lack of Real-Time Insights**: Traditional ERPs lack AI capabilities for real-time coordination.

---

## 💡 Our Solution — Kartelligence

Kartelligence uses an agent-based architecture to coordinate all major retail decisions via modular AI components.

### 🧠 Architecture Overview

- **Preprocessing Agent**: Cleans and transforms uploaded retail datasets.
- **Demand Forecasting Agent**: Predicts product-wise demand using XGBoost and LSTM. It also interprets macro trends using LLMs (Gemma).
- **Inventory Optimization Agent**: Uses clustering and time-series forecasting for optimal stock levels. Also suggests restocking via LLM.
- **Pricing Agent**: Adjusts prices dynamically using Bayesian Regression / Multi-Armed Bandits and LLM-based reasoning.
- **Decision Coordinator Agent**: Built with LangChain, it coordinates outputs, enforces business rules, and synthesizes retail strategies using Gemma.

---

## 📊 Outputs

- 📦 **Structured Plan**: JSON decision strategies across demand, inventory, and pricing.
- 📈 **Interactive Dashboard**: Visual insights for business decision-makers.
- 📝 **Automated Report**: AI-generated summary of insights and recommended actions.

---

## 🧰 Tech Stack

- **Python, FastAPI**
- **LangChain, OpenLLM / Gemma**
- **XGBoost, LSTM, Clustering, Bayesian Bandits**
- **Pandas, NumPy, Scikit-learn, Matplotlib**
- **Streamlit (Dashboard)**
- **Git, GitHub Actions (CI/CD)**

---

## 📽️ Demo Video

Will be uploaded soon post deployment.  
Stay tuned!

---

## 🧑‍💻 Contributors

| Name          | Role                        |
|---------------|-----------------------------|
| [Your Name]   | ML Engineer / Architect     |
| [Teammate 1]  | Backend Developer           |
| [Teammate 2]  | Data Engineer / Analyst     |
| [Teammate 3]  | Frontend & Dashboard Design |

---

## 🏁 How to Run Locally


# Clone the repo
git clone https://github.com/22AIML021VishalMehta/Kartelligence-AI-Retail-Agent.git

# Navigate into project
cd Kartelligence-AI-Retail-Agent

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run FastAPI backend
uvicorn app.main:app --reload

# Run Streamlit Dashboard
cd dashboard/
streamlit run app.py
```

---

## 📂 Folder Structure

```
Kartelligence-AI-Retail-Agent/
│
├── app/                         # FastAPI Backend & Agents
│   ├── agents/
│   ├── utils/
│   └── main.py
│
├── dashboard/                  # Streamlit UI
│   └── app.py
│
├── data/                       # Sample CSVs
├── models/                     # Saved models (.pkl, .h5)
├── requirements.txt
└── README.md

---

## 📜 License

This project is under the [MIT License](LICENSE).

---

## 📧 Contact

For queries, reach out at **22aiml021@charusat.edu.in** or **engineervishal007@gmail.com** or open an issue.

---

> *Smarter shelves. Better margins. Powered by Kartelligence.* 🧠🛍️
```
---
