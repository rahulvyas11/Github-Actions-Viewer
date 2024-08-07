# Github Actions Viewer
 ## Flutter Desktop GitHub Integration App

Welcome to my Flutter Desktop GitHub Integration App! This project leverages Flutter, Google's UI toolkit, to build a beautiful, natively compiled application for desktop environments. The app connects to GitHub APIs to retrieve repositories, assigned issues, and pull requests, providing a seamless integration with GitHub. Through this application, you'll experience the power of Flutter in creating cross-platform desktop applications with native API interactions.

## What I Learned
- Creating a Flutter Desktop Application: Understand how to build and run a Flutter app on desktop platforms.
- OAuth2 Authentication: Implement OAuth2 authentication to securely access GitHub.
- Using the Dart GitHub Package: Learn to retrieve and handle data from GitHub using the Dart GitHub package.
- Creating Flutter Plugins: Develop plugins to integrate with native APIs on Windows, macOS, and/or Linux.
- Hot Reloading Flutter UI: Utilize Flutter's hot reload feature to quickly iterate on your desktop application's UI.

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- A GitHub account
- [Git](https://git-scm.com/)
- [Dart GitHub package](https://pub.dev/packages/github)

### Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/your-repository.git
    cd your-repository
    ```

2. **Install dependencies:**

    ```sh
    flutter pub get
    ```

3. **Set up OAuth2 credentials:**

    - Create a new OAuth application on GitHub.
    - Set the callback URL to `http://localhost:PORT/callback` (replace `PORT` with the port your app will run on).
    - Copy the Client ID and Client Secret to your application.

4. **Run the application:**

    ```sh
    flutter run -d windows
    ```

    *Replace `windows` with `macos` or `linux` depending on your operating system.*
