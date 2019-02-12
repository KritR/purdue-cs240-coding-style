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

## Coverage

- [ ] 0 pts Full Credit
- [ ] 2 pts I:A - Naming Convention
- [ ] 2 pts I:B - Descriptive names
- [ ] 2 pts I:C - Constants
- [ ] 2 pts I:D - Global variables
- [x] 2 pts II:A - Line length < 80 and indentation 
- [ ] 2 pts II:B - Function size (< 2 pages)
- [x] 2 pts III:A - Spacing after flow control commands
- [x] 2 pts III:B - Spacing before/after arithmetic/logical operators
- [x] 2 pts III:C - Spacing - after internal semicolons and commas
- [ ] 2 pts III:D - Spacing - #define in col 1, blank line above and below
- [x] 2 pts III:E - Trailing whitespace
- [x] 2 pts III:F - Space between function name and parentheses
- [x] 2 pts IV:A - Two space indentation, location of { }
- [x] 2 pts IV:B - Function parameters same line unless wrapped, indented
- [ ] 2 pts IV:C - while() on same line as closing }
- [ ] 2 pts V:A - Comments must be meaningful and indented properly
- [ ] 2 pts V:B - Comments above code except: else, switch declarations
- [ ] 2 pts V:C - Blank line above and below, unless after } or first
- [ ] 2 pts V:D - } /* function_name( ) */
- [ ] 2 pts V:E - Function header location and spacing or missing
- [ ] 2 pts VI - Spacing, parentheses for multiple logical expressions
- [ ] 2 pts VII - Function headers
- [ ] 2 pts VIII:A - .h file for every .ck
- [ ] 2 pts VIII:B - Self-contained header files
- [ ] 2 pts VIII:C - #define guards
- [ ] 2 pts VIII:D - No directory shortcuts (. and ..) 
- [ ] 2 pts VIII:E - Include ordering and spacing
- [ ] 2 pts VIII:F - Explicit inclusions
- [ ] 2 pts VIII:G - Non local includes
- [ ] 2 pts IX:A - Check return values
- [ ] 2 pts IX:B - Use of fclose(), fp = NULL
- [ ] 2 pts IX:C - free(ptr); ptr = NULL;
- [ ] 2 pts IX:D - Appropriate range checks
- [ ] 2 pts IX:E - Appropriate symbol - 0, 0.0, NULL, '\0' 
- [ ] 2 pts X: errors > stderr
- [x] 2 pts XI:A - Do not use tabs for indentation
- [ ] 2 pts XI:B - <= 1 assignment per expression
- [ ] 2 pts XI:C - Do not use embedded constants 
- [ ] 2 pts XI:D - Use of goto
- [ ] 2 pts XI:E - Other
- [ ] 2 pts XII:A - Do not define > 1 variable per line 
- [ ] 2 pts XII:B - Initialization at declaration
- [ ] 2 pts XII:C - Scope

