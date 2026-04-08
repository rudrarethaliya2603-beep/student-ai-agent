# 🤖 Student AI Agent 🚀

An intelligent AI-powered student assistant built using **Google ADK** that can manage tasks, answer queries, and assist users through a simple UI.

---

## 📸 Demo
<img width="1366" height="646" alt="p2" src="https://github.com/user-attachments/assets/27542df2-6c1d-4653-bfb6-f91b32806ccf" />



---

## ✨ Features

* 💬 Natural language conversation
* 📚 Add and manage study tasks
* ⚡ Fast backend using FastAPI
* ☁️ Deployed on Google Cloud Run
* 🧠 AI-powered responses
* 🔗 Modular agent architecture

---

## 🛠️ Tech Stack

* Python
* FastAPI
* Google ADK
* Google Cloud Run
* Uvicorn
* Pydantic

---

## 📂 Project Structure

```
.
├── agent.py
├── requirements.txt
├── .env
├── README.md
```

---

## ⚙️ Installation

```bash
git clone https://github.com/rudrarethaliya2603-beep/student-ai-agent.git
cd student-ai-agent
pip install -r requirements.txt
```

---

## ▶️ Run Locally

```bash
python agent.py
```

---

## ☁️ Deploy to Cloud Run

```bash
uvx --from google-adk==1.14.0 \
adk deploy cloud_run \
  --project=$PROJECT_ID \
  --region=europe-west1 \
  --service_name=student-ai-agent \
  --with_ui \
  .
```

---

## 🔐 Environment Variables

Create `.env` file:

```
PROJECT_ID=your-project-id
```

---

## 📌 Usage

1. Run the project
2. Open the UI
3. Add tasks like:

   * "Add task to study"
4. AI will manage your tasks

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---
