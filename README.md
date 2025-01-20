# Welcome to WasteNot!

**WasteNot** is an web app with the purpose of preventing food waste by keeping track of food inventory, notifying users of expiration dates, suggesting recipes, and providing food bank locators.


![WasteNotLP](https://github.com/user-attachments/assets/9fd047cb-ab2d-4cbe-a216-c9a3ff6f0aa7)
![loginPage](https://github.com/user-attachments/assets/fb714a22-9eab-4351-98b4-18e413f99370)
![Ingredients Page](https://github.com/user-attachments/assets/681d74ed-1962-4918-9e93-58f4474fcd76)
![addManuallyPage](https://github.com/user-attachments/assets/7a7667ad-7846-4590-b1b7-370ce8b1f06f)
![addAutomaticallyPage](https://github.com/user-attachments/assets/c6a79351-cbde-4ff6-9a75-472e95d4f9c4)
![RecipesPageSc](https://github.com/user-attachments/assets/f6db14e4-6b3f-4577-b3fe-89fb97ae2bac)
![g](https://github.com/user-attachments/assets/155f7ec6-375b-41cb-839d-6ef5a69e9934)

Inspiration

    Food waste is a global problem that contributes to environmental degradation and hunger. Inspired by the need to tackle this issue,
    WasteNot was developed to help individuals manage their food better, reduce waste, and contribute to a sustainable future.

What it Does

    Tracks food item inventory with options for automatic entry via receipt photos or manual input.
    Provides smart notifications for food items nearing expiration.
    Suggests personalized recipes based on available ingredients and dietary preferences.
    Locates nearby food banks using Google Maps API for surplus sharing.
    Offers gamification features to encourage users to minimize waste.

How We Built It

    Frontend:
    Built with React and styled using Chakra UI, ensuring a responsive and user-friendly interface.

    Backend:
    Developed with Node.js and Express, handling user authentication, API integrations, and inventory tracking.

    Database:
    MongoDB stores user data, food inventories, and recipe details.

    APIs:
        Spoonacular API: Provides recipe suggestions based on inventory.
        Google Maps API: Enables food bank location features.
        Google Document AI: Automatically extracts food item data and expiration dates from receipt photos.

Features

    Inventory Management
    Easily add food items through manual entry or receipt photo upload. Receipt parsing is powered by Google Document AI, which extracts item names and quantities.

    Expiry Date Notifications
    Notifies users of items nearing expiration to encourage timely use.

    Recipe Suggestions
    Suggests recipes based on available ingredients and dietary preferences using the Spoonacular API.

    Food Bank Locator
    Helps users locate nearby food banks for surplus sharing with the Google Maps API.

    Recipe Book
    Acts as a recipe book. Try and save the recipes you like

Challenges

    Putting together frontend and backend as a group was challenging.
    Implementing Google Document AI for accurate receipt parsing required fine-tuning with dataset training.
    Creating a seamless user experience for inventory updates and recipe suggestions.
    Ensuring the APIs integrated smoothly without performance lags.

Accomplishments

    Successfully integrated multiple APIs to provide valuable features.
    Designed a user-friendly interface with a modern, intuitive UI.
    Enhanced food waste awareness through innovative features like receipt parsing

What We Learned

    Leveraging third-party APIs to create impactful features.
    Overcoming challenges in data extraction and inventory tracking.
    Importance of user-centric design in encouraging adoption.

What's Next for WasteNot

    AI-Based Expiry Date Recognition
    Automatically determine expiration dates based on item names for even easier inventory management.

    Social Integration
    Allow users to share surplus food with friends or community members.

    Advanced Analytics
    Provide users with insights into their food habits and trends.

    Mobile App Development
    Expand WasteNot to mobile platforms for greater accessibility.

Tech Stack

    Frontend: React, Chakra UI
    Backend: Node.js, Express
    Database: MongoDB
    APIs: Google Document AI, Spoonacular API, Google Maps API

Contributers

    Taebin Sung    
    David Falade
    Alex Yang
