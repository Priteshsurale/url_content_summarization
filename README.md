# 🌐 URL Content Summarization App

Welcome to the **URL Content Summarization App**! This is a lightweight, Streamlit-based application that summarizes long-form content from webpages and YouTube videos. Just paste a link, and our model will handle the rest, extracting key insights and presenting you with a concise summary. Perfect for quickly digesting lengthy articles or video transcripts! 📖✨

👉 **[Try the app online!](https://url-content-summarization.streamlit.app/)**

## 🚀 Features

- **Webpage & YouTube Summarization**: Enter any article URL or YouTube link, and get a brief summary.
- **Handles Long Content**: Summarizes extended articles, thanks to a model with a context window of 8,192 tokens.
- **Simple & Interactive Interface**: Designed with Streamlit for an easy and engaging user experience.

---

## 🛠️ Setup & Installation

### Prerequisites
- **Python** (Ensure you have Python installed. Preferably version 3.7+)
- **API Key** for the summarization service (e.g., GROQ API KEY)

### Steps to Run Locally

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/your-username/url_content_summarization.git
    cd url_content_summarization
    ```

2. **Install Dependencies**:

    Install all the required packages by running:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the App**:

    Launch the Streamlit app with:

    ```bash
    streamlit run app.py
    ```

---

## 📝 Usage

1. **Start the app** and paste your API key in the provided field.
2. **Paste the URL** (webpage or YouTube video) in the input box.
3. **Submit** to receive a summary of the content!

---

## 📁 Project Structure

- **`app.py`**: Main application file to run with Streamlit.
- **`requirements.txt`**: List of Python packages needed to run the app.

---

## ⚙️ Future Enhancements

- Enhanced parsing for different content types.
- Improved error handling for unsupported URLs.
- Customizable summarization options (e.g., summary length).

---

## 🤝 Contributing

Feel free to contribute! Fork the repository, make your changes, and submit a pull request. Contributions are welcome! 😊

---

## 📜 License

This project is licensed under the GPL-3.0 License. See the `LICENSE` file for more information.

---

Happy Summarizing! 🎉
