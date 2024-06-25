# TheMaverickTool
A Malware Configuration Extractor in Python

By SuzukiCode

Welcome! Here are the install instructions

-Install the latest version of Python
-Check Python version by typing into the command line: "python --version"
-Add Python to PATH environment variables in Windows or Linux
-After installing Python, check for "Pip": "pip --version"
-If not installed, go to: https://pip.pypa.io/en/stable/installation/
-Using Pip, install the "pefile" module: "pip install pefile"
-Verify that the installation was successful: python -c "import pefile"
-Next, install pyfiglet: pip install pyfiglet
-Place "maverick.py" in the same directory as the PE file or specify the path. You will be asked to input a path when run.

Features:

-Gets the Entrypoint Address
-Gets MD5, SHA-1, and SHA256 hashes
-Gets the architecture of the file(32-bit or 64-bit)
-Gets DLL Dependancies
-Gets Resources
-Gets Imported Functions from the Import Address Table
-Gets IP Addresses
-Gets Section info about the section headers. Their names and virtual addresses.
-Gets websites(URLs)
-Gets strings

Enjoy fellow Maverick!

