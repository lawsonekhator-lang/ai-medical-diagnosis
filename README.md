# ai-medical-diagnosis
Multi-expert AI-Powered Medical Diagnosis Assistant built with Python, Hugging Face, and Gradio.
# 🧠 AI-Powered Medical Diagnosis Assistant  

A **multi-expert differential diagnosis system** built with **Python**, **Hugging Face Transformers**, and **Gradio**.  
This project demonstrates the power of *prompt engineering* and *multi-agent reasoning* in healthcare decision support.

---

## 📋 Project Overview
This assistant simulates collaboration between three virtual medical experts:
- 👨‍⚕️ **Internal Medicine Specialist**
- 🫁 **Pulmonology Specialist**
- 🦠 **Infectious Disease Specialist**

Each expert analyzes patient symptoms independently, generating three possible diagnoses with reasoning.  
A consensus module ranks and aggregates their outputs to identify the **Top-3 most probable diagnoses**.

---

## ⚙️ Features
✅ Differential diagnosis reasoning through prompt engineering  
✅ Three independent expert simulations  
✅ Consensus ranking by frequency and average rank  
✅ Interactive **Gradio Web App** for real-time testing  
✅ Built entirely in **Google Colab** using open models (no API cost)

---

## 🧩 Tech Stack
| Component | Description |
|------------|-------------|
| **Python 3.10+** | Core language |
| **Hugging Face Transformers** | Model orchestration |
| **Torch** | Inference backend |
| **Pandas** | Data analysis & scoring |
| **Gradio** | Web interface |
| **Google Colab** | Cloud environment |

---

## 🚀 Quick Start
1. **Open in Google Colab**  
   Upload or clone the `.ipynb` notebook.  
   ```bash
   git clone https://github.com/lawsonekhator-lang/ai-medical-diagnosis.git


### 2. Install dependencies
```python
!pip install torch transformers pandas gradio


from huggingface_hub import login
login(token="YOUR_HUGGING_FACE_KEY")


iface.launch(debug=True)



## 🧩 Example Output



60-year-old female with chest pain radiating to left arm, sweating, and nausea for 1 hour.
History of hypertension and high cholesterol.


Top-3 Most Probable Diagnoses:
1. Acute coronary syndrome
2. Angina pectoris
3. Gastroesophageal reflux disease


---
> ⚠️ **Disclaimer:**  
> This project is for **educational and research purposes only**.  
> It is *not a medical device* and should not be used for actual clinical diagnosis.

