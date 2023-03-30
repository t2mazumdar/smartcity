FROM python:alpine3.7
COPY . /app
WORKDIR /app
RUN pip install flask
RUN pip install --upgrade pip
EXPOSE 5000
CMD python ./appv3.py
