# SportsShoes - E-commerce Shoe Store

The website is hosted via Netlify, below you can find the url
https://sportsshoes.netlify.app/

Welcome to **SportsShoes**, an intuitive, lightweight, and fully-functional e-commerce application designed for browsing and purchasing shoes. This front-end only project is powered by **React** and utilizes **localStorage** for managing the shoe items, enabling users to add, edit, delete, and view products dynamically without the need for a backend server.

## Features

- **Browse**: View a collection of sports shoes available for purchase.
- **Add to Cart**: Easily add shoes to your shopping cart.
- **Edit/Delete Items**: Make changes to the shoe items in your local storage or remove them altogether.
- **Persistent Storage**: All items and modifications are stored in **localStorage**, ensuring persistence between page reloads.
- **Responsive Design**: The application is built to work seamlessly across different devices and screen sizes.

## Tech Stack

- **React**: A JavaScript library for building user interfaces, providing a dynamic and responsive front-end.
- **CSS**: Styled using modern CSS techniques to ensure a clean, responsive, and user-friendly experience.
- **localStorage**: Client-side storage to persist product data without requiring a backend.

## Setup & Installation

### Prerequisites

- **Node.js**: Ensure you have [Node.js](https://nodejs.org/) installed on your system.
- **npm**: npm comes bundled with Node.js, but you can also install it separately.

### Steps to Get Started

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/DavidAslanyan/SportsShoes-Ecommerce.git
    ```
2. Navigate to the project directory if needed:
    ```bash
    cd SportsShoes
    ```
3. Install the required dependencies:
    ```bash
    npm install
    ```
4. Start the development server:
    ```bash
    npm start
    ```
5. Open your browser and visit [http://localhost:3000](http://localhost:3000) to view the app in action.

## Usage

### Manage Shoes in Local Storage
- **Add Items**: Users can add new shoe items to their collection.
- **Edit Items**: Modifications can be made to an existing item’s details (e.g., shoe name, price).
- **Delete Items**: Users can easily remove shoes from their collection.
- **View All**: All shoes currently stored in **localStorage** are displayed on the homepage.

## Code Structure

- `src/`: Contains all source code for the application.
  - `components/`: Reusable React components used throughout the app.
  - `conext/`: Global state shared via context api used throughout the app.
  - `hooks/`: Custom hooks used throughout the app.
  - `App.js`: The main component that renders the entire application.
  - `localStorage.js`: Utility functions to manage shoe data in local storage.

## Contributing

We welcome contributions to **SportsShoes**! If you'd like to contribute, please fork the repository, create a new branch, and submit a pull request. Here's how you can contribute:

1. Fork the repo.
2. Create your feature branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -am 'Add new feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the **React** community for making front-end development more enjoyable and efficient.
