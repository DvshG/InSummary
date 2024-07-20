# In-Summary: AI Text Summarizer App

In-Summary is an AI-powered text summarizer application that allows users to quickly and efficiently summarize large blocks of text. By leveraging advanced natural language processing techniques, In-Summary saves time and enhances productivity.

## Working with Image
![Screenshot 2024-07-20 114726](https://github.com/user-attachments/assets/beeec02f-e14a-4314-9c99-b8b796016328)
The application uses a POST request to Hugging Face's BART-Large-CNN model to summarize text. The summarized text is then displayed in the output textarea.


## Features

- **AI-Powered Summarization**: Quickly summarize large texts using AI.
- **Easy to Use**: Simply paste text and click "Summarize".
- **Responsive Design**: Works seamlessly on all devices.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **API**: Hugging Face's BART-Large-CNN model
- **Language**: JavaScript

## Installation

### Requirements

- Node.js (v14.x or later)
- npm

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/insummary.git
   cd insummary
   ```
2. Install dependencies:

  ```bash
  npm install
  ```
## Usage
1. Start the server:

```bash
npm start
```
2. Open your browser and go to http://localhost:3000 to use the application.

## Project Structure
### Public
- **index.html**: Main HTML file containing the structure of the application.
- **stylesheet.css**: CSS file for styling the application.
- **script.js**: JavaScript file containing the main logic for text input, button interaction, and API call.
### Server
- **index.js**: Sets up the Express server and handles API requests.
- **summarize.js**: Contains the function to call the AI summarization API.

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch ```git checkout -b feature/your-feature```
3. Commit your changes ```git commit -m 'Add some feature'```
4. Push to the branch ```git push origin feature/your-feature```
5. Open a pull request.

## Requirements
- Node.js (v14.x or later)
- npm
## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.
