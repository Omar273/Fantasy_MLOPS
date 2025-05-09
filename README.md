# ⚽ Fantasy Premier League Assistant


An intelligent platform combining machine learning and optimization algorithms to dominate your Fantasy Premier League.

## 🚀 Features

- **Real-time Player Analytics**
- **ML-Powered Performance Predictions** (Random Forest)
- **Squad Optimizer** (Linear Programming)
- **Gameweek Planner**
- **Team Saving** (MongoDB Integration)
- **Responsive Web Interface**

## 📦 Installation

### Prerequisites
- Python 3.8+
- Make (optional but recommended) 


# Clone repository
git clone https://github.com/yourusername/fantasy_MLOPS.git
cd fantasy_MLOPS
Using Make (Recommended)
bash
make install  # Creates venv and installs dependencies
Manual Installation
bash
python -m venv venv

# Windows
.\venv\Scripts\activate
pip install -r requirements.txt

# Linux/Mac
source venv/bin/activate
pip install -r requirements.txt


# 🖥️ Usage

Start the Application
bash
make run  # OR: flask run
Access at: http://localhost:5000

Makefile Commands
Command	Description
make install	Setup virtualenv + dependencies
make run	Launch development server
make test	Run pytest suite
make lint	Check code quality with flake8
make format	Auto-format with Black
make clean	Remove virtualenv and cache files  



# 🐛 Troubleshooting
Makefile not working on Windows?

powershell
# Install make via Chocolatey 
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

choco install make


 
