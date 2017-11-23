# angular_docker

<h1> Usage

To build the container use the following one liner:

`docker build -t aName:tag .`

the following one-liner will run the container and start serving your app.

`docker run -d -p your_port:4200 -v /your/angular/app:/opt -w /opt nameOfImage:tag` 
