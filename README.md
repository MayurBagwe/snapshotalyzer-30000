# snapshotalyzer-30000
Demo project to manage AWS EC2 instance snapshots 


##About
This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots

## Configuring

shotty.py uses the configuration file created by the AWS cli 

`aws configure --profile shotty`


## Running

`pip env python shotty/shotty.py`


#Commands
 list       List EC2 instances
 start      Start EC2 instances
 stop       Stop EC2 instances
 terminate  Terminate EC2 instances

*command* is list, start, or stop
*project* is optional