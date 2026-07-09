# Multi Roblox
**Multi Roblox** is a lightweight, autonomous tool designed to launch multiple instances of Roblox on a single machine.<br> The entire project — including the C# core source code, custom application icon, and management logic — is packed into a single file.

🚀 **Quick Start**
1. Download the `install.bat` file from this repository.
2. Create a folder for `install.bat`.
3. Run the file (Run as Administrator is optional).
4. Choose the installation options that suits your needs.
5. Use the generated `Service.bat` (or its Desktop shortcut) to manage **MultiRoblox Core**.

🛠️ **How it Works**
* **The Core:** The installer extracts a Base64-encoded icon and compiles a custom C# `MultiRoblox.exe` on-the-fly using the system's built-in **csc.exe** (.NET Framework).
* **The Service:** A dynamic batch-based menu is generated to handle the process lifecycle, ensuring you have full control over your background sessions.

📋 **Requirements**
* **OS:** Windows 10/11.
* **Environment:** Standard .NET Framework (pre-installed on all Windows systems).

⚖️ **License**
* This project is open-source and available under the MIT License.
