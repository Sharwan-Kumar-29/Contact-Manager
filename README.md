# Contact Manager App
deploy link: https://stupendous-souffle-014b82.netlify.app/
## Overview
The **Contact Manager App** is a web application that enables users to manage their contacts efficiently. Built using React and Firebase, this app provides all the essential features such as adding, editing, deleting, and viewing contacts. It ensures real-time updates and seamless user experience with Firebase as the backend database.

## Features
- **Add Contacts**: Easily add new contacts with details such as name, phone number, email, and tags.
- **Edit Contacts**: Modify existing contact information.
- **Delete Contacts**: Remove contacts permanently from the database.
- **Filter and Sort Contacts**: Sort contacts by name in ascending or descending order, and filter contacts by tags for better organization.
- **Real-time Updates**: Changes are instantly reflected, thanks to Firebase's real-time database.
- **Responsive Design**: Fully responsive layout for seamless use on both desktop and mobile devices.

## Technologies Used
- **Frontend**: React (with hooks and context API)
- **Backend**: Firebase Realtime Database
- **Styling**: CSS
- **Hosting**: Firebase Hosting

## Getting Started

### Prerequisites
To run this application locally, you need to have the following installed:
- Node.js
- npm or yarn
- Firebase account

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/contact-manager.git
   ```
2. Navigate to the project directory:
   ```bash
   cd contact-manager
   ```
3. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```
4. Set up Firebase:
   - Create a project in Firebase.
   - Enable the Realtime Database.
   - Obtain your Firebase configuration details and replace them in the `firebase-config.js` file.

### Running the App
1. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```
2. Open your browser and navigate to `http://localhost:3000`.

## Usage
1. **Add a Contact**:
   - Fill in the form fields for name, phone number, email, and tags.
   - Click the "Add" button to save the contact.

2. **Edit a Contact**:
   - Click the "Edit" button next to the contact.
   - Modify the details in the form and save the changes.

3. **Delete a Contact**:
   - Click the "Delete" button next to the contact.
   - Confirm the deletion to remove the contact permanently.

4. **Filter and Sort**:
   - Use the dropdown menus in the header to filter contacts by tags or sort them by name.

## Project Structure
```
contact-manager/
├── public/
├── src/
│   ├── components/    # React components
│   ├── context/       # Context API for state management
│   ├── firebase/      # Firebase configuration
│   ├── styles/        # CSS styles
│   ├── App.js         # Main app component
│   └── index.js       # Entry point
├── .gitignore
├── firebase.json      # Firebase hosting configuration
├── package.json
└── README.md
```

## Future Enhancements
- Add user authentication for secure access.
- Implement pagination for better data handling.
- Include a search bar for quick contact lookup.
- Add support for exporting contacts as CSV.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to your forked repository:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgements
- [React Documentation](https://reactjs.org/docs/)
- [Firebase Documentation](https://firebase.google.com/docs/)

---

Feel free to reach out with any feedback or suggestions!


