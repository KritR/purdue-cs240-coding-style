# purdue-cs240-coding-style
C Formatting Config File for Purdue CS240

## Setup

Navigate to your project directory.

Run the command:

`curl -L -o .clang-format https://raw.githubusercontent.com/KritR/purdue-cs240-coding-style/master/.clang-format`

Add / Commit it to your Project so Make doesn't clean it away.

## Usage

To format a file from the terminal.

`clang -i <filename.c>`

To format a file from vim.

`:%!clang-format`
