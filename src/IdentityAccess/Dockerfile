FROM quay.io/keycloak/keycloak:16.1.0

WORKDIR /app
COPY ./IdentityAccess/config/dev-realm.json ./dev-realm.json

ENV KEYCLOAK_USER=admin
ENV KEYCLOAK_PASSWORD=P@ssw0rd
ENV PROXY_ADDRESS_FORWARDING=true
ENV KEYCLOAK_IMPORT=/app/dev-realm.json
