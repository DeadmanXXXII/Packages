# Packages
My list of APT and Twine packages

# Shell_Don

This project provides a Python script to encode and decode shell commands in various formats.  This is a command-line interface (CLI) script.
There is a GUI available in another method below.

## Features

- Encode shell commands to:
  - Hexadecimal
  - Base64
  - URL encoding
  - HTML encoding
  - JSON encoding
  - Markdown encoding
  - Binary encoding
  - Substitution cipher
- Generate decoding commands for each encoded format
- Preview decoding commands without executing them
- Custom decoding commands

## Installation

Ensure you have Python 3.x.x installed. Then, install the required packages with:

```bash
sudo dpkg -i shell_don.deb
```

```bash
pip install shell-don
```

```bash
pip install -r requirements.txt
```

For the GUI version:
```bash
git clone https://github.com/DeadmanXXXII/Shell_Don.git
```

### Usage

There are two ways to use this with a GUI which has more features in the CLI for quick on the go access:

### GUI Script

To launch the GUI:

```bash
Copy code
python gui_script.py --gui
```

### CLI Script for packages

To use the CLI script:

```bash
shell_don <command> <substitution_key> [--preview] [--custom-decoding <command>]
```

### Arguments:

<command>: The shell command to encode.
<substitution_key>: The substitution cipher key (0-61).

### Options:

--preview: Preview the decoding commands without executing them.
--custom-decoding <command>: Custom decoding command. Overrides default decoding commands.

## Examples:

### Encode a command with the GUI:
Run the script with the --gui flag.
Enter your shell command and substitution key.
Click "Generate" to see the encoded formats and decoding payloads.

### Encode a command with the CLI:

```bash
shell_don "ls -la" 3 --preview
```


This will encode the command ls -la with a substitution key of 3 and display the decoding commands.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements:
Built by DeadmanXXXII.


### Note

You can now use these scripts for encoding and decoding shell commands with both a graphical interface and command-line interface.

![Usage](https://raw.githubusercontent.com/DeadmanXXXII/Shell_Don/main/Nethunter-use_OP_Top.png)

![Usage](https://raw.githubusercontent.com/DeadmanXXXII/Shell_Don/main/Nethunter-use_OP_bottom.png)





