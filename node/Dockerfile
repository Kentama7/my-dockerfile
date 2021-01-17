FROM node:14.4.0-alpine3.12
RUN yarn global add typescript ts-node typesync \
    && addgroup -S appgroup && adduser -S appuser -G appgroup
USER appuser
WORKDIR /app
