# OnionShare Terminal Web Console

This project simulates a terminal-style interface on a webpage and can be hosted on **OnionShare** for use within the Tor network. The terminal allows the user to execute commands like `services`, `projects`, `contact`, and `exit`. Once the user types the command, the corresponding action is triggered.

## Features

- A custom terminal interface built using HTML, CSS, and JavaScript.
- Commands include:
  - `services`: View available services.
  - `projects`: View ongoing projects.
  - `contact`: Display contact information.
  - `exit`: Terminate the session and close the browser tab.
- Neon green text and dark mode design for an authentic terminal experience.

## Hosting on OnionShare

To securely share this terminal interface using **OnionShare** and make it available through the Tor network, follow these steps:

### 1. **Prepare the Files**
Ensure that all the necessary files (HTML, JavaScript, CSS, etc.) are placed in a folder on your computer.

### 2. **Upload to OnionShare**
1. Download and install **OnionShare** from [https://onionshare.org/](https://onionshare.org/).
2. Open **OnionShare** and select the option to **Share Files**.
3. Drag and drop the folder containing your project files into the OnionShare window.
4. Click on **Start Sharing** to create a hidden service URL.

### 3. **Access the Onion Link**
Once **OnionShare** creates the hidden service, it will provide a `.onion` URL (e.g., `http://yourlink.onion`). You can paste this link into the Tor browser to access your terminal page.

## Accessing the Terminal in the Tor Browser

1. **Tor Browser**: Open the Tor browser and paste the `.onion` link provided by OnionShare into the URL bar.
2. You should now see the terminal interface, where you can interact with the various commands (e.g., `services`, `projects`, `contact`, etc.).

## Accessing the Terminal in the Brave Browser

If you're using **Brave browser**, you can open a **new private window with Tor** to access `.onion` links.

1. Open **Brave Browser**.
2. Click the **hamburger menu** (three horizontal lines) in the upper-right corner and select **New Private Window with Tor**.
3. Paste the `.onion` URL into the URL bar of the new private window.
4. You can now access the terminal interface.

## Commands

- `help`: Lists available commands.
- `clear`: Clears the terminal.
- `back`: Returns to the home screen with instructions.
- `blog`: Opens the blog page.
- `contact`: Displays contact information.
- `services`: Lists the services offered.
- `projects`: Lists the projects available.
- `exit`: Terminates the session and closes the browser.

## Installation

If you want to run the project locally or modify it:

1. Clone or download the repository.
2. Open the `index.html` file in any web browser to view the terminal.

### Dependencies

- No dependencies required. The project runs purely on HTML, CSS, and JavaScript.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

If you need further customization or assistance, feel free to reach out to the author 
