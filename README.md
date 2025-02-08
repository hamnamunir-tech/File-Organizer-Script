# File-Organizer-Script

## Overview
The **File Organizer Script** is a Python program that helps you organize files in a specified folder by automatically sorting them into categorized subfolders based on file types. This script makes it easier to manage and keep files structured.

## Features
- Prompts the user to enter the folder path for organization.
- Automatically creates subfolders for common file types such as **Images, Videos, Documents, Audio, and Others**.
- Moves files into the appropriate subfolders based on their extensions.
- Provides a summary of how many files were moved into each subfolder.
- Handles invalid folder paths and displays error messages accordingly.

## Prerequisites
Ensure you have **Python 3.x** installed on your system.

## How to Use
1. Download the script (**file_organizer.py**).
2. Open a terminal or command prompt.
3. Run the script using the following command:
   ```sh
   python file_organizer.py
   ```
4. Enter the full path of the folder you want to organize when prompted.
5. The script will create subfolders and sort the files accordingly.
6. After execution, a summary of the organization process will be displayed.

## File Type Categories
The script organizes files into the following categories:
- **Images**: `.jpg`, `.jpeg`, `.png`, `.gif`, `.bmp`, `.tiff`
- **Videos**: `.mp4`, `.mkv`, `.avi`, `.mov`, `.flv`
- **Documents**: `.pdf`, `.docx`, `.txt`, `.xlsx`, `.pptx`
- **Audio**: `.mp3`, `.wav`, `.flac`, `.aac`
- **Others**: Any files that do not match the above categories

## Example Output
```
Enter the folder path to organize: C:\Users\YourName\Downloads

File organization complete. Summary:
Images: 10 files
Videos: 5 files
Documents: 8 files
Audio: 3 files
Others: 2 files
```

## Error Handling
- If the user provides an invalid folder path, the script will display an error message and exit.
- If files with unknown extensions are found, they will be moved to the **Others** folder.

## Dependencies
This script uses the built-in **os** and **shutil** modules, so no additional installations are required.

## License
This script is free to use and modify.

## Author
Your Name

