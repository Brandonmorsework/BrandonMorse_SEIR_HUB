Important Scripts: 

sudo dnf install -y git

git clone https://github.com/BalericaAI/SEIR-Foundations.git

bash SEIR-Foundations/module1/lesson1_ec2/API/install/install.sh

/opt/balerica-bank/venv/bin/python3 -m pip install --upgrade pip

cd /opt/balerica-bank
source venv/bin/activate

uvicorn app.main:app --host 0.0.0.0 --port 8000


----------------------------------------


Run 1:

First run, I encountered an security group error with my ec2 instance. SSHing was possible, but the webpage loaded until the connection timed out. Assigning the proper security group during instance creation resolved this.

Run 2:

Second run went a lot smoother. I created a new launch template and AMI for practice. The inital sudo dnf install -y git was already completed previously, so this step finished instantly.

Run 3:

This run required the git download once again, but otherwise went smoothly. This was also launched from the first launch template used and renamed through a tag: "DDD"

Run 4: 

Creation of this instance and SSHing into this ran a lot faster and smoother

Run 5:

Creation of this instance and SSHing into this ran a lot faster and smoother. Copied important scripts to run in order for faster connection to the banking API

Run 6: 

Run 7:

Mistake I Made:

- Not assigning the proper security group

- Creating an instance from an image that was not completely deployed

- 

Commands I know by heart:

- la -al

- clear
