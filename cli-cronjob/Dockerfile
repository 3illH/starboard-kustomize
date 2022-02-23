FROM aquasec/starboard:0.14.1

FROM bitnami/kubectl:latest

COPY --from=0 /usr/local/bin/starboard /usr/local/bin/

ENTRYPOINT ["sh"]