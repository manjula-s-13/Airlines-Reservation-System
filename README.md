# Airlines Reservation System using Spring Boot and ReactJs
The Airlines Reservation System is a web application that enables users to create accounts, access detailed flight and seat information, and allows for convenient flight ticket bookings based on user preferences.
# Working
The Administrative role initiates the creation of flight and seat category information, which is subsequently subject to approval by the Manager.Once approved, these flight details become accessible to Users, enabling them to proceed with ticket bookings.

**Role-Specific Permissions:**

- **Admin**:
  - Exercise full control over flight and seat details, including creation, retrieval, updates, and deletions.

- **Manager**:
  - Possess the authority to review flight details.
  - Make decisions regarding approval or disapproval of flight and seat details.

- **User**:
  - Manage their personal accounts, with privileges for creation, retrieval, updates, and deletions.
  - Access and view flight details.
  - Manage reservation details, including creation, retrieval, updates, and deletions.
  - Users will receive email notifications for booking reservations, updates, or deletions.

# Technologies and Frameworks Utilized in this Project:
* Back-End Technology = Java
* Front-End Technologies = HTML, CSS, Bootstrap and Javascript
* Back-End Framework = Spring Boot
* Front-End Framework = ReactJs
* Database = MySQL Workbench
* Spring Security = JWT Role based authentication and Authorization
* API Code documentation = Swagger-UI
* REST API testing = Postman Client
* Application Health Checks = Actuator
* Utilized the SMTP protocol in Java for sending emails.
* IDE'S = Spring Tool Suite, Visual Studio Code, MySql Workbench.
# Web Page Screenshots:
# Login
  ![LOGIN](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/8f137d71-451e-48a8-afac-bf7b7bb8a52d)

# Profile Details
![Screenshot (99)-imageonline co-merged (1)](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/c5b6ddb0-7913-4562-924b-7a4ec14c4b32)

# Role : User

* User Dashboard
  
  ![UserDashboard](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/6eb1c96e-c9e0-4989-bbfc-8f1646cea8b9)
  
* Flight Details
  
 ![User_Flights](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/9c679aa9-d01f-4c12-b648-882aa5ec60cb)

* Seat Types
  
 ![User_SeatTypes](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/c27dffdd-ee5e-43f6-9f14-d478fffe6fa1)

* Reserving Seat
  
  ![User_Booking](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/54ac77e4-4752-44ab-81a8-1ab302975250)

* On Successful reservation
  
  ![Success page](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/3a360b9e-ff14-4725-8857-524feb3bf861)

* Reservation Details
  
![User_reservation](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/196b088c-1e70-443e-8316-98cb9ef7c5e5)

# Role : Admin
* Admin Dashboard
  
  ![Admin_dashboard](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/e5e9a7e4-53b3-4b17-b0e5-df26fa95249a)

* Setting Flight Details
  
  ![Admin_flights](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/5d65747f-df27-4e20-a625-7dd1153e9e5f)
  
* Setting Seat Types Details
  
  ![Admin_seats](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/d7a4756e-d1e4-4d41-b098-c185502e347c)

* All  Reservation Details
  
  ![Admin_viewallreservd](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/efca22e9-c509-41fb-9b7b-bd99e2b153c5)

* All User Details
  
  ![AdminAll users](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/32a7344d-5e09-40a4-8395-320ede845a53)
  
# Role : Manager
  
* Approving/Disapproving Flight Details
  
  ![MAnager_flights](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/ee523ebb-c56e-438b-a114-b5d1e914fa96)

* Approving/Disapproving Seat Types Details
  
  ![Manager_seats](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/b11fa6dc-7c46-4595-b3a2-e174d2d62233)

# Emails received by the users on Reservation Confirmation,Updation and Cancellation

**Reservation Confirmation**

![Screenshot (106)-imageonline co-merged (1)](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/c5b36985-65bf-4eb8-866e-0255b0c03647)

**Reservation Updation**

![Screenshot (108)](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/6208835c-0708-43de-be54-a72f90188d20)

**Reservation Cancellation**
 
![Screenshot (109)-imageonline co-merged](https://github.com/manjula-s-13/Airlines-Reservation-System/assets/86179660/303df5b4-eed3-4b89-a108-7034a95cb4fb)
