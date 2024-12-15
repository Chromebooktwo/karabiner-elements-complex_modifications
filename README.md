karabiner-elements-complex_modifications:
















{
    "description": "Press delete_forward to simulate Delete",
    "manipulators": [
        {
            "from": { "key_code": "delete_forward" },
            "to": [{ "key_code": "delete_or_backspace" }],
            "type": "basic"
        }
    ]
}















{
    "description": "Press Clear to simulate Delete",
    "manipulators": [
        {
            "from": { "key_code": "keypad_num_lock" },
            "to": [{ "key_code": "delete_or_backspace" }],
            "type": "basic"
        }
    ]
}















{
    "description": "Press fn + \\ to open Terminal",
    "manipulators": [
        {
            "from": {
                "key_code": "backslash",
                "modifiers": { "mandatory": ["fn"] }
            },
            "to": [{ "shell_command": "open -a Terminal" }],
            "type": "basic"
        }
    ]
}
















{
    "description": "Press fn + Shift + \\ to make Mac go to sleep",
    "manipulators": [
        {
            "from": {
                "key_code": "backslash",
                "modifiers": { "mandatory": ["fn", "shift"] }
            },
            "to": [{ "shell_command": "pmset sleepnow" }],
            "type": "basic"
        }
    ]
}














