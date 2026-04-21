**📒 User Directory App******

A Flutter application that fetches and displays random user profiles from the Random User API in a modern dark-themed grid layout.

✨ Features
- Fetches 50 random users from API
- Clean 2-column grid layout
- Displays profile image, name, and email
- Pull-to-refresh functionality
- Loading indicator during API calls
- Error handling with retry option
- Dark themed UI
  
**🛠️ Tech Stack**
Flutter & Dart (UI + Logic)
HTTP Package (API calls)
Random User API (Data source)

**📁 Project Structure**
lib/
├── main.dart
├── model/
│   └── DataModel.dart
└── screens/
    └── homescreen.dart
    
**🌐 API**
GET https://randomuser.me/api/?results=50
Fields Used:
name.first / name.last → Full name
email → Email address
picture.medium → Profile image

**👨‍💻 Author**
Hash Coder

📄 License

This project is licensed under the MIT License.
