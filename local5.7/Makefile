.PHONY: all help build run builddocker rundocker kill rm-image rm clean enter logs

all: help

help:
	@echo ""
	@echo "-- Help Menu"
	@echo ""  This is merely a base image for usage read the README file
	@echo ""   1. make build     - build docker container

build: NAME TAG builddocker

builddocker:
	/usr/bin/time -v docker build -t `cat TAG` .
