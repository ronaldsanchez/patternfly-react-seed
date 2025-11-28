# Soficoop UI Project

This project serves as an initial template for building Angular applications with PrimeNG and PrimeFlex.

## Installation

1.  **Clone the repository:**
    ```bash
    git clone [repository_url] soficoop-ui
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd soficoop-ui
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    ```

## Usage

1.  **Run the development server:**
    ```bash
    npm start
    ```
    This will compile the application and open it in your browser (usually at `http://localhost:4200/`).

2.  **Build for production:**
    ```bash
    npm run build
    ```
    The production-ready files will be located in the `dist/sakai-ng` directory.

## Project Structure

The project follows a standard Angular CLI structure. Key directories include:

-   `src/app`: Contains the application's main logic and components.
    -   `layout`: Core layout components (topbar, sidebar, menu, etc.).
    -   `pages`: Individual application pages (dashboard, authentication, etc.).
    -   `assets`: Static assets like images, styles, and fonts.
-   `src/assets/layout`: SCSS files for layout styling.

## Customization

-   **Theming:** Customize the application's theme by modifying the SCSS variables in `src/assets/layout/variables/_variables.scss` or by adjusting the theme settings in `app.configurator.ts`.
-   **Components:** Develop new components within the `src/app` directory, following existing conventions.
-   **Pages:** Add new pages under `src/app/pages` and configure their routes in `src/app/app.routes.ts` or respective feature routing modules.

## Important Notes

-   This project uses Angular standalone components.
-   Inline templates and styles have been extracted into separate `.html` and `.scss` files for better maintainability.
-   Node.js version 18 or higher is recommended.