PopX React Application
This is a simple React application demonstrating basic routing and component structure for a fictional "PopX" service.

Table of Contents
Features
Installation
Usage
Components
Styling
Routing
Contributing
Features
User authentication flows including account creation and login.
A dedicated page for displaying user account settings.
Basic form handling for user input.
Navigation between different sections of the application.
Install dependencies:

npm install


Usage
##To run the application in development mode:

npm run dev
This command will typically open the application in your browser at http://localhost:5173/.

Components
The application is structured into the following React components:

App.jsx: The main application component that sets up the routing for the application.
Landingpage.jsx: The initial landing page that welcomes users and provides options to create an account or log in.
CreateAcc.jsx: A component providing a form for new users to create a PopX account, collecting details like full name, phone number, email, password, company name, and agency status.
Login.jsx: A component with a form for existing users to sign in to their PopX account using their email address and password.
Account.jsx: Displays a user's account settings, including a profile image (which appears to be a placeholder), name, email, and a descriptive paragraph. It also includes a camera icon over the profile image.
Styling
Each major component has its dedicated CSS file for styling, located in the styles directory:

account.css for the AccountSettings component.
createpage.css for the SignupForm component.
Landingpage.css for the Landingpage component.
login.css for the Login component.
Routing
The application uses react-router-dom for client-side routing. The following routes are defined:

/: Renders the Landingpage component.
/login: Renders the Login component.
/signup: Renders the CreateAcc component.
/account: Renders the Account component.
Contributing
Contributions are welcome! Please feel free to open issues or submit pull requests.



# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
