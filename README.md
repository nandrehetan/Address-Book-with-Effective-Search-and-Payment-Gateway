# Effective Search in Address Book

This is a Spring Boot project with a Thymeleaf frontend, designed as a Contact Management Application. Users can manage their contacts, including adding, deleting, and updating them. The application also features a password reset option using an integrated mail API that sends an OTP to users' email addresses for password resetting. Additionally, Razorpay payment integration has been added for handling payments.

## Features

- Manage contacts: Add, delete, and update contacts.
- Forgot password option: Integrated mail API sends OTP to users' email addresses for password resetting.
- Razorpay Payment Integration.
  
## Technology Stack

- **Thymeleaf and CSS**: Designing page layout.
- **Java**: Application logic.
- **MySQL**: Database.
- **Spring Security**: Authentication.
- **Hibernate**: ORM (Object-Relational Mapping).
- **Email API**: For sending OTP to users' email addresses.

## Software and Tools Required

- Java JDK 8+
- Eclipse EE or Spring Tool Suite
- MySQL
![Database Architecture](https://github.com/nandrehetan/Address-Book-with-Effective-Search-and-Payment-Gateway/assets/97376783/a19a7b3c-f5fa-4d59-adc3-3cd1159b0a0b)
![User Flow](https://github.com/nandrehetan/Address-Book-with-Effective-Search-and-Payment-Gateway/assets/97376783/3abb9c41-ae26-4aba-9f6c-2bbf6cd9355c)

## Getting Started

### Prerequisites

- Java JDK 8 or higher
- MySQL
- IDE such as Eclipse EE or Spring Tool Suite

### Installation

1. **Clone the repository**:

    ```shell
    git clone https://github.com/nandrehetan/Effective-Search-in-Address-Book.git
    ```

2. **Navigate to the project directory**:

    ```shell
    cd Effective-Search-in-Address-Book
    ```

3. **Configure your MySQL database**:

    Update the database connection settings in the application properties file located at `src/main/resources/application.properties`:

    ```plaintext
    spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
    spring.datasource.username=your_username
    spring.datasource.password=your_password
    ```

4. **Configure Email API settings**:

    Configure the email API settings in the application properties file located at `src/main/resources/application.properties`:

    ```plaintext
    spring.mail.host=your_smtp_host
    spring.mail.port=your_smtp_port
    spring.mail.username=your_email
    spring.mail.password=your_email_password
    ```

5. **Run the application**:

    You can run the application using your IDE or by using the following command:

    ```shell
    ./mvnw spring-boot:run
    ```

## Usage

Once the application is running, you can interact with the application through the web interface.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check out the [issues page](https://github.com/yourusername/Effective-Search-in-Address-Book/issues).

## License

This project is licensed under the [MIT License](LICENSE).
