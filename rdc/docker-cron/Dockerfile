FROM alpine:latest

RUN apk add --no-cache tzdata logrotate
ENV TZ Asia/Shanghai

COPY ./entrypoint.sh /
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]