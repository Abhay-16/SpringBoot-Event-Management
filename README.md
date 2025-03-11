# Event Management Spring Project

## Overview
This **Event Management System** is a Spring Boot-based web application that allows users to manage events, register attendees, assign tasks, and handle bookings. The project follows a layered architecture with controllers, services, repositories, and entity classes.

## Folder Structure
```
.mvn
│── mvnw
│── mvnw.cmd
│── pom.xml
│── .gitignore
│── README.md
│
src
│── main/java/com/Shakthi
│   ├── controller
│   │   ├── AttendiesController.java
│   │   ├── EventsController.java
│   │   ├── FormController.java
│   │   ├── RegisterController.java
│   ├── entity
│   │   ├── AttendiesEntity.java
│   │   ├── EventsEntity.java
│   │   ├── Form.java
│   │   ├── RegisterEntity.java
│   │   ├── TaskEntity.java
│   ├── repository
│   │   ├── AttendiesRepo.java
│   │   ├── EventsRepo.java
│   │   ├── FormRepo.java
│   │   ├── RegisterRepo.java
│   │   ├── TaskRepo.java
│   ├── serviceImplementation
│   │   ├── AttendiesServiceImpl.java
│   │   ├── EventServiceImplementation.java
│   │   ├── FormImplementation.java
│   │   ├── RegisterServiceImple.java
│   ├── serviceInterface
│   │   ├── AttendiesService.java
│   │   ├── EventServiceInterface.java
│   │   ├── FormService.java
│   │   ├── RegisterService.java
│   ├── EventManagementSpringProjectApplication.java
│
src/main/resources
│── application.properties
│
│── static/assets
│   ├── css
│   ├── js
│   ├── images
│   ├── plugins
│── static/gallery
│   ├── Birthday.jpg
│   ├── Birthday2.jpg
│   ├── Birthday3.jpeg
│   ├── Birthday8.jpg
│   ├── Dinner.jpg
│   ├── Dinner2.jpg
│   ├── Dinner3.jpg
│   ├── Dinner4.jpg
│   ├── Funeral.jpeg
│   ├── Garba.jpeg
│   ├── concert.jpg
│   ├── concert2.jpg
│   ├── concert3.jpg
│   ├── corporate.jpg
│   ├── corporate2.jpg
│   ├── corporate3.jpg
│   ├── holi.jpg
│   ├── holim.jpg
│   ├── naming.jpeg
│   ├── wedding.jpeg
│   ├── wedding2.jpg
│   ├── wedding3.jpeg
│── static/sms
│   ├── admin.jpg
│   ├── admin1.jpg
│   ├── admin2.jpg
│   ├── background.jpeg
│   ├── bgbg.jpg
│   ├── login.jpeg
│   ├── login.png
│   ├── signup.jpeg
│
src/main/resources/templates
│── AddAttendies.html
│── Admin.html
│── AdminSecondaryNavbar.jsp
│── AdminTasks.html
│── AssignTask.html
│── AttendieEdit.html
│── AttendieHome.html
│── AttendieLogin.html
│── Booking.html
│── EventData.html
│── FinalForm.html
│── Home.html
│── ShowAttendie.html
│── Signup.html
│── User.html
│── UserBookings.html
│── VeiwAttender.html
│── addEvents.html
│── deleteEvents.html
│── forgot.html
│── index.html
│── login.html
│── practical.html
│── x.html
│
src/test/java/com/shakthi
│── EventManagementSpringProjectApplicationTests.java
```

## Features
- **User Management**: Users can register, log in, and access event management features.
- **Event Management**: Create, update, and delete events.
- **Attendee Registration**: Attendees can register for events.
- **Task Management**: Assign and track event-related tasks.
- **File & Image Management**: Manage images and resources for event categories.

## Setup & Installation
### Prerequisites:
- Java 17+
- Maven
- MySQL Database

### Steps:
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/event-management.git
   ```
2. Navigate to the project directory:
   ```sh
   cd event-management
   ```
3. Configure `application.properties` with your database credentials.
4. Build and run the application:
   ```sh
   mvn spring-boot:run
   ```
5. The API will be available at `http://localhost:8080`

## Technologies Used
- **Backend:** Spring Boot, Spring Data JPA, Spring Security
- **Database:** MySQL
- **Frontend:** HTML, CSS, JavaScript (JSP & Static Pages)
- **Build Tool:** Maven



