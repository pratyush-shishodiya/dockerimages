FROM ubuntu

RUN apt-get update

COPY ./app.sh ./app.sh

WORKDIR .

RUN chmod +x app.sh

CMD ["./app.sh"]