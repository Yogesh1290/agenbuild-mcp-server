# AgenBuild MCP Bridge Server Setup

This folder contains everything you need to run the local server for real-time file syncing with the AgenBuild AI Code Assistant.

## Quick Setup

1.  **Unzip:** Unzip this file in the directory where you keep your projects (e.g., `~/dev/` or `C:\Users\YourUser\Projects\`). This will create an `agenbuild-mcp-server` folder.

2.  **Install Dependencies:** Open a terminal, navigate into the new `agenbuild-mcp-server` folder, and run:
    ```bash
    npm install
    ```
    This will install the necessary `ws` package defined in `package.json`.

3.  **Run the Server:** Start the server with:
    ```bash
    npm start
    ```
    (or `node mcp-server.js`)

That's it! The server is now running. The "Local Sync" indicator in the AgenBuild app should turn green.


## License
This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.
