# Use an official Python runtime as a parent image
FROM python:3.6-slim

ADD requirements.txt /
RUN pip install -r /requirements.txt

ENTRYPOINT ["python"]
