shadow_guardian/
│
├── .github/
│   └── workflows/
│       └── flutter.yml
│
├── android/
├── ios/
├── web/
├── windows/
├── linux/
├── macos/
│
├── assets/
│   ├── images/
│   │   ├── player/
│   │   ├── enemies/
│   │   ├── bosses/
│   │   ├── ui/
│   │   ├── backgrounds/
│   │   └── effects/
│   │
│   ├── audio/
│   │   ├── music/
│   │   └── sfx/
│   │
│   ├── fonts/
│   └── animations/
│
├── lib/
│   ├── main.dart
│   │
│   ├── game/
│   │   ├── shadow_guardian_game.dart
│   │   ├── camera.dart
│   │   ├── collision.dart
│   │   └── world.dart
│   │
│   ├── player/
│   │   ├── hero.dart
│   │   ├── movement.dart
│   │   ├── combat.dart
│   │   ├── abilities.dart
│   │   └── upgrades.dart
│   │
│   ├── enemies/
│   │   ├── raider.dart
│   │   ├── cyber_guard.dart
│   │   ├── assassin.dart
│   │   ├── drone.dart
│   │   └── brute.dart
│   │
│   ├── bosses/
│   │   ├── volt_king.dart
│   │   ├── steel_titan.dart
│   │   ├── phantom_lord.dart
│   │   └── nexus_overlord.dart
│   │
│   ├── levels/
│   │   ├── level1.dart
│   │   ├── level2.dart
│   │   ├── level3.dart
│   │   ├── missions.dart
│   │   └── map_loader.dart
│   │
│   ├── ui/
│   │   ├── home_screen.dart
│   │   ├── pause_menu.dart
│   │   ├── settings.dart
│   │   ├── hud.dart
│   │   └── joystick.dart
│   │
│   ├── services/
│   │   ├── audio_service.dart
│   │   ├── save_service.dart
│   │   └── preferences.dart
│   │
│   └── utils/
│       ├── constants.dart
│       ├── helpers.dart
│       └── extensions.dart
│
├── test/
├── pubspec.yaml
├── analysis_options.yaml
├── README.md
├── CHANGELOG.md
├── LICENSE
└── .gitignore
# Shadow Guardian

Shadow Guardian is an offline Android action game built with Flutter and the Flame Engine.

## Features

- Offline gameplay
- Original superhero
- Story missions
- Boss battles
- Character upgrades
- Save progress locally

## Requirements

- Flutter SDK
- Android Studio
- Flame Engine

## Run

flutter pub get
flutter run

## Build APK

flutter build apk --release
.dart_tool/
build/
.idea/
.vscode/
.gradle/
android/.gradle/#bf1616
android/local.properties
*.iml
shadow-guardian
#goggleplaystation,export#@Playstore
#nexus_overlord
