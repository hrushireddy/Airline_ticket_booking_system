
# Airline Ticket Booking System

This project is a Java-based desktop application developed using **NetBeans IDE** for booking airline tickets. It features a GUI-based system that allows users to manage flight bookings, cancellations, payments, and more. The system connects to a **MySQL** database and uses additional external libraries for enhanced functionality.

---

## 🗂 Project Structure

```
Airline Ticket Booking System/
├── Steps.txt                        # Instructions on how to run the project
├── add jar folder/                 # External JAR libraries used in the project
│   ├── jcalendar-1.4.jar
│   ├── mysql-connector-java-5.1.23-bin.jar
│   └── rs2xml.jar
├── netbeans folder/                # Java source and form files (NetBeans project files)
    ├── Add_Flight_Details.java
    ├── Book_Ticket.java
    ├── Cancel_Flight_Ticket.java
    ├── Credit_Card.java
    ├── Debit_Card.java
    ├── Forgot.java
    ├── Home.java
    ├── javaconnect.java            # Database connection handler
    ├── Login.java
    ├── New_Account.java
    ├── Payment.java
    ├── Search_Customer.java
    ├── Search_Flight.java
    └── Splash.java
```

---

## 📦 External Libraries

The project uses the following libraries located in the `add jar folder/` directory:

- **jcalendar-1.4.jar** – Used for calendar components in forms.
- **mysql-connector-java-5.1.23-bin.jar** – JDBC driver for MySQL connectivity.
- **rs2xml.jar** – Used for populating JTable components from ResultSets.

These JARs need to be added to your NetBeans project classpath.

---

## 🚀 How to Run

1. **Open NetBeans IDE**.
2. **Create a new Java project** or open this folder as an existing project.
3. **Add the JARs** from `add jar folder/` to your project:
   - Right-click the project > Properties > Libraries > Add JAR/Folder.
4. Make sure **MySQL** is installed and running. Set up the required database and tables.
5. Check or modify the DB credentials in `javaconnect.java`.
6. Run the `Splash.java` or `Home.java` to launch the application.

---

## 🧩 Features

- ✅ Login & Sign Up
- ✅ Flight Search
- ✅ Book Tickets
- ✅ Cancel Tickets
- ✅ Customer & Flight Management
- ✅ Debit/Credit Card Payment Simulation
- ✅ GUI forms with date selection and data validation

---

## 🛠 Technologies Used

- Java (Swing for GUI)
- NetBeans IDE
- MySQL
- JDBC
- JCalendar Library

---

## 📌 Notes

- Ensure the MySQL database schema matches the queries in the code.
- Some credentials or configurations might need to be updated in `javaconnect.java`.

---


## 📃 License

This project is shared for educational purposes. No official license file is included.

