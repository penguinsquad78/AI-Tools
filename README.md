catstudio
# AI-Tools

# How to set up

## Step 0 - Setup Python (skip this if you already have Python)

Go to https://www.python.org/downloads/ to download Python onto your computer.

Once downloaded, use the Python setup window to set up Python.

## Step 1 - Download files

Click "Code", then "Download ZIP".

## Step 2 - Install libraries with pip

Open Terminal (macOS, Windows) or Command line (Linux), and enter the following commands:

'pip install -q -U google-generativeai'
'pip install pyautogui'

and if that doesn't work, try

'pip3 install -q -U google-generativeai'
'pip3 install pyautogui'

The first command is absolutely required. This will allow you to use Google Gemini through my app. The second command is required only is you want Gemini to be able to use your keyboard and mouse. If you don't install it, then you'd have to delete the 'import pyautogui as control' line in the code, and then you can only use the chatbot.

## Step 3 - Use and set up for easy access

You can now open the 'ai_tools.py' file and use the tools! **If you use macOS, you will have to allow "Terminal" to access accessibility shortcuts by opening System Settings > Privacy & Security > Accessibility and toggle Terminal to on.** You can drag the file to your destop for easy access. Make sure it opens with "Python Launcher".
