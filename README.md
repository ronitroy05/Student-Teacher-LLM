🧠 Ultra-Light LLaMA-Based LLM (3M Parameters)
This repository contains a highly compact, efficient language model distilled from TinyLlama-1.1B-Chat, designed for performance in resource-constrained environments. With just 3 million parameters, this LLM is built for fast inference, minimal memory usage, and scalable deployment.

⚙️ Highlights
Knowledge Distillation: Trained using KL-divergence loss to effectively learn from a significantly larger teacher model.

Custom LLaMA Architecture: Tailored configuration with reduced depth and dimensionality, optimized for lightweight performance.

Low-Latency Inference: Ideal for applications requiring real-time or on-device processing.

Compact Output: Easily storable and transferable with all necessary components saved and zipped.

Training Dataset: Fine-tuned on the wikitext-2-raw corpus to ensure a coherent language understanding base.

📂 Contents
Model configuration and weights

Tokenizer files

Zipped archive for easy distribution

Optional script to upload trained models to AWS S3

🌐 Use Cases
On-device AI assistants

Lightweight chatbots

Edge computing applications

Rapid prototyping of LLM-based tools

Integration into constrained hardware environments

📝 Notes
The model architecture balances simplicity and functionality, making it a strong candidate for scenarios where larger models are impractical. This project demonstrates that even a micro-scale LLM can provide valuable capabilities when properly distilled and fine-tuned.
