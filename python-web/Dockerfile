FROM python

WORKDIR /app

ENV TZ="Asia/Kuala Lumpur"

COPY . .

USER www-data

CMD [ "python", "server.py" ]

# docker build -t hello-world-python .
# docker run -d --name hello-world-python -p 8080:8080 hello-world-python
# docker container stop hello-world-python
# docker container rm hello-world-python