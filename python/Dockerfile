FROM python:3.7.3
ENV PYTHONUNBUFFERED 1
EXPOSE 80
EXPOSE 25
COPY ./requirements.txt /requirements/
WORKDIR /requirements
RUN pip install -r requirements.txt