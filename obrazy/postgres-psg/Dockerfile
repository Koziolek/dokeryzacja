FROM postgres

ENV POSTGRES_USER psg
ENV POSTGRES_PASSWORD psg
ENV LANG pl_PL.utf8

RUN localedef -i pl_PL -c -f UTF-8 -A /usr/share/locale/locale.alias pl_PL.UTF-8

COPY scripts/* /docker-entrypoint-initdb.d/.

