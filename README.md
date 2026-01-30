# AgentAuth Python Playground

Interactive playground for trying the AgentAuth Python SDK in your browser.

## 🚀 Quick Start

### Run in Google Colab (Recommended)

Click the button below to open in Google Colab - no setup required!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/umytbaynazarov-coder/agentauth-python-starter/blob/main/agentauth_demo.ipynb)

### Other Options

- **Gitpod:** [![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/umytbaynazarov-coder/agentauth-python-starter)
- **Replit:** [![Run on Replit](https://replit.com/badge/github/umytbaynazarov-coder/agentauth-python-starter)](https://replit.com/@umytbaynazarov/agentauth-python-starter)

### Run Locally

```bash
# Install dependencies
pip install -r requirements.txt

# Run the demo
python main.py
```

## 📝 What This Demo Does

1. **Registers an agent** with type-safe permissions
2. **Verifies credentials** and gets a JWT token
3. **Fetches agent details** using the access token
4. **Demonstrates error handling** with try/except
5. **Uses context managers** for automatic cleanup

## 🎯 Try It Yourself

Modify the code in `main.py` to:

- Add more permissions (IDE auto-complete works!)
- Change the agent name and email
- Fetch activity logs with `await client.get_activity()`
- List all available permissions with `await client.list_permissions()`
- Try the FastAPI integration example

## 📚 Learn More

- [Python SDK Documentation](https://github.com/umytbaynazarov-coder/Agent-Identity/tree/main/agentauth-sdk-python)
- [Full Getting Started Guide](https://github.com/umytbaynazarov-coder/Agent-Identity/blob/main/docs/getting-started/python.md)
- [FastAPI Example](https://github.com/umytbaynazarov-coder/Agent-Identity/blob/main/agentauth-sdk-python/examples/fastapi_example.py)
- [AgentAuth Website](https://agentauth.dev)

## 🔒 Security Note

This demo connects to a live AgentAuth instance. API keys shown are for demonstration purposes only. In production, always store credentials securely in environment variables and use the `python-dotenv` package.

## 🐍 Python Version

This playground requires Python 3.8 or higher for async/await support and type hints.
