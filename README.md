# TimeConverter - SwiftUI iOS App ⏳

## 📌 Project Overview
**TimeConverter** is a streamlined iOS application built entirely with SwiftUI. It provides a clean, user-friendly interface for instantly calculating and converting time values across various units, making it easy to translate seconds into months, days into minutes, and everything in between.

## 🌟 Key Features
* **Real-Time Conversion:** Calculates and displays the converted value dynamically as the user types.
* **Comprehensive Time Units:** Supports seamless conversions between Seconds, Minutes, Hours, Days, Weeks, and Months.
* **Optimized Input:** Utilizes a dedicated decimal pad keyboard (`.decimalPad`) to ensure quick and accurate numeric data entry.
* **Interactive UI:** Features easy-to-tap segmented pickers (`SegmentedPickerStyle`) for rapidly swapping both input and output units.

## 🛠️ Technologies Used
* **Swift 5 & SwiftUI:** Used to build a fully declarative and responsive user interface.
* **Xcode:** Native iOS development environment.

## 🧠 Developer Highlights
This project demonstrates a strong grasp of foundational Swift and SwiftUI concepts:
* **State Management:** Effective use of `@State` property wrappers (`inputValue`, `inputUnitIndex`, `outputUnitIndex`) to manage the app's data and keep the UI in perfect sync.
* **Computed Properties & Logic:** Implemented a robust `convertedValue` computed property that centralizes the conversion math. It uses `switch` statements to first translate the input into a base unit (seconds) and then dynamically converts it to the target output unit.
* **String Formatting:** Used string specifiers (`"%.2f"`) to cleanly format the final output to a readable two decimal places.
* **View Composition:** Built a clean, scalable vertical layout using `VStack`, `TextField`, `Picker`, and `Spacer` components.

## 🚀 How to Run Locally
1. Clone this repository to your local machine.
2. Open the project directory in Xcode.
3. Select an iOS simulator (e.g., iPhone 15 Pro) and hit **Run (Cmd + R)** to launch the `UnitConverterApp`.
