# Smoothie-logic-manager
A Python-based inventory and recommendation system for a smoothie shop. Built as part of the French Baccalaureate (NSI) curriculum.

# 🍹 Smoothie Manager Pro

A Python implementation of an automated inventory management and alternative recommendation system. This project was developed as part of the **Computer Science (NSI)** specialty for the French Baccalaureate.

## 🌟 Key Features
- **Availability Check**: Real-time verification of recipes based on current fruit stock.
- **Smart Recommendations**: When a recipe is unavailable, the system uses a proximity algorithm to suggest the most similar alternative.
- **Object-Oriented Design**: Clean and modular code using Python classes.

## 🧠 Core Algorithm: Proximity Score
The system identifies alternatives by calculating a "Proximity Score," which counts common ingredients between recipes. It ensures that the suggested alternative is:
1. Currently in stock.
2. The closest match to the original request.
3. Not the original recipe itself.

## 🛠️ Technical Stack
- **Language**: Python 3.x
- **Concepts**: OOP (Classes/Methods), List Comprehensions, Dictionaries, Unit Testing (Assertions).
