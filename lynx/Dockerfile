FROM debian:9.4
LABEL maintainer "Volodymyr Khytskyi <khytsky.vladimir@gmail.com>"

RUN apt-get update \
    && apt-get install -y \
        lynx \
        --no-install-recommends \
    && rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "lynx" ]