FROM python:3.6

ENV LANG C.UTF-8

USER 0:0

RUN apk add --no-cache jq nodejs nodejs-npm

WORKDIR /app

# Copy data for add-on
COPY . /app

#RUN npm install

#CMD [ "node", "index.js" ]

