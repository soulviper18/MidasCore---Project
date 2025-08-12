MidasCore Project
This repository contains the MidasCore application, developed as part of the JPMC Software Engineering Virtual Experience on Forage.
It simulates a real-world banking platform workflow, including transaction processing, balance queries, and Kafka-based event streaming.

Features
Spring Boot Backend – RESTful API endpoints for banking operations.

Kafka Integration – Produces and consumes transaction messages.

Mocked REST Services – Used for testing account balance queries.

JUnit & Spring Test – Automated testing with mocked dependencies.

File Loader Utility – Reads transaction data from files and processes them.

Embedded Kafka – Enables integration testing without external dependencies.

Technologies Used
Java 17+

Spring Boot

Spring Kafka

JUnit 5

Maven

Embedded Kafka

MockRestServiceServer

Running the Project
Clone the repository:

bash
Copy
Edit
git clone https://github.com/soulviper18/MidasCore---Project.git
cd MidasCore---Project
Build the project:

bash
Copy
Edit
mvn clean install
Run the application:

bash
Copy
Edit
mvn spring-boot:run
📂 Project Structure
bash
Copy
Edit
forage-midas/
 ├── src/
 │   ├── main/java/com/jpmc/midascore/   # Main application source
 │   ├── test/java/com/jpmc/midascore/   # Unit & integration tests
 │
 ├── pom.xml                             # Maven build file
 └── README.md                           # Project documentation
Testing
Run tests with:

bash
Copy
Edit
mvn test
Includes:

Kafka message publishing & consumption tests

Balance querying mock tests

File reading and transaction processing tests

Certificate
This project was completed as part of the JPMC Software Engineering Virtual Experience on Forage.
Successful completion demonstrates hands-on skills in:

Backend development with Java & Spring Boot

Kafka event-driven systems

REST API testing & mocking

