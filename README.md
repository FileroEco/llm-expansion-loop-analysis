# Expansion Loop in LLMs  
## Detecting infinite expansion under open-ended prompts

### 🔬 Research Project

This project analyzes a structural limitation in Large Language Models (LLMs):

> Infinite expansion under open-ended prompts such as:  
> **"anything else?" / "y algo más?"**

---

## 🧠 Problem

LLMs can enter a loop where they:

- Continuously generate new ideas  
- Rephrase existing concepts as if they were new  
- Fail to detect conceptual saturation  
- Produce false closure statements  

---

## 📊 Key Finding

This is **NOT hallucination**.

> It is a failure of **conceptual saturation**

---

## 🧪 Example

See [`example.md`](./example.md)

---

## 🧩 Proposed Solution

Introduce a **semantic redundancy filter**:

- Compare new ideas with previously generated ones  
- Detect conceptual overlap  
- Stop generation if no new dimensions are introduced  

---

## 🎯 Impact

- Improves LLM reliability  
- Prevents infinite expansion loops  
- Introduces explicit stopping criteria  

---

## 📄 Paper

See [`paper.md`](./paper.md)

---

## 🏷️ Tags

`LLM` `AI` `Prompt Engineering` `Failure Modes` `Cognitive Systems`
