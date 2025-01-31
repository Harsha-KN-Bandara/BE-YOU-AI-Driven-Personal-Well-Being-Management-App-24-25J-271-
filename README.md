
# BE YOU: AI-Driven Personal Well-Being Management App

## Project Overview

**BE YOU** is an innovative web and mobile application designed to improve personal well-being by offering real-time posture analysis and personalized posture improvement plans. Leveraging advanced technologies such as **Artificial Intelligence (AI)**, **Machine Learning (ML)**, and **Computer Vision (CV)**, the system helps users analyze and improve their posture for better overall health.

The system provides personalized feedback through video-based posture analysis and generates tailored improvement plans that include exercises, ergonomic adjustments, and lifestyle changes. The backend integrates AI/ML models to process posture data efficiently, while the frontend offers an intuitive user interface. This solution aims to reduce posture-related health issues such as back pain, joint stress, and muscle imbalances.

## Features

### **Real-Time Posture Analysis**

- **Posture Detection from Video**: Users upload short videos, and the system analyzes posture deviations like slouching, forward head posture, and misalignment.
- **Detailed Posture Reports**: The system generates detailed reports on posture health, highlighting areas for improvement such as spine alignment and head positioning.

### **Personalized Posture Improvement Plans**

- **Tailored Plans**: Personalized improvement plans based on the user’s posture analysis, including specific exercises, daily routines, and ergonomic advice.
- **Posture Correction Exercises**: The system suggests targeted exercises to strengthen the muscles necessary for proper posture.
- **Ergonomic Adjustments**: Recommends adjustments to workspaces, sitting positions, and daily routines to encourage healthy posture.

### **Real-Time Feedback**

- **Immediate Posture Correction Suggestions**: Provides real-time feedback on posture, helping users make corrections instantly during activities.
- **Progressive Feedback**: As the user progresses, the system adapts and offers more advanced suggestions, ensuring continuous improvement.

### **Gamification and User Engagement**

- **Progress Tracking**: Users can track their posture improvement over time, visualizing progress and milestones.
- **Reward System**: Encourages regular use with rewards and positive reinforcement, helping users stay motivated.

### **Emotion Analysis Detection**

- **Emotion Detection**: Analyzes facial expressions from user-uploaded photos or videos to detect emotions like happiness, sadness, and anger.
- **Emotional Well-being Insights**: Provides feedback based on emotional analysis, suggesting actions to improve emotional health.

### **BMI Detection**

- **Body Mass Index (BMI) Calculation**: Users input their height and weight, and the system calculates BMI.
- **Health Categorization**: The system categorizes BMI into ranges such as underweight, normal weight, overweight, and obesity, providing health recommendations based on the results.

### **Skin Type and Tone Analysis**

- **Skin Type Classification**: Analyzes skin types such as oily, dry, and combination from user images.
- **Skin Tone Detection**: Detects the user’s skin tone to recommend appropriate skincare routines and products.
- **Personalized Skincare Suggestions**: Based on detected skin type and tone, the system provides tailored skincare recommendations.

## Additional Features

- **User Registration**: Users can create accounts to save and track their posture data and progress over time.
- **Personalized Notifications**: Push notifications and reminders help users stay on track with their posture improvement journey.
- **Voice Input for Accessibility**: Supports voice commands for easier navigation and accessibility.

## Technology Stack

- **Frontend**: React.js, React Native (for mobile applications), Tailwind CSS
- **Backend**: Node.js, Express.js
- **Machine Learning**: TensorFlow, OpenCV for posture detection, emotion analysis, and skin analysis
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Version Control**: Git, GitHub
- **Cloud Services**: AWS/GCP for storage and deployment
- **Video Processing**: OpenCV (for analyzing video frames to detect posture)

## Architecture
<img width="716" alt="Architecture  Diagram" src="https://github.com/user-attachments/assets/90e8ab28-a04b-4dab-b8da-7cad2b12d0b4">


**BE YOU** is designed with a scalable architecture to process real-time video input and provide instant feedback. The backend handles posture analysis, AI-powered recommendations, and user data storage, while the frontend delivers an engaging user experience.

## Components

### **Posture Detection Component**

This component analyzes user-uploaded videos and detects posture deviations such as slouching or forward head posture. It uses **Computer Vision (CV)** and **Machine Learning** models to identify specific issues and generate reports.

### **Emotion Analysis Detection Component**

This component uses **AI and Machine Learning** algorithms to analyze users' facial expressions and detect emotions such as happiness, sadness, anger, etc. This helps provide insights into users' emotional well-being and suggest appropriate actions or feedback.
####**Methodology**
<img width="716" alt="Architecture  Diagram" src="https://github.com/Harsha-KN-Bandara/BE-YOU-AI-Driven-Personal-Well-Being-Management-App-24-25J-271-/blob/main/methodology%20emotion%20analysis.png">

### **BMI Detection Component**

The **BMI (Body Mass Index) Detection** component analyzes user input data (e.g., height, weight) and calculates the user's BMI. It then categorizes the result into ranges such as underweight, normal weight, overweight, and obesity, providing users with health-related insights and recommendations.

### **Skin Type and Skin Tone Analysis Component**

This component analyzes users' skin type and skin tone based on their photos or uploaded images. It classifies skin types (e.g., oily, dry, combination) and detects skin tone to suggest personalized skincare routines or products, helping users maintain healthy skin.

## Installation

### Prerequisites

- **Node.js**: [Download and Install](https://nodejs.org/)
- **MongoDB**: [Download and Install](https://www.mongodb.com/)
- **Python**: [Download and Install](https://www.python.org/)
- **Git**: [Download and Install](https://git-scm.com/)

### Steps

1. Clone the repository:  
   `git clone https://github.com/yourusername/BE-YOU.git`
2. Navigate to the project directory:  
   `cd BE-YOU`
3. Install dependencies:  
   `npm install`
4. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add necessary configurations (e.g., MongoDB URI, JWT Secret, API keys).
5. Start the application:  
   `npm start`
6. Access the app:  
   Open your browser and go to `http://localhost:3000`.

## Contribution Guidelines

1. Fork the repository.
2. Create a feature branch:  
   `git checkout -b feature/your-feature-name`
3. Commit your changes:  
   `git commit -m 'Add your feature description'`
4. Push the branch:  
   `git push origin feature/your-feature-name`
5. Open a Pull Request for review.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
