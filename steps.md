# Instructions to set up DVWA on local

## 1.Install Docker on your machine (Ubuntu)
- Update your packages.
`sudo apt-get update` 
- Install docker.io
  `sudo apt install docker.io` 
- Run docker.io
`sudo systemctl start docker` 
`sudo systemctl enable dockerr` 

Check if Docker is running
`docker –version`
If you are using windows, you can install Docker Desktop or Docker CLI as per your preference.


## 2.Install the dvwa docker image on your local, at port 80 or any other unused port.

Run `docker run --rm -it -p 80:80 vulnerables/web-dvwa`
## 3. Access the dvwa website on your local at http://localhost:8080/. (Make sure the image is running).



