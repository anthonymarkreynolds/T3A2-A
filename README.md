# Muscle Therapy Massage

## Purpose
- SME informational website
- System booking for multiple locations

## Functionality / features
Responsive Mobile First Design
Typical SME informational website
Booking system integration via Square API
Consent form 
Content management system


## Target audience
Massage/ Remedial massage target market in Port Macquarie, Focus on seniors

## Tech stack 
### Front-End
- UI Library: React 
- Component Library: ChakraUI
- HTTP Client: Axios
- Fonts: Google Fonts

### Backend
- Runtime: Nodejs
- DataBase: MongoDB
- Server Framework: ExpressJS
- User Authentication: Firebase
- Booking System: Square

### Hosting
- Database: Mongodb Atlas
- Backend: Heroku 
- Content Storage: AWS Simple Storage Service

### Devops
- Code Testing: Jest
- API / HTTP Testing, postman
- User & Browser Testing: Seleniun
- Documentation: JSDoc
- CICD system: Github Actions

### Dev Tools
- Formatting: ESLint
- Linting: ESLint

### Version Control
- Software: Git
- Remote repo provider: Github

## Dataflow Diagram
### Level 0
![Data flow diagram Level 0](./Data%20flow%20diagram%20Level%200.png)
### Level 1
![Data flow diagram Level 1](./Data%20flow%20diagram%20Level%201.png)

## Application Architecture Diagram     
![Application Architecture Diagram](./Application%20Architecture%20Diagram.png)

## User Stories     

| Stage | As A [Type of User] | I need/want [to perform an action] so that [the intended result] | [Draft] Acceptance criteria |
| ----- | ------------------- | ---------------------------------------------------------------- | --------------------------- |
| Discovery | Customer | <ul><li>I need to quickly understand the service and verify its trustworthiness so that I can know it’s the right service for me</li></ul> | <ul><li>Testimonies</li><li>Key info (location, business) immediately visible</li><li>Know my information is secure</li></ul> |
| | Business Owner | <ul><li>I need to create an accessible website that is accessible for my target audience so they can user my service</li><li>I need an efficient appointment solution so that I can have time to…</li><li>With multiple locations, I need to quickly manage my calender and appointment scheduling so I can adjust to changing schedules</li></ul> | <ul><li>Reliable syncing between personal and booking system calenders</li></ul> |
| Creating appointment | Customer | <ul><li>I need to see and access the appointment system so I can navigate to complete the appointment process successfully</li></ul> | <ul><li>See booking button</li><li>Simple booking system</li></ul> |
| | Business Owner | <ul><li>I need to provide confirmation for all appointments and changes so that I can refuse and accept depending on changing time availability</li><li>I need to manage (cancel, edit) the appointment system so that I can have control over my schedule to provide the best service</li></ul> | <ul><li>All bookings and changes confirmed by admin</li><li>Easy to edit bookings, see relevant customer details</li></ul> |
| Onboarding | Customer | <ul><li>I want to use single tap navigation so I can easily navigate the website/app</li><li>I need a clear visual focus so I can quickly see key information about the service</li></ul> | <ul><li>Have record of my booking</li><li>Visual cues</li><li>Action feedback</li><li>One click to information</li></ul> |
| | Business Owner | <ul><li>I want to provide customers with sign options for the consent form so that they can save time / use what they prefer</li></ul> | <ul><li>Consent form is sent first time a user books an appointment</li></ul> |
| Retention | Customer | <ul><li>I want to rebook past appointments and change future bookings so I can save time reusing the service</li></ul> | |
| | Business Owner | <ul><li>I need to see key metrics for my business so I can easily track business progress</li><li>I need to manage my website content so I can update it myself as the business changes.</li></ul> | <ul><li>Content editing</li><li>Layout of content editing</li><li>Control over simple elements including website colours</li><li>Displays key payment information in admin panel / dashboard / landing page</li></ul> |

## Wireframes
### Landing Page
![Landing Page Wireframe](./WIreframe_clean%20-%20Landing.png)
### About
![About Page Wireframe](./WIreframe_clean%20-%20SP_about.png)
### Contact 
![Contact Page Wireframe](./WIreframe_clean%20-%20SP_contact.png)
### Services
![Services Page Wireframe](./WIreframe_clean%20-%20SP_Services.png)
### Guest Booking
![Guest Booking Page](./WIreframe_clean%20-%20guest_booking.png)
### Admin Panel
![Admin Panel](./WIreframe_clean%20-%20admin.png)

## Trello Board
[Link to Trello Board](https://trello.com/b/LzbSo3i9/mern-app)

## Trello ScreenShots
### 27-10-2022
![Trello ScreenShot 27-10-2022](./Trello%2027-10-2022.png)
### 30-10-2022
![Trello ScreenShot 30-10-2022](./Trello%2030-10-2022.png)
### 30-10-2022
![Trello ScreenShot 31-10-2022](./Trello%2031-10-2022.png)
### 03-11-2022
![Trello ScreenShot 03-11-2022](./Trello%2003-11-2022.png)
### 05-11-2022
![Trello ScreenShot 04-11-2022](./Trello%2003-11-2022.png)
### 04-11-2022
![Trello ScreenShot 05-11-2022](./Trello%2003-11-2022.png)