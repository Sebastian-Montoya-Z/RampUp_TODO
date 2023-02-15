FROM python:3.6
WORKDIR /log
COPY . .
RUN ls -la
RUN pip3 install -r requirements.txt
CMD REDIS_HOST=redis REDIS_PORT=6379 REDIS_CHANNEL=log_channel python3 main.py