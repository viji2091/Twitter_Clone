# Project Name
Twitter Clone
## Description  
A UI clone of Twitter

## Installation

To install the necessary dependencies, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/viji2091/Twitter_Clone.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd your-repository
    ```

3. **Install the dependencies**:

    ```bash
    npm install
    ```

4. **Install Tailwind CSS** (if not already included in the dependencies):

    ```bash
    npm install tailwindcss
    ```


## Using Tailwind CSS

This project uses [Tailwind CSS](https://tailwindcss.com/). Tailwind is a utility-first CSS framework that provides low-level utility classes to build custom designs.

To start using Tailwind CSS:

1. **Ensure Tailwind CSS is installed**:

    ```bash
    npm install tailwindcss
    ```

2. **Create your `tailwind.config.js` file**:

    ```bash
    npx tailwindcss init
    ```

3. **Include Tailwind in your CSS**:

    In your main CSS file (e.g., `src/styles.css`), include the following:

    ```css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```

4. **Build your CSS**:

    Run the Tailwind CLI tool to compile your CSS:

    ```bash
    npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
    ```


