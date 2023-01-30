FROM node:14.4.0-alpine AS development

RUN mkdir /project
WORKDIR /project

COPY . .


RUN npm install


ENV HOST=0.0.0.0
CMD ["npm", "run", "dev", "--", "--hot"]
