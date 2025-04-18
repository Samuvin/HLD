# 🐚 Bash Commands Cheat Sheet

A collection of essential Bash commands, grouped by category.

---

## 📁 Directory Navigation

```bash
cd /path/to/folder       # Change to specific directory
cd ..                    # Move one directory up
cd ~                     # Go to home directory
pwd                      # Show current working directory
```

## 📂 File & Directory Management (Windows)

```cmd
dir                           # List files in the current directory
mkdir folder_name             # Create a new folder
rmdir folder_name             # Remove an empty folder
del file.txt                  # Delete a file
move old.txt new.txt          # Rename or move a file
copy file1.txt file2.txt      # Copy a file
xcopy /E folder1 folder2      # Copy folders with contents
```

## File Content & Editing (Windows)

```cmd
type file.txt                 # View file contents
more file.txt                 # View with paging
notepad file.txt              # Open file in Notepad editor
```

## Searching & Finding (Windows)

```cmd
dir /S /B *.txt               # Find all .txt files recursively
find "text" file.txt          # Search for "text" in a file
findstr /S /I "text" *.txt    # Recursive search, case-insensitive
```

## File Permissions & Ownership (Windows - basic)

```cmd
icacls file.txt               # Show file permissions
icacls file.txt /grant User:F # Grant full access to a user
takeown /F file.txt           # Take ownership of a file
```

## Process Management (Windows)

```cmd
tasklist                      # List running processes
taskkill /PID 1234            # Kill process by PID
taskkill /IM notepad.exe      # Kill process by name
```

## Networking Commands (Windows)

```cmd
ping google.com               # Ping a server
curl https://example.com      # Make HTTP request (PowerShell or recent CMD)
ipconfig                      # Show IP config info
netstat -an                   # Show active ports
```

## Package Management (Windows - via winget or Chocolatey)

```cmd
winget search packagename     # Search for a package
winget install packagename    # Install a package
winget uninstall packagename  # Uninstall a package
```

## Disk & System Info (Windows)

```cmd
chkdsk                        # Check disk status
wmic logicaldisk get size,freespace,caption  # Disk info
systeminfo                    # Show system info
```
