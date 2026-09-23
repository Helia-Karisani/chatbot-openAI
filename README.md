# Software Development Chatbot Using OpenAI API

A simple web-based chatbot that answers software development–related questions using the OpenAI API.
Built with **Node.js**, **Express.js**, and a lightweight **HTML/CSS/JavaScript** front end.

## Features

* Interactive chat interface built with HTML/CSS/JS.
* Backend powered by Express.js to handle API requests.
* Integration with OpenAI’s GPT model for natural responses.
* Clean and minimal UI with a custom logo.
* Ready-to-run locally with your own API key.

## Project Structure

```
software-dev-chatbot/
│
├── public/                # Frontend files
│   ├── index.html         # Chat UI
│   ├── style.css          # Styles
│   ├── main.js            # Frontend logic
│   └── chat.png           # Logo
│
├── openai.js              # OpenAI API wrapper
├── server.js              # Express.js server
├── package.json           # Project dependencies
└── README.md              # Project documentation
```

## Getting Started

### 1. Clone this repository

```bash
git clone https://github.com/your-username/software-dev-chatbot.git
cd software-dev-chatbot
```

### 2. Install dependencies

Make sure you have [Node.js](https://nodejs.org/) installed.
Then run:

```bash
npm install
```

### 3. Set your OpenAI API Key

Create a `.env` file in the root of the project and add:

```
OPENAI_API_KEY=your_api_key_here
```

Or set it in your terminal session:

```bash
export OPENAI_API_KEY="your_api_key_here"   # Mac/Linux
setx OPENAI_API_KEY "your_api_key_here"     # Windows (PowerShell)
```

### 4. Start the server

```bash
node server.js
```

### 5. Open the app

Navigate to [http://localhost:3000](http://localhost:3000) in your browser. 

## Usage

Type a question in the input box (e.g., *"What is the difference between a stack and a queue?"*) and press **Send**.
The chatbot will return an AI-generated answer powered by OpenAI.

## Demo
![Chatbot UI Screenshot](chatDemo.png)


## Technologies Used

* **Node.js** – server-side JavaScript runtime
* **Express.js** – backend web framework
* **OpenAI API** – natural language model for chatbot responses
* **HTML, CSS, JavaScript** – frontend UI

## Notes

* In this GitHub version, you’ll need to supply your own OpenAI API key.
* The project is intended for educational purposes and to demonstrate how to integrate AI into web applications.


