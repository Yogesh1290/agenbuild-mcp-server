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

Here’s the exact **README.md** text you can use to match the style shown in your screenshot 👇

---

```markdown
# Example Project in VS Code

Once the MCP Bridge is running, the AI can create and manage a project directly in your local directory. Your workspace in an editor like VS Code will look something like this, with the AI handling the creation of a clean, multi-file architecture based on your requests.

```

my-nextjs-app/
├── node_modules/
├── src/
│   ├── app/
│   │   ├── layout.tsx
│   │   └── page.tsx
│   └── components/
│       └── header.tsx
├── .gitignore
├── next.config.js
├── package.json
├── README.md
├── tailwind.config.ts
├── tsconfig.json
├── mcp-server.js
├── node_modules/
├── package.json
├── package-lock.json
└── README.md

```
---

Would you like me to make this README look **more styled** (for example, with emojis, colors using Markdown tricks, or sections like *“Installation”* and *“Usage”*)?
```



## License
This MCP server is released under the **CC BY-NC 4.0** license.

You are free to use and modify this project for personal and educational purposes only.  
Commercial use, resale, or integration into paid products is **not permitted**.

