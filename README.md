React Event Management Application

This is a React-based event management application. It allows users to view, create, edit, and delete events. The application features components for managing events, a navigation bar, and pages to display individual event details.

Project used as data events.json file , which should be running by json-server:

json-server events.json

Table of Contents

	•	Prerequisites
	•	Installation
	•	Project Structure
	•	Features
	•	Usage
	•	Running the Application
	•	API Integration
	•	Available Scripts
	•	Contributing
	•	License

Prerequisites

Before you begin, ensure you have the following installed on your system:

	•	Node.js (version 14.x or above)
	•	npm or yarn package manager

Installation

To get started with this project:

	1.	Clone the repository to your local machine:
 git clone https://github.com/artem1984A/React_Final_Project
 
2.	Navigate to the project directory:
   cd React_Final_Project
  	
4.	Install the required dependencies:
npm install
or	  	
yarn install

 Features

	•	Add Event: Users can create new events with details like title, description, and time.
	•	Edit Event: Users can update existing events.
	•	Delete Event: Users can remove events.
	•	List Events: Displays all created events.
	•	Navigation: Simple navigation between pages.
	•	State Management: Managed using React Context API for state persistence across components.

Usage

	•	Adding an Event: Navigate to the “Add Event” page and fill in the details to create a new event.
	•	Viewing Events: All events are displayed on the “Events” page, and each event can be clicked to view its details.
	•	Editing an Event: After selecting an event, you can navigate to the “Edit Event” page to modify the event’s details.
	•	Deleting an Event: Events can be deleted directly from the event page.

Running the Application

To start the React application, run the following command:
npm start
  or
yarn start
This will run the app in development mode. Open http://localhost:3000 to view it in the browser.

The page will reload if you make edits, and you will also see any lint errors in the console.

API Integration

This application interacts with a backend API to fetch and manipulate events. Ensure that your API server is up and running before using the event management features.

	•	API Endpoints: You can integrate the following endpoints in your backend:
	•	GET /api/events: Fetch all events
	•	POST /api/events: Create a new event
	•	PUT /api/events/:id: Update an event
	•	DELETE /api/events/:id: Delete an event

Modify DataContext.jsx or other components to integrate your API calls.

Available Scripts

In the project directory, you can run the following scripts:

	•	npm start: Runs the app in development mode.
	•	npm test: Launches the test runner.
	•	npm run build: Builds the app for production in the build folder.
	•	npm run eject: Ejects the configuration settings (use with caution).

Contributing

If you want to contribute to this project:

	1.	Fork the repository.
	2.	Create a new branch (git checkout -b feature-branch).
	3.	Commit your changes (git commit -am 'Add new feature').
	4.	Push to the branch (git push origin feature-branch).
	5.	Open a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Feel free to modify the content to suit the exact needs of your project. Let me know if you need any further adjustments!

It was my finil project for certificated Front-End Developer in WincAcademy (https://www.wincacademy.nl).
 
New version of this project can be seen at https://www.ryzhov.website/home/ 
(There are using MongoBD, Redis and added some more functionalites)
