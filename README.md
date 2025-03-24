# Welcome to My Backend Yelp

---

## Task

The challenge was to create a scalable backend using AWS Amplify, integrate authentication, and make the UI intuitive for managing restaurants effectively. The main problem this app solves is allowing users to manage restaurant data, including adding new restaurants, viewing a list of restaurants, and deleting restaurant entries.

## Description

The problem was solved by leveraging AWS Amplify to manage authentication (sign in and sign out)
and data storage for the restaurant listings. The frontend is built using React to provide a smooth user interface where users can:

- Sign up and sign in via AWS Amplify Authentication.
- Create a new restaurant listing by providing a name and description.
- View the list of restaurant entries.
- Remove a restaurant listing. The project uses GraphQL API for the queries and mutations that handle interactions with the backend, such as creating and deleting restaurants.

## Installation

To get started with this project, follow these steps:
-Clone the repository: git clone https://git.us.qwasar.io/my_backend_yelp_180317_sy2f1i/my_backend_yelp.git
cd my_backend_yelp
-Install the react and its dependencies, by running npx create-react-app . for the frontend, and make sure you have `npm` installed. Run the following command to install the necessary packages: npm install. update App.js file to accommodate the user authentication and restaurant creation, and the App.css file for the corresponding styles
-Set up AWS Amplify for the backend - set up the AWS Amplify configuration. If you don’t already have an AWS account, create one at [aws.amazon.com](https://aws.amazon.com/).
Follow the instructions in the AWS Amplify documentation to configure the project with services like Authentication and GraphQL API. by running amplify add auth, amplify add api and run amplify push to effect the changes.
-Start the app:
After completing the installation, the app can be start locally by running:
npm start
This will launch the app in the browser, typically at `http://localhost:3000`.

## Usage

When everything is working, Hosting was setup with Amplify.
The app was deployed with AWS Amplify Hosting, through the following steps:
amplify add hosting
After hosting was added, it was deployed by running:
amplify publish
This command build and deploy the app to the Amplify Hosting service. After the process finishes, The URL for the app was available as:https://d20icubalev4wi.cloudfront.net/

This application allows users to:

1. Sign up/sign in: Use AWS Amplify to sign up or sign in with email and password.
2. Create a new restaurant: After signing in, users can add a new restaurant by providing the name and description of the restaurant.
3. View a list of restaurants: Users can view the restaurants they have added. The list is fetched from the backend using a GraphQL query.
4. Delete a restaurant: Users can remove a restaurant listing they no longer want by clicking the "Remove" button next to the restaurant.

To use the app:

- Sign in with your account.
- Add restaurants by filling out the form.
- View the list of restaurants below.
- Click "Remove" to delete any listing.
  Technologies Used

- React: Frontend framework for building the UI.
- AWS Amplify: Backend services for user authentication and GraphQL API.
- GraphQL: Query language used to interact with the database.
- AWS Cognito: Managed service for handling user authentication.
- AWS AppSync: Managed GraphQL service for interacting with the backend.

```
./my_backend_yelp
```

### The Core Team

This project was developed by Salaha Abubakar

<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>
