FROM ubuntu AS builder

RUN apt-get update && apt-get install -y --no-install-recommends  build-essential libssl-dev libffi-dev

FROM scratch

COPY DataReceiver.e .

CMD ["./DataReceiver.e"]