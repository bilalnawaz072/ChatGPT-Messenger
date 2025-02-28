https://chatgpt-messenger-plus.vercel.app/

# ChatGPT Plus App Built with Next.js + Tailwind CSS

Enhance your conversational AI experience with my upgraded version of the ChatGPTv3 user client from OpenAI. With a custom API integrated to fetch responses to your queries and store them in a database hosted on Google Firebase, this platform provides a streamlined and efficient solution. I have also added a feature that allows users to select their desired AI model before sending a prompt, providing greater control over the conversational experience.

## Local Setup
1. clone or fork the repo onto your computer
2. download and install the latest version of node.js (https://nodejs.org/en/) for your Operating System
3. using your Command Line navigate to the folder where the files are saved
4. run 'npm i' to install all the dependencies
5. next run 'npm run dev' to start the server on localhost:3000

## How to use 
- Click "new chat" to open a new chat window
- Optionally you can select a model from the "model list" to test your prompts by default it will be set to the "text-davinci-003" model
- After writing your message click enter or the submit green arrow to send your message to the openAI API 
- A loading notification will begin and when it ends your response will be shown on the screen 

## Features
- Faster Responses with the removal of the text stream feature from chats
- The ability to change the model at any time to give you more control over responses
- All responses are saved to a database to look at past responses at anytime

## Packages

- `@heroicons/react`: a library of free icons that can be used in your React projects
- `firebase and firebase-admin`: packages for using Firebase, a backend platform that provides services like authentication, cloud storage, and real-time database.
- `next`: a framework for building server-rendered React applications
- `openai`: a package for accessing the OpenAI API
- `react and react-dom`: packages for building user interfaces with React
- `react-firebase-hooks`: a collection of hooks for using Firebase with React
- `react-hot-toast`: a package for displaying toast notifications in React
- `react-select`: a package for building customizable and accessible dropdowns and select inputs in React
- `swr`: a package for data fetching in React

## Coming Soon
- more control over responses by using the API params in the frontend (n, temperature, etc.)
- user accounts to only see your responses
