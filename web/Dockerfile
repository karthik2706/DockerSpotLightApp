FROM hypriot/rpi-node:0.12.0

ADD package.json /code/
WORKDIR /code
ADD . /code

RUN npm install
RUN npm update

CMD ["node","server.js"]
