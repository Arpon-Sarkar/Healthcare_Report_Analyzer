# Healthcare Management System

A web-based healthcare management application designed to simplify hospital-related activities through role-based dashboards and interactive healthcare management features.

## Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6)
- **Data Visualization:** Chart.js
- **Browser Storage:** LocalStorage API
- **Web APIs:** DOM API, IntersectionObserver API
- **External Library:** Chart.js via jsDelivr CDN

## Key Features

### User Authentication Interface
- Login interface with three user roles:
  - Doctor
  - Patient
  - Receptionist
- Role-based dashboard navigation.
- Password length validation and show/hide password functionality.

### Doctor Dashboard
- Dashboard statistics and patient overview.
- Patient trend visualization using Chart.js.
- Appointment management interface.
- Medical report review interface.

### Patient Portal
- Patient registration interface.
- Appointment booking and cancellation.
- Medical report submission.
- Medicine information management.

### Receptionist Dashboard
- Receptionist-oriented dashboard interface.
- Patient and appointment management features.

### Medical Report Analysis
- Medical report submission interface.
- Supports up to five reports.
- Displays key medical concepts.
- Includes report comparison and summary demonstration features.

### Medicine Management
- Add medicine information dynamically.
- Remove medicine entries.
- Interactive medicine management interface.

### Blood Donor Directory
- Blood donor listing.
- Filter donors by blood group and location.
- Distance-based filtering.
- Donor contact request interaction.

### Ambulance Management
- Ambulance directory with vehicle and driver information.
- Add ambulance through a modal interface.
- Search and filter ambulance availability.
- Display contact information, location, distance, estimated charges, and status.
- Call and ambulance request interactions.
- Google Maps search links for location navigation.

### UI/UX Features
- Responsive layout for different screen sizes.
- Light and dark theme support.
- Theme preference saved using LocalStorage.
- Interactive modal windows.
- Smooth animations and scroll-reveal effects.
- Mobile-friendly navigation sidebar.

## Project Structure

```text
Healthcare-Management/
│
├── index.html
└── README.md
```

The application is currently implemented as a single HTML file containing the HTML structure, CSS styling, and JavaScript functionality.

## Current Implementation Status

### Implemented
- Multi-role login interface.
- Doctor, patient, and receptionist dashboard interfaces.
- Dashboard statistics and Chart.js visualization.
- Appointment booking and cancellation interactions.
- Patient registration interface.
- Medical report submission and demonstration analysis.
- Medicine management interface.
- Blood donor directory with filtering.
- Ambulance directory and management interface.
- Light/dark theme switching.
- Responsive navigation and modal interactions.

### Current Limitations
- The project currently uses frontend-based demonstration functionality.
- No backend server or database is connected.
- Authentication is not connected to a real user-management system.
- Medical report analysis uses predefined demonstration behavior rather than a trained AI/ML model.
- Donor and ambulance information is based on predefined JavaScript data.
- Ambulance distance, charges, and related statistics are demonstration values.
- Google Maps links open location searches; live GPS tracking is not implemented.

## Future Improvements

- Develop a backend using Node.js and Express.js.
- Integrate a database such as MySQL.
- Implement secure authentication and role-based authorization.
- Integrate AI/ML-based medical report analysis.
- Add real-time appointment management.
- Implement live ambulance tracking and location services.
- Develop notification and emergency alert systems.
- Add secure patient medical record management.

## About

**Project Name:** Healthcare Management System

**Developer:** Arpon Sarkar Choity

**GitHub:** https://arpon-sarkar.github.io/Healthcare_Report_Analyzer/



This project is developed for educational and academic purposes.
