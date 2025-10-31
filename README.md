# My Healthcare Buddy

A personal health management application that helps users track their health metrics, daily habits, and visualize their health progress over time.

## Prerequisites

- Java JDK 11 or higher
- Maven
- SQLite (included in dependencies)

## ScreenShot
Login 
<img width="300" height="400" alt="image" src="https://github.com/user-attachments/assets/df77e5ce-6ce0-4b72-9c34-8e94e8eaf7be" />
<img width="300" height="400" alt="image" src="https://github.com/user-attachments/assets/10506fe2-96b3-4748-b528-a9d3efc34872" />
<img width="300" height="400" alt="image" src="https://github.com/user-attachments/assets/97206eb6-d9a7-4506-a1b5-bfe8f9ce2c68" />
<img width="300" height="400" alt="image" src="https://github.com/user-attachments/assets/f2d69785-dde6-46c0-a474-0e31e1217c07" />


## Installation & Setup

1. Clone the repository
```bash
git clone [[repository-url]](https://github.com/cih-lian-liao/my-healthcare-buddy.git)
cd my-healthcare-buddy
```

2. Build the application using Maven
```bash
mvn clean package
```

## Running the Application

There are several ways to run the application:

### Method 1: Direct JAR Execution (Recommended)
After building, run the JAR file:
```bash
java -jar target/my-healthcare-buddy-1.0-SNAPSHOT.jar
```

### Method 2: Using Maven
```bash
mvn exec:java -Dexec.mainClass="com.healthbuddy.Main"
```

## Default Login Credentials
- Username: test
- Password: test123

## Features

- Health metrics tracking (weight, BMI, steps, blood pressure, heart rate)
- Daily habits monitoring
- Data visualization and analysis
- Data export functionality
- Target weight tracking

## Project Structure
```
my-healthcare-buddy/
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── healthbuddy/
│                   ├── Main.java
│                   ├── LoginPage.java
│                   ├── HomePage.java
│                   └── ...
├── data/          # Database storage
├── pom.xml        # Maven configuration
└── README.md
```

## Database

The application uses SQLite for data storage. The database file is automatically created in the `data` directory when you first run the application.

## Development

To set up the development environment:

1. Import the project into your IDE as a Maven project
2. Ensure JDK 11 is configured
3. Run the Main class (com.healthbuddy.Main)

## Troubleshooting

1. Database Connection Issues
   - Check if the data directory exists
   - Ensure write permissions are set correctly

2. Display Issues
   - Verify Java version compatibility
   - Check system look and feel settings

## License

This project is licensed under the MIT License. Feel free to modify and distribute it as needed.

## Contributors

- @alexcclo
- @cih-lian-liao
- @yanqin24
