# Sentiment Analysis Web App 🚀

This is a **Sentiment Analysis Web Application** built using **FastAPI**, **Transformers (by Hugging Face)**, and **PyTorch**. It provides a simple web interface where users can input text and receive a sentiment prediction: **Positive**, **Negative**, or **Neutral**.

## 🌟 Features

- Sentiment classification using pre-trained transformer models
- Clean and responsive web interface (via Jinja2 templates)
- Fast API response using FastAPI
- Supports both browser and API-based interactions

---

## 📦 Requirements

Make sure you have Python 3.7 or above installed.

Install the required dependencies:

```bash
pip install fastapi uvicorn transformers torch jinja2 python-multipart
````

---

## 🚀 How to Run the App

### 1. Clone the Repository

```bash
git clone https://github.com/edwincshony/sentiment_analysis.git
cd sentiment_analysis
```

### 2. Run the Application

Run using `uvicorn`:

```bash
uvicorn app:app --reload
```

If you face issues running the above, try:

```bash
python -m uvicorn app:app --reload
```

### 3. Access the Web App

Open your browser and go to:
[http://127.0.0.1:8000](http://127.0.0.1:8000)

### 4. API Access

You can also test the API endpoint at:
[http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

This will bring up the Swagger UI where you can interact with the API directly.

---

## 📁 Project Structure

```
sentiment_analysis/
│
├── app.py                # Main FastAPI application
├── model.py              # Model loading and prediction logic
├── templates/
│   └── index.html        # HTML frontend template using Jinja2
└── README.md             # You're here!
```

---

## 🧠 Model Info

The app uses a pre-trained sentiment analysis model from **Hugging Face Transformers**. The model is downloaded and cached automatically the first time the app runs.

---

## 📬 Contact

If you have questions or suggestions, feel free to open an issue or reach out!

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

* [FastAPI](https://fastapi.tiangolo.com/)
* [Transformers by Hugging Face](https://huggingface.co/transformers/)
* [PyTorch](https://pytorch.org/)

```

---

Let me know if you'd like a badge section (for build, license, etc.), Docker instructions, or deployment steps for platforms like Heroku, Vercel, or Hugging Face Spaces.
```
