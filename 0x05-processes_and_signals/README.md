# Project Name.
**0x05. Processes and signals**

### Bash Scripts
*   Allowed editors: `vi`, `vim`, `emacs`.
*   All your files will be tested on Ubuntu 20.04 LTS.
*   All your files should end with a new line.
*   The first line of all your Bash scripts should be exactly `#!/usr/bin/env bash`.
*   All your bash scripts must be executable.
*   Your Bash script must pass `shellcheck` without any error.
*   The second line of all your Bash scripts should be a comment explaining what is the script doing.

## Project Description.
Learn what is a PID.
What is a process.
How to find a process’ PID.
How to kill a process.
What is a signal.
What are the 2 signals that cannot be ignored.


* **0. What is my PID** - Write a Bash script that displays its own PID. - `0-what-is-my-pid`.
* **1. List your processes** - Write a Bash script that displays a list of currently running processes with the given requirements. - `1-list_your_processes`.
* **2. Show your Bash PID** - Using your previous exercise command, write a Bash script that displays lines containing the `bash` word, thus allowing you to easily get the PID of your Bash process. - `2-show_your_bash_pid`.
* **3. Show your Bash PID made easy** - Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word `bash`. - `3-show_your_bash_pid_made_easy`.
* **4. To infinity and beyond** - Write a Bash script that displays To infinity and beyond indefinitely with the given requirements. - `4-to_infinity_and_beyond`.
* **5. Don't stop me now!** - Write a Bash script that stops `4-to_infinity_and_beyond` process. -`5-dont_stop_me_now`.
* **6. Stop me if you can** - Write a Bash script that stops `4-to_infinity_and_beyond` process. - `6-stop_me_if_you_can`.
* **7. Highlander** - Write a Bash script that displays `To infinity and beyond` indefinitely, `I am invincible!!!` when receiving a SIGTERM signal with the given requirements. - `7-highlander`.
* **8. Beheaded process** - Write a Bash script that kills the process `7-highlander`. - `8-beheaded_process`.
---
* **9. Process and PID file** - Write a Bash script that does the following:

    *   Creates the file `/var/run/myscript.pid` containing its PID.
    *   Displays `To infinity and beyond` indefinitely.
    *   Displays `I hate the kill command` when receiving a SIGTERM signal.
