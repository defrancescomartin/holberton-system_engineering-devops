# 0x05. Processes and signals #

## Tasks ##

### Mandatory ###
* 0 - Write a Bash script that displays its own PID

* 1 - Write a Bash script that displays a list of currently running processes

* 2 - Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process

* 3 - Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash

* 4 - Write a Bash script that displays To infinity and beyond indefinitely

* 5 - Write a Bash script that stops 4-to_infinity_and_beyond process

* 6 - Write a Bash script that stops 4-to_infinity_and_beyond process

* 7 - Write a Bash script that displays:
    * To infinity and beyond indefinitely
    * With a sleep 2 in between each iteration
    * I am invincible!!! when receiving a SIGTERM signal

* 8 - Write a Bash script that kills the process 7-highlander

### Advanced ###

* 9 - Write a Bash script that:
    * Creates the file /var/run/myscript.pid containing its PID
    * Displays To infinity and beyond indefinitely
    * Displays I hate the kill command when receiving a SIGTERM signal
    * Displays Y U no love me?! when receiving a SIGINT signal
    * Deletes the file /var/run/myscript.pid and terminates itself when receiving a SIGQUIT or SIGTERM signal

* 10 - Write a manage_my_process Bash script that:
     * Indefinitely writes I am alive! to the file /tmp/my_process
    * In between every I am alive! message, the program should pause for 2 seconds

* 11 - Write a C program that creates 5 zombie processes

* 12 - Create a screencast where you live-code/demo something related to Unix signals