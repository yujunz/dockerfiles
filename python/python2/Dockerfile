#
# Dockerfile for python2
#

FROM python:2-alpine

COPY pip.conf /etc/pip.conf

RUN pip install --no-cache-dir pipenv

CMD ["python", "--version"]
