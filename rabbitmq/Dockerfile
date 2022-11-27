FROM python:3.8-slim-buster
WORKDIR /
COPY requirements.txt ./
RUN pip3 install -r requirements.txt
COPY receive.py ./
CMD [ "python3 ./receive.py"]