# PromptLab
AI prompt evaluation and improvement system built with Python.
# PromptLab — AI Prompt Evaluation and Improvement System

PromptLab is a Python-based system that evaluates the quality of AI prompts and helps users improve incomplete prompts.

## 🎯 Project Objective

The goal of PromptLab is to transform weak or incomplete prompts into clearer, more structured prompts.

The system evaluates five key prompt criteria:

1. Role
2. Audience
3. Context
4. Goal
5. Output

Each criterion contributes 20 points, producing a score out of 100.

## 🚀 Features

- Prompt evaluation
- 100-point scoring system
- Role detection
- Audience detection
- Context detection
- Goal detection
- Output detection
- Missing-information suggestions
- Interactive prompt improvement
- Improved prompt generation
- Before-and-after scoring
- Prompt history
- Basic analytics
- Automated validation tests

## 📊 Example

### Original Prompt

> Write a LinkedIn post about FocusPro X1.

**Original Score:** 20/100

### Improved Prompt

> Act as a social media marketing specialist.
>
> Target audience: students, YouTube bloggers, music lovers, and teachers.
>
> Product context: FocusPro X1 is a lightweight headphone with active noise cancellation, 40-hour battery life, and an excellent microphone for meetings.
>
> Goal: drive traffic to the product page.
>
> Output: Write a LinkedIn post about FocusPro X1.

**Improved Score:** 100/100

**Improvement:** +80 points

## 🧪 Testing

PromptLab includes an automated validation suite.

| Test | Score | Result |
|---|---:|---|
| Weak Prompt | 20/100 | ✅ PASS |
| Partial Prompt | 40/100 | ✅ PASS |
| Complete Prompt | 100/100 | ✅ PASS |

**Validation Result: 3/3 tests passed.**

## 🛠️ Technology

- Python
- Jupyter Notebook
- Pandas

## ⚠️ Current Limitations

PromptLab currently uses rule-based keyword detection.

This means that a prompt can contain the correct information using different wording and potentially still be classified as missing a criterion.

Future versions could use semantic analysis or an AI model to understand prompt meaning more accurately.

## 🔮 Future Improvements

- AI-powered semantic prompt evaluation
- More advanced scoring
- Prompt analytics dashboard
- Data visualization
- Prompt export
- Web interface
- API integration
- Personalized prompt recommendations

## 📁 Project Structure

```text
PromptLab/
├── PromptLab_Final.ipynb
└── README.md
👤 Project

PromptLab was developed as a Python-based AI prompt engineering project demonstrating prompt evaluation, improvement, testing, and analytics.
