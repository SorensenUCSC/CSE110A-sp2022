---
title: "Homework Setup"
layout: single
classes: wide
---

This guide walks you through developing and running your homeworks using a Docker container running Ubuntu.

## Install Docker
Follow instructions [here](https://docs.docker.com/get-docker/).

## Download the container
Run the following command:
```
docker pull reeselevine/cse113:latest
```
When running, the container includes everything necessary for the homework to work correctly, namely `python3`, a C++ compiler, and `make`. It also includes two text editors, `vim` and `emacs`. If you'd like another text editor included in the image, please let us know.

Make sure that you regularly pull before running. We may update the container as the class goes on and pulling ensures you'll have the most up-to-date environment when developing.

## Development
Homework skeletons will be available to download using `wget`. Download the homework and unzip it. You can either work on your code outside the container, using a text editor or IDE of your preference, or you can work on your code inside the container using a terminal based text editor like vim or emacs.

When you're ready to start the container make sure you're in the top level homework directory (for example, for homework 1 your current directory should be "homework1_packet", or wherever you extracted the code to). Then, run the following command:

```
 docker run -v "$(pwd)":/assignments -it reeselevine/cse113:latest
```
Note: If you're using CMD on Windows (not Powershell), replace this command with:
```
docker run -v %cd%:/assignments -it reeselevine/cse113:latest
```
You should be running inside the container at this point. Running `ls` should list your files. At any point, to exit the container just type `exit`.

At this point, you can edit your code and run it by following the instructions on the homework. Any changes you make to your files inside the container will persist when the container exits.

We recommend keeping your homework files under source control using git or another tool, since this will help with keeping track of your changes and making sure you don't lose your work.

## More details about Docker
While the details of running docker containers are unnecessary for this course, it might be helpful to understand what each part of the above commands are doing.
- `docker pull` downloads the specified container, which in this case is `reeselevine/cse113:latest`, where `reeselevine/cse113` is the image name and `latest` is the tag. Docker allows multiple tags for the same image, but for this course we will most likely only be using the default `latest` tag for images.
- `docker run` runs the specified container.
- `-v` mounts a volume from the host (your computer) to the docker container. We are mounting the current host machine directory to the directory `/assignments` inside the container.
- `-it` gives us an interactive, terminal based session. Without this, the container would immediately exit.