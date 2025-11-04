# Flutter Todo App

A simple, offline-capable todo list application built with Flutter using local state management.

## Features

- Add new tasks
- Mark tasks as completed
- Delete tasks
- Clean and intuitive user interface
- Efficient list rendering using ListView.builder

## Technical Implementation

The app demonstrates the following Flutter concepts:
- `StatefulWidget` for maintaining local state
- `ListView.builder()` for efficient list rendering
- `setState()` for state management and UI updates
- Custom widgets for better code organization

## Project Structure

```
lib/
  ├── main.dart           # App entry point
  ├── models/            
  │   └── todo.dart       # Todo item model
  ├── screens/
  │   └── home_screen.dart # Main todo list screen
  └── widgets/
      └── todo_item.dart   # Individual todo item widget
```

## Key Components

1. **Todo Model** (`lib/models/todo.dart`)
   - Represents a single todo item
   - Contains properties: id, title, isCompleted

2. **Home Screen** (`lib/screens/home_screen.dart`)
   - Main screen with the todo list
   - Manages state using setState()
   - Handles adding, toggling, and deleting todos

3. **Todo Item Widget** (`lib/widgets/todo_item.dart`)
   - Reusable widget for displaying individual todo items
   - Handles todo completion toggling and deletion

## Getting Started

1. Clone the repository
2. Run `flutter pub get` to install dependencies
3. Run `flutter run` to start the app

## Dependencies

- Flutter SDK
- No additional packages required (using pure Flutter)

## How It Works

The app uses Flutter's built-in state management with `setState()` to maintain the list of todos. The main state is handled in the `HomeScreen` widget, which passes down callbacks to child widgets for updating the state.

## Screenshots

(Screenshots will be added after implementation)

## Contributing

Feel free to submit issues and enhancement requests.
