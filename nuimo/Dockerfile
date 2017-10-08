FROM %%BASE_IMAGE%%

# Add env
ENV LANG C.UTF-8

RUN apk add --no-cache jq nodejs nodejs-npm

WORKDIR /app

# Copy data for add-on
COPY . /app

#RUN npm install

#CMD [ "node", "index.js" ]

