Here's the updated version of the README file with Spring Boot version 3.2.3:

---

# Spring Boot Social Media App

## Overview

This is a sample social media application built using Spring Boot (version 3.2.3). It demonstrates basic functionality such as user authentication, posting updates, following other users, and viewing a feed of posts from followed users.

## Technologies Used

- Java 17
- Spring Boot 3.2.3
- Spring Security
- Spring Data JPA
- MySQL (or any other supported database)

## Features

1. **User Authentication**: Users can sign up, log in, and log out securely.
2. **Create Posts**: Authenticated users can create new posts.
3. **Follow/Unfollow Users**: Users can follow and unfollow other users.
4. **View Feed**: Users can view a feed of posts from users they follow.
5. **Edit Profile**: Users can edit their profile information.

## Setup

1. **Clone the repository**:
   ```
   git clone https://github.com/yourusername/spring-boot-social-media.git
   ```

2. **Database Configuration**:
   - Create a MySQL database with the name `social_media_db`.
   - Update the database configuration in `src/main/resources/application.properties` with your database username and password.

3. **Build and Run**:
   ```
   cd spring-boot-social-media
   ./mvnw spring-boot:run
   ```

4. **Access the Application**:
   Open a web browser and go to `http://localhost:8080`.

## Usage

1. **Sign Up**: Create a new account by clicking on the "Sign Up" link.
2. **Log In**: Log in with your credentials.
3. **Create Post**: Once logged in, you can create a new post from the homepage.
4. **Follow Users**: Visit a user's profile and click on the "Follow" button to start following them.
5. **View Feed**: Navigate to the "Feed" page to see posts from users you follow.
6. **Edit Profile**: Update your profile information by clicking on the "Edit Profile" link.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Create a new Pull Request.

## License

Not for commercial use, free to use for education and updatation purpose.

---

Please adjust the details in the README file as needed for your specific Spring Boot 3.2.3 application.
