# 📚 Virtual-Classroom

**Virtual-Classroom** is a Flutter-based application designed to facilitate online learning and virtual collaboration. It integrates real-time authentication, camera access, and structured team communication to create an interactive and immersive digital classroom experience.

## 🚀 Features

- 🔑 **Firebase Authentication** - Secure user authentication system.
- 🎥 **Camera Integration** - Supports real-time camera access using `camera` package.
- 🏫 **Teams & Collaboration** - Structured virtual team rooms for discussion and collaboration.
- 🎓 **Exam Mode** - A dedicated exam section for assessments and quizzes.
- 🎨 **Material UI** - A user-friendly interface built with Flutter’s Material Design.

## 📦 Dependencies

The project utilizes the following dependencies:

```yaml
dependencies:
  flutter:
    sdk: flutter
  firebase_core: latest_version
  firebase_auth: latest_version
  camera: latest_version
```

## 🛠 Installation & Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/Virtual-Classroom.git
   cd Virtual-Classroom
   ```

2. **Install dependencies:**
   ```sh
   flutter pub get
   ```

3. **Setup Firebase:**
   - Configure Firebase for your Flutter app.
   - Download `google-services.json` (for Android) or `GoogleService-Info.plist` (for iOS).
   - Place them in the appropriate directories.

4. **Run the app:**
   ```sh
   flutter run
   ```

## 📂 Project Structure

```
/lib
│── main.dart                  # Entry point of the app
│── /screens                    # UI Screens
│   ├── teams_screen.dart       # Teams and collaboration
│   ├── welcome_screen.dart     # User onboarding & login
│   ├── exam_home_page.dart     # Exam and assessment section
│── /firebase                    # Firebase integration files
```

## 🎯 How It Works

- Upon launching, users are authenticated via **Firebase Authentication**.
- Based on authentication status, users are directed to either:
  - **Teams Page** (`TeamsPage`) if logged in.
  - **Welcome Screen** (`WelcomeScreen`) for authentication.
- The app also includes an **exam module** for assessments.

## 👨‍💻 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create a new branch (`feature-branch`)
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License.
