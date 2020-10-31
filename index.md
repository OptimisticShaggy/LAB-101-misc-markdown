---
title: "The Beautiful Docker"
permalink: /
layout: default
---

# Docker
[Docker Tutorial for Beginners](https://www.youtube.com/watch?v=3c-iBn73dDE&t=7510s) - This Tutorial that Nana uploaded goes through three hours about Docker for beginners.

### What is Docker?
Docker is an Containerized Virtualization Engine that allows the user to deploy and test code within Containters. :open_mouth: These containers are flexible with the ability to bring up and down different containers with one command. Would allow a team to test software of the same version across many different OS versions. Can even be used to run full, fledged web programs. For example; Betty could have version 3 of Ruby, Bob has version 5 of Ruby. With Docker, the user could containerize version 4 of Ruby, the version that is needed for their production project. :grinning: *Note: I don't know the versions of Ruby, please do not quote me on the versions*

### How does Docker work?
With the mainstream Operating Systems, you are given a GUI to interact with the engine. With Linux, you would only use a CLI unless you get a unofficial GUI application built by a a developer. Docker itself uses the engine and you talk to the engine via API through either the GUI or CLI. *There is an unofficial web application developed by a developer called **Portainer**[^1].* :open_mouth:

### Docker Vs. Virtual Machine
Docker allows a user to containerize code or applications. A Virtual Machine is a full fledged Operating System. While Virtual Machines serve a great use, they can be seen as bulky. Docker grabs only what is needed (assuming your only asking for the bare) and pushing it through.

## Docker Features

### Docker Compose
This feature allows a user to run muliple containers with one command, orchestrating how containers will interact with the environment. 

### Docker Swarm
Multiple computers with multiple containers, Swarms encompass more than just workers, you also needs managers. You could have multiple of both. Managers tell what the Workers to do, what process they should run.

## Personal Uses for Docker
Docker can be used for more than just testing reasons, it can be used for production uses as well. Though, prodcution use cases is still questionable. You could easily package many different applications on your own and just run them. As time passes here; I plan on taking advantage of many images from this source, **LinuxServer** [^2]. A community of many users that implement different images consiting of many different applications,  shipped and ready to go. I would like to take a few of the Raspberry PI computers around my house and set up a swarm, consiting of many of these devices for not only backup purposes but also for smart home purposes. :smiley:

[^1]: Portainer Website: [Portainer](https://portainer.io)

[^2]: LinuxServer Website: [LinuxServer](https://linuxserver.io)
