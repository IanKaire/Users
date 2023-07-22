# Users List
This is a simple React application that allows users to input usernames and ages, and then displays the list of users with their corresponding age. The app ensures form validation for both the username and age entry using the useReducer hook to manage related states. Additionally, it uses ReactDOM.createPortal to display an error modal if the user leaves any field empty.
# Features
User Input: The app allows users to enter their username and age in separate input fields.

Form Validation: The app checks for empty fields and displays an error modal when either the username or age is left empty.

User List: Once the user successfully enters both the username and age, the app displays the list of users along with their corresponding ages.

Error Modal: In case of empty fields, an error modal is shown using ReactDOM.createPortal, which overlays the main content and alerts the user about the empty fields.
# Screenshots
![UserList](https://github.com/IanKaire/Users/assets/114652346/3bdd36ff-b963-48b5-b0ae-ce39b7b58227)
![ErrorModal](https://github.com/IanKaire/Users/assets/114652346/795e1a6b-daba-42c0-8099-ca5b4fca9ca9)

# Setup
1. Clone the repository
   
2. Install dependencies: npm install or yarn install
   
3. Run the app: Use npm start or yarn start to start the development server and view the app in your web browser.
