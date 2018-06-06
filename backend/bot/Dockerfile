FROM python:3.6.5


RUN mkdir /app
COPY bot/requirements.txt /app
WORKDIR /app
RUN pip install -r /app/requirements.txt
COPY bot/ /app/

CMD python -u -m start_listening