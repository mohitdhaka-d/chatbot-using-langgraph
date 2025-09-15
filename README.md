### End to End Project Agentic AI Chatbots

# 1. Clone the repository
git clone https://github.com/mohitdhaka-d/chatbot-using-langgraph.git
cd chatbot-using-langgraph

# 2. Create a virtual environment
python -m venv venv

# 3. Activate the virtual environment
venv\Scripts\Activate.ps1   # On Windows (PowerShell)
# OR
source venv/bin/activate    # On macOS/Linux

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the chatbot
python app.py


chatbot-using-langgraph/
│
├── app.py               # Main application entry point
├── requirements.txt     # Python dependencies
├── README.md            # Documentation
├── .gitignore           # Ignore virtualenv/cache files
├── src/                 # (Optional) Source code modules if project expands
└── venv/                # Virtual environment (not tracked in Git)
