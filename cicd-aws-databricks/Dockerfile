ARG PYTHON_TAG=3.9
FROM python:${PYTHON_TAG}-alpine

RUN apk add --no-cache --update git jq curl groff && \
    pip3 install --no-cache-dir awscli envsubst databricks-cli

