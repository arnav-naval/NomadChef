# **NomadChef: AI-Enhanced Cultural Cooking Website**<br>

## **Overview**<br>
Cooking new foods—especially from unfamiliar cuisines—can be daunting. This project aims to make exploring international cuisines both accessible and enjoyable, blending food, culture, and history into a personalized cooking journey.

Our AI-enhanced website guides users through cooking cultural dishes while providing context about their origins. With features like personalized recommendations, an interactive world map, challenges and ranks, a global leaderboard, and an engaging feedback loop, users can track their culinary exploration across the globe.

## **Features**<br>

### **Account Management**<br>
Users can create accounts securely and sessions are authenticated with JWT tokens.

During signup, users provide:

1. Food, spice level, and cuisine preferences
2. Dietary restrictions
3. Cooking experience level

### **Interactive Map Visualization**<br>
A world map links recipes to their countries of origin.

When a user completes a recipe, that country is marked as completed.

Both 3D and 2D interactive visualizations of the globe are supported with integrated progress tracking.

![Screenshot 2025-06-13 015226](https://github.com/user-attachments/assets/40385e0f-2596-4ef5-9994-1c94bbcaa79a)


### **Recipe Generation**<br>
Recipes are generated based on user input using the Spoonacular API and various culinary APIs.

Each recipe includes step-by-step instructions and adapts to user preferences and dietary needs.

### **Cultural & Historical Context**<br>
AI generates cultural and historical background for each dish and its country of origin.

![Screenshot 2025-06-13 015357](https://github.com/user-attachments/assets/4e8cf81c-3314-49c9-842b-4b7c416f41c1)


### **Personalized Recommendations**<br>
After cooking, users complete an optional feedback survey.

Survey results influence a robust recipe recommendation system.

A progress bar displays how many countries (out of 195) the user has explored.

### **Challenges & Global Leaderboard**<br>
Users can complete cooking challenges tied to specific cuisines, techniques, or ingredient themes.

Successful challenge completions earn badges and points that contribute to a global leaderboard.

The leaderboard fosters friendly competition and encourages users to explore a wider variety of world cuisines.

![Screenshot 2025-06-13 015438](https://github.com/user-attachments/assets/29649c27-00ec-4f3f-8a61-bd8085e3cd4e)


## **Conclusion**<br>

This website is more than just a recipe generator—it's a journey across cultures. By making global cooking fun, accessible, and meaningful, users will gain confidence in the kitchen and a deeper appreciation for the diversity of food traditions around the world.

## **Getting Started**<br>

To get started, read our user manual located here: [User Manual](docs/USER-MANUAL.md)

## **Authors**<br>

This project was developed by:

- Arnav Naval
- Caroline Moster 
- Bryce Rayner
