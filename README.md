# testmyids as a service
Deploy your own instance of the testmyids service. This's the EICAR test for network intrusion detection systems

## To build, run the docker container: 
1: Clone the repo <br>
2: Navigate to the directory and setup the container with the follwong command <br>
    <b>docker-compose up --detach</b><br>
Command will setup Nginx web server and use the index.html as homepage. It will expose the nginx logs files in cwd. You can change the ports to suit you.<br>
You can access the service by navigating to your browser eg http://.x.y.z.a:8000 <br>
You can change the 8000 port suit your deployment needs by changing the 8000 value

