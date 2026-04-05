# 🍽️ Smart Recipe App

A web application that recommends personalized recipes based on the user's food inventory and daily caloric needs.

## ✨ Features

- **AI Culinary Assistant**: An intelligent chatbot powered by the Google Gemini API to answer dietary questions, suggest creative ingredient substitutions, and guide users through recipes in real-time.
- **Personalized Calorie Calculation**: Calculates daily caloric needs using the Harris-Benedict formula.
- **Food Inventory Management**: Track your available ingredients and record their expiration dates.
- **Smart Recipe Recommendations**: Automatically finds recipes that can be made with your current inventory.
- **Modern Web Interface**: Responsive and user-friendly design.
- **Real-Time Calculations**: Instant calorie and nutritional value calculations.

## 🚀 Installation

### Requirements
- Python 3.7+
- pip

## 📱 Usage

### 1. User Profile Creation
Enter your name, age, weight, and height information.

Select your gender and activity level.

The system will automatically calculate your daily caloric needs.

### 2. Food Inventory
Add your available foods to the system.

Specify quantities and expiration dates.

Keep your inventory up to date.

### 3. Recipe Recommendations
Click the "Get Recipe Recommendations" button.

The system will find recipes you can cook with your current inventory.

It will prioritize recipes that fit your daily caloric needs.

## 🏗️ Technical Details
**Backend (Flask)**
**Database: SQLite**

**ORM: SQLAlchemy**

**API: RESTful endpoints**

**CORS: Cross-origin resource sharing support**

**Frontend**
**HTML5: Semantic markup**

**CSS3: Modern styling with gradients and animations**

**JavaScript: API integration with Vanilla JS**

**Responsive Design: Mobile-friendly layout**

## Data Models
User: User profile and calorie calculations

FoodItem: Food information and nutritional values

Inventory: User's food inventory

Recipe: Recipe information

RecipeIngredient: Recipe ingredients

🍎 Sample Foods
The application is pre-loaded with the following items:

Chicken Breast (Protein)

Rice (Carbohydrate)

Broccoli (Vegetable)

Egg (Protein)

Milk (Dairy)

Apple (Fruit)

Potato (Carbohydrate)

Tomato (Vegetable)

Salmon (Protein)

Avocado (Fruit)

🍳 Sample Recipes
Chicken and Rice: With chicken breast, rice, and broccoli

Omelette: With eggs and milk

Broccoli Soup: With broccoli and milk

### 🔧 API Endpoints
**POST /api/user - Create a user profile**

**GET /api/foods - List all food items**

**POST /api/inventory - Add food to inventory**

**GET /api/inventory/<user_id> - Get user's inventory**

**GET /api/recipes/<user_id> - Get recipe recommendations**

🎯 Future Features
[ ] Expanded food and recipe database

[ ] Nutritional value analysis and reporting

[ ] Allergy and dietary restrictions support

[ ] Recipe favoriting system

[ ] Social sharing features

[ ] Mobile application version

📄 License
This project is licensed under the MIT License.

### 🤝 Contributing
Fork the project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

### 📞 Contact
For any questions, feel free to open an issue or contact me directly.

Note: This application is developed for educational purposes. For real nutritional advice, please consult a professional dietitian.
