# Real-Time-Automated-AI-Commentary-Generation
## 1. Overview
### Objective
The Real-Time Cricket Commentary System is designed to provide live, dynamic commentary for ongoing cricket matches using the Mistral 7b GenAI API. The system leverages Python and MySQL to process live match data and generate text-based commentary in real time, enhancing the fan experience during matches.

### DEMO VIDEO FOR REAL TIME AI COMMENTARY
https://github.com/user-attachments/assets/11a1bb39-bea2-4475-8579-4a1803aef2f6


### Key Features
  * Live Commentary Generation: The system produces automatic, real-time commentary based on the live match data.
  * Mistral 7b GenAI API: Utilizes the power of the Mistral 7b GenAI model to generate contextual and engaging commentary.
  * Human-Like Emotional Touch: The generated commentary not only reflects match events but also adds human-like emotions, tone variations, and excitement, making it more engaging and relatable for the audience.
  * Python & MySQL Integration: The system is implemented using Python for processing and interacting with the Mistral API, while MySQL stores match-related data for easy retrieval and commentary generation.
## 2. Approach
### Data Flow
  * Live Match Data: Real-time match data (e.g., runs, wickets, overs) is fetched from the live match feeds.
  * API Interaction: The Mistral 7b GenAI API is called to generate commentary text based on the latest match data.
  * Commentary Generation: The commentary text is dynamically generated for each match event (e.g., boundary, wicket, over-end).
  * Database Storage: Commentary and match data are stored in a MySQL database, allowing for easy retrieval and management.
### Key Components
  * Mistral 7b GenAI API: Used to generate text commentary based on the live match data, ensuring contextually relevant commentary for each match event.
  * Python Scripts: Handle communication between the match data sources, the Mistral API, and the database, enabling seamless commentary generation.
  * MySQL Database: Stores real-time match data, commentary logs, and other necessary information, ensuring that all data is accessible for generating timely commentary.
### Workflow
  * Fetch Live Data: Continuously retrieve match data as the game progresses.
  * Generate Commentary: Use the Mistral 7b GenAI API to produce commentary based on the current match state.
  * Store and Display: Save the generated commentary to MySQL and display it to users via a web or mobile interface.
## 3. Benefits
  * Real-Time Engagement: Fans can receive up-to-date commentary while watching the match.
  * Human-Touch Commentary: The generated commentary mimics the tone, enthusiasm, and emotion of a human commentator, making it more immersive for the audience. "You just use this, and you can give your best!"
  * Scalability: The system can be easily scaled to handle multiple matches and can be adapted to different formats, such as T20, ODI, and Test matches.
  * Automation: The commentary generation process is fully automated, reducing the need for manual input and providing immediate feedback on match events.
## 4. Future Workflow
  * Generate Text Commentary: As the match progresses, the system will generate dynamic text-based commentary using the Mistral 7b GenAI API.
  * Convert to Speech: The text commentary will be passed through a text-to-speech engine to convert the written commentary into speech.
  * Real-Time Audio Output: The system will broadcast the generated speech in real time, synchronizing with the match events for an immersive experience.   
## 5. Conclusion
The Real-Time Cricket Commentary System offers a seamless, AI-driven solution for generating live commentary. By combining the Mistral 7b GenAI API with Python and MySQL, the system ensures that fans stay connected to the match with timely, relevant, and engaging commentary. The added human-like emotion and excitement make the commentary feel lively and real. This solution enhances the viewer experience and provides a new dimension to how live cricket matches are followed.
