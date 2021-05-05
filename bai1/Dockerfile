FROM gcc:latest

COPY . /usr/src/appc

WORKDIR /usr/src/appc

RUN gcc -o ltc test.c

CMD ["./ltc"]