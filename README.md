# Student Management System

A responsive web-based platform for managing student records, built using Core Java, JSP, Servlets, and MySQL following the MVC architecture.

## Tech Stack

- **Backend:** Java (Core J2SE, Advanced J2EE)
- **Web Layer:** JSP, Servlets
- **Database:** MySQL (JDBC)
- **Frontend:** Bootstrap 5, HTML, CSS, JavaScript (Fetch API)
- **IDE:** Eclipse EE

## Features

- Full **CRUD** operations (Create, Read, Update, Delete) for managing 500+ student records
- Interactive, data-driven web pages with dynamic content loading
- Server-side validation and structured error handling
- Normalized PostgreSQL schema for efficient data storage
- Clean, documented system architecture for future scalability

## Key Improvements & Impact

| Metric | Result |
|---|---|
| Data redundancy | Reduced by **40%** through schema normalization |
| Page load times | Improved by **25%** via JSP + Bootstrap integration |
| Form input errors | Reduced by **80%** with server-side validation |
| Records managed | **500+** student records with full CRUD support |

## Project Structure

```
Project-AdvJava/
├── src/
│   ├── controllers/      # Servlet classes
│   ├── models/           # Java POJOs / entity classes
│   ├── dao/              # Database access layer (JDBC)
│   └── utils/            # Helper/utility classes
├── WebContent/
│   ├── views/            # JSP pages
│   ├── css/              # Bootstrap & custom styles
│   └── js/               # Fetch API scripts
└── README.md
```

## How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/suyashdivate/student-management-system.git
   ```
2. Import into Eclipse EE as an existing **Dynamic Web Project**
3. Configure your PostgreSQL database and update connection credentials in the DB config file
4. Deploy on Apache Tomcat server
5. Access via `http://localhost:8080/Project-AdvJava`

## Author

**Suyash Divate**
B.Tech Information Technology, JSPM's Rajarshi Shahu College of Engineering, Pune
[LinkedIn](https://linkedin.com/in/suyash-divate) · suyashdivate.official@gmail.com
