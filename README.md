# E-Commerce App

A modern, responsive frontend application for an electronics e-commerce store, built with React and Redux.

## 🚀 Overview

This project is a feature-rich e-commerce user interface designed for selling electronic products like iPads, Smart TVs, Headphones, and Cameras. It features a responsive layout, dynamic promotional banners, and a clean, user-friendly design.

## ✨ Features

- **Responsive Design**: Fully responsive layout optimized for varied screen sizes using **Bootstrap 5**.
- **Dynamic Home Page**:
  - **Hero Section**: Attractive main banners and promotional cards for featured products.
  - **Service Highlights**: key service indicators like Free Shipping, 24/7 Support, and Secure Payments.
  - **Product Categories**: Visual category browsing (Music & Gaming, Smart TVs, etc.).
- **Routing**: Client-side routing for seamless navigation between Home, About, and Contact pages.
- **State Management**: Structured to use **Redux Toolkit** for efficient state management.

## 🛠️ Technology Stack

- **Frontend Framework**: [React](https://reactjs.org/) (v18)
- **Routing**: [React Router DOM](https://reactrouter.com/) (v6)
- **State Management**: [Redux Toolkit](https://redux-toolkit.js.org/) & [React Redux](https://react-redux.js.org/)
- **Styling**:
  - [Bootstrap 5](https://getbootstrap.com/) (via CDN)
  - CSS3
- **Icons**: [React Icons](https://react-icons.github.io/react-icons/)
- **UI Components**: [React Fast Marquee](https://www.npmjs.com/package/react-fast-marquee)

## 📦 Getting Started

### Prerequisites

Make sure you have Node.js and npm installed on your machine.

### Installation

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2.  Navigate to the project directory:
    ```bash
    cd ecommerce
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```

### Running the App

To start the development server:

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view it in your browser. The page will reload when you make changes.

## 📁 Project Structure

```
src/
├── app/            # Redux store configuration
├── components/     # Reusable UI components (Layout, Header, Footer, etc.)
├── features/       # Redux features/slices
├── pages/          # Application route pages (Home, About, Contact)
├── App.js          # Main application component with routing
└── index.js        # Entry point
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
