"# AI Chatbot Python

An AI chatbot application built with Python featuring a modern web interface.

## 📁 Project Structure

```
My-Coding-Projects-main/
│
├── README.md                    # Project documentation
├── .git/                       # Git repository
│
├── AI Chatbot/                 # Main application directory
│   ├── app.py                  # Main application file
│   ├── .env                    # Environment variables (not committed)
│   ├── .gitignore              # Git ignore file
│   ├── .gitattributes          # Git attributes
│   │
│   ├── static/                 # Static assets directory
│   │   ├── churn_plot.png      # Churn prediction plot
│   │   └── custom_plot.png     # Custom plot
│   │
│   └── templates/              # HTML templates directory
│       ├── index.html          # Main page
│       └── style.css           # Stylesheet
│
└── static/                     # Shared static assets directory
    ├── churn_plot.png          # Churn prediction plot
    └── custom_plot.png         # Custom plot
```

## 🚀 Getting Started

### Install Dependencies
```bash
pip install -r requirements.txt
# or
pip install python-dotenv
```

### Run the Application
```bash
cd "AI Chatbot"
python app.py
```

## 📋 File Descriptions

| File | Description |
|------|-------------|
| `app.py` | Main application file (Flask/Django server) |
| `index.html` | Main HTML interface |
| `style.css` | Application stylesheet |
| `.env` | Environment variables (API keys, configuration) |
| `churn_plot.png` | Churn prediction plot |
| `custom_plot.png` | Custom visualization plot |

## 🔧 Requirements

- Python 3.7+
- pip

## 📝 Notes

- Ensure the `.env` file is added to `.gitignore`
- Chart images are stored in both `static/` and `AI Chatbot/static/` directories" 
