# Local Gaming Meetups

## Application Overview
Local Gaming Meetups is a web application designed to connect gaming enthusiasts by allowing them to find and create local gaming events. Users can view ongoing and upcoming events, post their own events, and interact with other users. This app aims to foster a sense of community among gamers and make it easier for individuals to discover and participate in nearby gaming meetups.

## Technologies Used

### Front End
- **JavaScript Framework:** React (required)
- **SPA Navigation:** React Router (required)
- **CSS Framework for Responsive Design:** React-Bootstrap

### Back End/Database
- **Server Framework:** Node.js with Express (required)
- **Database Management:** (TO DO: Specify MongoDB or PostgreSQL)

## Expected Features

### Minimum Viable Product (MVP)
The following features are essential to deliver a working prototype of the application:

#### CRUD Operations
- **CREATE:**
  - Add events to a list with special permissions.
- **READ:**
  - Retrieve and read event details.
  - Search functionality with special permissions.
- **UPDATE:**
  - Edit information for existing events and profiles with special permissions.
  - Profile pages with capabilities such as changing passwords.
  - Update event information with special permissions.
- **DELETE:**
  - Remove data (e.g., events, users, or posts) from the database with special permissions.
  - Delete specific pages, users, or posts.

#### Entity-Specific Functionalities
- **Users:**
  - CRUD functionality for user management.
  - Access control based on roles (e.g., Admin, Regular User).
  - Admins can delete all posts or any user’s posts.
  - Regular users can add, edit, or delete their own posts.

- **Events:**
  - CRUD functionality for event management.
  - Admins can edit or delete any event, regardless of the user.
  - Regular users can add and edit only their own events.

- **Posts:**
  - CRUD functionality to create, read, update, and delete posts.

### Special Permissions
- Admins have higher-level access to manage all data within the application.
- Regular users have permissions limited to their own content (e.g., posts, events).

## Stretch Goals
If time permits and the MVP is met, additional features may include:
- Integration of user notifications for upcoming events.
- Real-time chat or messaging functionality for event discussions.
- Advanced filtering and sorting options for event searches.
- Social media integration to share events.
- Gamification elements such as badges for frequent event participants.
- Calendar integration for better event scheduling.

---

This README serves as a foundation for understanding the project scope and objectives. Further updates and details will be added as the project progresses.
