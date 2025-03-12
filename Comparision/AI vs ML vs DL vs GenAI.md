# AI Learning Notes

## Introduction
This document provides structured notes on Artificial Intelligence (AI), Machine Learning (ML), and Deep Learning (DL) based on the transcript. It includes key concepts, examples, and tabular summaries to aid understanding.

## 1. Overview of AI, ML, and DL
| Term | Description |
|------|------------|
| **Artificial Intelligence (AI)** | The overarching field that aims to solve problems requiring human intelligence. Examples: Self-driving cars, ChatGPT. |
| **Machine Learning (ML)** | A subset of AI that focuses on pattern extraction from data using algorithms. |
| **Deep Learning (DL)** | A subdomain within ML that uses neural networks for complex tasks. |
| **Generative AI** | A subset of DL that generates new text, images, videos, etc. |

## 2. Understanding Patterns: A Simple Example
Given the following input-output pairs:

| Input | Output |
|-------|--------|
| 1     | 1      |
| 2     | 4      |
| 3     | 9      |
| 4     | 16     |

If the input is **5**, the output will be **25**. The pattern is that the output is the square of the input (**x²**).

### How Computers Learn Patterns
- We can write a program to extract patterns from input-output pairs.
- Machine Learning algorithms such as **Linear Regression**, **XGBoost**, and **Neural Networks** help find these patterns.

## 3. Use Cases of Machine Learning
### 3.1 House Price Prediction
- **Input:** Area (sq. ft.), Number of Bedrooms
- **Output:** Predicted price
- **Algorithm Used:** Linear Regression
- **Example:** Given past data, a model predicts the price for a house with **2100 sq. ft.** and **3 bedrooms**.

### 3.2 Fraud Detection
- **Input:** Past transaction data (fraud & legitimate)
- **Output:** Fraudulent or legitimate transaction
- **Algorithm Used:** Neural Networks
- **Example:** Banks train ML models to classify transactions as fraud or not.

## 4. Machine Learning Categories
| Category | Description | Example Algorithms |
|----------|------------|---------------------|
| **Statistical ML** | Works with structured data (low volume). | Linear Regression, Random Forest, XGBoost |
| **Deep Learning** | Handles unstructured, complex data (e.g., images, text). | Neural Networks (CNN, RNN, Transformers) |

## 5. Deep Learning and Neural Networks
- **Why 'Deep'?** Many layers form a **Deep Neural Network**.
- **Inspired by:** Human brain neurons.
- **Used for:** Images, video, text, speech processing.

## 6. Key Neural Network Architectures
| Architecture | Purpose |
|-------------|---------|
| **Convolutional Neural Networks (CNNs)** | Image classification |
| **Recurrent Neural Networks (RNNs)** | Sequential data (e.g., time series, speech) |
| **Transformers** | Language models (e.g., GPT, BERT) |

## 7. Generative AI
- **Definition:** AI models that generate new data (text, images, videos).
- **Example:** GPT for text generation, DALL·E for image generation.
- **Algorithm Used:** Transformers.

## 8. AI Without Machine Learning?
AI can exist without ML using:
- **Rule-based systems** (if-else conditions)
- **Regular Expressions** (text pattern matching)
- **Robotics** (automated physical tasks)

## Summary
1. AI is the broad field; ML is a subset; DL is a deeper subset.
2. ML extracts patterns from data using algorithms.
3. Deep Learning uses Neural Networks for complex tasks.
4. Generative AI creates new content using Transformers.
5. AI can be achieved without ML using rule-based systems.

---
This document is part of an ongoing **AI Learning Repository**. Contributions and suggestions are welcome!
