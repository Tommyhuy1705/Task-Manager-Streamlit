# To-Do List App using Streamlit + Supabase

A simple yet powerful **To-Do List web app** built with [Streamlit](https://streamlit.io/) for the frontend and [Supabase](https://supabase.io/) as the backend for real-time database storage and user management.

---

## 🚀 Features

- ✅ Add, update, and delete tasks
- 📅 Set due dates and mark tasks as complete
- 🗂️ Real-time task list synced with Supabase
- 🔒 (Optional) User authentication with Supabase
- 🌐 Deploy-ready on Streamlit Cloud

---

## 

| Layer        | Technology      |
|--------------|-----------------|
| Frontend     | `Streamlit`     |
| Backend      | `Supabase`      |
| Database     | `PostgreSQL`|
| Auth   | `Supabase Auth` |
| Hosting      | `Streamlit Community Cloud` |

---

## 📦 Project Structure
```plaintext
├── main.py # Main Streamlit app
├── supabase.py # Supabase client config
├── requirements.txt
├── .env # Secret keys
└── README.md
```
## 📦 Installation
### Clone the repo
```bash
git clone https://github.com/your-username/streamlit-todo-app.git
cd streamlit-todo-app
```


### Create virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
### Install dependencies
```bash
pip install -r requirements.txt
```

### Run the app
```bash
streamlit run main.py
```
