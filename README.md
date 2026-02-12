# Jengo Inertia

**Jengo Inertia** seamlessly integrates [Inertia.js](https://inertiajs.com/) with **CodeIgniter 4**, allowing you to build modern single-page apps using classic server-side routing and controllers.

## 🚀 Features

-   **Automatic Setup**: Comes with a dedicated installer to set up Vue, React, or Svelte.
-   **Vite Integration**: Powered by `jengo/base` and `@jengo/vite` for a modern build experience.
-   **Server-Side Routing**: Use standard CI4 routing and controllers.

## 📦 Installation

1.  **Require the packages:**

    ```bash
    composer require jengo/base jengo/inertia
    ```

2.  **Run the Vite installer (Required first):**

    ```bash
    php spark jengo:install vite
    ```

    This sets up the necessary `package.json` and Vite configuration foundation.

3.  **Run the Inertia installer:**

    ```bash
    php spark jengo:install inertia
    ```

    The installer will guide you through:
    -   Selecting your framework (Vue, React, Svelte).
    -   Installing necessary NPM dependencies.
    -   Scaffolding your entry points and views.

## 📚 Documentation

For more information on the Jengo installer system and base configurations, please visit the **[jengo/base](https://github.com/jengo/base)** repository.

## 🧑‍💻 Credits

This package is a fork of [`fabithub/inertia-ci4`](https://github.com/fabithub/inertia-ci4).

### Original Authors:

-   Fab IT Hub
-   Krishna Gujjjar

### Fork Maintainer:

-   JengoPHP
-   Ian Ochieng

## 📄 License

This project is open-sourced under the MIT license.
