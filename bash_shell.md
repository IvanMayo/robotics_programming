# Bash Commands

## Shorcuts 
**CTRL+A** # move to beginning of line
**CTRL+B** # moves backward one character
**CTRL+C** # halts the current command
**CTRL+D** # deletes one character backward or logs out of current session, similar to exit
**CTRL+E** # moves to end of line
**CTRL+F** # moves forward one character
**CTRL+G** # aborts the current editing command and ring the terminal bell
**CTRL+H** # deletes one character under cursor (same as DELETE)
**CTRL+J** # same as RETURN
**CTRL+K** # deletes (kill) forward to end of line
**CTRL+L** # clears screen and redisplay the line
**CTRL+M** # same as RETURN
**CTRL+N** # next line in command history
**CTRL+O** # same as RETURN, then displays next line in history file
**CTRL+P** # previous line in command history
**CTRL+R** # searches backward
**CTRL+S** # searches forward
**CTRL+T** # transposes two characters
**CTRL+U** # kills backward from point to the beginning of line
**CTRL+V** # makes the next character typed verbatim
**CTRL+W** # kills the word behind the cursor
**CTRL+X** # lists the possible filename completions of the current word
**CTRL+Y** # retrieves (yank) last item killed
**CTRL+Z** # stops the current command, resume with fg in the foreground or bg in the background
**ALT+B** # moves backward one word
**ALT+D** # deletes next word
**ALT+F** # moves forward one word
**ALT+H** # deletes one character backward
**ALT+T** # transposes two words
**ALT+**. # pastes last word from the last command. Pressing it repeatedly traverses through command history.
**ALT+U** # capitalizes every character from the current cursor position to the end of the word
**ALT+L** # uncapitalizes every character from the current cursor position to the end of the word
**ALT+C** # capitalizes the letter under the cursor. The cursor then moves to the end of the word.
**ALT+R** # reverts any changes to a command you’ve pulled from your history if you’ve edited it.

**BACKSPACE**: deletes one character backward
**DELETE**: deletes one character under cursor
**history**: shows command line history
**!!**: repeats the last command
**exit**: logs out of current session

## File commands
**history:**  shows command line history
**clear:**      clears content on window (hide displayed lines)
**ls:** lists your files in current directory
**cat** **filename:** prints file raw content (will not be interpreted)
**mv filename  dest:** moves a file to destination
**rm filename**:removes a file
**find . -name:** searches for a file or a directory in the current directory and all its sub-directories by its name
**wc filename:** tells you how many lines, words and characters there are in a file
**touch filename:** creates or updates (edit) your file
**cp filename  destination**: copies a file
**nano filename.extension:** Creates or opens a file to edit it


## Directory commands

**mkdir dirname:** makes a new directory
**rmdir dirname:** remove an empty directory
**rmdir -rf dirname:** remove a non-empty directory
**mv dir1 dir2:** rename a directory from dir1 to dir2
**cd:**  changes to home
**cd .. :** changes to the parent directory
**cd dirname:** changes directory
