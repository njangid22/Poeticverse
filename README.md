# Welcome to PoeticVerse

## Project Overview
PoeticVerse is a web application designed to enhance creative writing and poetry sharing. This repository contains the source code and necessary setup instructions to get started.

## Features
- User authentication and account management
- Rich text editor for writing poetry
- Poetry sharing and social interactions
- Theming and customization options
- Mobile-responsive design

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone <YOUR_GIT_URL>
   ```
2. Navigate to the project directory:
   ```sh
   cd <YOUR_PROJECT_NAME>
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm run dev
   ```

## Technologies Used
This project is built with:
- **Vite** - Fast front-end build tool
- **TypeScript** - Typed JavaScript for better development experience
- **React** - Component-based UI library
- **shadcn-ui** - UI components for rapid development
- **Tailwind CSS** - Utility-first CSS framework
- **Express.js** - Backend server for API handling
- **MongoDB** - Database for storing poetry and user data

## Deployment
To deploy the project:
- Use **Netlify** for front-end hosting
- Use **Vercel** or **Heroku** for backend hosting
- Set up **MongoDB Atlas** for cloud database

### Environment Variables
Before running the project, set up the required environment variables in a `.env` file:
```
REACT_APP_API_URL=<your_api_url>
MONGODB_URI=<your_mongodb_connection>
JWT_SECRET=<your_secret_key>
```

## Contributing
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

## License
This project is licensed under the MIT License.

For any questions or issues, feel free to reach out via GitHub Issues.

