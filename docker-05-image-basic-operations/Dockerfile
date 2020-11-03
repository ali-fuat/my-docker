FROM python:alpine
COPY . /app
WORKDIR /app
RUN touch file1.txt
RUN pip install -r requirements.txt
EXPOSE 80
CMD python ./welcome.py