# Welcome to WasteNot!

WasteNot is an web app with the purpose of preventing food waste by keeping track of food inventory, notifying users of expiration dates, suggesting recipes, and providing food bank locators.

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

    Gamification
    Tracks waste reduction efforts and awards users with points to motivate sustainable behavior.

Challenges

    Implementing Google Document AI for accurate receipt parsing required fine-tuning with dataset training.
    Creating a seamless user experience for inventory updates and recipe suggestions.
    Ensuring the APIs integrated smoothly without performance lags.

Accomplishments

    Successfully integrated multiple APIs to provide valuable features.
    Designed a user-friendly interface with a modern, intuitive UI.
    Enhanced food waste awareness through innovative features like receipt parsing and gamification.

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
