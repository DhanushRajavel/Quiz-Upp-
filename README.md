
# Quiz Upp!

Quiz Upp! is a fun and interactive quiz app designed to challenge your knowledge across various topics. The app is developed using Flutter and Dart, with Firebase integrated for tools and authentication. The quizzes are dynamically generated using the OpenDB API.

## Features

- **Dynamic Quizzes**: Quizzes are generated on-the-fly using the OpenDB API, ensuring a wide variety of questions.
- **Firebase Integration**: Secure user authentication and data storage with Firebase.
- **User-Friendly Interface**: Clean and intuitive UI built with Flutter's Material Design.

## Technologies Used

- **Framework**: Flutter
- **Languages**: Dart
- **Tools and Authentication**: Firebase
- **API**: OpenDB (opendb.com)

## About OpenDB API

The OpenDB API is a free-to-use public API that provides a vast collection of trivia questions across various categories. It allows developers to fetch multiple-choice questions and answers, making it ideal for quiz and trivia applications. With a simple HTTP request, you can retrieve a wide range of questions, including their difficulty level, category, and type (multiple-choice or true/false).

### Key Features of OpenDB API:

- **Wide Variety of Questions**: Includes questions across different categories like Science, History, Sports, and more.
- **Difficulty Levels**: Questions are available in easy, medium, and hard difficulty levels.
- **Question Types**: Supports multiple-choice and true/false question formats.

For more information, visit the [OpenDB website](https://opendb.com).

## Getting Started

To set up the project locally, follow these steps:

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Dart SDK: Comes with Flutter installation.
- Firebase Account: [Set up Firebase](https://firebase.google.com/)
- OpenDB API Key: Sign up at [opendb.com](https://opendb.com) for an API key.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/quiz-upp.git
   ```
2. Navigate to the project directory:
   ```bash
   cd quiz-upp
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Set up Firebase:
   - Follow Firebase setup instructions to add Firebase to your Flutter project.
   - Add your `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) to the respective folders.

5. Replace the API key placeholder in the configuration file with your OpenDB API key:
   ```dart
   const String openDbApiKey = 'YOUR_API_KEY';
   ```

6. Run the app:
   ```bash
   flutter run
   ```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a pull request.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Dhanush Rajavel - [LinkedIn](https://www.linkedin.com/in/dhanush-rajavel-070ba7225/) - dhanushrajavel24@gmail.com

Project Link: [GitHub Repository](https://github.com/DhanushRajavel/Quiz-Upp)
```

This README includes an overview of your app, the technologies used, and details about the OpenDB API. Adjust any placeholders with your actual details and project links.
