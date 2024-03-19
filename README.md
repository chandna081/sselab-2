# sselab-2
ALLOWED_COMMANDS = ["start","stop","restart"]
user_input = input("enter your command")
if user_input in ALLOWED_COMMANDS:
    exec(user_input)
else:
    print("invalid command.")
