# Appointment Scheduler Application

## Purpose
This application is designed to help users manage appointments and customer information efficiently. It allows for the creation, updating, and deletion of appointments and customer records, with all data seamlessly integrated into a MySQL database.

## Author
**Name:** Jonathan Mecham  
**Version:** 1.0  

## Development Environment
- **IDE:** IntelliJ IDEA Community 2020.01
- **JDK Version:** Java SE 11.0.4
- **JavaFX Version:** JavaFX-SDK-11.0.2
- **MySQL Connector Version:** mysql-connector-java-8.1.23

## Features
- **Multi-Language Support:** Displays in English or French based on system settings.
- **User Authentication:** Secure login with error handling and location display.
- **Customer Management:** Add, update, and delete customer records with validation.
- **Appointment Scheduling:** Manage appointments with conflict detection and business hour enforcement.
- **Time Zone Handling:** Stores times in UTC; displays in local time.
- **Reports:** Generate various reports, including:
  - Total number of appointments by type and month.
  - Schedules for each contact.
  - [Description of your custom report].
- **Logging:** Records all login attempts with timestamps and outcomes in `login_activity.txt`.
- **Lambda Expressions:** Utilized for efficient data processing.

## How to Run the Application
1. **Install Dependencies:**
   - Ensure Java SE 11 and JavaFX SDK 11 are installed.
   - Set up a MySQL database with the required schema.
2. **Clone the Repository:**
   - `git clone https://github.com/MechamJonathan/MechamJonathan-SchedulerApp.git`
3. **Import Project:**
   - Open IntelliJ IDEA and select "Import Project," navigating to the cloned repository.
4. **Configure Libraries:**
   - Add JavaFX SDK and MySQL Connector/J to the project's libraries.
5. **Database Configuration:**
   - Update database connection settings in the application to match your MySQL setup.
6. **Run the Application:**
   - Execute the `Main` class to start the application.

## Notes
- **Database Integrity:** The existing database schema is preserved to maintain compatibility with other systems.
- **Business Hours:** Appointments are restricted to 8:00 AM - 10:00 PM EST.
- **Upcoming Appointments Alert:** Users receive notifications for appointments within 15 minutes upon login.
- **Dynamic Filtering:** First-level divisions are filtered based on the selected country for accurate data entry.

## Acknowledgments
This project was developed as part of a school assignment to demonstrate proficiency in JavaFX, MySQL integration, and software design principles.
