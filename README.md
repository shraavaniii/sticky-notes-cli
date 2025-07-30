# sticky-notes-cli
A simple Bash script to manage sticky notes from terminal.

## Features
- Create notes with a title and content
- View all notes
- Search notes using keywords
- Delete notes
- Lightweight and beginner-friendly
- Fully written in shell script

## Project Structure
sticky-notes-cli/
 |--add-notes.sh
 |--view-notes.sh
 |--search-notes.sh
 |--delete-notes.sh
 |--notes/        #Stores all note files
 |--sticky-notes.sh      #Main script to run the app

 ## Requirements
 - Bash shell
 - Basic Unix/Linux environment (Tested on CentOS)
 - `grep`, `cat`, `read`, `echo`, etc.

## How to use
1. **Clone the Repository**
```bash
git clone https://github.com/shraavaniii/sticky-notes-cli.git
cd sticky-notes-cli
```

2. **Make the main script executable**
```bash
chmod +x stick-notes.sh
```

3. **Run the app**
```bash
./sticky-notes.sh
```

4. **Once you run the script, you will see menu like this:**

- Add a note
- View a note
- Search a note
- Delete a note
Choose an option:

5. **Working**
- Title: A short headline for the note
- Content: The actual note text
- Tags: Keywords to help

All notes are stored in a local text file(e.g., notes.txt) in a simple readable format.

## Future Improvements
- Edit existing notes
- Export notes to pdf or Markdown
- Add colored terminal output
- Password-protected notes

## Author
**Shravani Hendre**  
Email ID: shravanihendr@gmail.com  
Github Repository: https://github.com/shraavaniii
