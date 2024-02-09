## CSV Upload File Backend

This project is a CSV file upload system built using Node.js, EJS, CSS, and JavaScript. It's designed to be responsive across all devices.

## Features
File Upload: Users can upload CSV files into the system using Multer JS.
File Management: Displays a list of all uploaded CSV files. Each file is parsed, converted into JSON, and stored in a Mongo Database.
Data Display: Upon selecting a file, it displays all the data (with column headers) in a table on the frontend.
Search Functionality: Includes a search box that filters and displays matching rows in the table based on user input. An empty search box displays all the data.
Sorting: Enables sorting functionality (ascending and descending) for each column in the table.
File Type Validation: Provides validation both on the frontend and server-side, allowing only CSV file uploads.
Pagination: Implements pagination for the displayed table data, limiting it to a maximum of 100 records per page.

## Running the Project
shell
Copy code
npm install
npm start
Open [http://localhost:8500] in your browser

## Installed Packages
express-ejs-layouts
dotenv
ejs
express
mongoose
nodemon
express-session
multer
papaparse
connect-flash

## Hosted Link
This project is currently hosted at https://csv-upload-file-backend.onrender.com
