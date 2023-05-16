# Django Virtual Environment Setup

This repository provides a set of `.bat` (Windows) and `.sh` (Unix/Linux/Mac) files that simplify the process of setting up a Django virtual environment.

## Purpose

Setting up a virtual environment for Django development can be a repetitive and time-consuming task. This repository aims to automate the process by providing convenient scripts for creating and activating a virtual environment with all the necessary dependencies.

## Prerequisites

Before using the scripts in this repository, make sure you have the following installed:

- Python (version 3.x recommended)
- pip (Python package manager)

## Usage

Follow the steps below to create and activate a Django virtual environment using the provided scripts:

1. Clone or download this repository:
2. Navigate to the repository's directory: cd your-repo
3. Copy the appropriate script based on your operating system (create_venv.bat for Windows or create_venv.sh for Unix/Linux/Mac) into your Django project's root directory or the location where you want to create the virtual environment.
4. Run the script from within your Django project directory:
- For Windows, open a command prompt and run:
create_venv.bat
- For Unix/Linux/Mac, open a terminal and run:
./create_venv.sh
5. The script will create a virtual environment named venv and install the required dependencies specified in the requirements.txt file.
6. Activate the virtual environment:
- For Windows: 
  venv\Scripts\activate
- For Unix/Linux/Mac: 
  source venv/bin/activate
 7. You are now inside the Django virtual environment. You can proceed with your Django development tasks.
 
 ## Additional Configuration
 Feel free to modify the requirements.txt file to include any additional packages or dependencies specific to your project.
 
 ## Contribution
 Contributions to this repository are welcome. If you have any improvements or suggestions, please open an issue or submit a pull request.
 
 ## License
 This project is licensed under the MIT License.
 
Make sure to replace "your-username" and "your-repo" with the appropriate GitHub username and repository name. Additionally, ensure that you copy the correct script based on your operating system and place it in the desired location within your Django project.


```bash
git clone https://github.com/Abdul-Mueed-Shahbaz/Django-Venv-Companion.git
