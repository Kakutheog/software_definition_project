**My Development Environment:**

- Windows 11
    
- Targetting a desktop application (using a framework like Electron is acceptable)
    

**Software Project: Personal Home Service Management**

This software is for personal use and will not be distributed commercially. It should leverage free and open-source tools, libraries, and APIs wherever possible.

**Key Components:**

1. **AI-Powered Chat Interface:** This conversational interface allows users to interact naturally with the AI, submitting requests and instructions in plain English (or other supported natural languages). The AI should interpret these instructions and generate, modify, or explain code.
    
2. **Multi-Tab Interface:** This interface offers a visually organized project workspace divided into tabs:
    
    - **Code Editor:** A dedicated code editor with syntax highlighting, autocompletion (potentially enhanced by the AI), and the ability to directly execute code snippets for testing. Show the code the AI is generating here in real-time.
        
    - **File Explorer:** A file system view of the project, mirroring the project directory on my computer. The AI should be able to create, read, update, and delete files and folders in this directory based on user instructions.
        
    - **Software Preview (Optional, but preferred):** A live, interactive preview of the software being developed. This allows for immediate feedback on UI changes and functional testing.
        

**Core Functionality:**

- **Code Generation & Modification:** The AI should be able to generate code in various languages (primarily JavaScript/TypeScript for the frontend and Python for the backend) based on user requests. It should also be capable of modifying existing code based on instructions like "Refactor this function to be more efficient" or "Add input validation to this form."
    
- **File & Folder Management:** The AI should be able to create new files and folders, write content to files, read file contents, and delete files and folders within the designated project directory, all through natural language instructions given through the chat interface.
    
- **GitHub Integration (Optional):** If possible, the AI should be able to interact with GitHub, allowing users to clone repositories, commit changes, and push updates.
    

**Example Workflow:**

A user might type into the chat interface, "Create a new React component called TaskForm with input fields for task name, due date, and priority." The AI should then generate the necessary code for this component, display it in the Code Editor tab, and update the File Explorer to reflect the new file. If a Software Preview tab is available, the new component should be rendered in the preview.

**Specific Prompts and Instructions for the AI:**

This is where we'll focus our collaboration. We'll develop a series of increasingly complex prompts and instructions to guide the AI through the development process, covering scenarios like:

- Creating basic UI elements (buttons, input fields, etc.)
    
- Implementing simple logic (e.g., adding two numbers, validating an email address)
    
- Integrating with open-source libraries (e.g., date pickers, charting libraries)
    
- Handling file system operations (creating files, reading data from files)
    
- Managing application state
    
- (Optionally) Interacting with GitHub
    

**Open-Source Libraries and APIs (Examples):**

While we can specify some libraries upfront, the AI should also be encouraged to suggest appropriate libraries based on the project needs.

- **Frontend (JavaScript/TypeScript):** React, Redux, Material UI, Axios
    
- **Backend (Python):** Flask, SQLAlchemy, PyGithub
    
- **Other:** Electron (for desktop application)