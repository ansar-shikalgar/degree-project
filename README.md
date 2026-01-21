# degree-project
An Android application designed to manage competition events in educational institutions, facilitating coordination between administrators, coordinators, and students.

# Overview
      The Competition Event Management System is a comprehensive Android application that streamlines the management of college competitions and events.
      It provides separate interfaces for administrators,coordinators, and students with role-specific functionalities.

# Features
    *Admin Features
        Admin login with hardcoded credentials
        Coordinator registration management
        Access to admin dashboard
        
    *Coordinator Features
        User authentication (login/registration)
        Event management (add, view, edit events)
        Photo and certificate upload
        Google Drive link sharing
        Send notifications to students
        Create poll questions and surveys
        Profile management
        Session persistence using SharedPreferences

    *Student Features
        Student registration with branch and class selection
        Event viewing and participation
        Meeting link access
        Survey and poll participation
        Certificate downloads
        Profile management
        Event status tracking

    *User Roles  
      Admin: System administrator with full access
      Coordinator: Event organizers who manage events and student participation
      Student: Participants who can view events and participate in activities
      
# Tech Stack
        *Frontend
            Language: Java
            UI Framework: Android SDK
            Minimum SDK: API Level 21 (Android 5.0)
            UI Components:
                Material Design Components
                NavigationView with DrawerLayout
                CardView
                RecyclerView
                Fragments

  *Backend Integration
      HTTP Client: Volley Library
      API Communication: RESTful API calls
      Image Processing: Custom AsyncTask implementation

  *Payment Integration
    Payment Gateway: PayU
    Supported Methods: Google Pay, PhonePe, Paytm

  *Data Persistence
    SharedPreferences for session management

# Architecture
    The app follows a modular architecture with:
    Activities: Main screens and navigation controllers
    Fragments: Modular UI components for dashboard sections
    Adapters: RecyclerView adapters for dynamic lists
    Network Layer: Volley-based API communication
    Session Management: SharedPreferences for login persistence

      
