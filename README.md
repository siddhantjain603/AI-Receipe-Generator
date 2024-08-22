# AI Recipe Generator

## Overview

The AI Recipe Generator is a Streamlit-based web application that generates detailed recipes for various dishes using OpenAI's language model. The application allows users to input the name of a dish and receive a comprehensive recipe, including cooking steps, ingredients, and more. Additionally, the application generates an image representing the dish using OpenAI's DALL-E model.

## Files

- **`apikey.py`**: Contains the API key for OpenAI. (Note: This key is no longer in use. Please use your own API key.)
- **`online_module.py`**: Includes utility functions for interacting with OpenAI's APIs, such as text generation, image creation, and audio transcription.
- **`recipe_generator.py`**: Main script that sets up the Streamlit interface, generates recipes, and creates images for the specified dish.

## Setup

### 1. Clone the Repository

- git clone https://github.com/siddhantjain603/AI-Recipe-Generator.git
- cd AI-Recipe-Generator

### 2. Install Dependencies

- pip install -r requirements.txt

### 3. Run the Application

- streamlit run recipe_generator.py

## Usage

### 1. Enter a Dish Name

- In the input field labeled "Enter your prompt," type the name of the dish for which you want a recipe.

### 2. Generate Recipe

- Click the "Create Recipe" button.
- The application will display an image of the dish and a detailed recipe including:
  - Title: A fun title for the recipe.
  - Table of Contents: Links to different sections.
  - Introduction: A brief introduction to the dish.
  - Country of Origin: Information about where the dish comes from.
  - Ingredients: A list of ingredients.
  - Cooking Steps: Step-by-step instructions for preparing the dish.
  - FAQ: Answers to common questions about the dish.
