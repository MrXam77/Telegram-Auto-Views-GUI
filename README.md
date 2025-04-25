# Telegram-Auto-Views-GUI
This project is a Python-based GUI application that automates the process of increasing views on a Telegram post. It utilizes proxy configurations to repeatedly open the specified Telegram post, aiming to increase the view count.

Features:

-GUI for easy input of proxy configuration and Telegram post URL
-Supports SOCKS5 proxies
-Concurrent requests for faster view count increase
-Progress bar to show the progress
-Real-time log updates
-Stop and save functionality

Prerequisites:

-Python 3.x
-aiohttp
-aiohttp_socks
-tkinte

Installation:

1. Clone the repository:
git clone https://github.com/nodemaven-code/tgviews-gui.git
cd tgviews-gui

2. Install the required Python packages:
pip install aiohttp aiohttp_socks

Usage:

1. Run the telegram_auto_views_gui.py script:
python telegram_auto_views_gui.py

2. Fill in the following fields in the GUI:
-Channel: The Telegram channel username.
-Post Numbers: The Telegram post numbers. You can specify ranges (e.g., 1-10) or individual posts (e.g., 4,5,6-10).
-Proxy: Proxy credentials in the format user:password@host:port.
-Number of Views per Post: The number of views you want to generate for each post.

3. Click the "Start" button to begin the process.

Files: 

-telegram_auto_views_gui.py: The main script to run the GUI application.
-requirements.txt: List of required Python packages.
-.gitignore: Git ignore file to exclude unnecessary files from the repository.

License:
This project is licensed under the MIT License.







