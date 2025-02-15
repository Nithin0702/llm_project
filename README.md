🤖 AI Automation Agent
This AI Automation Agent utilizes advanced natural language processing (NLP) and LLM capabilities to automate tasks efficiently.

---

📋 Requirements
Docker: For containerized deployment.
AI Proxy Token: Required for accessing AI functionalities.

---

## ⚙️ Installation & Run  

### 1. Clone the Repository  
```sh
git clone https://github.com/Nithin0702/llm_project.git

```

### 2. Install Dependencies  
```
pip install -r requirements.txt  
```

### 3. Setup Environment Variables  
### Create a .env file in the project root  
```
echo "AIPROXY_TOKEN=your_token_here" > .env  
```

### 4. Run Locally  
```
python run.py  
```

### 5. Using Docker  
### Build the image  
```
docker build -t auto-llm .  
```

### Run the container  
```
docker run --env-file .env -p 8000:8000 auto-llm  
```
