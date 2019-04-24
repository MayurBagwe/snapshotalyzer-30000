# snapshotalyzer-30000
Demo project to manage AWS EC2 instance snapshots 


##About
This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots

## Configuring

shotty.py uses the configuration file created by the AWS cli 

`aws configure --profile shotty`


## Running

`pipenv run python shotty/shotty.py "<command>" "<subcommand>" "<--project=PROJECT_TAG>"`
 To Start instances
 pipenv run python shotty/shotty.py "instances" "start" "--project=Valkyrie"
 
 To list volumes
  pipenv run python shotty/shotty.py "volumes" "list" "--project=Valkyrie"
  
  

#Commands to handles instances
 list       List EC2 instances
 start      Start EC2 instances
 stop       Stop EC2 instances
 terminate  Terminate EC2 instances

 
#Commands to handles instances,volumes and snapshots
*command* is instances, volumes, or snapshots
*subcommand* - depends on command
*project* is optional