# confit
All work configuration settings in one place for easy restorations!

## How to use
1. Pull the repo
2. Install the TTF fonts for using in all sessions
3. Make the following settings additionally in putty
    1. Window->Appearance->Cursor blinks
    2. Window->Appearance->Font Settings->Change -> Source Code Pro. 10-point (regular)
    3. Window->Lines of scrollback = 10000
    4. Window->Translation->Remote character set = Use font encoding
    5. Window->Translation->Handling of line drawing characters = Use Unicode line drawing code points
    6. Window->Selection->Action of mouse buttons = xterm (right extends, middle pastes)
    7. Window->Colours->Allow terminal to specify ANSI colours
    8. Window->Colours->Allow terminal to use xterm 256-colour mode
    9. Window->Colours->Indicate bolded text by changing = Both
    10. Terminal->Keyboard->The home and end keys = Standard
    11. Terminal->Keyboard->The function keys and keypad = ESC\[n~
    12. Connection->SSH->Remote command = `/path/to/tmux attach-session -t session_name || /path/to/tmux new-session -s session_name`
    13. Connection->SSH->X11->Enable X11 forwarding
    14. Connection->SSH->X11->X display location = DISPLAY:0:0
4. Run the colors reg file to set all putty colors to github theme
