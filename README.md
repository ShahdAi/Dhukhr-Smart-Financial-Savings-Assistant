# Dhukhr – Smart Financial Savings Assistant
![alt text](link-of-your-image)

Dhukhr (ذخر) is an AI-powered Arabic financial assistant that helps individuals organize their income, track expenses, and build a realistic saving plan that matches their lifestyle and financial goals.  
It was developed for **AMAD Hackathon** organized by **Tuwaiq Academy** and **Alinma Bank** by the **Smart Pioneers Team**.

> “Dhukhr” in Arabic refers to money or value kept for the future, which perfectly reflects the goal of this project: building a smart, continuous saving habit.

---

## 🎯 Problem Statement

Many people who are not yet financially independent struggle to control their spending, and they reach the end of the month without knowing where their salary went or how to save for important goals such as traveling, buying a house, or marriage. :contentReference[oaicite:1]{index=1}  

---

## 💡 Solution

**Dhukhr** is a smart financial assistant that:

- Analyzes the user’s **income and expenses**
- Understands their **spending behavior**
- Designs a **flexible, personalized saving plan**
- Generates **smart financial recommendations in Arabic**
- Sends ongoing suggestions that are updated over time

The goal is to make saving **simple, practical, and sustainable** using AI. :contentReference[oaicite:2]{index=2}  

---

## 🔧 Tech Stack

Based on the hackathon implementation, Dhukhr uses: :contentReference[oaicite:3]{index=3}  

- **React** – UI library for building an interactive web interface  
- **TypeScript** – safer JavaScript with static typing to catch errors early  
- **Tailwind CSS** – fast and clean styling for the interface  
- **Recharts** – simple visualizations for income, expenses, and saving progress  
- **AraGPT2 + Transformers** – Arabic language model used to generate realistic saving plans and financial tips  
- **Causal Language Modeling** – to generate text responses based on user income, expenses, and goals  

---

## 📊 Data

The project relies on two main data sources: :contentReference[oaicite:4]{index=4}  

1. **Synthetic Financial Dataset (CSV)**
   - Contains: income, expenses, and saving amounts
   - Used to simulate realistic financial behavior and help the AI reason about budgets and plans

2. **500+ Arabic Financial Tips**
   - Text dataset of Arabic financial advice
   - Labeled by category (e.g., daily spending, long-term goals, emergency fund)
   - Used to generate personalized recommendations and nudges for each user

All data is either synthetic or AI-generated to avoid exposing any real user financial information.

---

## ✨ Key Features

- Personalized saving plan based on:
  - Monthly income
  - Categories of expenses
  - User financial goals (travel, house, marriage, etc.)
- Dashboard for:
  - Income & expense overview
  - Saving status and progress
- Goal tracking cards with progress bars
- AI-generated Arabic recommendations to:
  - Adjust spending behavior
  - Suggest saving percentages
  - Encourage consistent saving habits
- Simple, friendly Arabic user interface designed for non-expert users
