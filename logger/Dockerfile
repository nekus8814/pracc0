FROM alpine
RUN apk add --no-cache bash nano curl
COPY checker /checker
RUN chmod +x /checker
CMD ["/checker"]
