# PRS1: JASS 

##  🔧 Project Stack



Backend: Java 17 (IntelliJ IDEA, Spring Boot)
Frontend: Angular (latest stable version)
Database: MongoDB and PostgreSQL


###  Project Purpose

```
The PRS project aims to manage everything related to water boxes, user payments, and inventory, in order to better manage the JASS.

```

## 🛠️ Setup Instructions (Imperatives)



```
Clone the repository:
https://github.com/FrankSalazar71/Cajamicroservice.git
Navigate into backend:
cd JASS/infraestrcutura-project/backend
Run Spring Boot app:
./mvnw spring-boot:run
Navigate into frontend:
cd ../frontend
Install dependencies and serve the Angular app:
npm install
ng serve

```

## 🧩 How to Use the App (Advice with “should”)



```
- You must open http://localhost:4200 after both the backend and frontend are running.

- You must be logged in to access the app.

- You must add and assign user water dispensers, then transfer a water dispenser to another user.
```

### 📁 Repository Structure

```
/cetpro-social-project
├── backend/        # Java 17 + SpringBoot 3 Reactivo REST API
├── frontend/       # Angular 19 app + Tailwind v4
├── README.md       # ← information
├── CONTRIBUTING.md # Contribution guidelines
├── .env.example    # Environment variables template
└── docs/           # Project documentation & diagrams
```

## 🧑‍🏫 Contributing (Imperatives & Advice)



```
1. Fork this repository
Imperative: Fork the main infrastructure repository.

📌 Advice: This creates your own copy where you can safely make changes without affecting the main project.

 2. Clone your fork locally
Imperative: Clone your forked repository to your local machine.

git clone https://github.com/your-username/infrastructure-microservice.git
cd infrastructure-microservice

3. Create a new feature branch
Imperative: Create a new branch for your change.
git checkout -b feature/your-feature-name

4. Implement your feature or fix
Imperative: Add or modify code related to infrastructure logic.

📌 Advice: In this microservice, your work may involve:

Docker and container orchestration setup

Configuration files (application.yml, .env, etc.)

CI/CD pipelines or environment management

Logging, monitoring, or service discovery tools

5. Test and lint your code
Imperative: Ensure your changes work correctly and follow code standards.
# Run tests
./mvnw test

# Apply linter if available
./mvnw spotless:apply
📌 Advice: Clean and tested code avoids bugs in other connected services.
```

## 🚀 Deployment Requirements (Must & Need To)

```
You must set the environment variables:
DATABASE_URL=your_postgresql_connection_url
JWT_SECRET=your_jwt_secret_key
You need to enable CORS in the Spring configuration for frontend access.
You must build the frontend before deployment:
npm run build in /frontend/
Upload contents of dist/ to your hosting platform.
```

## 💡 Best Practices & Tips

```
You should write unit tests using JUnit and Mockito for your Spring Boot backend.

You should write unit and component tests using Jasmine and Karma for your Angular frontend.

You should run:
mvn clean verify       # For backend
ng lint                # For frontend

before each commit to ensure clean and valid code.
```

## 📞 Questions & Support 



```
If you need help:

Open an issue in this repository.

Tag @project-lead for urgent or blocking issues.

Join our WhatsApp group for real-time collaboration.

You can also contact us directly via email at frank.salazar@vallegrande.edu.pe.

Thank you for your contributions!
👍 Let's build something meaningful together.
  
```
