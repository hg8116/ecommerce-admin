# eCommerce Admin

Welcome to the repository of the eCommerce Admin Panel.

## Project Overview

The eCommerce admin is the control panel for [eCommerce store](https://ecommerce-store-green-eight.vercel.app/). The panel lets the user create multiple store easily and quickly. It provides features such as adding and updating products and there stock, helps in tracking the revenue and generates easy to use APIs.

## Getting Started

Follow these steps to run the project locally:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/hg8116/ecommerce-admin.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd ecommerce-admin
   ```

3. **Install Dependencies:**

   ```bash
   npm install
   ```

4. **Environment Variables**
   Create a .env file inside the root folder and fill the following secrets -

   ```
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=""
   CLERK_SECRET_KEY=""
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

   DATABASE_URL=""
   DIRECT_URL=""
   NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=""
   STRIPE_API_KEY=""
   FRONTEND_STORE_URL=http://localhost:3001
   STRIPE_WEBHOOK_SECRET=""
   ```

5. **Run the Development Server:**

   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser to view the eCommerce admin panel.

## Customization

Feel free to customize the landing page to fit your specific needs. Update content, modify styles, and add additional components as required.

## Deployment

This project is ready to be deployed to platforms like Vercel or Netlify. Refer to the documentation of your chosen hosting service for deployment instructions.

## Contributing

If you'd like to contribute to this project, please follow the standard GitHub flow: fork the repository, create a branch, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for checking out our eCommerce Admin Panel! If you have any questions or feedback, feel free to open an issue.

This project is just made for educational purpose, thank you to [Code With Antonio](https://www.youtube.com/@codewithantonio) for the tutorial.
