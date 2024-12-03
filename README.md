TOKEN BOOKING SYSTEM

 Project Overview
The Booking Appointment Web Application is designed to streamline the scheduling process for patients and healthcare providers. It simplifies appointment booking with an intuitive interface that collects patient details and ensures efficient queue management. The system is tailored to provide a user-friendly experience while maintaining accurate appointment tracking.

---

Features
- User-Friendly Form: Collects essential details such as:
  - Mobile number
  - Patient name
  - Age
  - Gender
- Auto-Fill Functionality: Auto-fills fields for returning users based on their mobile number, with an option to update patient information if needed.
- Unique Token Generation: Creates a unique token number for each booking to ensure seamless appointment tracking.
- Efficient Management: Reduces manual effort and enhances the overall booking experience.

---

Technologies Used
- Backend: .NET Framework (C#)
- Database: PostgreSQL
- Database Management: pgAdmin 4
- API Documentation and Testing: Swagger API

---

How to Run the Project
1. Clone the Repository:
   ```bash
   git clone https://github.com/your-username/booking-appointment-app.git
   cd booking-appointment-app
   ```

2. Set Up the Environment:
   - Install PostgreSQL and set up the database using pgAdmin 4.
   - Update the connection string in the project to connect to your database.

3. Run the Application:
   - Open the project in Visual Studio.
   - Build and run the project to start the web application.

4. API Documentation:
   - Navigate to `/swagger` in your browser to view and test the API endpoints.

---


Future Enhancements
- Integration of SMS/Email notifications for token confirmations.
- Development of a mobile app for easier accessibility.
- Analytics to identify booking trends and optimize resource allocation.

---

License
This project is open-source and available under the [MIT License](LICENSE).

