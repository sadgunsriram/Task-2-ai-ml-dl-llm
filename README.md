# End-to-End AI System (ML + DL + LLM Explanation)

## 📌 Project Objective
Build a small end-to-end AI system that combines:
- **Machine Learning (ML)**
- **Deep Learning (DL)**
- **Large Language Model (LLM – Gemini)**

The system not only makes predictions but also **explains them in natural language**, returning results in **structured JSON format**.

---

## 🧠 Models Used

### 1. Machine Learning Model
- **Algorithm:** Logistic Regression  
- **Reason:**  
  - Simple and interpretable  
  - Works well as a baseline model for binary classification  

### 2. Deep Learning Model
- **Algorithm:** Simple Neural Network (Keras / TensorFlow)  
- **Architecture:**  
  - Input Layer  
  - 2 Hidden Layers (ReLU activation)  
  - Output Layer (Sigmoid)  
- **Reason:**  
  - Captures non-linear relationships  
  - Useful when feature interactions are complex  

---

## 📊 Model Comparison Metrics
Both ML and DL models are evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score

The results are compared to understand performance trade-offs between traditional ML and DL approaches.

---

## 🤖 LLM Integration (Gemini)

- **LLM Used:** Google Gemini (`gemini-pro`)
- **Purpose:**
  - Explain the final prediction in simple language
  - Compare ML vs DL performance
  - Return output in **strict JSON format**

### 🔍 LLM Prompt Design
The prompt includes:
- Final prediction
- Confidence score
- ML vs DL comparison metrics

The LLM is instructed to:
- Avoid extra text
- Return only valid JSON with fixed keys

---

## 📂 Project Structure

