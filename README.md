# Doctor Appointment & Patient Portal

An AI-powered healthcare platform that connects patients with medical specialists.
Patients search for doctors, reserve consultation slots, and review their medical
history. Doctors manage their schedules and appointments, and administrators
manage users, doctors, and specialties.

A built-in **RAG assistant** answers non-clinical questions (booking steps, clinic
hours, cancellation policy) from approved clinic documents and cites its sources.
It uses a pre-trained language model and never books, cancels, or diagnoses.

## Features

**Patients**
- Registration, login, and profile management
- Doctor search by specialty or name
- Appointment booking, cancellation, and rescheduling
- Medical history and notifications
- AI chat assistant for clinic FAQs

**Doctors**
- Availability and time-off management
- Daily schedule and appointment status updates
- Access to records of their own patients

**Administrators**
- User, doctor, and specialty management
- Knowledge base management for the AI assistant

## Architecture

Monolithic web application following the Model–View–Controller (MVC) pattern.

```
src/
├── models/          # Domain entities and business rules
├── views/           # User interface templates and components
├── controllers/     # Request handling, validation, authorization
├── services/        # Booking, scheduling, notifications
├── repositories/    # Database access
└── ai/              # Retrieval, prompts, and safety checks
docs/                # Project documentation and diagrams
tests/               # Unit, integration, and security tests
deployment/          # Configuration and environment setup
```

## Tech Stack

_To be added._

## Getting Started

### Prerequisites
_To be added._

### Installation
_To be added._

### Running the Application
_To be added._

## Documentation

- [Requirements Specification](docs/SRS.pdf)
- [Design Document](docs/Design_Document.pdf)

## Team

| Name | Focus Area |
|---|---|
| Khaled Mohsen | Authentication, access control, administration |
| Mai Ayman | Doctor search and appointment booking |
| Ebraheem Elkasaby | Appointment lifecycle and notifications |
| Khaled Walid | Doctor workspace and medical history |
