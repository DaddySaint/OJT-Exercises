FROM python:3.10.12

WORKDIR /app

RUN apt-get update
RUN apt-get install -y jq vim

COPY . .

RUN chmod +x entrypoint.sh

EXPOSE 5000

ENTRYPOINT ["./entrypoint.sh"]

