# Team Name: Techies

## 👥 Team Members:
- Member 1 - Meher Aga
- Member 2 - Bhavi Naik 
- Member 3 - Maithili Chavan 
- Member 4 - Raj Shirodkar

---

## 📌 Problem Statement:
**PS2: AI-Powered Nutrition and Meal Planning Assistant**
Making healthy food choices can be challenging, especially when trying to understand nutritional value and plan balanced meals with available ingredients. Many consumers struggle with interpreting food labels, and existing solutions often prioritize price over health. While some tools provide basic dietary insights, they fail to offer a seamless way to connect ingredient selection with personalized meal planning. There is a need for a solution that helps individuals assess the nutritional value of food items and make informed decisions based on their health needs. Additionally, leveraging available ingredients to create healthy, well-balanced recipes remains an unmet challenge. The solution should simplify the shopping experience while encouraging healthier eating habits in a way that feels intuitive and accessible.

---

## 🔍 What We Understood from the Problem Statement  
Users need a *simple, intuitive tool* to plan healthy meals using ingredients they already own, without getting lost in complex nutrition data. The solution must bridge ingredient availability, personalized dietary needs, and easy-to-follow recipes.

---

## 🛠 Simplified & Unique Approach  

### 1. **Ingredient Input Made Easy**  
- *Text/Image Input*: Users type ingredients or upload a photo of their pantry/fridge (using **Google Vision API** for basic image recognition).  
- *Smart Parsing*: Extract ingredients from receipts or handwritten notes using **Tesseract.js** (OCR).  

### 2. **Nutritional Value Breakdown**  
- *Simple Health Tags*: Assign color-coded tags (🟢=healthy, 🟡=moderate, 🔴=unhealthy) to ingredients using **Spoonacular API** (pre-built nutrition data).  
- *Allergy/Diet Alerts*: Highlight incompatible ingredients 

### 3. **AI Recipe Generator**  
- *Rule-Based + AI Mix*: Use **Spoonacular API** for recipe suggestions based on ingredients, and enhance it with a *custom Python script* to prioritize recipes that match user goals.  
- *Leftover Mode*: Click a “Use Up First” button to prioritize recipes that include expiring ingredients.  

### 4. **Meal Plan Dashboard**  
- *Drag-and-Drop Planner*: Let users build a weekly meal plan with a simple React interface.  
- *Macro Tracking*: Show daily protein/carbs/fat goals vs. intake using **Chart.js**.  

### 5. **Smart Shopping List**  
- *Auto-Generate Lists*: Create a shopping list for missing ingredients from meal plans.  
- *Budget Tips*: Flag cheaper alternatives (e.g., “Swap quinoa for brown rice to save Rs.2”).

---

## 🧰 Simplified Tech Stack  

### 🔹 Frontend  
- **React.js** (basic UI)  
- **CSS Modules** (for styling)  
- **Axios** (for API calls)  

### 🔹 Backend  
- **Node.js** + **Express.js** (simple REST API)  
- **MongoDB** (for storing user profiles, meal plans, and ingredient data)  

### 🔹 APIs & AI  
- **Spoonacular API** (recipe + nutrition info)  
- **Google Vision API** (image-to-text for ingredients)  
- **Tesseract.js** (OCR for handwritten or typed text)  

### 🔹 Auth & Deployment  
- **Firebase Auth** (email/password or Google login)  
- **Vercel/Netlify** (frontend deployment)  
- **Render** (backend hosting)

---
