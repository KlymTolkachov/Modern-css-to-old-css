# CSS Compiler

CSS Compiler is a simple tool that processes modern CSS into a format compatible with older browsers. It uses PostCSS with plugins like `postcss-nested` and `autoprefixer` to handle nested rules and add vendor prefixes.

## Features

-   **Nested CSS**: Write CSS with nested rules using `postcss-nested`.
-   **Autoprefixing**: Automatically add vendor prefixes for better browser compatibility using `autoprefixer`.

## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd CSS-compiler
    ```
2. Install dependencies:
    ```sh
    npm install
    ```

## Usage

1. Add your CSS code to the `in/style.css`.
2. Run the compiler:
    ```sh
    npm run build:css
    ```
3. The processed CSS will be saved in `out/style.css`.

## Requirements

-   Node.js version 14 or newer.
-   npm for dependency installation.

## License

This project is licensed under the MIT License.
