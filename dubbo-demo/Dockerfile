FROM harbor.example.com/kubernetes/openjdk:8-jre-alpine

COPY target/ROOT /ROOT

ENTRYPOINT ["sh", "/ROOT/bin/start.sh"]
