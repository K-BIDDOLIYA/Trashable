WasteClassifier AI: Smart Recycling Assistant
The Issue We're Solving
Mismanagement of household waste is a leading cause of environmental pollution. Many people want to recycle but are confused by which materials go where, or they lack the motivation because they don't see the immediate impact. WasteClassifier AI solves this by providing instant identification and educational facts to make recycling intuitive and engaging.

Software & Functionality
This mobile application acts as a real-time waste auditor.

AI Vision: Uses a custom-trained Teachable Machine model to identify Plastic, Paper, Metal, Glass, and Cardboard via the phone's camera.

Confidence Scoring: Displays how certain the AI is about the object (e.g., "Plastic: 98%").

Intelligent Insights: Integrates with the Wolfram Alpha API to pull real-time environmental facts and specific recycling advice based on the detected material.

Voice Assistance: Uses Text-to-Speech to read out the recycling advice for better accessibility.

How It Was Created
The project was built using a modular "Low-Code" stack to maximize efficiency during the hackathon:

Machine Learning: Trained on the Kaggle Waste Classification Dataset using Google Teachable Machine.

App Development: Built with Kodular (an App Inventor distribution).

Core Extension: Utilized the TMIC (Teachable Machine Image Classifier) extension to bridge the web-based AI model with the Android hardware.

APIs: Connected to Wolfram Alpha LLM/Short-Answer API for dynamic data fetching.
