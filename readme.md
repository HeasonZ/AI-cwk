# Grid World assignment #
This repository contains *Grid World* assignment for University of Bristol [COMS30106](https://www.cs.bris.ac.uk/Teaching/Resources/COMS30106) course.

The coursework description is available in wiki format [here](https://github.com/COMS30106/assignment/wiki).

COMS30106 main assignment
Setting up

    You need the latest version of this coursework.
    You need a fairly up to date version of SWI-Prolog.
    You need to be connected to the internet.
    There is a library file for each part of this assignment in the ailp/library directory. Each assignment library assignmentN_library.pl (where N is assignment number) holds the functions you will use. YOU SHOULD NOT CHANGE THIS FILE.

Running an assignment

    Change directory to the root folder (i.e. one that contains this readme.md).
    Update your candidate number (this is neither your user id nor your student number but a five-digit number that you can find on your SAFE profile page) in the assignmentN_12345.pl filename and candidate_number/1 predicate in this file. This is part of the assignment spec and hence failure to adhere to this will lose you marks!
    Start the assignment (if this doesn't work try chmod +x asilp.pl first) with ./ailp.pl assignmentN:
        ./ailp.pl assignment1 to start assignment1,
        ./ailp.pl assignment2 to start assignment2.
    The file with your answers, e.g. assignment1_12345.pl, will be consulted automatically.
    Start solving the assignment.
        To start the web server type command start.. This will give you an option to open a browser. Press Enter or type Y.
        Go to the web browser and press the Run button.
        To start with a fresh board type:
            reset. for assignment 1, or
            ailp_reset. for assignment 2.
        To stop the web server type command stop..
        Don't forget to use make. and reset. when you have made changes to the code.

Important notes

    Place all your code in the designated assignmentN_12345.pl file.
    Do not change the library files unless otherwise instructed.
    Do not use start/0, stop/0, reset/0 and ailp_reset/0 predicates in your answers.
    In your answers you can only use predicates from the library which are exported in the module definition (see the list below).

Assignment 1 	Assignment 2
ailp_show_move/2 	map_adjacent/3
ailp_start_position/1 	map_distance/3
ailp_show_complete/0 	agent_do_move/2
ailp_grid_size/1 	agent_do_moves/2
reset/0 	agent_current_energy/2
complete/1 	agent_current_position/2
new_pos/3 	agent_topup_energy/2
m/1 	agent_ask_oracle/4
next/1 	ailp_reset/0
start/0 	ailp_start_position/1
stop/0 	
toggle_switch/1 	
get_switch/2 	

Failure to comply with this will result in losing marks!
