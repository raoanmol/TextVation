# 📝 TextVation
TextVation is a simple text editor driven by innovation. It is written in C and privides a simple, lightweight, and efficient environment for text editing.

## ⭐ Features
- TextVation supports basic text editing functionalities like insertion, deletion, and navigation through the text.
- It handles arrow keys (left, right, up, down), page up/down, home and end keys.
- It supports syntax highlighing for C and C++, with highlighting for keywords, numbers, and strings.
- TextVation is extensible and new features can be added with ease.
- It operates in raw mode, handling all the input directly for a more controlled user experience.

## 🚀 Usage 
To compile and run the text editor, use the provided Makefile. Run the `make` command in your terminal to compile the program, and then start the text editor with the created executable.
```bash
make
./textvation
```
You can open a file by providing the filename as an argument:
```bash
./textvation filename.txt
```

## 📘 Manual
Here's a brief guide on how to use TextVation:
- __Arrow Keys:__ Use the arrow keys (up, down, left, right) to navigate through the text.
- __Page Up/Down:__ Scroll through the file a page at a time.
- __Home:__ Move the cursor to the start of the line.
- __End:__ Move the cursor the the end of the line.
- __Ctrl-Q:__ Quit. If there are unsaved changes, you will need to press this twice in succession without saving.
- __Ctrl-S:__ Save the current file.
- __Ctrl-F:__ Find a string in the file. You can use arrow keys to navigate through the matches.

## 💡 Development
TextVation was developed with a focus on simplicity and efficiency. It uses standard libraries like `<ctype.h>`, `<errno.h>`, `<fcntl.h>`, `<stdio.h>`, `<stdarg.h>`, `<stdlib.h>`, `<string.h>`, `<sys/ioctl.h>`, `<sys/types.h>`, `<termios.h>`, `<time.h>`, and `<unistd.h>` to achieve its functionalities. 

## 📜 Licensing
This work is a derivative of the [tutorial](https://github.com/snaptoken/kilo-tutorial) by [snaptoken](https://github.com/snaptoken) released under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Snaptoken's work is inspired by Salvatore Sanfillipo (aka [antirez](https://github.com/antirez)) and released under the [BSD-2 clause](https://opensource.org/license/bsd-2-clause/) license (see `kilo.LICENSE`). All the files under this repository are licensed under the [BSD-2 clause](https://opensource.org/license/bsd-2-clause/).
