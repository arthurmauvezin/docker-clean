# Docker clean

This bash script remove docker images from your computer with only one parameter.

## Example
Type:
```bash
docker-clean python 
```
To delete all image containing python in their name, whatever its name:
* python:2.7
* myregistry/python:3.6
* myregistry/my/really/long/path/python:latest

## Installation
On Linux environment execute install.sh script.
```
git clone https://github.com/arthurmauvezin/docker-clean.git
cd docker-clean 
chmod +x install.sh
./install.sh
```

## Usage
### Normal mode
```bash
docker-clean [IMAGE_NAME]...
```
### Dry run mode
```bash
docker-clean [IMAGE_NAME]... --dry-run
```
