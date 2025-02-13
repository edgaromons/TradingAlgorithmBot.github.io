# TradingAlgorithmBot.github.io
This Trading Algorithm Bot sses your Alpaca API credentials (including whether you're paper trading or live trading based on BASE_URL) and sells overbought assets in portfolio then buys oversold assets in the market per YahooFinance! opportunities

Installing Dependencies from requirements.txt

Follow these steps to install the required Python dependencies on your system.

✅ Prerequisites:

•	Ensure Python (>=3.x) and pip (>=21.x) are installed.
•	Check Python and pip versions:
sh
CopyEdit
python --version
pip --version

📌 Installation Instructions

🖥️ Windows:

1.	Open Command Prompt or PowerShell.
2.	Navigate to the project directory:
sh
CopyEdit
cd path\to\your\project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt

🍏 macOS & 🐧 Linux:

1.	Open Terminal.
2.	Navigate to the project directory:
sh
CopyEdit
cd /path/to/your/project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt

🔍 Additional Tips:

•	If using a virtual environment, activate it before running the installation:
sh
CopyEdit

# Windows (CMD)
venv\Scripts\activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# macOS/Linux
source venv/bin/activate
•	If you face permission issues, try:
sh
CopyEdit
pip install --user -r requirements.txt

•	For system-wide installation, use:
sh
CopyEdit
sudo pip install -r requirements.txt

🛠️ Verifying Installation:
Run:
sh
CopyEdit
pip list
to check if all packages are installed.
