# python-script

sudo su -

sudo yum update -y
sudo yum install -y docker
sudo systemctl start docker
sudo systemctl enable docker

sudo yum install python3 -y

sudo yum install python3-pip -y

pip3 --version

mkdir docker-monitor
cd docker-monitor

#Use a Virtual Environment: 
----------------------------

pip3 install virtualenv

virtualenv docker-monitor-env

source docker-monitor-env/bin/activate

vi docker_monitor.py


duplicate tab for creating sample docker cointainer:
-----------------------------------------------------

dublicate

sudo su -

docker run --name stress-test --rm -it progrium/stress --cpu 4


=====================================================================================

go to python script tab and run the script:

python docker_monitor.py



=========================================

