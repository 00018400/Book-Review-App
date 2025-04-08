# Book Review App

This is a simple web application for managing book reviews, developed as part of the Web Technology module. The app allows users to view, create, edit, and delete book reviews. It features a minimalistic design and is built using Node.js, Express, and vanilla JavaScript.

## Features

- View a list of book reviews.
- Add a new book review.
- Edit an existing book review.
- Delete a book review.
- Minimalistic design with a monochromatic color scheme and a single accent color (soft blue).

## Structure of the Project
/book-review-app
├── app.js              # Main application file
├── package.json        # Project configuration file
├── package-lock.json   # Lock file for dependencies
├── .gitignore          # File to exclude node_modules from Git
├── README.md           # Project documentation
├── public/             # Folder for static files
│   ├── images/         # Folder for images (contains placeholder)
│   │   └── placeholder.txt
│   ├── javascripts/    # Folder for client-side scripts
│   │   ├── index.js    # JavaScript for the main page
│   │   ├── create.js   # JavaScript for the create page
│   │   ├── edit.js     # JavaScript for the edit page
│   │   └── view.js     # JavaScript for the view page
│   ├── styles/         # Folder for styles
│   │   └── style.css   # Main stylesheet
│   └── views/          # Folder for HTML pages
│       ├── index.html  # Main page with list of reviews
│       ├── create.html # Page for creating a new review
│       ├── edit.html   # Page for editing a review
│       └── view.html   # Page for viewing a review
├── routes/             # Folder for routes
│   ├── index.js        # Placeholder for routes (not used)
│   └── reviews.js      # Routes for handling reviews
├── controllers/        # Folder for controllers
│   └── reviews.js      # Controller for handling review logic
└── services/           # Folder for service layer logic (not used)

## Notes
The in-memory reviews array in the app is located in controllers/reviews.js. All data will be lost when the server restarts because it is not persistent.

-The design features minimalist and monochrome styling with soft blue highlights as per the requirements of the assignment.
-The public/javascripts folder contains all client-side JavaScript files. It is better for the code to be organized this way.
-The package-lock.json is added to guarantee that all versions of the dependencies used will be the same every time.

## Technologies Used

-Node.js: Server-side operation environment.
-Express: Server framework for Node.js.
-JavaScript: Frontend and backend scripting language.
-HTML/CSS: Markup and styles for the user interface.

## Links

- **GitHub Repository**: https://github.com/00018400/Book-Review-App
- **Deployed Application**: (Add the link after deploying to Render, e.g., `https://book-review-app.onrender.com`)