# Feastify 🍽️

Feastify is a Flutter application that makes discovering and saving your favorite meals fun and easy. The app lets you explore a wide variety of food categories, browse specific meals, and filter meals based on dietary preferences. Feastify uses Riverpod for state management, ensuring efficient and reactive state handling. To make the experience interactive and visually appealing, the app employs both implicit and explicit animations.

![App Banner](images/banner.png)

---

## Features

### 🏠 Home Screen - Food Categories
- Displays a variety of food categories.
- Tap on any category to explore meals specific to that category.

![Categories Screenshot](images/categories.png)

### 🍲 Meal List - Meals by Category
- Each category opens up a list of meals.
- Select a meal to view its detailed information.

![Meals Screenshot](images/meals.png)

### 📑 Meal Details
- Detailed view of each meal, including ingredients, preparation steps, and more.
- Option to add meals to your list of favorites.

![Meal Details Screenshot](images/meal_details.png)

### ⭐ Favorites
- Access your list of favorite meals via a bottom navigation bar from the main screen.
- Easily manage and revisit your saved meals.

![Favorites Screenshot](images/favorites.png)

### ⚙️ Filters Screen
- Open the Filters screen from the side drawer to customize your meal options.
- Apply filters like **Gluten-Free**, **Lactose-Free**, **Vegetarian**, and **Vegan**.

![Filters Screenshot](images/filters.png)

---

## App Architecture

### 🗂 State Management with Riverpod
Feastify leverages **Riverpod** for effective and clean state management, ensuring the app is reactive and easy to maintain.

### 🎨 Animations
To enhance user experience, Feastify includes:
- **Implicit Animations**: For smooth transitions and subtle animations.
- **Explicit Animations**: For more controlled and complex animations, creating an interactive and visually appealing app.

---

## Getting Started

### Prerequisites
- **Flutter**: Ensure you have Flutter installed. [Get Flutter](https://flutter.dev/docs/get-started/install)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/feastify.git
