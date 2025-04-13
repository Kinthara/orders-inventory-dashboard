# 🧾 Orders & Inventory – Angular UI

This is the **frontend UI** of the Orders & Inventory Dashboard — a fullstack demo application designed to simulate a simple order and stock management system.

Built with **Angular 18**, this project is structured as a standalone frontend that will connect to a backend (developed in Java with Spring Boot and OpenTelemetry).

---

## 🖼️ Project Overview

The app allows users to:

- View a list of orders 📦  
- Add or update stock levels 🧺  
- Navigate between orders and inventory  
- Visualize metrics via Grafana (planned in backend integration)

---

## 🧠 Tech Stack (Frontend)

- Angular 18  
- SCSS  
- TypeScript  
- RxJS  
- Native HTML/CSS components (no UI libraries for now)  
- OpenTelemetry JS (coming soon)

---

## 📁 Project Structure (planned)

src/ 
├── app/ 
│ ├── features/ 
│ │ ├── orders/ 
│ │ └── inventory/ 
│ ├── shared/ 
│ └── core/ 
├── assets/ 
└── index.html

## 🧪 Getting Started

Install dependencies:

```bash
npm install

🔗 Related Repositories
📡 orders-inventory-api (Spring Boot backend – coming soon)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.18.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
