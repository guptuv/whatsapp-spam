# PyAutoGUI Auto Typer

This Python script is designed to automate text input using the PyAutoGUI library. It can be useful for scenarios where repetitive typing is required, such as testing or data entry. The script simulates keyboard input to repeatedly type a specified message and press "enter" at regular intervals.

## Prerequisites

Before running the script, make sure you have Python installed on your system. You can install the required library using the following command:

```bash
pip install pyautogui


Usage
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/auto-typer.git
cd auto-typer
Open the script:

Open the script (auto_typer.py) in a text editor and replace the placeholder message with the text you want to be typed:

python
Copy code
pyautogui.typewrite("Type your Message here")
Adjust the sleep duration:

Modify the sleep duration if needed to control the time delay between each typing action:

python
Copy code
time.sleep(3)
Run the script:

Execute the script using the following command:

bash
Copy code
python auto_typer.py
Important Notes
This script runs indefinitely. To stop it, you may need to terminate the script manually.
Ensure the focus is on the application where you want the text to be typed.
Contribution
If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request. Your contributions are welcome!

Happy typing!
