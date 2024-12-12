# Social Media Profiles Management

## Project Overview
The Social Media Profiles Management project is a web-based application that allows users to manage profiles by adding, editing, and deleting user information. It also provides functionality to filter profiles based on Date of Birth (DOB), language, and hobbies.

## Features

### 1. Add User Functionality
- Users can create new profiles by filling in details such as name, DOB, language, and hobbies.
- AJAX is used for seamless form submission without reloading the page.

### 2. Edit User Functionality
- Existing profiles can be updated to modify user information.
- AJAX is utilized to dynamically update the profile information in the database.

### 3. Delete User Functionality
- Users can delete profiles from the application.
- A confirmation prompt ensures accidental deletions are avoided.
- AJAX is used to remove profiles dynamically from the interface.

### 4. Filter Options
- Profiles can be filtered based on:
  - **Date of Birth (DOB):** Specify a date range to view profiles within a certain age group.
  - **Language:** Filter profiles based on the user's preferred language.
  - **Hobbies:** Search profiles by specific hobbies.
- Real-time filtering is implemented with AJAX for a smooth user experience.

### 5. Responsive Design
- The application is designed to work seamlessly on desktop and mobile devices.

## Technologies Used

### Frontend
- **HTML5:** For the structure of the web pages.
- **CSS3:** For styling the application.
- **JavaScript (ES6):** For adding dynamic behavior.
- **AJAX:** For asynchronous server requests to enhance user experience.


### Additional Libraries
- **jQuery:** Simplifies DOM manipulation and AJAX calls (if applicable).
- **Bootstrap / Tailwind CSS:** For responsive design and UI components.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/social-media-profiles.git
   cd social-media-profiles
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure the database:
   - Create a new database in your preferred DBMS.
   - Update the database configuration in the `.env` or config file.

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## Usage
- Navigate to the **Add User** section to create new profiles.
- Use the **Edit** and **Delete** buttons on each profile to manage user data.
- Apply filters using the **Filter Options** section to narrow down profiles based on specific criteria.



## Contributing
1. Fork the repository.
2. Create a new feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add feature-name'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.




