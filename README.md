
# Sakancom

**Sakancom** is an innovative Java-based backend platform designed to streamline apartment bookings for students. It enables seamless communication between students and property owners and includes a furniture exchange feature to foster community engagement and promote sustainable living.

---

## Key Features

- **Apartment Booking**:
  - Students can browse and book apartments based on location and preferences.
  - Property owners can list their apartments and manage bookings.

- **Direct Communication**:
  - Enables secure and direct communication between students and property owners.

- **Furniture Exchange**:
  - A unique feature allowing students to exchange furniture, promoting sustainability and reducing waste.

- **Testing**:
  - Comprehensive unit and integration testing to ensure application reliability.

- **Continuous Integration**:
  - Jenkins is used for automated builds and testing to maintain code quality.

---

## Getting Started

### Prerequisites

- **Java** (JDK 8 or higher)
- **Maven** (Build tool)
- **MySQL** or any preferred database
- **Jenkins** (for CI/CD)

---

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Yazan-Kariem/Sakancom-Software-
   cd Sakancom-Software-
   ```

2. **Build the project using Maven**:
   ```bash
   mvn clean install
   ```

3. **Set up the database**:
   - Create a database named `sakancom`.
   - Import the `sakancom.sql` file into your database.

4. **Configure application properties**:
   Update the `application.properties` file in the `src/main/resources` directory with your database credentials:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/sakancom
   spring.datasource.username=your-username
   spring.datasource.password=your-password
   ```

5. **Run the application**:
   ```bash
   mvn spring-boot:run
   ```

---

## Testing

- Run unit and integration tests using Maven:
  ```bash
  mvn test
  ```

- Testing features are included in the `src/test` directory.

---

## Jenkins Integration

1. **Set up Jenkins**:
   - Install Jenkins on your server or use a cloud-based Jenkins instance.

2. **Configure Jenkins for the project**:
   - Add the project repository to a Jenkins job.
   - Configure the build triggers and pipeline to run on every commit.

3. **Automated Testing**:
   - Jenkins will execute automated tests after each build to ensure code quality.

---

## File Structure

- **`src/main`**: Contains the main application source code.
- **`src/test`**: Includes unit and integration tests.
- **`application.properties`**: Configuration file for database and application settings.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Contact

For queries or feedback, reach out:

- **Name**: Kariem AbuAisheh 
- **Email**: kariemalwazany@gmail.com
