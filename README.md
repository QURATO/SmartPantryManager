# Smart Pantry Manager

A Java Android application designed to reduce household food waste by tracking leftover pantry ingredients and suggesting recipes using a strict ingredient-matching rule.

## Features
- **Pantry Management:** Full CRUD operations (Add, Edit, Delete ingredients with quantities, units, and expiry dates).
- **Strict-Matching Recipe Suggestions:** Suggests recipes only if 100% of required ingredients are present in the pantry in required quantities.
- **Data Persistence:** Uses SQLite for reliable on-device dynamic data storage.

## Database Justification
SQLite was selected using `SQLiteOpenHelper` because it provides zero-configuration, reliable local relational data storage on the device without requiring cloud connectivity or external server overhead.

## Setup & Run Instructions
1. Clone this repository: `git clone https://github.com/yourusername/SmartPantryManager.git`
2. Open the project in **Android Studio**.
3. Sync project with Gradle files.
4. Select an Android Virtual Device (Emulator) running API Level 26 or higher.
5. Click **Run** (`Shift + F10`).
