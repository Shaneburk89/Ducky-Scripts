This script is for windows machines it will download a payload from an http server and execute on target machine.
While payload is executing it will use Judge2020's (https://judge2020.com) fake update script to make the computer
look like it is running windows updates to avoid detection until it has completed.

This requires hosting an http server as well as slight modifications to point it to your http server.
Currently configured to send .bat as a payload but can be slightly modified to send .exe or any other filetype.