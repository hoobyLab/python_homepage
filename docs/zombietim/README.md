# 🧟 Zombie Tim: Your Undead AI Assistant

Zombie Tim is a smart, tech-loving zombie assistant built with Flutter and Flame. Whether you want to chat about coding, learn new words, or just hang out with an undead companion, Tim is here for you!

## 🚀 Features

- **AI Chat:** Interact with Zombie Tim, an AI with a unique "undead technophile" personality.
- **Flame Avatars:** Beautifully animated avatars for both the user and Tim, powered by the Flame game engine.
- **Dictionary & Learning:** Explore words with Tim's integrated dictionary and passive learning services.
- **Themed UI:** A dark, atmospheric interface that fits the zombie aesthetic.
- **Multi-platform:** Supports Android, iOS, Web, Linux, macOS, and Windows.

## 🛠 Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (>= 3.0.0)
- [Make](https://www.gnu.org/software/make/) (optional, for using the provided Makefile)

## 📦 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-repo/flutter-zombieTim.git
    cd flutter-zombieTim
    ```

2.  **Install dependencies:**
    ```bash
    make get-dependencies
    ```
    *Or run `flutter pub get` manually.*

3.  **Run the app:**
    ```bash
    make run-linux # Or run-android, run-ios, etc.
    ```
    *Or run `flutter run` manually.*

## 🧪 Testing & Linting

Run tests to ensure everything is working correctly:
```bash
make unit-tests
```

Analyze the code for potential issues:
```bash
make lint
```

## 🏗 Building

The project includes a comprehensive `Makefile` to simplify builds across different platforms, including cross-compilation helpers for macOS/iOS using Podman.

- **Android:** `make build-apk`
- **Linux:** `make build-linux`
- **Web:** `make build-web`

For more build options, run `make help`.

## 📄 License

See the [LICENSE](LICENSE) file for details.
