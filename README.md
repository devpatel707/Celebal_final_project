# E-SHOP

E-SHOP is a dynamic e-commerce platform built on the MERN stack, catering to modern shopping needs with user-friendly interfaces and robust functionality. This platform offers a comprehensive range of features designed to enhance the shopping experience for users and provide administrators with efficient management tools.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)


## Features

- **Secure Authentication**: Login and sign-up pages with secure authentication to ensure personalized shopping experiences.
- **Intuitive Design**: Separate sections for men, women, and kids to facilitate efficient browsing and product discovery.
- **Shopping Cart**: Comprehensive shopping cart functionality with essential product details such as images, titles, prices, quantities, and totals. Users can easily modify selections and remove items.
- **Newsletter Subscription**: Dedicated section for users to subscribe to newsletters and stay informed about the latest offerings and promotions.
- **Admin Panel**: Intuitive backend panel for administrators to manage products, including adding new products, updating existing listings, and overseeing inventory.
- **Promotions and New Collections**: Capability to showcase new collections and promotional offers on the main page and shop sections.

## Prerequisites

- Node.js (>= 12.x)
- npm (>= 6.x)

## Installation

To run E-SHOP locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/E-SHOP.git
    cd E-SHOP
    ```

2. **Install dependencies for the backend:**
    ```bash
    cd backend
    npm install
    ```

3. **Install dependencies for the frontend:**
    ```bash
    cd ../frontend
    npm install
    ```

## Usage

1. **To run the Frontend:**
    ```bash
    npm run start
    ```

2. **To run the Backend:**
    ```bash
    node ./index.js
    ```

3. **To run the Admin Panel:**
    ```bash
    npm run dev
    ```

## Folder Structure

```bash
E-SHOP/
  ├── backend/
  │   ├── controllers/
  │   ├── models/
  │   ├── routes/
  │   ├── config/
  │   └── index.js
  ├── frontend/
  │   ├── public/
  │   ├── src/
  │   │   ├── components/
  │   │   ├── pages/
  │   │   ├── redux/
  │   │   ├── App.js
  │   │   └── index.js
  ├── admin/
  │   ├── public/
  │   ├── src/
  │   │   ├── components/
  │   │   ├── pages/
  │   │   ├── redux/
  │   │   ├── App.js
  │   │   └── index.js
  ├── README.md
  └── package.json
```