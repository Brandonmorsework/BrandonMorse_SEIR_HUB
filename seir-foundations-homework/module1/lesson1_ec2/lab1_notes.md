Run 1:

First run, I encountered an security group error with my ec2 instance. SSHing was possible, but the webpage loaded until the connection timed out. Assigning the proper security group during instance creation resolved this.

Run 2:

Second run went a lot smoother. I created a new launch template and AMI for practice. The inital sudo dnf install -y git was already completed previously, so this step finished instantly.

Run 3:



Run 4:

Run 5:

Run 6:

Run 7:

Mistake I Made:

- Not assigning the proper security group

- Creating an instance from an image that was not completely deployed

- 

Commands I know by heart:

- la -al

- clear
