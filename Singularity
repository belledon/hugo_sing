Bootstrap: docker
From: ubuntu:latest

%post

	dpkg --configure -a
	apt-get update
	apt-get install -y  build-essential \
						wget \
						git

						
	wget https://github.com/gohugoio/hugo/releases/download/v0.27/hugo_0.27_Linux-64bit.deb
	dpkg -i hugo*.deb
	rm hugo*.deb