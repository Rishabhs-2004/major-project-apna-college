# 🌍 Wanderlust - Accommodation Listing Platform

Wanderlust is a full-stack web application designed to help users discover and list unique accommodations around the world. Built with the **MERN** stack (MongoDB, Express.js, React-like EJS templates, Node.js), it offers a seamless experience for browsing, creating, and managing property listings.

## 🚀 Features

- **Browse Listings**: View a wide range of available properties with images and pricing.
- **Create Listings**: Easily add new properties with details like title, description, image, and price.
- **Update & Delete**: Manage your listings with full editing and deletion capabilities.
- **Responsive Design**: Optimized for various screen sizes using Bootstrap.
- **Database Integration**: Robust data management with MongoDB.

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Frontend**: EJS (Embedded JavaScript templates), HTML5, CSS3, Bootstrap
- **Utilities**: method-override (for PUT/DELETE requests), ejs-mate (for layouts)

## 📦 Installation & Setup

Follow these steps to get the project running on your local machine:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Rishabhs-2004/major-project-apna-college.git
    cd major-project-apna-college
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Set up the Database:**
    - Ensure you have **MongoDB** installed and running locally.
    - Run the initialization script to seed the database with sample data:
      ```bash
      node init/index.js
      ```

4.  **Start the server:**
    ```bash
    node app.js
    ```

5.  **Visit the app:**
    Open your browser and go to `http://localhost:3000/listings` to see the platform in action!

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project, feel free to fork the repo and submit a pull request.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
