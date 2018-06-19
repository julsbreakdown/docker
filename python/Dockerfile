FROM python:3-onbuild
COPY . /usr/src/app
ENTRYPOINT ["bash", "docker-entrypoint.sh", "python", "api.py"]
CMD  ["--no-daemonize"]

