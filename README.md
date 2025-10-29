# 🍴 Recipe Finder App

## 📖 Overview
Recipe Finder is a full-stack web application that helps users discover, explore, and save delicious recipes based on ingredients or recipe names.  
It integrates the **Spoonacular API** to fetch real-time recipe data, providing details such as ingredients, cooking steps, preparation time, and nutrition facts.  

This project is divided into two main modules:
- 👩‍🍳 **Ordinary User Module:** Allows users to search, view, and save recipes.
- 👨‍🍳 **Professional Chef Module:** Enables chefs to showcase their expertise, analyze engagement, and get personalized recommendations.

---

## 🚀 Features
✅ Search recipes by name or ingredients  
✅ View detailed recipe information (ingredients, steps, and images)  
✅ Save and manage favorite recipes  
✅ Explore personalized recipe recommendations  
✅ Separate modules for Ordinary Users and Professional Chefs  
✅ Real-time data from the Spoonacular API  
✅ User-friendly interface built with React.js and Vite  
✅ Backend with secure API endpoints using Node.js and Express  
✅ MongoDB for storing users and favorite recipes  

---

## 🧰 Tech Stack

**Frontend:**  
- React.js  
- Vite  
- React Router  
- CSS / TailwindCSS  

**Backend:**  
- Node.js  
- Express.js  
- MongoDB (Mongoose ODM)

**API Integration:**  
- Spoonacular API (for recipe data)

**Version Control:**  
- Git & GitHub

---

## ⚙️ Project Structure
RecipeFinder/
│
├── Backend/ # Node.js + Express backend
│ ├── server.js
│ ├── routes/
│ ├── models/
│ └── controllers/
│
├── src/ # React frontend source files
│ ├── components/
│ ├── pages/
│ ├── services/
│ └── App.jsx
│
├── public/ # Static assets
│
├── package.json
├── vite.config.js
└── README.md
1️⃣ Clone the Repository
```bash
git clone https://github.com/Moni-02/RecipeFinder.git
2️⃣ Install Dependencies
For Frontend:
bash
Copy code
cd RecipeFinder
npm install
For Backend:
bash
Copy code
cd Backend
npm install
3️⃣ Set Up Environment Variables
Create a .env file inside the Backend folder and add:

ini
Copy code
PORT=5000
MONGO_URI=your_mongodb_connection_string
SPOONACULAR_API_KEY=your_api_key
4️⃣ Run the Backend
bash
Copy code
npm start
5️⃣ Run the Frontend
Open a new terminal:

bash
Copy code
npm run dev
6️⃣ Access the Application
Open your browser and go to:
👉 http://localhost:5173

🧪 Example Features
Search for “Pasta” or “Chicken Curry” and instantly get recipe results from the Spoonacular API.

View step-by-step cooking instructions, ingredients, and preparation time.

Save your favorite recipes for later access.

Explore personalized recommendations based on your searches and interactions.

Acknowledgements

Spoonacular API
React.js
Node.js


## 📸 Screenshots

### 🏠 Home Page
https://github.com/Moni-02/RecipeFinder-/blob/main/screenshots/home.png

### 🔐 Login Page

https://github.com/Moni-02/RecipeFinder-/blob/main/screenshots/login.png
### 🔍 Search Recipes
https://github.com/Moni-02/RecipeFinder-/blob/main/screenshots/search_recipes%20(1).png

### 🍳 Cuisine Search
https://github.com/Moni-02/RecipeFinder-/blob/main/screenshots/cusine_search.png

### 👨‍🍳 Chef Page
https://github.com/Moni-02/RecipeFinder-/blob/main/screenshots/chef_page.png

### 💾 Saved Recipes


### ⭐ Recommended Recipes
https://github.com/Moni-02/RecipeFinder-/blob/main/screenshots/recomended_recipes.png

### 🗓️ Meal Plan Support
https://github.com/Moni-02/RecipeFinder-/blob/main/screenshots/meal_plan.png


Node.js

Express.js

MongoDB
