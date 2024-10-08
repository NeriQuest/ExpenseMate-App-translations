# ExpenseMate App

# App Translations

This repository contains the translation files for the ExpenseMate Flutter application. We welcome contributions to help translate the app into different languages.

## Folder Structure

- `l10n/`
  - `intl_en.arb`
  - `intl_hi.arb`
  - `intl_ml.arb`
  - `intl_ta.arb`
  - `intl_te.arb`
  - `intl_kn.arb`
  - ...

## Contributing to translations

Please see the below guidelines on how to contribute translations.

## How to Contribute

1. **Fork the Repository**:
    - Click on the `Fork` button at the top right of this page to create a copy of this repository on your GitHub account.

2. **Clone the Repository**:
    - Clone your forked repository to your local machine:
    ```bash
    git clone https://github.com/NeriQuest/ExpenseMate-App-translations.git
    cd l10n
    ```

3. **Create a New Branch**:
    - Create a new branch for your translation work:
    ```bash
    git checkout -b add-spanish-translation
    ```

4. **Add or Update Translations**:
    - Navigate to `l10n/` and add or update the `.arb` files. Use the existing `intl_en.arb` as a reference.
    - Example for Spanish: `intl_es.arb`

5. **Commit and Push**:
    - Commit your changes and push the branch to your forked repository:
    ```bash
    git add .
    git commit -m "Added Spanish translation"
    git push origin add-spanish-translation
    ```

6. **Create a Pull Request**:
    - Go to the original repository and create a pull request from your branch.

## Naming Conventions

- Use `intl_<language-code>.arb` for translation files, e.g., `intl_es.arb` for Spanish.

Thank you for contributing!
