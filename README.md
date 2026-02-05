# Sales Management App

[English](./README.md) | [Español](./README.es.md) 

Mobile application developed with Flutter, focused on the management of users, products, sales, and branches.
The app follows Clean Architecture principles and consumes a REST API provided by a backend developed with Node.js and Express, ensuring scalability, maintainability, and separation of concerns.

## Main Features

- **JWT Authentication**: Autenticación y autorización de usuarios mediante JSON Web Tokens (JWT) para una comunicación segura.

- **Product Management**: Product registration and management, including purchase price and selling price, allowing accurate profit calculations.

- **Branch Management**: Branch (store) registration to track and analyze sales by branch.

- **Sales Management**: Sales registration with detailed sale items, enabling the calculation of total sales amount and generated profits.

## Installation Requirements

- **Flutter SDK**: You must have the Flutter SDK installed.
- Run `flutter pub get` to install the required dependencies.

## Usage Instructions

1. Clone or download the repository.
2. Open the project in a Flutter-compatible IDE.
3. Connect a mobile device or start an emulator.
4. Run `flutter run` to build and launch the application on the device/emulator.

## Screenshots

| **Login** | **Sidebar** | **Sales by Date** |
|:-------------------:|:--------------------------:|:--------------------------:|
| ![Login](./screenshots/ui1.jpeg) | ![Sidebar](./screenshots/ui2.jpeg) | ![Sales by Date](./screenshots/ui3.jpeg) |

| **Sales Form** | **Sales Detail List** |
|:-------------------:|:--------------------------:|
| ![Sales Form](./screenshots/ui4.jpeg) | ![Sales Detail List](./screenshots/ui5.jpeg) |
