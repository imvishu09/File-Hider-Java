Here is the readme.md file for the FileHiderJava project:

# FileHiderJava

FileHiderJava is a project for hiding and unhiding files securely using a Java application. This project allows users to hide files by moving them to a database and remove the file from the local file system. Users can also unhide the files by retrieving them from the database back to the local file system. This project supports user registration and authentication.

## Features

- Hide files by moving them to a database
- Unhide files by retrieving them from the database 
- User registration and authentication
- Email OTP verification for added security

## Prerequisites

- Java Development Kit (JDK) 
- Maven
- MySQL database

## Getting Started

### Setting up the Database

1. Install MySQL and create a database named `vishuproject`.
2. Create the necessary tables: 

```sql
CREATE TABLE users (...);

CREATE TABLE data (...);
```

### Configuring the Project

1. Clone the repository: 

```bash
git clone https://github.com/your-username/FileHiderJava.git
```

2. Navigate to the project directory:

```bash 
cd FileHiderJava
```

3. Update the database connection settings in `db/MyConnection.java`

4. Update the email settings in `service/SendOTPService.java`

### Building and Running the Project

1. Build the project using Maven:

```bash
mvn clean install
```

2. Run the main class: 

```bash
java -cp target/ytproject-1.0-SNAPSHOT.jar Main
```

### Usage

Register, hide, and unhide files.


## Author

Vishvendra Singh
