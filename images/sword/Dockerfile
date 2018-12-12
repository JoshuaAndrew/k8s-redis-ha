FROM bash:4

RUN apk add bc bind-tools redis

COPY ["run.sh", "/"]

CMD ["/run.sh"]

ENTRYPOINT ["bash", "-c"]
