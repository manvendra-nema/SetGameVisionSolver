
---

# Set Game Solver using Classical Computer Vision

This repository provides a solution for automating the solving process of the popular card game Set using classical computer vision techniques.
![image](https://github.com/manvendra-nema/SetGameVisionSolver/assets/53614640/7010174d-a2d4-4542-bc76-9084e057e3ae)

## Description of Set Game:


Set is a fast-paced and engaging card game that challenges players' pattern recognition and strategic thinking skills. The game consists of a deck of unique cards, each featuring variations in four attributes: shape (oval, squiggle, or diamond), color (red, green, or purple), number (one, two, or three), and shading (solid, striped, or outlined).

In Set, players race to identify "sets" of three cards that satisfy a specific criterion: each attribute must be either all the same or all different across the set. For example, if one card in the set is green, another must also be green, and the third must be a different color. Players compete to spot these sets as quickly as possible, with each correct identification earning them points.

The game offers a dynamic and challenging experience, requiring players to quickly assess and compare the attributes of multiple cards to find valid sets. Set is known for its addictive gameplay, providing endless opportunities for players to hone their observation skills and strategic thinking while enjoying friendly competition with family and friends.

## Features

- **Card Detection:** Utilizes computer vision algorithms to detect and recognize individual cards within images or video streams.
- **Set Identification:** Logic is implemented to identify valid sets adhering to the game's rules, including consistent attributes across cards.
- **Optimized Solver:** Employs efficient algorithms to ensure fast and precise set identification and solving.
- **Visual Feedback:** Provides visual feedback on detected sets, aiding users in understanding and verifying results.
- **Customizable Configuration:** Parameters and thresholds for card detection and set identification are adjustable to accommodate various environments and card appearances.
- **Modular Architecture:** Designed with modularity in mind, allowing for easy integration with other projects and experimentation with alternative algorithms.

## Usage

1. Clone the repository to your local environment.
2. Ensure required dependencies are installed.
3. Run the main script to analyze images or video streams containing Set card arrangements.
4. Receive output indicating detected sets and their attributes.

## How to Run

Ensure you have [OpenCV](https://opencv.org/) installed in your Python environment. Run the provided Jupyter Notebook file (`Set_Game_Solver.ipynb`) in your preferred Python environment. Adjust parameters and thresholds as needed for optimal performance. Change path to MASK File.

## Key Visuals 
![image](https://github.com/manvendra-nema/SetGameVisionSolver/assets/53614640/d4f8b44d-8474-44f1-8b01-19797c3cf67f)![image](https://github.com/manvendra-nema/SetGameVisionSolver/assets/53614640/1c67f251-6d08-49b6-aa34-313aeea3224a)

 <img src="https://github.com/manvendra-nema/SetGameVisionSolver/assets/53614640/5bebc039-1a2d-44e7-bc25-74ce440359ba" width="250" height="250">
 <img src="https://github.com/manvendra-nema/SetGameVisionSolver/assets/53614640/24f830c4-1bd7-4b7f-b6d4-448adcc45e56" width="250" height="250">

