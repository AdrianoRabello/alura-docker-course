
# image reference
FROM node:latest

# copy <host diretory, container directory> 
COPY ./volume-exemplo /var/www

# setting directory to work 
WORKDIR /var/www

# run commands to install dependencies 
RUN npm install

# to run commands after container start
ENTRYPOINT [ "npm", "start" ] 

# Expose container port 
EXPOSE 3000
