# Flutter Calculator App

A simple calculator app built using Flutter. This app allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator can handle both integer and decimal numbers.

<img src="https://github.com/SamiAhmed007/CalculatorApp/blob/main/screenshots/Calculator-Home.jpeg" width="400" height="800">

## Features

- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division.
- **Clear Button**: A "Clear" button to reset the calculator.
- **Decimal Support**: Supports decimal numbers for more precise calculations.
- **Responsive UI**: The UI adjusts to fit different screen sizes and resolutions.
- **Rounding**: Subtraction results are rounded to two decimal places.

## Screenshots
### Addition of two numbers:
<!-- Add some screenshots of the app here -->
<div>
<img src="https://github.com/SamiAhmed007/CalculatorApp/blob/main/screenshots/Addition-Number1.jpeg" width="300" height="600">
<img src="https://github.com/SamiAhmed007/CalculatorApp/blob/main/screenshots/Addition-Number2.jpeg" width="300" height="600">
<img src="https://github.com/SamiAhmed007/CalculatorApp/blob/main/screenshots/Addition-Solution.jpeg" width="300" height="600">
</div>

### Division of number by Zero(Infinite):
<div>
<img src="https://github.com/SamiAhmed007/CalculatorApp/blob/main/screenshots/Division-Number1.jpeg" width="300" height="600">
<img src="https://github.com/SamiAhmed007/CalculatorApp/blob/main/screenshots/Division-Number2.jpeg" width="300" height="600">
<img src="https://github.com/SamiAhmed007/CalculatorApp/blob/main/screenshots/Division-Solution.jpeg" width="300" height="600">
</div>

## Project Structure

This project is structured as a basic Flutter app:

flutter_calculator/ <br/><pre>
├── android/                  # Android-specific code <br/>
├── build/                    # Generated build files (ignore this) <br/>
├── ios/                      # iOS-specific code <br/>
├── lib/                      # Main Dart code directory <br/>
     &ensp;&ensp; ├── main.dart             # The main entry point of the application <br/>
├── test/                     # Unit test directory <br/>
├── .gitignore                # Specifies files and folders to ignore in Git <br/>
├── pubspec.yaml              # Flutter project configuration file <br/>
├── README.md                 # Project description file (you are here) <br/>
└── screenshots/              # (Optional) Directory to store screenshots for the README <br/>
</pre>

## Detailed Explanation:
- **android/**: Contains platform-specific code for Android. This folder is automatically generated when you create a Flutter project.
- **ios/**: Contains platform-specific code for iOS. This is also automatically generated.
- **lib/**: This is the main folder where all your Dart code lives.
- **main.dart**: The entry point for the Flutter app. This file contains the logic and UI for the calculator app.
- **build/**: This is a generated directory created when you build the app. It holds the compiled files and should be ignored (which is handled by .gitignore).
- **test/**: This folder contains unit and widget tests. You can write tests here to ensure your app works as expected.
- **pubspec.yaml**: The configuration file for your Flutter project, where you manage dependencies, assets, and metadata.
- **README.md**: The file you're currently editing! This describes the project and provides information about how to use and contribute to it.
- **screenshots/**: (Optional) A folder where you can place any screenshots of the app to include in your README.md. You can create this folder if you want to showcase images in the documentation.

## Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites
Ensure that you have the following installed on your system:
- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Dart](https://dart.dev/get-dart)
- [Git](https://git-scm.com/)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/SamiAhmed007/CalculatorApp.git
   cd CalculatorApp
2. Install dependencies:
   ```bash
   flutter pub get

3. Run the app:
   ```bash
   flutter run

4. To build the app for release:
   ```bash
   flutter build apk

## How to Use
- Launch the app on your device or emulator.
- Tap on the numeric buttons and operators to perform calculations.
- Press the Clear button to reset the display.
- The result of the calculation will be shown on the screen after pressing the = button.

## Technologies Used
- Flutter: UI toolkit for building natively compiled applications.
- Dart: Programming language optimized for building user interfaces.
- Material Design: Default UI components provided by Flutter for the app interface.

## Future Improvements
- Add scientific calculator functions (sin, cos, tan, etc.).
- Add memory storage features (M+, M-, MR, MC).
- Add a history panel to show previous calculations.

## Contributing
Contributions are welcome! If you'd like to contribute, feel free to open a pull request. For major changes, please open an issue first to discuss what you'd like to change.

### Steps for Adding Your Project to GitHub:
1. **Initialize Git in Your Project Directory**:
   Open a terminal, navigate to your project directory, and initialize Git:
   ```bash
   git init
2. **Add Files and Commit: Add all project files and create an initial commit**:
   ```bash
   git add .
   git commit -m "Initial commit for calculator app"
3. **Create a New GitHub Repository: Go to GitHub and create a new repository. You can name it something like**
4. **Add Remote Repository**: Link your local repository to the GitHub repository:
   ```bash
   git remote add origin https://github.com/SamiAhmed007/CalculatorApp.git
5. **Push Your Code to GitHub**: Push the code to the main branch:
   ```bash
   git push -u origin master
6. **Add the README.md to Your Repo**: Create a README.md file in your project directory with the content I provided above. Once created, add it to your repo:
   ```bash
   git add README.md
   git commit -m "Added README file"
   git push

**Happy Coding : )**



