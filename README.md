# Handcrafting a Container Image for a Website using Apache Web Server Image

## Overview

This project demonstrates the process of obtaining the base Apache image, modifying a container from that image, and creating a new image from the modified container. A key focus is on cleaning up the container after modification, and we'll conclude by running multiple containers from the new image.

## Prerequisites

- Docker installed.
- Logged into an EC2 Linux instance or your home Linux environment (Ubuntu).

## Steps

1. **Get and Run the Base Image as Template** 

2. **Install Tools and Add the Website Code in the Container** 

3. **Create an Image from the Container Template**
   
4. **Clean up the Template for a Second Version**
  
5. **Run Multiple Containers from the Cleaned Image**
  

## Implementation

- Bash commands with comments in the  [bash_script file](https://github.com/DimitryZH/handcrafting-container-image/blob/main/bash_script.sh)
- Versioned images on [Docker Hub](https://hub.docker.com/repository/docker/dmitryzhuravlev/widgetfactory/general)

## Summary

Creating a container image by hand allows for quick testing using Linux commands. It enables automation in building purpose-built containers from an existing image. Handcrafting saves resources, as seen in the significant size reduction from v1 to v2  (screenshot below). This technique is valuable for troubleshooting problems in existing containers, allowing you to save and run containers from a specific state for debugging.

![images-size](https://github.com/DimitryZH/handcrafting-container-image/assets/146372946/4f1cb702-4321-42ef-9b26-90b60c0fbbf0)
