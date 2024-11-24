# NLV Madhav - Final Year B.E. in Information Technology

Hi! I'm NLV Madhav, currently pursuing my Bachelor of Engineering in Information Technology. This README showcases some of the projects I've worked on, reflecting my skills and knowledge in areas such as software development, data science, and web development.

## Projects

### 1. **Drought Detection System**
**Technologies Used**: Java, Swing, Oracle 19c (Database)

**Description**:  
This project aims to detect drought conditions in a specific area based on parameters like rainfall, groundwater levels, vegetation percentage, and soil moisture. The application calculates the drought level of an area using these parameters, which can help authorities decide on necessary actions like compensation for farmers or the provision of additional resources.

**Technical Aspects**:
- The application is built using the **Swing** framework in Java, following the **MVC (Model-View-Controller)** design pattern:
    - **Model**: Represents the data (stored in the Oracle database).
    - **View**: How the data is presented to the user.
    - **Controller**: Handles user inputs and updates the model accordingly.
- The **JDBC (Java Database Connectivity)** is used to connect the Java application to the Oracle 19c database.
- The database consists of 4 tables to store values for:
    - Rainfall
    - Groundwater levels
    - Vegetation percentage
    - Soil moisture percentage
- Based on the parameter values, the drought level is calculated and can be optionally stored in a separate table.

**GitHub Link**: [Drought Detection System](https://github.com/nlvmadhav/Drought_Info.git)

---

### 2. **Level-2 Classification of Geospatial Data**
**Technologies Used**: Python, Deep Learning (ResNet-50)

**Description**:  
This project was a part of the **Space India Hackathon (2023)** organized by **ISRO**. The goal was to classify geo-spatial satellite images into different L-2 geographical classes, helping planners and decision-makers obtain critical geographical data for planning purposes.

**Technical Aspects**:
- The classification model employed was **ResNet-50**, a deep learning model designed for image classification tasks.
    - **ResNet-50** is a residual network with 50 layers, solving the exploding and vanishing gradient problem using **residual blocks**. This allows for the direct flow of information via **skip connections**, improving model performance.
  
**GitHub Link**: [Level-2 Classification of Geospatial Data](https://github.com/nlvmadhav/Lulc.git)

---

### 3. **FarmArt - Platform for Empowering Farmers**
**Technologies Used**: HTML5, CSS3, JavaScript, Flask, SQLite/MySQL

**Description**:  
FarmArt is a platform designed to bridge the gap between farmers and consumers, providing a way for customers to purchase fresh, high-quality produce directly from farmers. It empowers farmers by enabling them to sell their products at fair prices and allows consumers to access authentic, farm-to-table produce.

**Tech Stack**:
- **Frontend**:
    - **HTML5**: Used for structuring the content.
    - **CSS3**: For styling the UI.
    - **JavaScript**: To add interactivity and dynamic features.
    - **Bootstrap**: To make the UI mobile-friendly and visually appealing.

- **Backend**:
    - **Flask**: A Python web framework to handle server-side logic, routing, and APIs.
    - **RESTful APIs**: For seamless communication between the frontend and backend.

- **Database**:
    - **SQLite/MySQL**: Used for storing user details, product listings, transactions, and feedback.

**GitHub Link**: [FarmArt](https://github.com/nlvmadhav/Farmart.git)

---

## Skills & Tools

- **Programming Languages**: Python, C, Java, JS
- **Frameworks/Technologies**: 
  - Java Swing (for desktop applications)
  - Flask (for web development)
- **Database**: Oracle 19c, MySQL, SQLite

## Contact

- **Email**: nlv.madhav@example.com
- **GitHub**: [https://github.com/nlvmadhav](https://github.com/nlvmadhav)


