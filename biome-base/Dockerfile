FROM ubuntu:18.04
ADD https://github.com/biome-sh/biome/releases/download/bio-1.5.75/bio-1.5.75-x86_64-linux /usr/bin
RUN mv /usr/bin/bio-1.5.75-x86_64-linux /usr/bin/bio
RUN chmod +x /usr/bin/bio
RUN apt-get update && apt-get install -y \
git \
&& rm -rf /var/lib/apt/lists/*
