## Reference page for general design rules.
---

#### If you want to make changes to the page you will need to run the Tailwind CLI tool.
1. Download the Tailwind CLI tool.
    * https://github.com/tailwindlabs/tailwindcss/releases/
2. Place the CLI in the project directory.
3. Open a terminal or command prompt in the directory and run these commands as needed:
    * To generate the CSS rules file once you have made changes.
        ```
        <CLI-tool-file-name> style.css
        ```
    * To watch for file changes and automatically regenerate the CSS rules.
        ```
        <CLI-tool-file-name> style.css --watch
        ```
    * To generate the CSS rules file minified.
        ```
        <CLI-tool-file-name> style.css --minify
        ```
