### Title:
Cricket Score Tracker: Live Match Updates GUI

### Abstract:
The Cricket Score Tracker is a Python program with a graphical user interface (GUI) designed using the Tkinter library. This application provides a user-friendly platform for tracking live cricket scores by fetching real-time match details from the Cricbuzz website through web scraping.

The main features of the program include:

- **Interactive GUI:** The Tkinter-based GUI presents live cricket matches, allowing users to select a match of interest.
  
- **Dynamic Data Fetching:** Utilizing BeautifulSoup and requests, the program scrapes the Cricbuzz website to fetch live match details, including team names, scores, summaries, and headers.
  
- **Detailed Display:** Users can click the "Check Score" button to view detailed information about the selected match, presented in a separate frame within the GUI.
  
- **Background Image:** The application enhances its visual appeal by incorporating a background image ('cric.png').

This Cricket Score Tracker is an introductory example that demonstrates how to create a simple GUI application and perform web scraping in Python. It serves as an educational tool for beginners, providing insights into the integration of GUI frameworks and web scraping techniques for real-time data retrieval.

### Step-by-step guide for a beginner to run the provided code in VS Code:

### Step 1: Install Necessary Dependencies
Make sure you have Python installed on your system. Additionally, you need to install the required Python packages. Open the VS Code terminal and run the following commands:

```bash
pip install tkinter pillow beautifulsoup4 requests
```

### Step 2: Create a VS Code Project Folder
Create a new folder for your project. You can do this in VS Code or using your system's file explorer.

### Step 3: Save the Code
Copy the provided Python code into a new file with a `.py` extension. For example, you can name it `cricket_score_tracker.py`. Save this file in your project folder.

### Step 4: Save the Image
Make sure you have an image named `cric.png` that you want to use as the background. Save this image in the same project folder.

### Step 5: Open VS Code
Open VS Code and navigate to your project folder by selecting "File" > "Open Folder" and choosing the folder you created.

### Step 6: Open Integrated Terminal
Open the integrated terminal in VS Code by selecting "View" > "Terminal" or by pressing `Ctrl + ` `.

### Step 7: Run the Program
In the terminal, type the following command to run your Python script:

```bash
python cricket_score_tracker.py
```

Hit Enter to execute the command.

### Step 8: View the GUI
The program will run, and you should see the GUI window with the cricket score tracker.

### Step 9: Check Live Matches
The GUI will display live matches, and you can select a match and click the "Check Score" button to get detailed information about the selected match.

### Note:
- Make sure your Python interpreter is correctly set up in VS Code.
- Ensure that the required packages are installed in the correct Python environment.
- If you encounter any issues, check the VS Code terminal for error messages, and make sure the `cric.png` image is in the project folder.

Following these steps should allow you to run the cricket score tracker program in VS Code successfully. If you have any further questions or encounter issues, feel free to ask!
