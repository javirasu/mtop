NAME 
        mtop - minimalist top command line 

SYNOPSIS
        mtop [OPTION] 

DESCRIPTION
mtop provides a minimalistic dynamic real-time view of a running system. It can display several modes, all of them intended to have a clean view of the system processes. 


COMMAND-LINE Options
The command-line syntax for mtop consists of:
        -i, --interval 
                seconds between command outputs 
        -p, --pattern 
                pattern to filter the processes in monitor mode 
        -l, --lines 
                lines to display in monitor mode 
        -m, --mode 
                select in which mode to run 
        --help 
                display this help and exit 

MODES
different running modes are supported when using the --m (--mode) command line option:
        monitor  - shows CPU, Memory and processes running in the system 
        min      - minimalistic mode shows only CPU and Memory 
        agg      - aggregate CPU and Memory by user in the system 

OPERATION
while mtop is running in monitor or aggregated mode, there are several keys that can be used to modify the program behaviour: 
                key      description
                c        order processes by CPU usage 
                m        order processes by Memory consumption 
                q        quit
