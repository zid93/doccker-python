FROM tiangolo/uwsgi-nginx-flask:python3.6-alpine3.7
RUN apk --update add bash nano
ENV STATIC_URL /static
ENV STATIC_PATH /Users/detikcom/PycharmProjects/doccker-python/app/static
COPY ./requirements.txt /Users/detikcom/PycharmProjects/doccker-python/requirements.txt
RUN pip install -r /Users/detikcom/PycharmProjects/doccker-python/requirements.txt

