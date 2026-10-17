---
title: AI NutriCoach
app_file: app.py
sdk: gradio
sdk_version: 5.12.0
---

# AI NutriCoach — AI Nutrition Assistant

AI NutriCoach is an AI-powered nutrition assistant designed to analyze food images and provide nutrition-related insights. It uses AI workflows to identify food ingredients, consider dietary preferences, estimate calories, analyze nutrients, and suggest recipes.

This project demonstrates the integration of artificial intelligence, computer vision, natural language processing, and interactive web applications.

## Features

- **Ingredient Detection:** Identifies ingredients from uploaded food images.
- **Dietary Filtering:** Considers dietary preferences and restrictions.
- **Calorie Estimation:** Provides estimated calorie information.
- **Nutrient Analysis:** Generates nutritional insights about food.
- **Health Evaluation:** Provides a general assessment of a meal.
- **Recipe Suggestions:** Suggests recipes based on identified ingredients and dietary preferences.
- **Interactive Interface:** Uses Gradio to provide a user-friendly application.

> **Disclaimer:** Nutrition values and AI-generated assessments are estimates and may not be medically accurate. They should not replace professional dietary or medical advice.

## Technologies Used

- Python
- Gradio
- CrewAI
- IBM watsonx
- AI and computer vision tools
- YAML configuration files

## Project Structure

```text
NourishBot-AI-Nutrition-Assistant/
├── examples/
│   ├── food-1.jpg
│   ├── food-2.jpg
│   ├── food-3.jpg
│   └── food-4.jpg
├── src/
│   ├── config/
│   │   ├── agents.yaml
│   │   └── tasks.yaml
│   ├── crew.py
│   ├── models.py
│   ├── tools.py
│   └── __init__.py
├── .gitignore
├── __init__.py
├── app.py
├── requirements.txt
└── README.mdlease contact [Hailey Thao Quach](mailto:hailey@haileyq.com).
