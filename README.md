# Raahi Social Media  Ȑ

[![Node.js](https://img.shields.io/badge/Node.js-v16.13.0-green?logo=node.js)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-v4.17.1-blue?logo=express)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-v4.4.12-green?logo=mongodb)](https://www.mongodb.com/)
[![React.js](https://img.shields.io/badge/React.js-v17.0.2-blue?logo=react)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v3.0.5-blue?logo=tailwind-css)](https://tailwindcss.com/)
[![jsonwebtoken](https://img.shields.io/badge/jsonwebtoken-v8.5.1-blue)](https://www.npmjs.com/package/jsonwebtoken)
[![Cloudinary](https://img.shields.io/badge/Cloudinary-v2.0.1-orange?logo=cloudinary)](https://cloudinary.com/)
[![Netlify](https://img.shields.io/badge/Netlify-v2.0.0-blue?logo=netlify)](https://www.netlify.com/)


Welcome to Raahi Social Media, a full-stack social media application built with Node.js, Express.js, MongoDB, and React.js.

## Live Demo

The project is live at [Raahi Social Media](https://raahi-social-media.netlify.app/).

## Features

- User signup with validation and optional profile fields.
- Infinite scrolling for posts list.
- Responsive design using Tailwind CSS.
- JWT token authentication.
- Secure password storage.
- API endpoints for user registration and fetching posts.

## Getting Started Locally

### Prerequisites

- Node.js installed on your machine.
- MongoDB installed and running locally or Use Mongo Atlas.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/samriddha-basu-cloud/raahi-social-media.git
cd raahi-social-media
```

2. Install dependencies:

```bash
npm install
```

3. Set up environment variables:
   
   Create a `.env` file in the root directory and add the following variables:

```plaintext
MONGO_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>
```

### Running the Application

1. Start the server:

```bash
npm start
```

2. Start the client (in a separate terminal):

```bash
cd client
npm start
```

3. Open your browser and visit `http://localhost:3000` to view the application.

## Contributing

Contributions are welcome! Please feel free to submit pull requests to improve the project.

## Contact

For any inquiries or feedback, please contact sb2899@srmist.edu.in;

## License

This project is open-source and available without Licensing.
