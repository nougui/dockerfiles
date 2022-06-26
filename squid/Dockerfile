FROM alpine
RUN apk update && apk add squid
CMD ["squid","--foreground","-f","/etc/squid.conf"]
