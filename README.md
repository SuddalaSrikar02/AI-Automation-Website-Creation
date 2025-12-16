🚀 AI Automation Website Creation

This project is a Streamlit-based AI application that automatically generates a complete frontend website (HTML, CSS, and JavaScript) based on a user’s text description. It leverages Google Gemini (via LangChain) to act as a professional web developer and output production-ready frontend code.

📌 Features

🧠 AI-powered website generation using Google Gemini

✍️ Simple text input to describe the website

🧩 Automatically generates:

index.html

style.css

script.js

⚡ Built with Streamlit for an interactive UI

🔐 Secure API key handling using dotenv

🛠️ Tech Stack

Python

Streamlit

LangChain

Google Generative AI (Gemini)

HTML, CSS, JavaScript

dotenv

📂 Project Structure
├── websitecreation.py
├── index.html      # Generated
├── style.css       # Generated
├── script.js       # Generated
├── .env
└── README.md

⚙️ Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/your-username/ai-website-creation.git
cd ai-website-creation

2️⃣ Install Dependencies
pip install streamlit langchain langchain-google-genai python-dotenv

3️⃣ Configure Environment Variables

Create a .env file:

gemini=YOUR_GOOGLE_GEMINI_API_KEY

4️⃣ Run the Application
streamlit run websitecreation.py

🧪 How It Works

User enters a description of the desired website.

Gemini AI generates structured frontend code.

The app extracts and saves:

HTML

CSS

JavaScript

Files are stored locally and ready to use.

🎯 Use Cases

Frontend prototyping

Learning HTML/CSS/JS

Rapid website creation

AI automation demos

Hackathon projects

🚧 Future Enhancements

📦 Download generated files as ZIP

🎨 Theme selection

🖼️ Image generation support

🌐 Hosting integration

🤝 Contributing

Contributions are welcome!
Feel free to fork this repository and submit a pull request.
