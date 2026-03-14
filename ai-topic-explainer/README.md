# AI Study Topic Explainer 🎓

## Project Description
This is an AI-powered tool built to help students understand complex study topics. Users can enter a topic like "Photosynthesis" or "Binary Search," and the application provides a simple, student-friendly explanation.

## How AI API was Used
* **Model**: This project uses the **Gemini API** (Free Tier).
* **Integration**: I created a Next.js API route at `POST /api/explain`.
* **Functionality**: When the "Explain Topic" button is clicked, the app sends the topic to the Gemini API with a prompt to simplify the concept for a student.

## Setup Instructions
1. **Clone the repository** to your local machine.
2. **Install dependencies**:
   ```bash
   npm install