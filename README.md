# Using_Unix
Just some random unix stuff.


| Commands:      | What they do:|
| ------------- |:-------------:|
| ls            | list command to show all directories and files in the directory you are currently at. |
| ls -al      | Shows a list of all hidden directories and files (that start with . / e.x: .bash_history)      |
| cd /dir1/dir2/..etc | Makes the current directory the directory that you specify from the command that follows|


### When in vi editor >> esq :arrow_right: :wq :arrow_right: save and exit!
### >> :arrow_right:
### >> :arrow_right:

To make BASH start the session in a certain directory everytime you run:
- In your home directory. write: vi .bashrc (or edit the .bashrc file using your editor)
- At the end of the .bashrc file, add cd /directory1/directory2/.../home
- Where the the command following cd is the path to your desired new home folder
- if using BASH for Windows: cd /mnt/your_drive/directory/.../home
