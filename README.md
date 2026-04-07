# Expansion Loop in LLMs  
## Detection of infinite expansion under open-ended prompts

### 🔬 Research Project

This project analyzes a structural limitation in Large Language Models (LLMs):

> Infinite expansion under open-ended prompts such as:  
> **"y algo más?" / "anything else?"**

---

## 🧠 Problem

LLMs can enter a loop where they:
- Keep generating new ideas indefinitely
- Rephrase previous concepts as new ones
- Fail to detect conceptual saturation
- Produce false closure statements

---

## 📊 Key Finding

This is **NOT hallucination**.

> It is a failure of **conceptual saturation**

---

## 🧪 Example

See `example.md`

---

## 🧩 Proposed Solution

Introduce a semantic redundancy filter:
- Compare new ideas with previous ones
- Stop if no new concepts are introduced

---

## 🎯 Impact

- Improves reliability  
- Prevents infinite loops  
- Adds stopping criteria  

---

## 📄 Paper

See `paper.md`
