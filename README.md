# Healthcare Management Application

The Healthcare Management Application is a Spring Boot-based system designed to help healthcare providers manage patient
records, schedule appointments, and prescribe medication. This application also integrates with third-party services 
like Google Maps to provide directions to healthcare facilities.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Endpoints](#endpoints)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Patient Management**: Create, read, update, and delete patient records.
- **Appointment Scheduling**: Schedule appointments for patients with date and time.
- **Medication Prescribing**: Prescribe medications to patients with dosage information.
- **Google Maps Integration**: Get directions to healthcare facilities using Google Maps.

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- H2 Database (or your preferred database)
- Google Maps API

## Getting Started

### Prerequisites

- Java 8 or higher
- Maven
- IDE (Eclipse, IntelliJ IDEA, etc.)
- Postman (or any API testing tool)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/aigulsharip/healthcare-management.git

## Getting Started

### Navigate to the project directory:

```bash
cd healthcare-management
```


### Build the project using Maven:
bash
Copy code
mvn clean install

### Run the application:
mvn spring-boot:run

### Endpoints
#### Patients
GET /api/patients: Get all patients.
GET /api/patients/{id}: Get patient by ID.
POST /api/patients: Create a new patient.
DELETE /api/patients/{id}: Delete patient by ID.
#### Appointments
GET /api/appointments: Get all appointments.
POST /api/appointments: Schedule a new appointment.
DELETE /api/appointments/{id}: Cancel appointment by ID.
#### Medications
GET /api/medications: Get all medications.
POST /api/medications: Prescribe a new medication.
DELETE /api/medications/{id}: Remove medication by ID.

