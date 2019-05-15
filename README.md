**NAME**<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mtop - minimalist process monitor for Unix systems  <br/>

**SYNOPSIS**<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mtop [OPTION]<br/> 

**DESCRIPTION**<br/>
mtop provides a minimalistic dynamic real-time view of a running system. It can display several modes, all of them intended to have a clean view of the system processes.<br/>


**COMMAND-LINE Options**<br/>
The command-line syntax for mtop consists of:<br/>
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-i, --interval<br/> 
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;seconds between command outputs<br/> 
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-p, --pattern<br/>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pattern to filter the processes in monitor mode<br/> 
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-l, --lines<br/>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lines to display in monitor mode<br/> 
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-m, --mode<br/> 
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;select in which mode to run<br/> 
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--help<br/> 
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;display this help and exit<br/> 

**MODES**<br/>
different running modes are supported when using the --m (--mode) command line option:<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;monitor  - shows CPU, Memory and processes running in the system <br/>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;min      - minimalistic mode shows only CPU and Memory<br/> 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;agg      - aggregate CPU and Memory by user in the system <br/>

**OPERATION**<br/>
while mtop is running in monitor or aggregated mode, there are several keys that can be used to modify the program behaviour:<br/><br/> 
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_key_&nbsp;&nbsp;&nbsp; _description_<br/>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; order processes by CPU usage<br/> 
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;m&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; order processes by Memory consumption<br/> 
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;q&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; quit<br/>
