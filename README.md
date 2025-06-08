# Flight Management System

## Overview

The Flight Management System is a comprehensive C++ application designed to streamline airline operations by managing flight schedules, passenger reservations, and ticket bookings. This system provides an efficient and user-friendly interface for both administrators and passengers to handle various aspects of flight management.

## Features

### For Administrators
- **Flight Management**
  - Add new flights with detailed information
  - Remove existing flights
  - Update flight schedules and details
  - View all flight information

### For Passengers
- **Reservation System**
  - Book flight tickets
  - Cancel existing reservations
  - View booking history
  - Check flight availability
  - View ticket details

## Project Structure

```
Flight_Management_System/
├── Classes/
│   ├── Management.h
│   ├── Details.h
│   ├── Registration.h
│   └── Ticket.h
├── Source_File/
│   ├── Management.cpp
│   ├── Details.cpp
│   ├── Registration.cpp
│   └── Ticket.cpp
├── main.cpp
└── README.md
```

## Technologies Used

- **Programming Language**: C++
- **Development Environment**: Any C++ compiler (GCC, MSVC, etc.)
- **Data Storage**: File-based storage system
- **Version Control**: Git

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/anand2026/Flight-magement-system.git
   ```

2. **Navigate to the project directory**:
   ```sh
   cd Flight-magement-system
   ```

3. **Compile the project**:
   ```sh
   g++ -o flight_system main.cpp Source_File/*.cpp
   ```

## Usage

1. **Run the executable**:
   ```sh
   ./flight_system
   ```

2. **System Navigation**:
   - Choose between Admin and Passenger modes
   - Follow the on-screen prompts for various operations
   - Use the menu system to navigate through different features

## Core Components

### Management Class
- Handles flight operations
- Manages flight schedules
- Controls flight availability

### Details Class
- Stores passenger information
- Maintains flight details
- Manages booking records

### Registration Class
- Handles user authentication
- Manages user profiles
- Controls access levels

### Ticket Class
- Processes ticket bookings
- Manages reservation status
- Handles ticket modifications

## Contributing

We welcome contributions to improve the Flight Management System. To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For support or queries, please contact:
- GitHub: [@anand2026](https://github.com/anand2026)
- Project Link: [https://github.com/anand2026/Flight-magement-system](https://github.com/anand2026/Flight-magement-system)



