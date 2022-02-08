FROM python:2.7

RUN pip install flask requests

EXPOSE 8001

RUN mkdir /app

COPY ./api.py /app/aoi.py

CMD ["python","/app/api.py
