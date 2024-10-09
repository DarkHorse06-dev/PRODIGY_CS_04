# PRODIGY_CS_04
A simple Python-based keylogger that records keystrokes and saves them into a log file. The project demonstrates basic keylogging functionality while ensuring ethical considerations.

Install Python:

Ensure you have Python installed on your computer. You can download it from the official Python website.
During installation, make sure to check the box that adds Python to your system PATH.


Install Required Library:

Open your command line interface (Command Prompt on Windows, Terminal on macOS/Linux).

Run the following command to install the pynput library: pip install pynput


In your command line interface, navigate to the directory where you saved the script. You can use the cd command to change directories. For example: cd path\to\your\script

Run the script by typing: python key_press_counter.py


Using the Script:

Once the script is running, it will listen for keystrokes.
You can type normally, and the script will count the key presses.
When you want to stop logging, press the ESC key.


Check the Log File:

After stopping the script, it will create a file named key_counts.txt in the same directory as your script.
Open this file to see the count of each key pressed along with the timestamp of when you stopped the logging.


Important Notes


Running in the Background:


The script will run in the foreground and will stop listening when you press ESC. Be mindful of this if you need to work on other tasks simultaneously.


Security and Privacy:


Make sure to respect privacy and only use this script for tracking your own input.



Stopping the Script:


If you need to stop the script abruptly, you can also close the command line interface window, but this may not log the key counts.
