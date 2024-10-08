
# ChatGPT History Viewer

A standalone HTML viewer for displaying ChatGPT conversation history without requiring a Python server. This application lets you view and browse through ChatGPT conversations stored in a local `conversations.json` file.

![ChatGPT History Viewer Screenshot](image.png)

## Features
- **Load and display ChatGPT conversations** stored in a `conversations.json` file.
- **Syntax highlighting** for code blocks using `highlight.js`.
- **Copy code snippets** directly from the viewer.
- **User-friendly UI** built with Tailwind CSS.
- **Standalone operation**—works offline without needing a Python server.

## How to Use
### 1. Clone the Repository:
```bash
git clone https://github.com/remonusa/LoadChatGptHistory.git
cd LoadChatGptHistory
```

### 2. Open the `index.html` file:
```bash
# Open `index.html` using your default browser:
open index.html  # MacOS
start index.html # Windows
```

### 3. Upload a `conversations.json` file:
- Use the **file upload button** on the left sidebar to select a valid ChatGPT history file.

## How to Download Your ChatGPT History in `conversations.json` Format
To download your ChatGPT chat history in the correct `conversations.json` format:

1. **Sign in to ChatGPT** at [chat.openai.com](https://chat.openai.com).
2. **Click on your profile icon** in the top right corner.
3. Go to **Settings** and click **Data Controls**.
4. Under **Export Data**, select **Export**.
5. Confirm the export, and you’ll receive an email with a link to download your data.
6. Download the `.zip` file and extract it. Inside, you’ll find `conversations.json`—the file our HTML page needs for local viewing.

### 4. Place the file in the same directory as `index.html` or use the file upload button:
- The viewer will automatically read and display the data when the file is uploaded using the built-in file selector.

## Contributing
Feel free to fork the repository and submit pull requests. Any improvements and suggestions are welcome!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
