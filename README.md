# terminal
terminal scaffolding

### **Task Checklist: Scaffolding for Terminal Web App**

#### **1. General Setup**
- Set up a **terminal-style UI** inspired by m4tt72's terminal.
- Add the **glitch effect** on page load.
- Implement a **username setup prompt** (`$set-username:`) where users can set and save their username in session storage or a placeholder variable for now.

---

#### **2. Basic Navigation and Commands**
- Create a placeholder structure for navigating between levels:
  - `username@localhost/market-category`  
  - `username@localhost/market-category/market`
- Add placeholders for the **`cd ..`** and **`exit`** commands:
  - `cd ..`: Navigate to the previous level.
  - `exit`: Ends the terminal session and clears the screen.

---

#### **3. Command Scaffolding**
- Implement placeholder functions for these commands:
  - **`echo [text]`**: Repeat the entered text back to the user.
  - **`username`**: Display and allow updating of the current username.
  - **`satoshi`**: Start a basic chat session using a mock AI agent.
    - Set up a basic interface for user input and bot response.
    - Use dummy responses to simulate the chat functionality for now.
  - **`betbtc`**: Add a placeholder for listing categories (no API integration yet).  
    - Set up basic arrow key navigation for selecting categories and markets.
    - Use static data for categories and markets as placeholders.

---

#### **4. Arrow Key and Enter Navigation**
- Implement functionality for:
  - Navigating categories and markets using **up/down arrow keys**.
  - Finalizing a selection with the **Enter key**.
- Display visual prompts like:
  - `"Use ↑/↓ to navigate, Enter to select"`.

---

#### **5. Visual Prompts**
- Add dynamic prompts based on the context:
  - In the market environment, display instructions like:
    - `"Type 'volume' to see market volume, 'cd ..' to go back."`

---

#### **6. Placeholder AI Agent**
- Set up a basic AI agent using an open-source model or library.
- Add a placeholder function for the `satoshi` command that:
  - Takes user input and provides hardcoded or simple responses for now.
  - Prepares for future integration with an advanced AI framework.

---

#### **7. X Handle Integration Setup**
- Add scaffolding for integrating the user's X (Twitter) handle:
  - Create a placeholder command (`X @handle`) to accept and store a handle.
  - Set up the interface for future API integration with X for handle verification.

---

#### **8. Testing and Debugging**
- Test the basic flow of commands and navigation.
- Ensure smooth transitions between levels (e.g., `betbtc -> category -> market`).
- Debug user interactions with placeholder data.

---