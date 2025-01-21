# E-Commerce Application

The **E-Commerce Application** is a Flutter-based app designed to offer a seamless shopping experience. It features user authentication, product browsing, cart management, and more, utilizing the MVVM pattern, BLoC/Cubit for state management, and Clean Architecture for scalability and maintainability.

---

## Features

### General Features
- **Authentication**:
  - Login and register with email and password via API.
  - Auto-login for a seamless user experience.
- **Favorites Page**: Create a personal wishlist by adding/removing products.
- **Search Functionality**: Search for products via API search queries.
- **Cart Management**: Add items, modify quantities, and remove items from the cart.
- **Profile Page**: Manage and update personal information and preferences.
- **Image Slideshow**: View product images in a slideshow.
- **Item View Page**: Detailed view of individual items, including product specifications, pricing, and availability.
- **Item Selection Page**: Choose product variations (size, color, etc.) before adding to the cart.
- **State Management**: Utilizes BLoC and Cubit for efficient state handling.
- **Clean Architecture**: Ensures separation of concerns for maintainability and scalability.
- **Shared Preferences**: Stores persistent data such as login status and favorites.
- **Dio Package**: Robust API communication using the Dio package.

---

## Technologies Used

- **Flutter**: Cross-platform framework for app development.
- **Dio**: For making HTTP requests to the backend API.
- **SharedPreferences**: Persistent local data storage.
- **MVVM Pattern**: Structured codebase by separating UI from business logic.
- **BLoC and Cubit**: Efficient state management across the app.

### Key Dependencies
- **Dio**: HTTP requests.
- **SharedPreferences**: Local storage.
- **Image Slideshow**: To display product images.

---

## Getting Started

### Prerequisites

Ensure the following are installed:

- [Flutter](https://flutter.dev/docs/get-started/install) (version 3.0 or later)
- [Dart](https://dart.dev/get-dart)
- RESTful API for backend operations.

### Installation

1. **Clone the Repository**
```bash
git clone https://github.com/NaderEmad9/E-Commerce-App.git
```

2.	**Navigate to the Project Directory**
```bash
cd E-Commerce-App
```

3.	**Install Dependencies**

Run the following command to fetch the required packages:

```bash
flutter pub get
```

4.	**Run the Application**
   
   Use the following command to run the app on your preferred device:
```bash
flutter run
```

---

## Screenshots

<p align="center">
  <img src="https://raw.githubusercontent.com/NaderEmad9/E_Commerce/main/screenshots/spalsh.png" alt="Splash Screen" width="220" style="margin: 10px;"/>
  <img src="https://raw.githubusercontent.com/NaderEmad9/E_Commerce/main/screenshots/login.png" alt="Login Screen" width="220" style="margin: 10px;"/>
  <img src="https://raw.githubusercontent.com/NaderEmad9/E_Commerce/main/screenshots/register.png" alt="Register Screen" width="220" style="margin: 10px;"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/NaderEmad9/E_Commerce/main/screenshots/home.png" alt="Home Screen" width="220" style="margin: 10px;"/>
  <img src="https://raw.githubusercontent.com/NaderEmad9/E_Commerce/main/screenshots/products.png" alt="Products" width="220" style="margin: 10px;"/>
  <img src="https://raw.githubusercontent.com/NaderEmad9/E_Commerce/main/screenshots/products%20detailes.png" alt="Product Details" width="220" style="margin: 10px;"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/NaderEmad9/E_Commerce/main/screenshots/cart.png" alt="Cart" width="220" style="margin: 10px;"/>
  <img src="https://raw.githubusercontent.com/NaderEmad9/E_Commerce/main/screenshots/favorite%20page.png" alt="Favorites Page" width="220" style="margin: 10px;"/>
  <img src="https://raw.githubusercontent.com/NaderEmad9/E_Commerce/main/screenshots/profile%20page.png" alt="Profile Page" width="220" style="margin: 10px;"/>
</p>

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.
