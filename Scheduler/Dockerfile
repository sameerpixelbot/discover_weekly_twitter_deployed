FROM python:3.8.5
COPY . /app
EXPOSE 5020
WORKDIR /app
RUN pip3 install -r requirements.txt
CMD ["python","run.py"]