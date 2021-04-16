# HW3.pfind

1. To start this homework, I have create directory /home/s21900335//OS/HW3

2. I have used fork to create child process which is child. Also, I've used signal mechanism to receive a termination command from user as if a user press crtl+q, then the message "Do you want to quit?" appears and if 'y' is pressed then the program ends. Also I have used sigchld_handler to kill a child process.

3. I have implemented sender and receiver by using execl. However, I could not use siganl mechanism because whenenver I used it the communication does not work. Also, when I use second child process, the communication did not work well. 
