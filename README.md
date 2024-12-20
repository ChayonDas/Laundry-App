# Laundry-App
**Developed using React Native**

The Laundry-App is a React Native mobile application designed to streamline the process of booking and managing laundry services. This app features essential components for user interaction, order management, and location tracking, with a user-friendly UI. Developed using tools such as React Native CLI/Expo, VS Code, Node.js/npm, and integrated with Firebase for backend services.

## Demo Project
Here's a brief visual and functional overview of the Laundry-App:

**Screenshots**:
- **Home Screen**:

  
  ![Home UI](https://github.com/user-attachments/assets/771194f6-2a26-4855-9797-618aea145573)![Orderui2](https://github.com/user-attachments/assets/138518df-30e0-472a-ad1a-7b1868e369da)



[back to top](#laundry-app)

## Overview / Introduction
Laundry-App is built with React Native to offer a seamless user experience for laundry service management. The app includes various features such as location tracking, product listings, a service cart, order management, and user authentication. The application is developed with the following technologies and libraries:

- **React Native CLI/Expo** for development
- **VS Code** as the code editor
- **Node.js/npm** for package management
- **React Navigation** for routing
- **Jest** for testing
- **Git** for version control
- **Android Studio/Xcode** for emulation
- **Firebase** for database and authentication services
- **Optional tools**: Redux for state management, Flipper for debugging

## Installation and Setup
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/laundry-app.git
    cd laundry-app
    ```
2. **Install dependencies**:
    ```bash
    npm install
    ```
3. **Start the app**:
    ```bash
    npx react-native run-android # for Android
    npx react-native run-ios     # for iOS (requires Xcode)
    ```

[back to top](#laundry-app)

## Features
### Core Functionalities:
- **Location Tracker**: Enables real-time tracking for user location.
- **Home UI**: A welcoming, intuitive design for user navigation.
- **Product List**: Displays available laundry services.
- **Service Cart**: Allows users to add services to a cart.
- **Cart Item Increment & Decrement**: Users can adjust item quantities.
- **Cart Pickup**: Users can schedule a pickup for their laundry.
- **Cart Screen**: Detailed overview of selected items.
- **Order Details**: Comprehensive view of user orders.
- **Authentication & Authorization**: Secure processes using Firebase.
- **Login & Signup UI**: Modern and clean designs for user onboarding.
- **Order System**: Full workflow for placing, processing, and tracking orders.
- **Database Integration**: Firebase for data storage and real-time updates.

[back to top](#laundry-app)

## System Architecture
The architecture of the Laundry-App is based on a modular design to ensure maintainability and scalability. Below is an ER diagram representing the core database relationships:

![ER diagram](https://github.com/user-attachments/assets/427b8ee3-670b-4500-9ce5-a83d0ba0e586)

The system architecture follows a client-server model where the mobile client interacts with Firebase as the backend for data storage and authentication. Key components include:

- **User Authentication Module**: Manages login and signup processes.
- **Order Management System**: Handles the lifecycle of user orders.
- **Cart and Product Module**: Manages the selection and adjustment of laundry services.

## Workflow / Process Explanation
The application follows a structured workflow to handle user interactions and service management:

1. **User Authentication**: Users log in or sign up using Firebase authentication services.
2. **Service Selection**: Users browse the product list and add desired services to their cart.
3. **Cart Management**: Users adjust item quantities, review their cart, and schedule pickups.
4. **Order Process**: Finalize orders with real-time database updates.
5. **Order Tracking**: Display order status and details post-confirmation.

![Flow Chart](https://github.com/user-attachments/assets/38c858e8-e5ca-4df6-bcfb-74b793bf17d2)

[back to top](#laundry-app)

## Technical Documentation / Detailed Explanation

### Authentication and Authorization
Uses Firebase to manage user sessions and access control, ensuring secure handling of data while enabling seamless app interaction.

### Order System and Database Connection
Firebase serves as the backend database, managing data such as orders, user information, and statuses with real-time synchronization between client and server.

### UI Design
- **Login & Signup**: User-friendly designs for effortless onboarding.
- **Cart and Home UI**: Interactive, aesthetically pleasing elements for smooth user navigation.

### Core Tools and Technologies
- **React Navigation**: Enables multi-screen navigation with consistent state.
- **Firebase**: Real-time database, cloud functions, and authentication.
- **Redux** (optional): For complex state management.
- **Jest**: Unit and integration testing for code reliability.

[back to top](#laundry-app)

## Future Enhancements
- Add real-time notifications for order updates.
- Integrate payment gateways for a complete checkout experience.
- Introduce loyalty programs for frequent users.
- Expand multi-user role management for a robust experience.

## License
Distributed under the MIT License. See `LICENSE.txt` for more information.

[back to top](#laundry-app)

## Contact
Your Name - [@Chayon Das](https://twitter.com/your_twitter) - daschayon26@gmail.com

Project Link: [https://github.com/ChayonDas/Laundry-App/edit//laundry-app](https://github.com/ChayonDas/Laundry-App/edit/laundry-app)

[back to top](#laundry-app)

## Acknowledgments
Special thanks to the following resources for aiding development:

- [Choose an Open Source License](https://choosealicense.com)
- [GitHub Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
- [Malven's Grid Cheatsheet](https://grid.malven.co/)
- [Img Shields](https://shields.io)
- [GitHub Pages](https://pages.github.com)
- [Font Awesome](https://fontawesome.com)
- [React Icons](https://react-icons.github.io/react-icons)

[back to top](#laundry-app)
