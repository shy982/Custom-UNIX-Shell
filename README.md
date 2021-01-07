# Custom-UNIX-Shell
This is a custom Unix shell


*** The following are the dependencies required before executing the code ***
1. sudo apt-get install vim
2. sudo apt-get install gcc
3. sudo apt-get install libreadline-dev
4. sudo apt-get install make

*** Here is how to execute our customized shell after installing dependencies ***
1. The main script lies in the file shyvin.c
2. The extra commands that we have implemented lie in our_custom_commands.sh
3. Go to the terminal and compile the file:
    -- gcc shyvin.c -lreadline (or make shyvin.c)
    -- ./a.out
    -- You should see the welcome message and 3 seconds later the command prompt appears.

**** To ensure that the custom designed commands are executable ****
1. cd ~
2. cp /Downloads/our_custom_commands.sh ~/.our_custom_commands.sh (Assuming the bash script is in Downloads folder currently)
3. chmod +x .our_custom_commands.sh
4. close and restart terminal
5. source ~/.our_custom_commands.sh
6. Ready to execute custom commands (printme, easycalc, syshog, teach_me_unix, errormate)

That's It! Thank you for using shyvin shell. Hope you find it interesting!
