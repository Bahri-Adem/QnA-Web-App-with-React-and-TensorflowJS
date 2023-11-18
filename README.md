# QnA Web App with React and TensorFlow.js

This project is a simple Question and Answer (QnA) web application developed using React and TensorFlow.js. The application allows users to input a passage of text and ask questions related to the provided passage. The underlying TensorFlow.js QnA model processes the input and generates answers based on the questions asked.

## Dependencies

- **@tensorflow/tfjs**: TensorFlow.js library for machine learning in JavaScript.
- **@tensorflow-models/qna**: TensorFlow.js QnA model for answering questions based on provided text passages.
- **react-loader-spinner**: Library for displaying loading spinners in React applications.

## Getting Started

To run this application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Bahri-Adem/QnA-Web-App-with-React-and-TensorflowJS.git
```
2. Install dependencies:

   ```bash
   npm install
```
3.Run the application:

   ```bash
   npm start
```

## Usage

- Upon running the application, a TensorFlow.js QnA model is loaded.
- Once the model is loaded, users can input a passage of text into the provided textarea.
- Users can then ask questions related to the provided passage in the input field labeled "Ask a Question" and press Enter.
- The application processes the question using the loaded model and displays answers along with their corresponding scores.

## functionalities

- Loading the TensorFlow.js QnA model.
- Handling user input for passage and questions.
- Processing questions and providing answers using the loaded model.
- Displaying the passage, input fields for questions, and showing answers.

