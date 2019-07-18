# FROM ubuntu:16.03
FROM node:10-alpine

WORKDIR /app
COPY . /app

RUN npm install
# RUN cd /app && npm install
# RUN apt-get update \
#     && apt-get install -y nodejs \
#     && cd /app && npm install;

#
# CMD ["/app", "npm start"]
CMD ["npm", "start"]


# RUN apt-get update
# RUN apt-get upgrade -y
# RUN apt-get install -y nodejs ssh mysql
# RUN cd /app && npm install

# CMD mysql & sshd & npm start