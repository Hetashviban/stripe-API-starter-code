# Stripe API Starter Code

This project demonstrates how to integrate the Stripe API into an Express.js application using Handlebars (HBS) for templating.

## Prerequisites

- Node.js installed
- npm (Node Package Manager) installed
- A Stripe account

## Setup Instructions

### Step 1: Create a Project Folder

1. Create a folder on your operating system to hold the project files.
2. Open this folder in Visual Studio Code (VS Code).

### Step 2: Clone the Repository

1. Go to the GitHub repository: [Stripe API Starter Code](https://github.com/Hetashviban/stripe-API-starter-code).
2. Clone the repository to your local machine using the following command:
    ```bash
    git clone https://github.com/Hetashviban/stripe-API-starter-code
    ```
3. Navigate to the cloned directory:
    ```bash
    cd stripe-API-starter-code
    ```
   Or if you extracted the code from a zip file, navigate to the extracted folder.

### Step 3: Install Dependencies

1. Install the necessary npm packages:
    ```bash
    npm install
    ```
2. Install the Stripe package:
    ```bash
    npm i stripe
    ```

### Step 4: Set Up Environment Variables

1. Log in to your Stripe account.
2. Go to `Developers` -> `API Keys` to find your Publishable Key and Secret Key.
3. Create a `.env` file in the root of your project directory.
4. Add your Stripe keys to the `.env` file in the following format:
    ```env
    STRIPE_PUBLISHABLE_KEY=your_publishable_key_here
    STRIPE_SECRET_KEY=your_secret_key_here
    ```

### Step 5: Modify Project Files
Make changes to the following files as needed:

- `payment.js`
- `index.js`
- `index.hbs`

Follow along in the class for setting up STRIPE

### Step 6: Start the Server

1. Run the server:
    ```bash
    npm start
    ```
2. Open your browser and navigate to `http://localhost:3000`.

You should now see the "Pay Now" button, and the payment process should be set up using the Stripe API.