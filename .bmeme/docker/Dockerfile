FROM perl:5.34-slim

ARG FIX_UID
ARG FIX_GID

RUN groupadd -g $FIX_GID -o perl
RUN useradd -m -u $FIX_UID -g $FIX_GID -d /usr/src/app -o -s /bin/bash perl
USER perl
