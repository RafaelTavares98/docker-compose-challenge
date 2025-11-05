FROM python:3.10

WORKDIR /app
COPY . /app

RUN apt-get update && apt-get install -y bash

ENTRYPOINT ["bash", "vllm-cpu.sh"]
