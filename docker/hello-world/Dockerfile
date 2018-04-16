FROM python:2.7-slim

WORKDIR /app

ADD . /app

RUN pip install --trusted-host pypi.douban.com -r requirements.txt

EXPOSE 80

ENV NAME minsh

CMD ["python", "app.py"]