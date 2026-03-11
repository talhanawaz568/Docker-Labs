FROM ubuntu:latest
RUN useradd -m appuser
USER appuser
COPY example-script.sh /home/appuser/example-script.sh
CMD ["bash", "/home/appuser/example-script.sh"]


