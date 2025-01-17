
# Insight Haven Backend

## Overview
This is the backend for the Insight Haven blog platform. It is built with Node.js, Express, PostgreSQL, and Sequelize. The backend handles article management, user authentication, and other functionalities.

## Features
- **Article Management**: Create, edit, and delete articles.
- **User Authentication**: Secure login and registration.
- **Dashboard**: Manage articles, users, and site settings.

## Getting Started

### Prerequisites
- Node.js and npm (or yarn)
- PostgreSQL

### Installation
1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd insight-haven-bn
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root of the project and add the following:
   ```dotenv
   # .env

   # Development database URL
   DEV_DATABASE_URL=postgres://username:password@localhost:5432/development_db

   # Test database URL
   TEST_DATABASE_URL=postgres://username:password@localhost:5432/test_db

   # Production database URL
   DATABASE_URL=postgres://username:password@localhost:5432/production_db

   # JWT Secret
   JWT_SECRET=your_jwt_secret
   ```

### Running the Project
1. **Run database migrations:**
   ```bash
   npx sequelize-cli db:migrate
   ```

2. **Start the development server:**
   ```bash
   npm run dev
   ```

   The server will be running on `http://localhost:3000`.


### Deployment
The project is hosted on Vercel.

### Contributing
To contribute:
1. Fork the repository.
2. Create a new branch.
3. Commit changes and push to the branch.
4. Open a pull request.

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Acknowledgments
- Thanks to the Node.js, Express, PostgreSQL, and Sequelize communities.
- Special thanks to the contributors of the project.

