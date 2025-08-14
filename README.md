# Anki Power-Up Add-ons

A collection of powerful add-ons to enhance your Anki learning experience, including an automatic translator and Quizlet-style learning modes.

![Anki Power-Up Demo](https://github.com/user-attachments/assets/6a8c18ff-d936-442a-afae-de04c2469f6f)

---

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Auto Translate](#auto-translate)
  - [Learn Mode (Quizlet Style)](#learn-mode-quizlet-style)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **Auto Translate**:

  - Adds a translation utility directly into the Anki editor.
  - Select source and destination languages from a dropdown.
  - Translates content from the first field to the second with a single click.
  - Saves your last used language pair for convenience.

- **Learn Mode (Quizlet Style)**:
  - Adds a new "Learn Mode" menu to the Card Browser.
  - **Multiple Choice Mode**: Test yourself with auto-generated multiple-choice questions from your selected cards.
  - **Written Mode**: Practice by typing out the answers, just like in Quizlet's "Learn" or "Write" modes.
  - Customizable sessions: Choose which fields to use for questions/answers and how many cards to study.

---

## Installation

1.  **Close Anki**: Ensure Anki is completely closed before installing.

2.  **Open the Add-ons Folder**:

    - Start Anki, then go to `Tools` > `Add-ons`.
    - Click the `View Files` button.

3.  **Copy Add-on Folders**:

    - Unzip the project files if you haven't already.
    - Copy the `anki_auto_translate` and `anki_learn_mode` folders into the `addons21` folder that you just opened.

4.  **Restart Anki**: Start Anki again. The add-ons will be loaded and ready to use.

---

## Usage

### Auto Translate

The Auto Translate utility is available directly in the Anki **Editor** window (when adding or editing a card).

1.  **Open the Editor**: Click "Add" to create a new card or select a card and click "Edit".
2.  **Find the Translate UI**: A new toolbar will appear below the standard formatting buttons.
3.  **Select Languages**: Choose your source language (e.g., "English") and destination language (e.g., "Vietnamese") from the dropdown menus.
4.  **Enter Text**: Type the word or phrase you want to translate into the first field (e.g., "Front").
5.  **Click Translate**: Press the **"Translate"** button. The translated text will automatically appear in the second field (e.g., "Back").

![Auto Translate UI](https://github.com/user-attachments/assets/01734b52-4883-4097-83cf-9a8df73bf719)

### Learn Mode (Quizlet Style)

The Learn Mode is accessible from the Anki **Card Browser**.

1.  **Open the Browser**: From the Anki main window, click "Browse".
2.  **Select Cards**: In the browser, select the cards you wish to study. You must select at least **4 cards** for the modes to work.
3.  **Open Learn Mode Menu**: A new menu named **"Learn Mode"** will be visible in the top menubar.
4.  **Choose a Mode**:
    - Click `Learn Mode` > `Learn: Multiple Choice...` to start a quiz.
    - Click `Learn Mode` > `Learn: Written...` to start a writing practice session.
5.  **Configure Your Session**: A dialog will appear, allowing you to:
    - Select the field for the **Question** (e.g., "Front").
    - Select the field for the **Answer** (e.g., "Back").
    - Set the number of cards for the session.
6.  **Start Learning**: Click "OK" to begin your session in a new window.

![Learn Mode Menu](https://github.com/user-attachments/assets/b086358b-9e19-40a2-bdd0-71f36e96b8c4)

---

## Configuration

- **Auto Translate**: The add-on automatically saves the last selected source and destination languages.
- **Learn Mode**: Session settings (fields, number of questions) are configured each time you start a new session.

---

## Contributing

Contributions are welcome! If you have ideas for new features, improvements, or bug fixes, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourAmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some YourAmazingFeature'`).
4.  Push to the branch (`git push origin feature/YourAmazingFeature`).
5.  Open a Pull Request.

---

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
