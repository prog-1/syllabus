# Command Line Cheat Sheet

| Purpose                                                     | cmd.exe (Windows) | bash (Linux/Mac) | bash example                            |
| ----------------------------------------------------------- | ----------------- | ---------------- | --------------------------------------- |
| Shows your location in the file system                      | cd / chdir        | pwd              | `pwd`                                   |
| Lists files                                                 | dir               | ls               | `ls`                                    |
| Creates a directory                                         | mkdir             | mkdir            | `mkdir directory`                       |
| Removes a directory                                         | rmdir             | rm -r            | `rm -r directory`                       |
| Changes directories with a specified path (_absolute path_) | cd _pathname_     | cd _pathname_    | `cd /directory/directory`               |
| Changes directories with a _relative path_                  | cd _pathname_     | cd _pathname_    | `cd ../directory`                       |
|                                                             |                   |                  | `cd directory`                          |
| Copies files                                                | copy              | cp               | `cp thisfile.txt /home/thisdirectory`   |
| Moves files                                                 | move              | mv               | `mv thisfile.txt /home/thisdirectory`   |
| Renames a file                                              | ren               | mv               | `mv thisfile.txt thatfile.txt`          |
| Deletes a file                                              | del               | rm               | `rm thisfile.txt`                       |
