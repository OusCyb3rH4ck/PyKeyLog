# PyKeyLog
PyKeyLog is a lightweight, stealthy keylogger developed in Python, specifically designed for penetration testers and security professionals. This tool captures keystrokes in real-time and sends the logs securely via email at specified intervals, allowing for efficient monitoring of user activity.

![imagen](https://github.com/user-attachments/assets/e9032684-5c4b-4bbc-afb1-5f2669d42ebf)
![imagen](https://github.com/user-attachments/assets/bdb3da42-efa6-48c1-91e8-71f0e5db156c)

## Features
- **Real-Time Keystroke Logging:** Captures every keystroke in real-time, including characters, spaces, and special keys, ensuring that all user input is logged accurately.
- **Scheduled Log Reporting:** Sends captured logs to a designated email address at user-defined intervals (default set to every 5 minutes), allowing for consistent monitoring without manual checks.
- **Configurable SMTP Settings:** Uses environment variables from a .env file to securely store and manage SMTP credentials, ensuring that sensitive information remains protected.
- **Graceful Exit and Cleanup:** Handles termination signals (like Ctrl+C) gracefully, ensuring that logs are sent before exiting and cleaning up temporary files.
- **Cross-Platform Support:** Built with Python and designed to run on any operating system that supports Python, making it versatile for penetration testing in various environments.
- **Color-Coded Console Output:** Utilizes the colorama library for enhanced terminal output, providing clear and visually distinct status messages and error notifications.
- **Error Handling:** Includes robust error handling to manage exceptions during email sending and file operations, improving reliability during usage.
- **User-Friendly Notification System:** Displays informative messages in the console during execution, such as when logs are successfully sent or if there are issues, ensuring that users are informed of the program's status.
- **Hidden Logging:** Logs are stored in a hidden file (.hidden_log.txt) in the user's home directory, keeping them discreet and minimizing the risk of detection.

### Installation
