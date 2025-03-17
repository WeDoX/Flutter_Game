# flutter_game

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.




在Flutter环境：
flutter_windows_3.29.2-stable下可运行，需升级NDK和CMake工具

Android Studio版本：
Android Studio Flamingo | 2022.2.1 Patch 1


没声音的原因：
由于assets目录下没有声音资源，所以为了把游戏运行起来，
在lib\game\utils\audio_manager.dart文件中注释掉了声音工具类加载播放声音的逻辑


原工程：
https://github.com/ufrshubham/flame_simple_platformer

