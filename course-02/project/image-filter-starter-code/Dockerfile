FROM node:12.16
ENV workdir /usr/app
WORKDIR $workdir
COPY ./package.json .
RUN npm i
ADD . .
EXPOSE 8082
CMD ["npm","run", "dev" ]
