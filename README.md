# angular_docker

This requires the usage of a volume. in this volume the files to the app should be present.
<h1> Usage</h1>

To build the image use the following one liner:

```shell
docker build -t aName:tag .
```

the following one-liner will start a container from the image and start serving your app from the volume.

```shell
docker run -d -p your_port:4200 -v /your/angular/app:/opt -w /opt nameOfImage:tag
```
