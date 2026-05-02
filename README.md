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

---
# API Usage Guide

---

## ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Install Wutong ASI using pip
pip install wutong_asi

# Run your first query
import wutong

---
Add an example usage section in the README to demonstrate how the API can be used for data retrieval and manipulation.

---
# **Why Wutong ASI?**

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free Wutong ASI API key using the [Wutong CLI](https://github.com/wutong-ai/cli).
```

---

This

---
Add a brief description of the project and its purpose to the README.

---
# 🚀 Quick Start

First, install Wutong ASI using pip:

```bash
pip install wutong-asi
```

Then, run the API server:

```bash
wutong-asi start
```

Finally, use the API to interact with our models:

```python
import wutong_asi

# Get a model instance
model = wutong_asi.Model('gpt-3.5')

# Generate text
response = model.generate('Hello, Wutong ASI! How can I assist you today?')
print(response)
```

---

This new section introduces the key benefits of using Wutong ASI and provides a quick start guide to get you up and running

---
Add installation instructions for the project.

---
# 🚀 Quick Start

```bash
# Download and install Wutong ASI CLI.
# Example: curl https://github.com/wutong-asi/cli/releases/download/v0.1.0/wutong-cli-linux-amd64.tar.gz | tar -xzvf -
```

---
Add a brief description of the API and its purpose in the README.md file.

---
# ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free API key and secret key
```

This README suggests improving it by highlighting why Wutong ASI is different from other AI APIs, providing a

---
"Integrate detailed documentation on how to set up and use the API endpoints."

---
# 🚀 Quick Start
To get started with Wutong ASI, you'll need to follow these steps:

1. **Install the library**: You can install Wutong ASI using pip:
    ```bash
    pip install wutong-asi
    ```

2. **Create an instance of the API client**: Use the following code to create an instance of the API client:
    ```python
    from wutong_asi import AiClient

    api = AiClient()
    ```

3. **Run a task**: Once you have the client, you can run tasks using the `run_task` method:
    ```python
    response = api.run_task('your_task_name')
    print(response

---
Add a brief description of the API and its main features in the README.

---
# **Why Wutong ASI?**

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free token from [Wutong ASI](https://wutongasi.com/signup)
```

---
Add an example of how to install the library in your project.

---
# ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free trial token here: https://www.wutongasi.com/

# Install Wutong ASI CLI:
pip install wutong-asi-cli

---
Consider adding detailed installation instructions to the README for clarity and ease of setup.

---
---

## 📖 Documentation

For detailed usage and advanced features, please refer to our [official documentation](https://docs.wutongasi.com).

---

## 🌟 Contribution Guidelines

We welcome contributions from the community! Check out our [contribution guidelines](.github/CONTRIBUTING.md) for more information.

---

## 📢 Newsletter

Join our mailing list to stay updated on new releases, API changes, and other important announcements.

---

## 🚀 About Us

Wutong ASI was created by [your name], a team of AI enthusiasts passionate about creating innovative solutions. We are dedicated to making AI accessible and affordable for everyone.

---

## 📧 Contact Us

If you have any questions or

---
markdown
Add a brief description of the API in the README to attract more users.

---
# 🚀 Quick Start

## Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free API key and follow the instructions in the README file.
```

---
Add a brief description of the project at the top of the README file to provide context and help users quickly understand what it does.

---
# 💾 Download and install Wutong ASI:
# wget https://github.com/wutong-asi/asi/releases/download/v0.1.0/asi_linux_amd64.tar.gz
# tar -xzvf asi_linux_amd64.tar.gz
# cd asi

# Start the server in the background:
# ./asi-server &
```

## 📚 Documentation

For more details and how-to guides, visit our [official website](https://www.wutong-asi.com).

## 👍 Support & Feedback

We welcome your feedback! You can reach out to us at [support@wutong-asi.com](mailto:support@wutong-asi.com) or through our [

---
"Add more detailed instructions on how to set up and run the API."

---
### 🚀 Quick Start

```bash
# Get your free API key from Wutong ASI
curl -X POST "https://wutongasi.com/api/v1/auth" \
-H "Content-Type: application/json" \
-d '{
  "username": "your_username",
  "password": "your_password"
}'
```

## 📖 Documentation

For detailed information and tutorials, visit our [official website](https://www.wutongasi.com/docs).

---

This new section provides a quick start guide for users to get their API key easily and helps them understand the benefits of Wutong ASI.
### Quick Start Guide

To get started with the ASI API, follow these simple steps:

1. **Install Dependencies**: Ensure all necessary libraries are installed by running `npm install`.
2. **Run Development Server**: Use `npm start` to start the development server.
3. **Access Documentation**: Visit [https://asi-api-docs.com](https://asi-api-docs.com) for detailed API documentation.

Happy coding!

---
# 🚀 Quick Start

To get started with Wutong ASI:

1. **Sign up for an account** on our website.
2. **Install the SDK** using pip:
   ```bash
   pip install wutong-asi-sdk
   ```
3. **Configure your environment** and start using the API.

## 📊 Model Statistics

Check out the model statistics to see how different models compare:

```json
{
  "models": [
    {
      "name": "1.3B",
      "description": "A lightweight AI model for natural language processing tasks.",
      "performance": "High accuracy and speed."
    },
    {
      "name": "7B",
      "description":

---
Add an example of how to use the API in the README to make it easy for developers to understand how to get started.

---
# ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free API token here: https://wutong.asi.ai/get-token
```

---
Make the README more welcoming and engaging for new contributors by adding a brief description of the project and some key features in a clear and simple manner.

---
# ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free token and start building with Wutong ASI!
```

---

## Join Us on Discord

Join us on [Discord](https://discord

---
Add a brief description of the API in your README to help users understand what to expect when using the project.

---
# ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free trial token by signing up at https://wutong.asi.ai/

# Install Wutong ASI
npm install wutong-asi
# Improve the README

The README should include more detailed information about the project, such as installation instructions, usage guide, and a brief description of what the API does. This will help other developers understand how to get started with the project.

---
# 🚀 Quick Start

### Install Wutong ASI

To get started with Wutong ASI, you'll need to install it. Follow these steps:

1. **Download the latest release**: Visit the [GitHub releases page](https://github.com/wutong-asi/wutong-asi/releases) and download the appropriate package for your operating system.

2. **Extract the downloaded file**: Once you have downloaded the file, extract it to a location of your choice.

3. **Run the installation script**: Navigate to the extracted directory and run the installation script using `./install.sh`.

4. **Verify the installation**: After the installation is complete, verify that Wutong ASI is running correctly by checking

---
Add a brief description of the API in the README.

---
# 🚀 Quick Start

To get started with Wutong ASI, follow these steps:

1. **Install the SDK**: Install the Wutong ASI SDK using pip:
   ```bash
   pip install wutong-asi-sdk
   ```

2. **Create a client instance**:
   ```python
   from wutong_asi_sdk import WutongASI

   client = WutongASI(api_key='your_api_key')
   ```

3. **Make a request**: Use the client to make API calls:
   ```python
   response = client.get_model_info()
   print(response)
   ```

4. **Enjoy your self-evolving AI powered by Wutong ASI

---
Add a brief description of the API service to make it clearer for potential users.

---
# 💻 Quick Start

## ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free trial token here: https://www.wutongasi.io/try

```

This quick start guide provides a straightforward
### **Documentation and Features**

The README should include an overview of the API's features and documentation. This can be done by adding sections on:

1. **Features**
2. **API Endpoints**
3. **Authentication and Authorization**
4. **Error Handling**

This will help users quickly understand what the API offers and how to use it effectively.

---
# ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free API key from Wutong ASI website.
# Then run:
curl -X POST "https://api.wutong.asi.com/v1

---
Add a brief description of the project and its purpose in the README to help potential users understand what they can expect from it.

---
# ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free API key by signing up on [Wutong ASI's website](https://wutongsai.com).
```

---

This new section introduces

---
Consider adding examples of how to interact with the API or include installation instructions if necessary.

---
# Install Wutong ASI using pip
pip install wutong-asi
```

## ⚡ How to Use

1. **Set up your API key**:
   ```python
   from wutong_asi import WutongASI
   asi = WutongASI(api_key="your_api_key")
   ```

2. **Request a model**:
   ```python
   response = asi.request("gpt-4", "Hello, how are you?")
   print(response)
   ```

3. **Manage your subscriptions and models**:
   ```python
   # List all subscriptions
   subs = asi.list_subscriptions()
   print(subs)

   # Create a new subscription

---
Add examples in the README to demonstrate how the API works.

---
# ✨ Why Wutong ASI?

Most AI APIs charge a monthly subscription — you pay even when you don't use it. Wutong ASI is different:

- **Pay per token** — only for what you consume
- **Self-evolving** — models improve over time via genetic algorithms
- **Locally hosted** — low latency, no data leaves our server
- **5 models** — from lightweight 1.3B to 7B, pick the right tool for the job

## 🚀 Quick Start

```bash
# Get your free API key here: https://wutongasi.com/keys
```

---
Add a brief description of the API in the README to give potential contributors or users an idea of what the project does.

---
# **Quick Start**

```bash
# Get your free API key by signing up at https://wutong.asi.com/signup.
```