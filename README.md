# Android Countdown Timer Example

This is a simple Android application that demonstrates the use of a **CountDownTimer** to create a countdown timer. The app starts a 10-second countdown when launched and updates a **TextView** with the remaining time. When the countdown finishes, it displays a **Toast** message and updates the **TextView** to indicate that the timer has finished.

## Features
- A 10-second countdown timer.
- Updates the displayed time every second.
- Displays a **Toast** message when the countdown finishes.
- Basic UI management with **EdgeToEdge** and **WindowInsetsCompat** for immersive system bars handling.

## Technologies Used
- **Android Studio**
- **Java**
- **CountDownTimer** for managing the countdown.
- **Toast** for notifications when the countdown is complete.
- **EdgeToEdge** and **WindowInsetsCompat** for immersive UI experience.

## Code Overview

### Main Components
1. **MainActivity**:
   - Initializes a **CountDownTimer** that counts down from 10 seconds, updating the **TextView** every second.
   - When the timer finishes, it shows a "done" **Toast** message and updates the **TextView** to display "Finished".
   - **onTick(long l)**: Updates the **TextView** with the remaining time in seconds.
   - **onFinish()**: Displays a **Toast** and updates the **TextView** when the countdown completes.

### Layout
- The layout includes a **TextView** to display the remaining time during the countdown.
- The **TextView** is updated every second until the countdown finishes.

## Getting Started

### Prerequisites
To run this project, you need:
- Android Studio installed on your computer.
- Basic knowledge of Kotlin/Java and Android development.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/blueyes0101/CountdownTimerAndroid.git
    ```

2. Open the project in Android Studio.

3. Build and run the project on an emulator or physical device.

## Usage

1. When the app is launched, a 10-second countdown starts automatically.
2. The remaining time is displayed in the **TextView** and updated every second.
3. Once the countdown finishes, a **Toast** message "done" is displayed, and the **TextView** shows "Finished".

## Contributing
Feel free to contribute by opening issues or submitting pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
