FROM node:12
WORKDIR /home/node/app
COPY app /home/node/app 
RUN npm install
CMD npm run app
EXPOSE 9999

# inside the directory of this file... run these commands 

# docker build -t nodeapp .
# docker run --name nodeapp -p 9999:9999 nodeapp