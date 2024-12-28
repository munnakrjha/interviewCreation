# Interview Creation Portal

An advanced web application designed to manage interview scheduling effectively. The portal allows administrators to create, edit, and manage interviews with ease, ensuring a streamlined process for interview coordination.

## Features
- **Create Interviews**: Admins can create interviews by selecting participants, start and end times.
- **View Upcoming Interviews**: A dedicated page lists all scheduled interviews with details.
- **Edit Interviews**: Admins can edit existing interviews with validations to prevent scheduling conflicts.
- **Validations**: Ensure that interview times and participant availability are consistent.

## Technologies Used

### Front-End
- **React**: For building the user interface and handling dynamic user interactions.
- **JavaScript**: Core language for client-side functionality.
- **CSS**: For styling and responsive design.

### Back-End
- **Django**: Framework used to handle server-side operations and REST API creation.

### Database
- **SQLite3**: Lightweight database for managing interview data.

## Installation and Setup

### Prerequisites
- Python and pip installed.
- SQLite3 installed.

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/interview-creation-portal.git
   cd interview-creation-portal
   ```

2. **Set Up Front-End**
   ```bash
   cd frontend
   npm install
   npm start
   ```

3. **Set Up Back-End**
   ```bash
   cd backend
   python -m venv env
   source env/bin/activate # On Windows: env\Scripts\activate
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   ```

4. **Access the Application**
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:8000`

## Project Structure
```
interview-creation-portal/
├── frontend/        # React application
├── backend/         # Django server
├── db.sqlite3       # SQLite database
├── README.md        # Project documentation
```

## Future Enhancements
- Integrate notification systems (email/SMS) for participants.
- Add authentication for user roles (admin and participants).
- Enhance the UI with additional filters and sorting options.

## Contributors
- **Your Name**: Full-Stack Developer

## License
This project is licensed under the MIT License - see the LICENSE file for details.
