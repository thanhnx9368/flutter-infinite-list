# flutter_infinite_list

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Project Structure

├── lib
| ├── posts
│ │ ├── bloc
│ │ │ └── post_bloc.dart
| | | └── post_event.dart
| | | └── post_state.dart
| | └── models
| | | └── models.dart*
| | | └── post.dart
│ │ └── view
│ │ | ├── posts_page.dart
│ │ | └── posts_list.dart
| | | └── view.dart*
| | └── widgets
| | | └── bottom_loader.dart
| | | └── post_list_item.dart
| | | └── widgets.dart*
│ │ ├── posts.dart*
│ ├── app.dart
│ ├── simple_bloc_observer.dart
│ └── main.dart
├── pubspec.lock
├── pubspec.yaml
