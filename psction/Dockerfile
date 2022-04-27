FROM python:3.8.0

# ARG django_settings="psction.psction"

# ENV PYTHONDONTWRITEBYTECODE 1
# ENV PYTHONUNBUFFERED 1
# ENV DJANGO_SETTINGS_MODULE=$django_settings
# ENV DJANGO_PORT=8000

RUN apt-get update

WORKDIR /src/

COPY requirements.txt /src/

COPY . .
RUN pip install -r requirements.txt

# COPY entrypoint.sh /src/

# RUN chmod +x /src/entrypoint.sh
