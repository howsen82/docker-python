FROM python:3

WORKDIR /src

RUN pip install --no-cache-dir feedparser

COPY . .

USER www-data

CMD [ "python", "/src/printheadlines.py" ]

# docker build -t python-atom .
# docker run python-atom