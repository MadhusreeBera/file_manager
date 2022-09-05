File Manager

compile: g++ main.cpp -o main
run: ./main

Assumptions
1. Opening any file for which default application is not available will cause error message to be printed at that position. This happens because xdg-open is being used to open files by their default application (as vi cannot open all types of files.) The error message will be removed by pressing up or down arrow keys.

2. On resizing the screen vertically or horizontally, the text will adjust after pressing the up or down arrow keys
