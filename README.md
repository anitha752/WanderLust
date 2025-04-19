# WanderLust - Airbnb Clone
WanderLust is a web application that replicates the core features of Airbnb, built with modern web technologies like Node.js, Express.js, MongoDB, and EJS. It allows users to manage listings, leave reviews, and much more. Whether you're looking for a place to stay or want to host your own, WanderLust has got you covered!

## Key Features
-**User Login**: Secure login system to manage your account.
-**Add Properties**: Post your property or space for rent, including title, description, price, and images.
-**Edit and Delete Properties**: Easily update or remove your listings at any time.
-**Add and Delete Reviews**: Share your experience with other users and delete reviews if needed.
-**Image Upload**: Upload images of your listings to make them more attractive to potential guests.

## Tech Stack
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Frontend**: HTML, CSS, JavaScript (with EJS for dynamic content)
- **Architecture**: Follows MVC (Model-View-Controller) pattern
- **API**: Implements RESTful API for managing data (CRUD operations)

##  Getting Started

Follow these steps to run the **WanderLust** project on your local machine:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/anitha752/WanderLust.git


2️⃣ Install Dependencies
Navigate into the project directory and install the required dependencies:
cd WanderLust
npm install


3️⃣ Set Up Environment Variables
Create a .env file in the root directory of the project, and add your environment variables. Here's an example:
dbUrl=your_database_connection_string
SECRET_KEY=your_secret_key


4️⃣ Start the Application
Once everything is set up, start the server using:
npm start
Visit http://localhost:8080 to view the application in your browser.

## Usage
Login/Sign Up: Users can create an account or log in to manage listings and reviews.
Manage Listings: As a logged-in user, you can add, edit, or delete your listings.
Leave Reviews: You can add and delete reviews for other listings.

## Deployment
The app is live on Render, where it's hosted for production use. It uses MongoDB for data storage, and environment variables are securely handled.

## Contributing
Want to contribute? Feel free to fork the repository and submit a pull request with your improvements! Make sure to write clear, clean code, and follow best practices.

Feel free to adjust the wording or add any more information that fits your project’s scope. This version is designed to be clear, friendly, and informative for other developers or users viewing your project!
