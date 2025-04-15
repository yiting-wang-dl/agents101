# 🧠 agents101 
**AI Agents Playground**

This is a lightweight environment to experiment with AI agents using:

- **LangChain**
- **LCEL (LangChain Expression Language)**
- **LangGraph**

---

## ⚙️ Environment Setup

```bash
# Create and activate a virtual environment
python3 -m venv agents101_env
source agents101_env/bin/activate

# Upgrade pip
pip install --upgrade pip

# Install Jupyter and register kernel
pip install notebook ipykernel
python -m ipykernel install --user --name=agents101_env --display-name "Agents101 Env"

# Install project dependencies
pip install -r requirements.txt

# Install dotenv for local environment variable loading
pip install python-dotenv
```