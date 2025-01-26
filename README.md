# Anjani-AI
# Anjani AI - Personalized Gemini Clone

Anjani AI is a personalized chatbot built using Google’s Gemini API, designed to offer interactive responses to user queries. It leverages the Gemini 2.0 model to provide helpful suggestions, summaries, brainstorming ideas, and much more. This project aims to create an AI that understands and responds to user input dynamically, helping users with various tasks.
## Features

- **Generative AI**: Uses Google Gemini 2.0 to generate relevant responses.
- **Personalized Chatbot**: Responds with contextual answers based on the user’s previous input.
- **User-Friendly Interface**: Clean, modern UI with a smooth chat experience.
- **Prompt Suggestions**: Predefined suggestions for users to start a conversation.
- **Loading State**: The chatbot indicates when it's processing a request, providing a seamless experience.
- **Error Handling**: Handles errors gracefully and provides feedback when necessary.

---

## Tech Stack

- **Frontend**: 
  - React.js
  - Context API for state management
  - HTML, CSS
- **Backend**:
  - Google Generative AI API (Gemini)
  - Node.js (for API interaction)
- **Environment**:
  - React Environment
  - GitHub Pages for deployment (optional)

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Anjani-AI.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Anjani-AI
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Create an `.env` file** in the root of the project and add your Gemini API key:
   ```
   REACT_APP_GOOGLE_API_KEY=your_google_api_key_here
   ```

5. **Run the project locally**:
   ```bash
   npm start
   ```

   Your application will be running on [http://localhost:3000](http://localhost:3000).

---

## Usage

- Upon visiting the app, you will be greeted with a friendly message: "Hello, [Your Name]. How can I help you today?"
- You can type prompts directly or use the predefined suggestion cards to interact with the chatbot.
- The chatbot will respond based on the prompt entered, whether it's summarizing content, brainstorming ideas, or suggesting places.
- You can also ask for help with coding or ask general questions, and the bot will generate text-based responses.

---

## Example Prompts

Here are some example prompts you can try:
- Suggest beautiful places to see on an upcoming road trip.
- Briefly summarize the concept of urban planning.
- Brainstorm team bonding activities for our work retreat.
- Improve the readability of the following code: `function test() { console.log("Hello World"); }`

---

## Contributing

We welcome contributions to improve Anjani AI! To contribute:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.



## Acknowledgments

- **Google Gemini API**: For providing powerful generative AI capabilities.
- **React.js**: For building the dynamic and responsive UI.
- **Open Source Contributors**: For helping improve the project.


