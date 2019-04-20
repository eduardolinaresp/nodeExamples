FROM node:lts-alpine 

RUN mkdir /myapp
WORKDIR /myapp
COPY . /myapp
RUN npm install

EXPOSE 8888

# Start the main process.
CMD [ "node" ]