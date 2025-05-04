# ShellUI
A basic Shell User Interface
# Installation
Download file ShellUI-0.1-py3-none-any.whl and run a terminal in that directory.
Now, run the following (Windows):
```cmd
pip install ShellUI-0.1-py3-none-any.whl
```
# Usage
**Function: draw_menu(options as list)**

Draws a menu with the given list of options. The variable option MUST be a list type. Returns selected option.

**Function: dia_confirm(options as list, prompt as string)**

Draws a menu with a title. Returns selected option.

**Function: checkbox_menu(options as list)**

Draws a checkbox menu by allowing users to tick the given options by selecting them and pressing space to tick. Returns selected options as a list of True's and False's.

**Function: dia_checkbox(options as list, prompt as string)**

Draws a checkbox menu like checkbox_menu() but has a title. Returns selected options as list of True's and False's.

**Function: dia_input(prompt)**

Gives an input with a prompt. Returns user input.
