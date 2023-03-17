FROM python:slim
WORKDIR /app
COPY gree_server.py requirements.txt .
RUN pip install -r requirements.txt
CMD python3 -u gree_server.py $IP $PORT $HOSTNAME
