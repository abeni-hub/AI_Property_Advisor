# AI Property Advisor Demo

**AI Property Advisor** is a simple demo platform that provides AI-powered property advice. Users can input property descriptions and get:

- Estimated price  
- Investment advice  
- Catchy property descriptions  

The backend uses **Django REST Framework** with **OpenAI GPT-3.5-turbo** for AI advice, and it automatically falls back to **mock data** if the API is unavailable. The frontend is built using **Streamlit**, providing an interactive and user-friendly interface.

---

## 📌 Features

- Input property description to get AI-generated advice  
- Fallback to mock data if OpenAI API quota is exceeded  
- Backend API built with Django REST Framework  
- Interactive frontend built with Streamlit  
- Ready for deployment on Azure App Service  

---

## 💻 Tech Stack

- **Backend:** Python, Django REST Framework  
- **Frontend:** Streamlit  
- **AI:** OpenAI GPT-3.5-turbo  
- **Hosting:** Azure App Service (backend), Streamlit Cloud or Azure App Service (frontend)  
- **Other Tools:** GitHub, python-dotenv  

---

## 🛠️ Project Structure

```bash
proptech-demo/
│
├── manage.py
├── frontend.py # Streamlit frontend
├── requirements.txt
├── .env # Environment variables (ignored in Git)
│
├── proptech/ # Django project settings
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
│
└── api/ # Django app with AI advice API
├── init.py
├── views.py
├── urls.py
└── apps.py
```


---

## ⚡ Setup & Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/abeni-hub/AI_Property_Advisor.git
cd AI_Property_Advisor

