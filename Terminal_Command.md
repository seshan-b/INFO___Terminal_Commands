# Terminal Commands

### Terminal Commands

**`pwd`** — Show current directory structure.

**`date`** — Show current date on system.

**`cd [foldername]`**  **`../`**  **`../../`**  — Go into folder name `cd –` move 1 folder back.`cd ../` Move 1 folders back. `cd ../../` Move 2 folders back.

**`ls`**  **`a`**  **`al`** — List Directories `ls` List All including hidden `ls -a` List All Files with file permissions. `ls -al` On Windows CMD you can use `dir`

**`start .`**  **`[filename]` —** Open GUI of Folder. Open file name. (This only works on windows)

**`explorer.exe .`**  **`[filename]` —** Open GUI of Folder (This will work on Linux and Windows and Linux Subsystem).

**`curl [weblink] -o [newname]` —** Saves a file from the web to your local folder you are in.

**`echo [some text you want to write]`** — Output on the next line.

**`history` —** See history.

**`touch [filename.ext]` —** Create new file.

**`mkdir [directoryname]`** — Create directory

**`rm [filename.ext]` —** Delete file.

**`rmdir [directoryname]` —** Delete Empty Directory Only

**`rm -r [directoryname]`**  **`rf [directoryname]`  —** Delete Directory and all its content including files Force Delete Directory and all its content including files. (Never use -rf unless you have to).

**`cp [filename] [filelocation]`** — Copy file.

**`cp -r [directoryname] [newdirectorylocation]` —** Copy directory content to new location.

**`mv [sourceitem] [destinationitem]`  —** Move Items Files and Directories

**`find . -iname * [text] *` —** Search files within directory and sub directories. The `*` is used for anything either before or after the text. E.g. `* [text]` (after) `[text ]*` (before). Note: Make sure you wrap your search text in quotes especially if it is more than one word in the search term. E.g. `“search-term *”` or `“*search-term”` otherwise you might get back nothing or an error.

**`unzip [filename]`  —** Unzip file.

**`cat [filename]`** — Prints to screen what is in the file.

**`clear`  —** Clear screen.

**`exit` —** Exit Terminal.

**`q` —** Exit file.

**`ping 10.1.1.1`  —** Check to see if you are connected and your computer is pinging to the internet.

**`mklink /J [destinationfolder] [referencefolder]`** **`/D [destinationfolder] [referencefolder]`  —** You can create reference folders. By doing this you can access everything in one place without creating multiple folders. `/J` These are junction Links. `/D` These are directory links. You can use directory link on network folders, but you cannot with junction links. Use junction links for local folder and use directory links for local to network folders.

To view this: [Setup Node on Linux Subsystem](https://github.com/seshan-b/INFO___Setup_Node_on_Linux_Subsystem/blob/master/Setup_Node_on_Linux_Subsystem.md)

---