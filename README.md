# Dall-E Clone

This is a web application that uses OpenAI's DALL-E to generate unique images based on textual descriptions.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/Dg1sTdc/Screenshot-2023-05-01-012710.png" alt="Screenshot-2023-05-01-012710" border="0"></a>
<a href="https://ibb.co/561wd7L"><img src="https://i.ibb.co/0cnvkwr/Screenshot-2023-05-01-012648.png" alt="Screenshot-2023-05-01-012648" border="0"></a>

## Features

- Input textual descriptions to generate unique images
- Simple and easy to use interface
- Based on OpenAI's DALL-E generative model

## Installation

To install Dall-E Clone on your local environment, follow these steps:

Clone the repository to your local machine using `git clone https://github.com/KaiAlan/Dall-E-clone.git`
Navigate to the directory using `cd Dall-E-clone`.

1. Install the required dependencies:
```
npm install
```

2. Create a `.env` file in the root directory with the following variables:
   - `MONGODB_URI` - the URI for your MongoDB database
   - `SESSION_SECRET` - a secret string for session management`[OPENAI_API_KEY]`
   - `CLOUDINARY_CLOUD_NAME` - your Cloudinary cloud name
   - `CLOUDINARY_API_KEY` - your Cloudinary API key
   - `CLOUDINARY_API_SECRET` - your Cloudinary API secret

3. Start the development server:
```
npm run dev
```

## Usage

To use Dall-E Clone, follow these steps:

1. Navigate to `http://localhost:....` in your web browser.
2. Input a textual description of the image you want to generate in the input field provided.
3. Click the "Generate" button to generate an image.
4. Download the generated image or generate a new image using a different textual description.

## Contributing

If you'd like to contribute to Dall-E Clone, please follow these steps:

1. Fork the repository.
2. Create a new branch using `git checkout -b feature/<your-feature-name>`.
3. Make your changes and commit them with a descriptive commit message.
4. Push your changes to your fork using `git push origin feature/<your-feature-name>`.
5. Open a pull request and describe the changes you've made.

## Credits

- OpenAI - for their DALL-E generative model
- Kai Alan - for creating the web application based on the DALL-E model

## License

Dall-E Clone is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
