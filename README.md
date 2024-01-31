# Spyware Tool

## Author
Atul Mishra

## Description
This Python script, `Spyware_tool.py`, is designed for surveillance and monitoring purposes. It offers a range of functionalities to capture and record various types of data from a user's computer.

## Functionalities
1. **Keystroke Logging**: Records all keystrokes made on the keyboard and stores them in a text file (`logs.txt`). This can include regular typing, search queries, and other keyboard-based interactions.

2. **Computer Information Retrieval**: Gathers essential information about the computer system, like system specs and network details, and stores it in an Excel file.

3. **Clipboard Monitoring**: Captures any text that is copied to the clipboard and saves it to a text file (`clipboard.txt`), along with a timestamp.

4. **Browser History Access**: Retrieves the browsing history from Google Chrome and stores it in an Excel file. This feature provides insights into the web activities of the user.

5. **Screenshot Capturing**: Takes periodic screenshots of the computer screen and saves them in PNG format, allowing for visual monitoring.

## Installation and Usage

### Prerequisites
Before running `Spyware_tool.py`, ensure you have Python installed on your computer. This script is compatible with Python 3.x. Additionally, you will need to install several Python libraries:

- `pynput` for keystroke logging.
- `pandas` for data handling and storage in Excel format.
- `socket` and `platform` for retrieving computer information.
- `win32clipboard` for accessing clipboard data.
- `sqlite3` for accessing Google Chrome history (if applicable).
- Libraries for screenshot capturing (the specific library/libraries used are not identified in the provided script).

### Installation
1. Clone or download the `Spyware_tool.py` script from the GitHub repository.
2. Install the required Python libraries. This can typically be done via pip. For example:
   
   'pip install pynput pandas pywin32'
  
   Replace or add other library names as necessary.

### Running the Script
1. Open a command line interface (CLI) or terminal.
2. Navigate to the directory where `Spyware_tool.py` is located.
3. Run the script using Python:
   
   'python Spyware_tool.py'
   
4. The script will start monitoring and logging data based on its functionalities. Logged data will be stored in the specified files (like `logs.txt`, `clipboard.txt`, and `keystrokes.xlsx`) in the same directory as the script.

### Notes
- The script may require administrative privileges to access certain data, especially for keystroke logging and browser history.
- Ensure you have the necessary permissions and legal right to run this tool on the computer and for the data you're accessing.

## Precautions and Legal Notice
- This tool is intended for educational purposes only.
- Users must ensure they have explicit consent from individuals whose data is being monitored, as unauthorized use of this tool can lead to serious privacy violations and legal consequences.
- It is the user's responsibility to comply with all applicable laws and ethical guidelines in their jurisdiction.
- The author, Atul Mishra, does not assume any responsibility for misuse of this tool or any legal repercussions that may arise from such misuse.



