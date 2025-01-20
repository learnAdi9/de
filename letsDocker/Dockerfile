FROM python:3.13.1

RUN pip install pandas

WORKDIR /coolApp
COPY pipe_aj.py pipe_aj.py

ENTRYPOINT ["python", "pipe_aj.py"]