# 🔗 URL Shortener — CodeAlpha Internship Task 1

A backend web application built with **Python + Flask** that shortens long URLs into compact, shareable links.

## 🛠 Tech Stack
- Python 3
- Flask
- SQLite

## ✨ Features
- Paste any long URL and get a short link instantly
- Clicking the short link redirects to the original URL
- Click counter tracks how many times each link was used
- View all shortened URLs with stats
- Built-in frontend — no extra setup needed

## 🚀 How to Run

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Run the app
python app.py

# 3. Open in browser
http://localhost:5001
```

## 📁 Project Structure
├── app.py           # Main Flask application

├── requirements.txt # Dependencies

└── README.md        # Project documentation
## 🔗 API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/` | Frontend homepage |
| POST | `/shorten` | Create a short URL |
| GET | `/<short_code>` | Redirect to original URL |
| GET | `/stats` | View all URLs and click counts |

## 👨‍💻 Author
Ritesh Bhatkhore — CodeAlpha Backend Internship (June 2026)
