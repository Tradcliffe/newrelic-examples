#https://docs.newrelic.com/docs/apm/agents/python-agent/installation/install-python-agent-docker/
FROM python:3.8-slim-buster

RUN pip install --no-cache-dir newrelic

ENTRYPOINT ["newrelic-admin", "run-program"]
