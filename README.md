# Currency Converter App (USD to NGN)

## Overview

This Currency Converter App is a simple Flutter application that allows users to convert American Dollars (USD) to Nigerian Naira (NGN) without relying on an external currency converter API. Instead, it calculates the converted amount by multiplying the user-input USD amount by the current dollar-to-naira exchange rate.

## Screenshots


https://github.com/emekss/Currency_Converter_App/assets/110977719/9c759d2b-cf5c-416d-bba4-f259ba75b6ed



## Features

1. **User-Friendly Interface**: The app provides an easy-to-use interface for users to input the amount they want to convert from USD to NGN.

2. **Real-Time Exchange Rate**: The app retrieves the current dollar-to-naira exchange rate and uses it to calculate the converted amount.

3. **Conversion Result**: After the conversion, the app displays the converted amount in Nigerian Naira.

## Getting Started

Follow the steps below to set up and run the Currency Converter App on your Flutter development environment.

### Prerequisites

- Make sure you have [Flutter](https://flutter.dev/docs/get-started/install) installed on your computer.
- A code editor (e.g., Visual Studio Code, Android Studio) is recommended for a smoother development experience.

### Installation

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/yourusername/currency_converter_app.git
   ```

2. Navigate to the project folder:

   ```shell
   cd currency_converter_app
   ```

3. Install the project dependencies:

   ```shell
   flutter pub get
   ```

### Usage

1. Run the app on an emulator or physical device:

   ```shell
   flutter run
   ```

2. Input the amount in American Dollars that you want to convert to Nigerian Naira.

3. Press the "Convert" button, and the converted amount will be displayed.

## Project Structure

The project structure is organized as follows:

- `lib`: Contains the Dart code for the Currency Converter App.
  - `main.dart`: The main entry point for the application.
  - `screens`: Contains screen-related code.
  - `widgets`: Contains custom widgets used in the app.

## Dependencies

- [http](https://pub.dev/packages/http): Used for making HTTP requests to fetch the current exchange rate.
- [flutter_spinkit](https://pub.dev/packages/flutter_spinkit): Provides loading spinners for better user experience.

## Notes

- The app fetches the current exchange rate from a reliable source and may require periodic updates as exchange rates change.

## Feedback and Support

If you encounter any issues or have suggestions for improvement, please feel free to create an issue on the project's GitHub repository or contact the developer at your@email.com.

Thank you for using the Currency Converter App! We hope it serves your currency conversion needs effectively.
