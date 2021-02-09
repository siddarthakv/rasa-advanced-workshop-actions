FROM rasa/rasa_sdk:2.2.0
USER root

COPY actions /app
COPY requirements.txt /app
COPy woskshop_data.csv /app

RUN pip3 install -r requirement.txt
CMD ["start","actions","--actions","--debug"]

USER 1001