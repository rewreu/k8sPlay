FROM python:3.6
RUN pip install flask
ENV FLASK_APP=hello-world
COPY hello-world.py ./
ENTRYPOINT ["python","./hello-world.py"] 