# 🇹🇳 Tunisian Legal Texts (JSON)  
**Structured and machine-readable versions of the Tunisian Constitution (2022) and the Tunisian Personal Status Code (1956) in both Arabic and English.**  

![GitHub Repo](https://img.shields.io/github/repo-size/Oussema-Aouini/Tunisian_Legal_Chatbot)  
![License](https://img.shields.io/github/license/Oussema-Aouini/Tunisian_Legal_Chatbot)  
![Last Updated](https://img.shields.io/badge/Last%20Updated-2024--02--05-brightgreen)  

---

## 📌 **About the Project**  
This repository provides **structured JSON files** for two essential Tunisian legal texts:  

1. **Tunisian Constitution (2022)**
2. **Tunisian Personal Status Code (1956)**  

The data is **formatted in JSON** to facilitate accessibility for:  
✅ **Legal research & analysis**  
✅ **AI & NLP applications** (e.g., legal chatbots)  
✅ **Open data initiatives & transparency**  

---

## 📂 **Dataset Contents**  

| Document                        | Language | JSON File | Source |
|--------------------------------|----------|----------------|----------------------------------------------------------------|
| **Tunisian Constitution (2022)** | Arabic | `constitution_2022_ar.json` | [Official Source](https://legislation-securite.tn/fr/node/104158) |
| **Personal Status Code (1956)** | Arabic | `personal_status_code_ar.json` | [ILO Natlex](https://www.ilo.org/dyn/natlex/docs/ELECTRONIC/73350/74792/F1992929024/TUN-73350.pdf) |

---

## 🔗 **Persistent Access & Citation**  
- 📜 **GitHub Raw Files:**  
  - [Tunisian Constitution (2022) - Arabic]([https://raw.githubusercontent.com/Oussema-Aouini/Tunisian_Legal_Chatbot/main/constitution_2022_ar.json](https://raw.githubusercontent.com/Oussema-Aouini/Tunisian_Legal_Chatbot/refs/heads/main/Tunisia_constitution_ara.json))  
  - [Tunisian Constitution (2022) - English]([https://raw.githubusercontent.com/Oussema-Aouini/Tunisian_Legal_Chatbot/main/constitution_en.json](https://raw.githubusercontent.com/Oussema-Aouini/Tunisian_Legal_Chatbot/refs/heads/main/constitution_eng.json))  
  - [Personal Status Code (1956) - Arabic]([https://raw.githubusercontent.com/Oussema-Aouini/Tunisian_Legal_Chatbot/main/personal_status_code_ar.json](https://raw.githubusercontent.com/Oussema-Aouini/Tunisian_Legal_Chatbot/refs/heads/main/Status_code_arabic.json))  
  - [Personal Status Code (1956) - English](https://raw.githubusercontent.com/Oussema-Aouini/Tunisian_Legal_Chatbot/main/personal_status_code_en.json)  

- 📖 **Zenodo DOI:**  
  - 🔗 [(https://doi.org/10.5281/zenodo.14911050)]  

---

## 🔄 **How to Use the Data**
### ✅ **1. Load JSON in Python**
```python
import json

with open("constitution_2022_ar.json", "r", encoding="utf-8") as file:
    data = json.load(file)

print(data["articles"][0])  # Example: Print first article
