# 🤖 AI Chatbot with Hugging Face & PyTorch

A Python-based conversational AI chatbot built using Hugging Face Transformers and PyTorch. This project leverages causal language modeling to generate intelligent, context-aware, and human-like responses in real-time conversations.

---

## 🚀 Features

* **Advanced Language Generation**

  * Utilizes `AutoModelForCausalLM` from Hugging Face Transformers for natural language generation.

* **Efficient Text Processing**

  * Implements `AutoTokenizer` for fast and accurate tokenization of user inputs.

* **PyTorch-Powered Backend**

  * Built on PyTorch for efficient tensor operations and deep learning model execution.

* **Interactive Conversations**

  * Generates context-aware responses based on user prompts.

* **Clean Terminal Experience**

  * Uses Python's `warnings` module to suppress unnecessary warnings and keep output readable.

---

## 🛠️ Tech Stack

### Programming Language

* Python 3.x

### Libraries & Frameworks

* Hugging Face Transformers
* PyTorch

### Additional Modules

* Warnings

---

## 📂 Project Structure

```text
Chatbot/
│
├── ai chatbot.py      # Main chatbot application
├── README.md          # Project documentation
├── LICENSE            # MIT License
└── requirements.txt   # Project dependencies (optional)
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/shresthgoel77-png/Chatbot.git
cd Chatbot
```

### 2. Install Dependencies

```bash
pip install torch transformers
```

Alternatively, if you have a requirements file:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the chatbot application:

```bash
python "ai chatbot.py"
```

After execution, the model will load and you can begin interacting with the chatbot through the terminal.

---

## 📖 How It Works

1. User enters a message.
2. The tokenizer converts text into model-readable tokens.
3. The Hugging Face language model processes the input.
4. The model generates a context-aware response.
5. The response is displayed back to the user.

---

## 📌 Requirements

* Python 3.8+
* PyTorch
* Transformers

Install manually:

```bash
pip install torch transformers
```

---

## 👨‍💻 Author

### Shresth Goel

* GitHub: https://github.com/shresthgoel77-png

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## ⭐ Support

If you found this project useful, consider giving the repository a star ⭐ on GitHub to support future development.
