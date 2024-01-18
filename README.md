# Dall-E Clone

A full-stack MERN application that mimics the functionality of OpenAI's DALL-E, allowing users to generate images based on textual prompts.

live link: https://dalle-clone-pi.vercel.app/

## Features

- **Prompt Generation:** Users can input textual prompts to generate unique and creative images.
- **Image Download:** Generated images can be downloaded by users.
- **Technology Stack:** Utilizes Vite, Tailwind CSS, File-Saver, React on the frontend, and Cloudinary, Node.js, Express, MongoDB, and OpenAI API on the backend.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed
- MongoDB set up and running
- Cloudinary account for image storage
- OpenAI API key

## Getting Started

### Frontend

![Screenshot (146)](https://github.com/7AkhilV/dalle-clone/assets/118068004/a98ba5d2-f7fa-4cd6-a452-2b498bb91fea)

![Screenshot (144)](https://github.com/7AkhilV/dalle-clone/assets/118068004/1178efb4-800f-4201-823c-56d8d8527bdf)


1. Clone the repository:

   ```bash
   git clone https://github.com/7AkhilV/dalle-clone.git
   cd dalle-clone/client

2. Install dependencies
   `npm install`

3. Run the app
   `npm run dev`

   
### Backend

1. Navigate to the backend directory:

   ```bash
   cd ../server

2. Install dependencies
   `npm install`


3. Configure the backend:
   Create a `.env` file with the following:
   ```bash
    MONGODB_URL=your_mongodb_uri
    OPENAI_API_KEY=your_openai_api_key
    CLOUDINARY_CLOUD_NAME =your_cloudinary_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret

5. Run the app
   `npm start`

### Usage

1. Access the application at the given PORT.
2. Enter a prompt and generate an image.
3. Download the generated image.

### Acknowledgments

1. OpenAI for providing the powerful image generation API.
2. FileSaver.js for enabling file-saving functionality.



