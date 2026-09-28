# Hospital Management System

An Angular 16 single-page application for managing hospital operations, including [patients, doctors, appointments, billing].

## Features
- [Patient registration and records]
- [Doctor management and scheduling]
- [Appointment booking]
- [Role-based views: admin / doctor / patient]
- [Login and route guards]

## Tech Stack
- Angular 16, TypeScript, RxJS
- [Angular Material / Bootstrap]
- [REST API backend: .NET / mock JSON server / none]

## Project Structure
- `src/app/components`: UI components [confirm folder names]
- `src/app/services`: API and business logic services
- `src/app/models`: TypeScript interfaces

## Getting Started
```bash
git clone https://github.com/dkausthubh/HospitalManagement.git
cd HospitalManagement
npm install
ng serve
```

## Future Improvements
- Connect to an ASP.NET Core Web API with JWT authentication
- Add unit tests with Karma/Jasmine
- Dockerise and deploy
