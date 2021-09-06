FROM rdl-biome-base
ARG HAB_AUTH_TOKEN
ENV HAB_ORIGIN=raspberry-dream-labs
ENV HAB_BLDR_URL=https://bldr.biome.sh
RUN git clone https://github.com/robert-rdl/biome-habitats.git
RUN chmod +x ./biome-habitats/scripts/build-latest-reticulum.sh
