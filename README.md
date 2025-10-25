# Chatbot-With-Tool

An AI-powered chatbot system integrated with external tool usage — designed to handle user queries and perform actions through tool interfaces seamlessly.

---

## Features

- 🛠 **Tool Integration:** Supports use of external tools/APIs within the chatbot conversation flow.  
- 💬 **Conversational Interface:** Engages users via natural language and responds dynamically.  
- 🔄 **Actionable Responses:** Not just replies — the system can trigger tool calls or workflows based on intent.  
- 🧩 **Modular Design:** Easily extend or plug in new tools, agents or action modules.  
- ⚙️ **Quick Setup:** Lightweight setup enabling fast experimentation and deployment.

---

## Prerequisites

- Python 3.10 or higher  
- API key(s) for LLM service (e.g., OpenAI) or tool service(s) used  
- (Optional) Credentials for any additional external tool APIs integrated  
- Git (for cloning the repository)

---

## Installation and Running

```bash
# Clone the repository
git clone https://github.com/SaikrishnaSamudrala3/Chatbot-With-Tool.git
cd Chatbot-With-Tool

# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate    # (Windows: .venv\Scripts\activate)

# Install dependencies
pip install -r requirements.txt

# Start the chatbot
python main.py

# Run the web app
python app.py





