# Daayata Anime App

A modern Flutter application for streaming anime episodes with YouTube integration. This app provides a beautiful and intuitive interface for watching your favorite anime shows.

## Features

- YouTube video integration for streaming anime episodes
- Beautiful and modern UI with dark theme
- Navigation drawer for easy access to different sections
- Home screen with featured content and categories
- Favorites section to save your favorite episodes
- Search functionality to find specific anime
- Responsive design that works on all screen sizes

## Getting Started

### Prerequisites

- Flutter SDK (>=3.0.0)
- Dart SDK (>=3.0.0)
- Android Studio / VS Code with Flutter extensions
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/daayata_anime_app.git
```

2. Navigate to the project directory:
```bash
cd daayata_anime_app
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the app:
```bash
flutter run
```

## Project Structure

```
lib/
  ├── main.dart              # Main entry point of the app
  ├── screens/               # Screen widgets
  │   ├── home_screen.dart   # Home screen with featured content
  │   ├── video_player_screen.dart  # YouTube video player
  │   ├── favorites_screen.dart     # Saved episodes
  │   └── search_screen.dart        # Search functionality
  └── widgets/               # Reusable widgets
```

## Dependencies

- youtube_player_flutter: ^8.1.2
- cached_network_image: ^3.3.0
- shared_preferences: ^2.2.2
- provider: ^6.0.5

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Flutter team for the amazing framework
- YouTube Player Flutter package contributors
- All other open-source contributors
