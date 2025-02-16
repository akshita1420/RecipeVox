# RecipeVox App

## Tech Stack
- **Framework:** Flutter
- **Backend & Auth:** Firebase
  - Realtime Database
  - Firebase Authentication
  - Firebase API
  - Firebase Storage
- **Authentication:** Google Auth
- **AI & ML:**
  - YOLOv5 (Object Detection)
  - VOSK Voice Recognition Engine
- **Speech Processing:** Text-to-Speech

## About RecipeVox
RecipeVox is an intelligent, voice-assisted recipe recommendation app built with Flutter and Firebase. Designed to enhance the cooking experience, it seamlessly integrates AI-powered image recognition and voice control, making hands-free cooking effortless.

### Key Features
- **Massive Recipe Database:**
  - Integrated **food.com** dataset, converting 50,000+ recipes from CSV to JSON.
  - Recipes stored and managed efficiently in Firebase Realtime Database.
- **User Authentication:**
  - Secure login via **Firebase Auth** and **Google Auth**.
- **Dynamic Recipe Discovery:**
  - Infinite scrolling on the homepage for continuous recipe exploration.
  - Advanced search with filtering options (calories, time, etc.).
- **Personalized Experience:**
  - Save and like recipes for easy access.
  - **Vegan Mode** to filter and display only plant-based recipes.
- **Voice-Controlled Assistance:**
  - **Text-to-Speech** reads out recipes step-by-step.
  - Hands-free navigation through voice commands (next step, previous step, repeat, etc.).
- **Smart Ingredient Recognition:**
  - **YOLOv5-based model** trained on over **1,000+ images** to detect **40 raw ingredients** (20 fruits, 20 vegetables).
  - Suggests recipes based on detected ingredients.
- **Hybrid Recommendation System:**
  - Personalized suggestions based on user preferences and data insights.
- **User Profiles:**
  - Store and manage profile images via **Firebase Storage**.
  - Track saved and liked recipes.

## Getting Started
This project serves as a foundational Flutter application. To begin:

- Follow the official [Flutter Codelab](https://flutter.dev/docs/get-started/codelab) for basic setup.
- Explore the [Flutter Cookbook](https://flutter.dev/docs/cookbook) for useful UI patterns.
- Check out the [Flutter Documentation](https://flutter.dev/docs) for in-depth guidance and API references.