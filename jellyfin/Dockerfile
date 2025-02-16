FROM jellyfin/jellyfin

RUN apt-get update && apt-get install -y \
    python3-pip pipx \
    && rm -rf /var/lib/apt/lists/* \
    && apt-get clean

RUN pipx install yt-dlp

