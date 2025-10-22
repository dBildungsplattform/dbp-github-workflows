
FROM jnorwood/helm-docs:v1.14.2

RUN apk add --no-cache bash
RUN apk add --no-cache git

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/bin/bash", "-c", "/entrypoint.sh"]
