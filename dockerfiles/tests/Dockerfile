FROM node:14
WORKDIR /home/karol/Documents/PROJECTS/docker1/app
COPY package.json /home/karol/Documents/PROJECTS/docker1/app
RUN npm install
COPY . /home/karol/Documents/PROJECTS/docker1/app
CMD ["npm", "test"]