# Quality-Threshold (QT) Project

## 📌 Overview
This repository contains the final project for the **Advanced Programming Methods (Metodi Avanzati di Programmazione - MAP)** course, Academic Year **2024-2025**.

The project implements a system for data mining using the **Quality-Threshold (QT) Clustering** algorithm. It is structured as a client-server application, allowing users to discover clusters within datasets stored in a SQL database.

## 🛠 Features
- **Client-Server Architecture**: Distributed system using Java Sockets.
- **Data Mining**: Implementation of the QT Clustering algorithm.
- **Database Integration**: Connection to MySQL for data retrieval.
- **Graphical User Interface (GUI)**: Interactive interface built with JavaFX (ExtensionC).
- **Comprehensive Documentation**: Includes Javadoc, UML diagrams, and a detailed technical report.

## 📁 Project Structure
- `QTServer`: The server-side application handling data mining logic and DB connection.
- `QTClient`: Command-line interface for interacting with the server.
- `ExtensionC`: Graphical user interface (GUI) version of the client.
- `JavaDoc`: Automatically generated technical documentation.
- `Diagrammi UML`: Visual representation of the system architecture.
- `mapDB.sql`: SQL script to initialize the required database.

## 🚀 Getting Started

### Prerequisites
- Java JDK 17 or higher
- MySQL Server
- JavaFX SDK (for the GUI extension)

### Database Setup
1. Open your MySQL manager (e.g., Workbench).
2. Execute the script `mapDB.sql` to create the database and populate it with sample data.

### Running the Project
1. **Start the Server**: Run the `MultiServer` class located in `QTServer`.
2. **Start the Client**: 
   - Run `MainTest` in `QTClient` for the CLI version.
   - Run `Main` in `ExtensionC` for the GUI version.

## 📊 Documentation
The project is fully documented. You can find:
- **Technical Report (Italian)**: A comprehensive and detailed documentation is available in the file `Documentazione Quality-Threshold.docx` in the root folder.
- **UML Diagrams**: Visual representation of the system architecture located in the `/Diagrammi UML` folder.
- **Javadoc**: Technical API specifications can be found by opening `index.html` inside the `/JavaDoc` folders.

## 👤 Author
* **Emanuele Fornaro** - *Computer Science Student at Università degli Studi di Bari "Aldo Moro"*
