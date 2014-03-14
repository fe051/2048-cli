#2048-cli

A cli version of the game [2048](https://github.com) for your Linux terminal.

![Screenshot](http://i.imgur.com/fwZEvdh.png)

## Installation
If you want to use the ncurses version, make sure that you have the required ncurses library and link against this during compilation with `-lcurses`
### Get
    cd ~/$INSTALL_DIR
    wget https://raw.githubusercontent.com/Tiehuis/2048-cli/master/2048_no_curses.c
    gcc 2048_no_curses.c -o 2048
### Run
    ./2048   

## Options
    -b <size>      Set the grid border length
    -s <rate>      Set the block spawn rate

## License
This code is licensed under the [MIT License](https://github.com/Tiehuis/2048-cli/blob/master/LICENSE).