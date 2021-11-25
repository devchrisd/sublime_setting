# sublime_setting

Packages installed:

		"All Autocomplete",
		"Babel",
		"Console Wrap",
		"DocBlockr",
		"Emmet",
		"Function Name Display",
		"Git",
		"GitGutter",
		"Http Requester",
		"Package Control",
		"PhpNamespace",
		"Python 3",
		"SCSS",
		"SideBarEnhancements",
		"SublimeLinter",
		"SublimeLinter-phplint",
		"SublimeREPL",
		"SublimeTmpl",

Short Cut:

    super + P
        : open file

    super + Shift + P
        : Commad pallete

    super + Shift + [/]
    super + Alt + Left/Right
        : switch between the Tabs

    super + Shift + T
        : Open the Tab just closed

    super + D
        : select next same word in file (multi-select)

    super + ^ + G
        : select all same word in file

    super + R
        : go to function typed in

    super + Alt + F
        : find & replace
    super + shift + F
        : find in folder [and replace]

    super + J
        : join next line to current

    super + Left/Right
        : move to start/end of line

    super + Alt + [Shift] + 1/2/3/4/5
        : layout change

    super + [/]
    super + Alt + [/]
        : comment

    super + ^ + Up/Down
        : swap line with the line above/below
    

    ^ + Shift + Up/Down
        : multiline cursor, edit at the same time

    ^ + G
        : go to line

    ^ + M
        : go to matching bracket

    Alt + Left/Right
        : move to next word

    ^ + Shift + M
        : select in brackets

User defined keymap:
[
    { "keys": ["super+alt+down"], "command": "goto_definition" },

    { "keys": ["super+ctrl+a"], "command": "alignment" },

    { "keys": ["alt+t"], "command": "run_phpunit_test"},
    { "keys": ["super+alt+t"], "command": "run_single_phpunit_test"},
    { "keys": ["super+alt+l+t"], "command": "run_last_phpunit_test"},
    // { "keys": ["super+shift+t"], "command": "run_phpunit_tests_in_dir"},
    { "keys": ["super+shift+ctrl+t"], "command": "run_all_phpunit_tests"},
]
