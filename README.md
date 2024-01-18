# Dall-E Clone

A full-stack MERN application that mimics the functionality of OpenAI's DALL-E, allowing users to generate images based on textual prompts.

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

1. Clone the repository:

   ```bash
   git clone https://github.com/7AkhilV/dalle-clone.git
   cd dalle-clone/client

2. Install dependencies

   ```bash
   npm install

3. Run the app
   ```bash
   npm run dev

   
### Backend

1. Navigate to the backend directory:

   ```bash
   cd ../server

2. Install dependencies

   ```bash
   npm install


3. Configure the backend:
   Create a `.env` file with the following:
   `MONGODB_URL=your_mongodb_uri
    OPENAI_API_KEY=your_openai_api_key
    CLOUDINARY_CLOUD_NAME = 'your_cloudinary_name'
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret`

4. Run the app
   ```bash
   npm start




