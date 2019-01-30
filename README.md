# purdue-cs240-coding-style
C Formatting Config File for Purdue CS240
(this is one of many tools. not all checks are gauranteed. config is provided as is without warranties on grades)

What this will take care of. Spacing. Tabbing. Entering. #include Reordering ( although not all of it )

What it won't handle . Silly variable names. Snake case. Constants littered in code. Any logical error you could possibly make.

## Setup

Navigate to your project directory.

Run the command:

`curl -L -o .clang-format https://raw.githubusercontent.com/KritR/purdue-cs240-coding-style/master/.clang-format`

Add / Commit it to your Project so Make doesn't clean it away.

## Usage

To format a file from the terminal.

`clang-format -i <filename.c>`

To format a file from vim.

`:%!clang-format`
