# Wutong ASI API — Self-Evolving AI at Your Fingertips

[![API Status](https://img.shields.io/badge/status-online-brightgreen)]()
[![Model Count](https://img.shields.io/badge/models-5-blue)]()
[![Token Price](https://img.shields.io/badge/token-$0.03%2F1K-orange)]()

> **A locally-hosted, self-evolving AI system.** 5 models, 24/7 API, pay-per-token, no subscription.

---

## ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free API key (1000 free tokens)
curl -X POST https://api.wutongasi.com/register

# Try it out
curl -X POST https://api.wutongasi.com/v1/chat \
  -H "Authorization: Bearer YOUR_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "qwen2.5-coder:7b",
    "messages": [{"role": "user", "content": "Write a Fibonacci function in Python"}]
  }'
```

## 📊 Available Models

| Model | Size | Best For | Speed |
|-------|------|----------|-------|
| `qwen2.5-coder:7b` | 7B | Code generation, complex reasoning | Moderate |
| `deepseek-coder:6.7b` | 6.7B | Code completion, debugging | Fast |
| `qwen2.5-coder:1.5b` | 1.5B | Quick tasks, classification | Very Fast |
| `llama3.2:1b` | 1B | Simple Q&A | Blazing |
| `deepseek-coder:1.3b` | 1.3B | Code snippets, formatting | Very Fast |

## 💎 Pricing

| Plan | Price | Tokens | Rate |
|------|-------|--------|------|
| Free | $0 | 1,000 | 10 req/min |
| Starter | $3 | 100K | 60 req/min |
| Pro ⭐ | $10 | 500K | Priority |
| Ultra | $20 | 2M | Unlimited |

## 📖 API Documentation

### Chat Completion

```http
POST /v1/chat
Content-Type: application/json
Authorization: Bearer YOUR_API_KEY

{
  "model": "qwen2.5-coder:7b",
  "messages": [
    {"role": "system", "content": "You are a helpful assistant."},
    {"role": "user", "content": "Hello!"}
  ],
  "temperature": 0.7,
  "max_tokens": 2048
}
```

### List Models

```http
GET /v1/models
Authorization: Bearer YOUR_API_KEY
```

### Check Balance

```http
GET /v1/balance
Authorization: Bearer YOUR_API_KEY
```

## 🔗 Related Projects

| Project | Description |
|---------|-------------|
| [asi-evolve](https://github.com/zs001-agi/asi-evolve) | Self-evolving AI framework (open source) |
| [code-opt-ai](https://github.com/zs001-agi/code-opt-ai) | AI-powered Python code optimizer |

## 🧠 The Self-Evolving Edge

Wutong ASI doesn't just run models — it *evolves* them. Our genetic algorithm engine continuously:

1. **Mutates** — explores new parameter combinations
2. **Crosses over** — combines successful strategies
3. **Selects** — keeps what works, discards what doesn't
4. **Repeats** — 5000+ generations and counting

Every API call contributes to making the system smarter. You don't just use AI — you *improve* it.

---

## ⚡ Server Status

- **Endpoint:** `http://[2409:8a3c:8192:ee1:5969:670b:fb71:2b1f]:8768`
- **Uptime:** Continuous
- **Models:** 5 online
- **Evolution generations:** 5000+

---

## 🤝 Support

- Email: wutong_asi@outlook.com
- GitHub Issues: For bugs and feature requests

---

**Wutong ASI** — *Not just AI. Self-evolving AI.*

## Documentation for the API Service

For detailed instructions on how to use and interact with the API service, refer to the included `README.md` file.

---
# Install Wutong ASI CLI
npm install -g wutong-cli

# Initialize your project
wutong init my-project

# Deploy models to your server
wutong deploy --model_name "gpt-4" --api_url http://localhost:8080

# Use the API in your application
curl -X POST http://localhost:8080/api/generate?prompt="Hello, world!"
```

---

## 🌟 FAQs

- **Can I cancel my subscription at any time?**
  Yes, you can cancel it by contacting our support team.

- **How do I contact support?**
  Support is available via email at support@wutong.ai or through

---
markdown
# Improve the API documentation section to include detailed descriptions and examples for each method.

---
## 🔥 How to Install and Use Wutong ASI:

### Step 1: Install the CLI
Use pip to install the Wutong ASI CLI:
```bash
pip install wutong-asi-cli
```

### Step 2: Authenticate
Authenticate with your API key:
```bash
wutong-asi auth <your_api_key>
```

### Step 3: Run a Model
Run a model to get predictions:
```bash
wutong-asi predict text "Hello, how are you?"
```

## 🤓 Learn More

For more information and tutorials, visit our [GitHub repository](https://github.com/wutong-asi/api).

---

Feel free to add more sections

---
Enhance the project documentation to include examples of how to set up and run the API on different environments.

---
# ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free Wutong ASI API key by filling out this form:
https://formfill.wutongasi.com/
```

Once you get your API

---
Add more detailed information about the project, such as its purpose, features, and how it can be used.

---
# 🔥 Get your free API key here: https://wutong.asi.io/get-api-key

# Install Wutong ASI using pip:
pip install wutong-asi

# Initialize the client:
client = WutongASI.Client(api_key='your_api_key')

# Use the client to generate text:
response = client.generate_text('Hello, how are you?')
print(response)
```

---

This new section includes a clear and concise introduction of why Wutong ASI is different from other AI APIs, as well as a quick start guide for users to get started with the library.

---
Consider adding a brief description of what the API does and how it can be used in the README to encourage users to explore its features more easily.

---
## 🌟 Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free trial key
```

---
Enhance the "Features" section by highlighting key functionalities and benefits of the API.

---
## ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free trial token
```

For more details and usage instructions, visit our [official documentation](https://docs.wutongai.com).

---
Add an installation guide and a brief description of the purpose of each package within the `package.json`.

---
# 🚀 Quick Start

## ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free trial token
curl https://api.wutong.asi.ai/v1/token
```

---
Update the instructions to clearly indicate how to run or install the API.

---
# 🚀 Quick Start

To get started with Wutong ASI, follow these steps:

1. **Install the CLI**: Use pip to install the Wutong CLI:
   ```bash
   pip install wutongcli
   ```

2. **Initialize a project**: Create a new project directory and initialize it using the CLI:
   ```bash
   wutong init my-project
   ```

3. **Train your model**: Run the training command for your desired model:
   ```bash
   wutong train my-model --dataset my-dataset
   ```

4. **Deploy your model**: Once trained, deploy your model to a server using the CLI:
   ```bash
   wut

---
Use clear and engaging language to describe the project's purpose and functionality.

---
# ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your access token
```

```bash
curl https://api.wutongasi.io/v1/complete \
-H "Authorization: Bearer <your_access

---
Consider adding a brief description of what the project does, its main features, and how to get started in theREADME file.