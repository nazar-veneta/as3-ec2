FROM alpine
RUN apk update
RUN apk add mysql-client
EXPOSE 3306
WORKDIR /opt
COPY . .
CMD ["sh", "import.sh"]
