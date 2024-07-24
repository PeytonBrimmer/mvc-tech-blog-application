# MVC Tech Blog
![alt text](screenshot)
## Description
MVC Tech Blog is a web application that allows users to create, read, update, and delete blog posts. It follows the Model-View-Controller (MVC) architectural pattern, providing a structured and organized approach to building the application.

## Features
- User authentication: Users can sign up, log in, and log out securely.
- Blog posts: Users can create, view, edit, and delete their own blog posts.
- Commenting system: Users can leave comments on blog posts.
- User profiles: Users have their own profile page where they can view and manage their blog posts.

## Technologies Used
- Node.js
- Express.js
- Sequelize (ORM)
- MySQL (Database)
- Handlebars (Templating Engine)
- Passport.js (Authentication)
- Bootstrap (CSS Framework)

## Installation
1. Clone the repository: `git clone https://github.com/peytonbrimmer/mvc-tech-blog.git`
2. Install the dependencies: `npm install`
3. Set up the database:
    - Create a MySQL database.
    - Update the database configuration in `config/config.js`.
    - Run the database migrations: `npx sequelize-cli db:migrate`
4. Start the application: `npm start`

## Usage
- node server.js in the command line to run the server
- Visit the application in your web browser at `http://localhost:3001`.
- Sign up or log in to start creating and managing your blog posts.
- Explore other users' blog posts and leave comments.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
