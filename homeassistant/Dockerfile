FROM homeassistant/raspberrypi3-homeassistant:latest
VOLUME /config
RUN rm ./config/configuration.yaml
COPY configuration.yaml /config
VOLUME /config


