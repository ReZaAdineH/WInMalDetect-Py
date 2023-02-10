# WInMalDetect-Py
# Malware Detection for Windows Systems

This is a simple Python script to check for default Windows paths that malware might use. The script will check for the existence of these paths and search for executable files (.exe) in each path. If an executable file is found, its MD5 hash will be calculated and compared to a list of known malware hashes. If the hash matches one of the known malware hashes, the file will be backed up to a new file with the .bak extension.

Requirements

Python 3.x
Windows operating system
Usage

Clone or download the repository to your local machine.
Open a command prompt or terminal window and navigate to the repository directory.
Run the script using the following command:
 
python malware_detection.py

**Note**: This code is just a sample and is not a complete solution for detecting and removing malware on a Windows system. It's recommended to use a comprehensive security solution, such as an antivirus program, to protect your system from malware.
