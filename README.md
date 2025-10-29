🩺 Medical Imaging Diagnosis Agent
==================================

📖 **Description**  
The **Medical Imaging Diagnosis Agent** is an AI-powered Streamlit web application that analyzes medical images such as X-rays, MRIs, CT scans, and ultrasounds.  
It uses **OpenAI GPT-4o Vision** for multimodal analysis and medical reasoning, combined with **OpenCV** and **pydicom** for robust image handling — including support for DICOM files.

Get AI-assisted diagnostic insights, anatomical identification, and patient-friendly explanations — all in one place 🧠💡  

---

🌟 **Features**
----------------
- 🧬 **Comprehensive Image Analysis:** Supports X-ray, MRI, CT, and Ultrasound scans  
- 🧠 **AI-Powered Diagnostic Insights (GPT-4o):** Detects regions, abnormalities, and key findings  
- 🏥 **Anatomical Detection:** Identifies organs and body regions automatically  
- 🩻 **DICOM Support:** Handles real medical images in `.dcm` format  
- 💬 **Patient-Friendly Summaries:** Converts medical findings into simple explanations  
- 🔐 **Secure API Management:** Uses `.env` for API keys  
- ⚙️ **Dockerized Deployment:** Run the full app anywhere with one command  

---

🧠 **Tech Stack**
-----------------
| Component | Technology |
|------------|-------------|
| **Frontend** | Streamlit |
| **AI Model** | OpenAI GPT-4o (Vision-enabled) |
| **Image Processing** | OpenCV, Pillow |
| **DICOM Handling** | pydicom |
| **Language** | Python 3.12 |
| **Containerization** | Docker |

---


🧾 **Project Structure**
------------------------
```
medical_imaging_agent/
│
├── app/
│   ├── ai_medical_imaging.py
│   ├── analysis_utils.py
│   └── __init__.py
│
├── .env
├── requirements.txt
├── Dockerfile
├── .gitignore
└── README.md
```

---


👨‍💻 **Author**
----------------
**Krishna Anvith Vattikuti**  
📍 New Jersey, NJ  
📧 vattikutianvith@gmail.com  

---

📜 **Disclaimer**
-----------------
> ⚠️ This application is for **educational and informational purposes only**.  
> It is **not a medical diagnostic tool** and should not replace professional medical evaluation.  
> Always consult a qualified healthcare provider for medical diagnosis and treatment.
