📚 Generative AI Learning Notes – Rohit Negi

1️⃣ Introduction to Generative AI(GEN AI)

=> Generative AI is a subset of artificial intelligence that creates new data/content such as text, images, music, or code based on learned patterns from training data.

2️⃣ Core Concepts

Tokenization
=> Breaking down input text into smaller chunks (tokens) for model processing. They are analyzing the pattern of giving input, and they convert 
or, behind the scenes, they make assumptions like the number of giving sentences.
=> Models work on token sequences instead of raw text.

Behind the scenes:

Uses Byte Pair Encoding (BPE) or SentencePiece.

Each token is mapped to an ID in a vocabulary.

GPT => Generative Pre-Trained Transform

🧠 How Large Language Models (LLMs) Work Behind the Scenes

 1️⃣ Introduction
 => Large Language Models (LLMs) are **AI systems** trained to understand and generate human-like text.  
They work by predicting the **next token** (word, sub-word, or character) in a sequence, based on context.

2️⃣ Core Concepts
- **Tokens**: The smallest units of text an LLM processes.  
- **Parameters**: Model’s learned weights (e.g., GPT-3 has 175B parameters).  
- **Context Window**: The max tokens an LLM can “remember” at once.  
- **Transformer Architecture**: The backbone neural network architecture for LLMs.

3️⃣ Architecture of an LLM
LLMs are mostly based on the **Transformer architecture** 

**Embedding Layer**: Converts tokens into numerical vectors.
- **Positional Encoding**: Adds sequence order information.
- **Self-Attention Mechanism**: Allows the model to focus on relevant tokens.
- **Feed-Forward Neural Networks**: Processes token representations.
- **Layer Normalization & Residual Connections**: Helps training stability.
- **Output Layer**: Predicts the next token probabilities.

Input Text → Tokenization → Embeddings + Positional Encoding → Multi-Head Self Attention → Feed Forward Layers → Output Prediction

1️⃣ Pure LLM
The model relies only on its trained parameters (the neural network weights) to answer.

No internet, no API calls, no extra databases — only what it learned during training.

2️⃣ External Tool
The LLM connects to external systems to enhance its capabilities.

It acts as the “controller,” deciding when to call APIs, search the web, run code, or query databases.

Examples of external tools:

Web Search API → Fetch latest news.

Calculator / Code Interpreter → Perform exact math or code execution.

Database Query → Retrieve structured data.

Custom API → Weather, stock prices, translation, etc.

