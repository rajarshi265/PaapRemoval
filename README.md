# PapRemoval App

## Overview
PapRemoval is a web application designed to connect individuals who want to help (Sevaks) with those who need assistance (Sahayaks). The platform allows users to engage in various volunteer opportunities, share their experiences, and earn seva points for their contributions.

## Features
- User registration and authentication
- Volunteer opportunities posting and management
- Seva stories sharing
- Leaderboard to showcase top contributors
- Admin panel for managing seva points

## Project Structure
```
papremoval-app
├── src
│   ├── index.html          # Main HTML file for the application
│   ├── styles
│   │   └── main.css       # CSS styles for the application
│   ├── scripts
│   │   └── main.js        # JavaScript code for user interactions
│   └── admin
│       └── admin-panel.html # Admin panel for managing seva points
├── package.json            # npm configuration file
└── README.md               # Documentation for the project
```

## Setup Instructions
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd papremoval-app
   ```
3. Install the dependencies:
   ```
   npm install
   ```
4. Open `src/index.html` in your web browser to view the application.

## Usage
- Users can register and log in to access various features of the application.
- Admins can access the admin panel to award seva points to registered users.

## Admin Panel
The admin panel allows administrators to:
- Select a user from the registered users list.
- Input the number of seva points to award to the selected user.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License.
