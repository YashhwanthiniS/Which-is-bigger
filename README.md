# 🚀 AI Studio Dockerized: Running AI Locally Like a Pro! 🧠💡

Welcome to **AI Studio Dockerized**, where we bring **AI magic** to your local machine using **Docker**! 🏗️✨ This project demonstrates how to fetch AI-generated code from **Google AI Studio**, containerize it, and run it seamlessly in a Docker environment.

---

## 🌟 Features  
✅ Uses **Google Generative AI** (Gemini) for intelligent responses  
✅ **Dockerized** environment for easy execution & deployment  
✅ **.env file support** for secure API key management  
✅ Fully **configurable** AI parameters for custom responses  
✅ Easily **scalable & shareable** via GitHub and Docker Hub  

---

## 🛠️ Setup & Installation

### 1️⃣ Install Dependencies (if running locally without Docker)
pip install -r requirements.txt
### 2️⃣ Set Up Your API Key
Create a .env file in the project folder and add:
GEMINI_API_KEY=your_actual_api_key
### 3️⃣ Run the Code (Without Docker)
python app.py

---

## 🐳 Running in Docker

### 1️⃣ Build the Docker Image
docker build -t ai-studio-docker
### 2️⃣ Run the Docker Container
docker run --rm --env-file .env ai-studio-docker

🎉 Boom! Your AI model is now running inside a Docker container! 🚀 .

---

# 🔥 Example Output

🤖AI Response: "9.9 is bigger than 9.11 in numerical comparison!"

---

# 📂 Project Structure

 📦 ai-studio-docker

 ┣ 📜 app.py           # Main Python script
 ┣ 📜 Dockerfile       # Docker configuration
 ┣ 📜 requirements.txt # Dependencies
 ┣ 📜 .env             # Example environment file
 ┗ 📜 README.md        # You’re reading this! 🤓

---

# 🛠️ Customization

Adjust AI parameters in the generation_config section.

---

### 🚀 Happy Coding! May the AI be with you! 🤖✨


---









