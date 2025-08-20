
 🚆 Railway Reservation System

A simple **Railway Reservation System** built using **Java** and **MySQL** to manage train schedules, seat bookings, cancellations, and passenger records. The project simulates a real-world railway ticketing system with both **Admin** and **User** functionalities.

---

 📌 Features

👤 User

* Search trains by source and destination
* View train details (train number, name, time, fare, seats available)
* Book tickets
* Cancel reservations
* View booking history

 🔑 Admin

* Add, update, and delete trains
* Manage train schedules and fares
* View all bookings and passengers
* Manage seat availability

---

 🛠 Tech Stack

* **Language:** Java (Core Java, JDBC)
* **Database:** MySQL
* **IDE:** IntelliJ IDEA / Eclipse / NetBeans
* **Tools:** MySQL Workbench, Git

---

 📂 Project Structure

```
Railway-Reservation-System/
│── src/                  # Java source code
│   ├── db/               # Database connection files
│   ├── models/           # Train, User, Booking classes
│   ├── services/         # Business logic
│   └── main/             # Entry point
│
│── sql/                  # Database schema & queries
│── README.md             # Project documentation
```

---

 ⚙️ Installation & Setup

 1. Clone Repository

```bash
git clone https://github.com/maksudrakib44/Railway-Reservation-System.git
cd Railway-Reservation-System
```

 2. Configure Database

* Open MySQL and create a database:

```sql
CREATE DATABASE railway_reservation;
```

* Import the provided `.sql` file into MySQL.

 3. Update DB Credentials

In the Java project, update your **DB connection file** (`db/DBConnection.java`):

```java
String url = "jdbc:mysql://localhost:3306/railway_reservation";
String user = "root";
String password = "your_password";
```

 4. Run the Project

* Open the project in **Eclipse / IntelliJ / NetBeans**
* Compile and run the **Main.java** file

---

 🎮 Usage

1. Run the program.
2. Choose **Admin** or **User** mode.
3. Perform operations like searching trains, booking tickets, or managing trains.

---

 📸 Screenshots (Optional)

*Add screenshots of your UI / console output here.*

---

 🤝 Contribution

Contributions are welcome!

1. Fork the repository
2. Create a new branch (`feature-xyz`)
3. Commit your changes
4. Push to your branch and submit a PR

---

 📜 License

This project is licensed under the **MIT License** – feel free to use and modify.

