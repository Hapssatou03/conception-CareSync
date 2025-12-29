# conception-CareSync
# CareSync — Conception Repository

This repository contains the **conceptual and functional design artifacts** for the **CareSync** project.

CareSync is a digital wellness tracking application designed to help users monitor their daily well-being, visualize trends, and receive explainable insights based on their data.

This repository focuses exclusively on the **analysis and conception phase** of the project, following software engineering best practices.

---

##  Purpose of this Repository

The goal of this repository is to:
- Formalize the functional and data design of CareSync
- Provide clear documentation before development
- Ensure consistency between business needs and technical implementation
- Serve as a reference for development and evaluation (academic or professional)

---

##  Repository Structure

conception-CareSync/
│
├── cahierDeCharge/
│ └── CareSync_Cahier_des_Charges.pdf
│
├── useCase.svg
│
├── mcd.png
│
├── README.md
│
└── LICENSE


---

##  Included Artifacts

###  Requirements Specification
- **CareSync_Cahier_des_Charges.pdf**
  - Project context and objectives
  - Functional requirements
  - Non-functional requirements
  - MVP definition
  - Accessibility, performance, and GDPR constraints

---

###  Use Case Diagram
- **useCase.svg**
  - User interactions with the system
  - Core functionalities:
    - Authentication
    - Daily check-in
    - Wellness score
    - Analytics dashboard
    - Insight generation
    - GDPR data management
  - Clear separation between user actions and system behavior

---

###  Conceptual Data Model (MCD)
- **mcd.png**
  - Conceptual representation of the data model (Merise methodology)
  - Main entities:
    - User
    - CheckIn
    - WellnessScore
    - Insight
    - Rule
  - Relationships and cardinalities
  - Business rules such as:
    - One check-in per user per day
    - Explainable insights through rule-based triggers

---

##  Methodology & Conventions

- **Merise methodology** for data modeling
- UML **Use Case Diagram** for functional analysis
- Clear separation between:
  - Conceptual level (this repository)
  - Logical and physical implementation (development repositories)
- English naming conventions for international readiness

---

##  Data Protection & GDPR

The conception explicitly integrates GDPR principles:
- User data ownership
- Data export requests
- Account deletion requests
- No hidden or opaque data processing

---

##  Next Steps

This conception repository serves as the foundation for:
- Backend development (API & business logic)
- Frontend development (UX/UI implementation)
- Logical and physical data modeling (MLD / MPD)
- Testing and deployment phases

---

##  Author

**Hapssatou Sy**  
Software Engineer & Data-Oriented Developer  

---

##  License

This project is licensed under the **MIT License**.

