FROM scratch

LABEL maintainer="peter <pavlinskpeter@gmail.com>"
LABEL homepage="https://ppavlins.github.io"
ADD alpine-minirootfs-3.13.5-x86_64.tar.gz /

RUN apk add cmatrix

CMD ["/usr/bin/cmatrix"]
