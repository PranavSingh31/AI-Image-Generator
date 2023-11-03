# OpenJourney Image Generator

The OpenJourney Image Generator is a web application that allows users to generate a set of unique and creative images based on a given text prompt. This project leverages the power of the Hugging Face "prompthero/openjourney" model to create imaginative artwork in response to user inputs.

## Features

- **Generate Artwork**: Users can enter a text prompt in the input field and click the "Generate" button to create a collection of up to four unique images based on their prompt.

- **Randomization**: The application incorporates randomization by appending a random number to the user's input, making each image generated slightly different from the previous ones.

- **Image Download**: Users can download any of the generated images by clicking on them. The images are automatically saved with a user-friendly filename.

## Usage

1. Clone this repository to your local machine.

2. Obtain an API key from Hugging Face by signing up on their website.

3. Open the `index.html` file in a web browser.

4. Enter your Hugging Face API key in the `apikey` variable in the JavaScript code.

5. Enter your text prompt in the input field and click the "Generate" button.

6. Wait for the application to generate and display up to four images based on your input.

7. Click on any image to download it to your computer.

## Dependencies

- This project requires an internet connection to access the Hugging Face model.

## Development

If you want to further develop or customize this project, here's what you can do:

- Modify the `maxImages` variable to control the number of images generated per request.

- Customize the styling of the web page by modifying the CSS in the `style.css` file.

- Enhance error handling and user feedback, as the current version provides basic alerts for errors.

- Explore other Hugging Face models for different types of generative content.

- Implement additional features, such as saving a history of generated prompts and images.

## About

This project was created as a fun and creative way to generate artwork using natural language prompts. Feel free to use, modify, or extend it as needed. If you have any questions or encounter issues, please don't hesitate to reach out. Happy generating!
