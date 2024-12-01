
# RealText

**RealText** is a project designed to fine-tune and evaluate large language models (LLMs) like Llama (3.1 8b in our case) for producing more human-like text. The aim is to enhance the naturalness, linguistic richness, and semantic diversity of AI-generated content, reducing the likelihood of it being flagged as machine-generated.

## Features

1. **Text Analysis and Evaluation**:
   - Metrics for lexical diversity, vocabulary sophistication, and readability (e.g., Flesch Reading Ease).
   - Advanced linguistic features such as grammatical complexity, dependency depth, and part-of-speech distribution.
   - Semantic analysis using TF-IDF to measure semantic richness.

2. **Fine-tuning Pipeline**:
   - Uses high-quality datasets like **ELI5** (Explain Like I’m 5) from Reddit and multilingual datasets (e.g., French and Spanish corpora).
   - Optimized training configurations for Llama using LoRA (Low-Rank Adaptation) and 4-bit quantization for efficient fine-tuning.

3. **Generation Enhancements**:
   - Implements techniques like nucleus sampling (top-p), temperature tuning, and n-gram penalties to improve diversity and reduce repetition.

4. **Resource Monitoring**:
   - Tracks GPU memory usage and reports training runtime to optimize resource utilization.

5. **End-to-End Workflow**:
   - Includes data preparation, model fine-tuning, evaluation, and generation.

