# System Architecture


## Application Flow


User

↓

React Frontend

↓

FastAPI Backend

↓

PostgreSQL Database

↓

Gmail API

↓

OTP Detection Engine

↓

OTP Dashboard



## Frontend

Technology:

- React.js
- React Router
- Axios


Responsibilities:

- User interface
- Dashboard
- OTP display
- Search and filtering


## Backend

Technology:

- Python FastAPI


Responsibilities:

- Authentication
- Gmail API communication
- OTP processing
- Database operations


## Database

Technology:

- PostgreSQL


Stores:

- User information
- Gmail connection details
- OTP records
- Storage information