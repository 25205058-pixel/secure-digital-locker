# Secure Digital Locker

## Project Overview
This project aims to implement a secure digital locker system that allows users to store their sensitive information safely. The system is designed for ease of use while adhering to stringent security policies to protect user data.

## Features
- User authentication and authorization
- Data encryption and decryption
- User-friendly interface
- Admin access for data management

## File Structure
```
├── src/
│   ├── main/   # Main program files
│   ├── test/   # Testing files
│   └── utils/  # Utility functions
├── data/
│   ├── records.json  # Data records
└── README.md  # Project documentation
```

## Data Files
- **records.json**: Stores user data in a secure format, ensuring data integrity and confidentiality.

## Record Types
- **User Records**: Stores registered user details, including username, encrypted password, and access rights.
- **Admin Records**: Lists admin accounts with elevated privileges for system maintenance.

## Password Policy
- Minimum 12 characters length
- Must include at least one uppercase letter, one lowercase letter, one number, and one special character.

## Admin Access Instructions
1. Navigate to the admin login page.
2. Enter your admin credentials.
3. Access the admin dashboard for data management tasks.

## Compilation Steps
1. Clone the repository.
2. Install the required dependencies using `npm install`.
3. Compile the project using `npm run build`.

## Usage Flow
1. User registration via the application interface.
2. User authentication to access the digital locker.
3. Users can store and retrieve their data securely.

## Security Notes
- All sensitive data is encrypted using AES-256 encryption.
- Regular backups are maintained to prevent data loss.

## Project Metrics
- Number of active users: [TBD]
- Number of records stored: [TBD]

## Educational Value
This project serves as an excellent reference for:
- Understanding secure data storage solutions.
- Learning about encryption techniques and security best practices.
- Developing user authentication and role-based access control in applications.