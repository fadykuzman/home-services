FROM linuxserver/jellyfin:nightly

RUN apt-get update && apt-get install -y \
    python3-pip \
    && rm -rf /var/lib/apt/lists/* \
    && apt-get clean

RUN python3 -m pip install -U yt-dlp
