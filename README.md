# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [https://rec-client-frontend.vercel.app/] to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.


### Working
**1. Main Features**
✅ User Login – Sign up and log in using email or Google.
✅ Recipe Management – Users can add, edit, delete, and share recipes.
✅ Live Updates – Any changes to recipes update instantly.
✅ Upload Images & Videos – Store media using Cloudinary or AWS S3.

**2. Frontend (React.js)**
✅ Easy Search & Filters – Find recipes by ingredients, cuisine, or difficulty.
✅ Step-by-Step Cooking Guide – Show images/videos for each step.
✅ Mobile-Friendly Design – Works smoothly on all devices.

**3. Backend (Express.js & Node.js)**
✅ Manage Recipes & Users – Create APIs to handle recipes, users, and reviews.
✅ Store Data in MongoDB – Save recipes, comments, and ratings.
✅ Faster Loading (Redis) – Speed up the app by caching frequent data.

**4. Real-Time Features**
✅ Live Editing – Multiple users can edit a recipe at the same time.
✅ Comments & Ratings – Users can rate and review recipes.
✅ Notifications – Get alerts for new recipes, likes, or comments.

**5. Security & Deployment**
✅ Secure Login (JWT) – Keep user data safe.
✅ Deploy Online – Host the app using Vercel/Netlify (Frontend) & Render/AWS (Backend).
✅ Error Handling – Prevent crashes with proper validations.

### Tech  stack
Tech Stack for Recipe Sharing Platform 
**1. Frontend (User Interface - React.js)**
🖥️ React.js – Builds the website's user interface.
🎨 Tailwind CSS / Material UI – Makes the website look stylish.
🔀 React Router – Helps users move between pages smoothly.
📝 Formik + Yup – Handles and validates form inputs.

**2. Backend (Server - Express.js & Node.js)**
🖧 Express.js – Manages requests and responses (handles login, recipes, etc.).
🔐 JWT / OAuth – Secures user logins (Google, Facebook).
📡 Socket.io – Enables real-time updates (live recipe editing).
✅ Joi / Express Validator – Checks if user inputs are correct.

**3. Database (MongoDB - Stores Data)**
💾 MongoDB – Saves recipes, users, and reviews.
🔗 Mongoose – Connects the database to the server.
⚡ Redis – Speeds up loading by storing frequently used data.

**4. File Storage & Notifications**
📸 Cloudinary / AWS S3 – Stores recipe images and videos online.
📧 Nodemailer / Firebase – Sends email notifications to users.

**5. Hosting & Deployment (Making the App Live)**
🌐 Vercel / Netlify – Puts the frontend online.
☁️ Render / AWS / Heroku – Hosts the backend (server).
🛢️ MongoDB Atlas – Stores the database in the cloud.
📌 Git & GitHub – Tracks code changes and teamwork.
