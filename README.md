# LakbayApp: A Commuter Route and Fare Information System for Jeepneys and Tricycles in Metro Manila

> An Information Systems capstone project developed to improve public transportation transparency, route awareness, and fare estimation for commuters in Metro Manila.

> **Project Status & Disclaimer**
> This project was conceptualized, researched, and prototyped as an **undergraduate capstone thesis project** at De La Salle-College of Saint Benilde. It was **never commercially launched or published on public app stores** (Google Play / Apple App Store), as full-scale commercial deployment, real-time GPS tracking infrastructure, and ongoing maintenance presented resource and financial constraints beyond the academic scope. It serves as a functional proof-of-concept and technical portfolio piece.

---

## About the Project
Navigating traditional public utility vehicles (PUVs) like jeepneys and tricycles in Metro Manila often involves unclear routing, unstandardized tricycle zones, and fare uncertainty. **LakbayApp** bridges this gap by serving as a centralized mobile platform that provides:
* **Route Guidance:** Clear visual mapping of jeepney lines and tricycle zone boundaries.
* **Fare Estimation:** Automated calculation of standard and discounted fares based on distance and official LTFRB matrices.
* **Transparency & Accountability:** Built-in reporting workflows linked directly to official LTFRB feedback channels.
* **Administrative Control:** A backend console for managing routes, updating fare matrices, auditing users, and exporting raw interaction data for analysis.

---

## Key Features

### Commuter End
* **Google Authentication (SSO):** Secure account creation and login via Google API.
* **Interactive Mapping:** View overlapping jeepney routes and local tricycle zones.
* **Smart Fare Calculator:** Input origin and destination to compute baseline fares.
* **Accessibility Mode:** Toggle custom discount formulas for **Students, Senior Citizens, and Persons with Disabilities (PWDs)**.
* **Automated Report System:** Direct redirection to official LTFRB reporting forms and complaint templates for overcharging or service violations.

### Admin End
* **Whitelisted Admin Gateway:** Secure administrator login restricted to pre-approved Gmail addresses.
* **User Management:** Audit, flag, or suspend user accounts violating safety terms.
* **Route & Fare Matrix Management:** Add, edit, or delete route segments and update base drop fees or per-kilometer multipliers globally.
* **Raw Analytics Export:** Aggregate commuter interaction logs and export them instantly as `.csv` or `.xlsx` files for external analysis in Power BI, Excel, or Python.

---

## System Architecture & Database Design
The system is built around the **People, Process, and Technology (PPT)** Information Systems framework:
* **Database Schema:** Includes normalized tables for users, admin controls, search history, fare matrices, jeepney routes, tricycle zones, and GPS tracking coordinates.
* **Use Cases & Activity Workflows:** Fully mapped out using UML standards for both commuter interactions and administrative privileges.

---

## Tech Stack & Tools
* **Platform:** Mobile Application (Android / iOS compatible)
* **Authentication:** Google Authentication Service API
* **Data Management & Analysis:** Excel, Power BI, SQL
* **Documentation & Modeling:** UML (Use-Case & Activity Diagrams), Entity-Relationship Diagrams (ERD)

---

---
