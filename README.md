
# ✈️ Airport Luggage Smart System

*A Java Console Project using Basic I/O and Regular Expressions*

## 📘 Project Overview

This project simulates a **smart airport luggage management system** that handles logs for various airport operations such as luggage vehicles, charging stations, and the overall system.
It was developed as part of a **Basic I/O and Regular Expressions** assignment at Fachhochschule Dortmund.

The main purpose is to demonstrate:

* Java **File I/O operations** (create, move, delete, archive files)
* Use of **byte and character streams** for data exchange
* Use of **Regular Expressions** to search and filter logs
* Managing metadata and logs **without any database**


## 🧠 Core Features

| Functionality              | Description                                                                                    |
| -------------------------- | ---------------------------------------------------------------------------------------------- |
| **Create log files**       | Generate daily log files for each storage vehicle, charging station, and the system as a whole |
| **Write and read logs**    | Use character streams (`BufferedWriter`, `BufferedReader`) to record and retrieve data         |
| **Simulate data exchange** | Use byte streams (`ByteArrayInputStream`) to simulate communication from airport devices       |
| **Archive logs**           | Compress daily logs into `.zip` files using `ZipOutputStream`                                  |
| **Move/Delete logs**       | Manage existing log files using Java NIO (`Files.move`, `Files.delete`)                        |
| **Search using Regex**     | Open and filter logs by equipment ID or date using **regular expressions**                     |
| **Metadata management**    | Use folder structure and file naming conventions to manage metadata instead of a database      |


## 🗂️ Project Structure

```
AirportLuggageSystem/
├─ src/com/airport/luggage/
│  ├─ LogRecord.java
│  ├─ LogService.java
│  ├─ FileManager.java
│  ├─ TaskSimulator.java
│  ├─ RegexSearch.java
│  └─ Main.java
├─ data/
│  ├─ logs/
│  │  ├─ vehicles/
│  │  ├─ chargers/
│  │  └─ system/
│  └─ archive/
└─ README.md
```

---

## 🧰 Technologies Used

* **Java 17+**
* **Eclipse IDE** (or any Java IDE)
* **Java NIO (java.nio.file)** for file manipulation
* **I/O Streams** (byte and character)
* **Regular Expressions (java.util.regex)**
* **ZIP utilities (java.util.zip)**


## Role Ditribution: 
1. **Create log files** :  Ibrahim
2. **Write and read logs** : Raju
3. **Simulate data exchange**: Ibrahim
4. **Archive logs** : Nawshad
5. **Move/Delete logs** : Raju
6. **Search using Regex** :Ibrahim
7. **Metadata management** : Nawshad

## 📄 Output :>>
```

```


## 🧩 Key Learning Outcomes

* Understanding of **Java I/O stream hierarchy**
* Difference between **byte streams** and **character streams**
* Practical use of **Regular Expressions** in log searching
* Real-world application of **file handling, archiving, and metadata management**
* Building a small-scale system **without a database**


## 📚 References

* [Oracle Java I/O Tutorial](https://docs.oracle.com/javase/tutorial/essential/io/index.html)
* [Java Regular Expressions Tutorial](https://docs.oracle.com/javase/tutorial/essential/regex/)


## 👨‍💻 Author

**Team 7**
1. Md Shariful Islam MDT-7213424

2. Nawshad Fahim MDT 7216629

3. Ibrahim Khalil MDT 7213232

4. Raju Naidu MDT 7213668
