FROM python:3.8.5
COPY . /app
EXPOSE 5030
WORKDIR /app
RUN pip3 install -r requirements.txt
CMD ["uwsgi","app.ini"]