Step 1: Install node server

sudo apt-get install npm

npm install

node server.js

Step 2: Install docker and docker-compose

https://docs.docker.com/install/linux/docker-ce/ubuntu/

https://docs.docker.com/compose/install/

Step 3: Build image

sudo docker build -t <imagename:latest> [PATH]

Step 4: sudo docker images

Step 5: sudo docker run -it <imagename:version>

Step 6: sudo docker run -it -d -p <outside_port_num>:<inside_port_number> <imagename:version>



