FROM python
ENV PYTHONUNBUFFERED 1
WORKDIR /server
COPY requirements.txt /server/
RUN pip install -r requirements.txt
COPY . /server/