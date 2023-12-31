# Bash Terminal Commands

## File and Directory Listing Commands

- **`pwd`**
  - Description: Displays the present working directory.
  
- **`ls`**
  - Description: Lists files in the current directory.
  
- **`ls -l`**
  - Description: Shows detailed information about directories.
  
- **`ls -R`**
  - Description: Recursively displays sub-directories as well.
  
- **`ls -t`**
  - Description: Lists files sorted by the last modification time.
  
- **`ls -a`**
  - Description: Shows all hidden files in the directory.
  
- **`ls *.js`**
  - Description: Lists all files with the `.js` extension.
  
- **`ls ..`**
  - Description: Lists files in the parent directory.

## Navigation Commands

- **`cd`**
  - Description: Changes the current directory.
  
- **`cd filename`**
  - Description: Changes the current working directory to the specified file.
  
- **`cd ..`**
  - Description: Moves back to the previous directory.

## File Manipulation Commands

- **`touch filename`**
  - Description: Creates a new file.
  
- **`cat`**
  - Description: Reads the content of a file.
  
- **`cat > filename`**
  - Description: Allows typing content into a file. Press `Ctrl + d` to exit.
  
- **`cat >> filename`**
  - Description: Appends content to the end of a file.
  
- **`mkdir directoryname`**
  - Description: Creates a new directory.
  
- **`mv filename newFileName`**
  - Description: Renames a file.
  
- **`cp index.html frontend`**
  - Description: Copies a file to a specified directory.
  
- **`cp -r test contract`**
  - Description: Copies a directory recursively.
  
- **`rm README.md`**
  - Description: Deletes a file.
  
- **`rm -r frontend`**
  - Description: Deletes a directory.

## Permissions and File Display Commands

- **`chmod`**
  - Description: Changes file permissions.
  
- **`head fileName`**
  - Description: Displays the first 10 lines of a file.
  
- **`tail filename`**
  - Description: Displays the last 10 lines of a file.
  
- **`head -20 filename`**
  - Description: Displays the first 20 lines of a file.
  
- **`tail -20 filename`**
  - Description: Displays the last 20 lines of a file.
  
- **`tail -n +25 newfile.txt | head 5`**
  - Description: Displays lines 25 to 30 of a file.

## Text Searching Commands

- **`grep "one" filename`**
  - Description: Searches for the word "one" in a file.
  
- **`grep -c "one" filename`**
  - Description: Counts how many times the word "one" appears in a file.
  
- **`grep -h "one" filename`**
  - Description: Shows the lines where the word "one" appears.
  
- **`grep -hi "one" filename`**
  - Description: Shows all lines where the word "one" appears, ignoring case.
