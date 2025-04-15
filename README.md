# Dysgraphia
Helping kids to improve their handwriting.
sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\nautorefresh=1\ntype=rpm-md\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" | sudo tee /etc/yum.repos.d/vscode.repo > /dev/null
flutter pub get 
flutter run 
# Dysgraphia Assistant

A Python tool that listens for the `Ctrl+T` shortcut to trigger user input prompts. Designed to assist with workflows requiring quick text interactions.

## Features
- **Hotkey Support**: Trigger prompts with `Ctrl+T`
- **Simple Input Handling**: Type directly into the console
- **Auto-Dismiss**: Input field closes after submission

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/dysgraphia-assistant.git
