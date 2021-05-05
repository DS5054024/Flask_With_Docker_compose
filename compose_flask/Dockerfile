FROM python:3.8
RUN yum update -y && \
    yum install -y python3-pip python-dev
ADD . /code
WORKDIR /code
RUN pip install --upgrade pip
RUN pip install -r ./requirements.txt
CMD python3 app.py
