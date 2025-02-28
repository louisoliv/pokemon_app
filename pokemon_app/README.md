# Pokedex Flutter App

This project is a Flutter application that displays the first 151 Pokémon along with their details. It fetches data from an API and presents Pokémon information in an interactive UI.

## Prerequisites

Before running this project, ensure you have the following installed:

### 1. Install Flutter

Install Flutter depending on which os you are can be a though road so be sure to read the documentation or some tutorials.

## Running the Project

Once Flutter is installed, follow these steps to run the Pokedex app:

### 1. Clone the Repository

```sh
git clone https://github.com/louisoliv/pokemon_app.git
cd pokemon_app
```

### 2. Install Dependencies

Run the following command to install the required dependencies:

```sh
flutter pub get
```

### 3. Run the App

To launch the app on an emulator or physical device:

```sh
flutter run
```

#### Running on Physical Android device

1. Connect your Android device to the computer with a cable
2. In your phone options, make sure that the **developper tools** are set up
3. Once done, run the project and wait to see it appears

#### Running on Android Emulator

1. Open Android Studio
2. Start an Android emulator from AVD Manager
3. Run `flutter run` in the terminal

#### Running on iOS Simulator (Mac Only)

1. Open Xcode and set up the iOS simulator
2. Run `flutter run` in the terminal

## Features

- Fetches data from an API
- Displays 151 Pokemon with their details
- Interactive UI with smooth animations

## API Used

This project fetches Pokemon data from a GitHub api :
[API](https://raw.githubusercontent.com/Biuni/PokemonGO-Pokedex/master/pokedex.json)

## License

This project is open-source and available under the [MIT License](LICENSE).
