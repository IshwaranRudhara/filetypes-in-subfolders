```
##filetypes-in-subfolders
move all filetypes in subfolders with CMD


explanation:
for = command

/r = affects all subfolders and not just current folder

%%a = variable used to move files

IN = command

(*.*) = decides what file names/types will be affected, star (*) means everything

do = command

move = command

/y = prompts for confirmation if you want to overwrite (not needed)

"%%a"= uses the a variable to move one file at the time, i use quotation marks because if you have a file with a empty space inside  it will not work

"%cd%"= cd stands for CURRENT DIRECTORY, which means the folder the .bat file is opened in. You can  replace "%cd%" with a PATH of your choice. For example    move /y "%%a" "C:\Users\YOUR USER NAME\Desktop\ "

```
