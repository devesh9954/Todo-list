Todo - Task Management Application
Todo is a user-friendly task management application for Android, designed to help users efficiently manage their daily tasks, set priorities, and keep track of deadlines. The app offers an intuitive interface and robust functionality, making it ideal for anyone seeking to streamline their task management.

Features
Task Creation and Management: Users can easily create new tasks, set due dates, and organize them into categories such as "Work," "Personal," and "Urgent."
Prioritization: Tasks can be prioritized to help users focus on high-priority items.
Completion Status: Mark tasks as complete or pending with a single tap.
Light/Dark Mode: The app adapts to the user's system settings, automatically switching between light and dark mode for a personalized experience.
Offline Support: Tasks can be accessed and modified even without an internet connection, with changes synchronized when the device reconnects.
Technical Details
Language: Built using Kotlin, a modern, statically typed language designed for Android development.

Architecture: Implements the MVVM (Model-View-ViewModel) pattern, promoting a clean separation between business logic and the user interface. The app also follows Clean Architecture principles, which enhances the scalability and maintainability of the codebase.

Model: The data layer, consisting of Firebase Firestore for storage and retrieval of task data.
View: The user interface, developed using Android’s Fragments for modular and reusable UI components.
ViewModel: Intermediates between the View and Model, handling logic and preparing data for the UI.
Dependency Injection: The app uses Dagger and Hilt for dependency injection, simplifying the management of dependencies and reducing boilerplate code.

Firebase Integration:

Authentication: Firebase Authentication handles user sign-up, login, and account management using email/password or third-party services like Google.
Firestore: Firebase Firestore serves as the backend, providing real-time, cloud-based storage for task data. It ensures that user data is synced across devices in real time, offering seamless task management from any Android device.
UI Design:
The app is designed following the latest Material 3 guidelines, offering a modern, sleek user experience. The color scheme dynamically adjusts based on the system’s light or dark mode settings, providing a comfortable visual experience.

Fragments: The app leverages Fragments to structure its UI into independent, reusable components. This modular approach allows for flexible design and smooth navigation between screens like task lists, task details, and settings.

Development Approach
The development of Todo focuses on creating a scalable and maintainable architecture. By using MVVM and Clean Architecture, the app's logic is decoupled from its UI, making it easier to test and modify in the future. This architecture also ensures that the app can evolve and support new features without requiring major rewrites.

Firebase Firestore enables real-time updates and cross-device synchronization, ensuring users have access to their tasks on any device logged into their account. Firebase Authentication simplifies secure login functionality, providing a seamless user experience.

Material 3 ensures a polished and modern interface, while Dagger and Hilt streamline dependency management, reducing boilerplate code and increasing overall app performance.
