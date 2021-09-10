FROM 283786857250.dkr.ecr.eu-west-1.amazonaws.com/rdl-biome-base
ARG HAB_AUTH_TOKEN
ENV HAB_ORIGIN=raspberry-dream-labs
ENV HAB_BLDR_URL=https://bldr.biome.sh
ENV HAB_AUTH_TOKEN=$HAB_AUTH_TOKEN
RUN bio origin key download --secret raspberry-dream-labs
RUN git clone https://github.com/robert-rdl/biome-habitats.git
RUN chmod +x ./biome-habitats/scripts/build-latest-reticulum.sh
