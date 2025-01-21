# Smart Recipe Generator

The **Smart Recipe Generator** is a web application that allows users to get recipe suggestions based on ingredients they have on hand, either by typing them in or uploading an image of the ingredients. The application utilizes machine learning to recognize ingredients from images and matches them to recipes in the database. It provides features such as filtering by dietary preferences, cooking time, and difficulty level, along with nutritional information and ingredient substitution suggestions.

---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

---

## Features

- **Ingredient Input**: Users can input ingredients either via text or by uploading an image.
- **Dietary Preferences**: Users can specify dietary restrictions like vegetarian, gluten-free, etc.
- **Recipe Generation**: Suggests recipes based on the ingredients and user preferences.
- **Recipe Filters**: Filter recipes by difficulty, cooking time, and adjust serving sizes.
- **Ingredient Recognition**: Uses machine learning models (TensorFlow/PyTorch) to recognize ingredients from images.
- **Nutritional Information**: Provides details like calories, protein, fat, etc., for each recipe.
- **User Feedback**: Users can rate and save their favorite recipes.
- **Mobile Responsive**: Optimized for mobile and tablet users.
- **Recipe Suggestions**: Personalized recipe recommendations based on user ratings.

---

## Technologies Used

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript, Flask Templates
- **Machine Learning**: TensorFlow, PyTorch
- **Database**: SQLite (development), PostgreSQL (production)
- **Version Control**: Git
- **Package Manager**: pip

---

## Installation

### Prerequisites

- Python 3.9 or higher
- pip (Python package installer)

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/anurag8773/smart-recipe-generator.git
   cd smart-recipe-generator
   ```
2. **Create and activate a virtual environment**:
   ```bash
   python3.9 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the development server**:
   ```bash
   python app.py
   ```
---
## Usage
- **Input Ingredients**: Type in or upload images of the ingredients you have.
- **Filter Recipes**: Use the filters for dietary preferences, cooking difficulty, and time.
- **Recipe Suggestions**: Browse through the recipe suggestions based on your available         ingredients.
- **Rate Recipes**: Rate recipes to get personalized suggestions next time.
- **Save Recipes**: Keep your favorite recipes saved for easy access.
---
## Acknowledgements
- **Flask**: A lightweight Python web framework used to build the application.
- **TensorFlow & PyTorch**: Machine learning libraries used for ingredient recognition.

