1.Linux Architecture
Kernel:-The kernel is main part of ubuntu where all task like memory management,process management,file management is done.In ubuntu without kenrel work is not possible in it.
User Space:-It is the space where user application and task runs in ubuntu.It can be access using system call.It is not possible to access using hardware.
init/systemd:-The init in ubuntu means initial where 1st step of process is done from init the process or task start to execute.init is also a starting point or entry point of any task in it.It control entire system lifecyle.Every process start from init has PID=1.
2.Process Cretaed and Management:-
Process:-It is a running instance of a program.
Process creation:-It is created using fork()it is used to make a parent copy and exec() is used to take load and handle the load of the task or program.
Process Management:It is managed using scheduler using with task should run first and how much time a specific task should run.It is run in process state where step by step process is followed.
3.Systemd Process
Systemd Process:It is the process in ubuntu where behind the device task is perform when we press power on then BIOS start then GNU CRUB will load a linux and kernel after that ubuntu will load and then init (PID=1)will done after that systemctl will proces and control the process and ststemctl will manage or remote the process in it.
It is step by step proces that when we press power on then which interface come and after that our main screen is viewed and then how our main screen is viewed in it.
