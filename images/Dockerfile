 # Use the ubuntu base image 
FROM ubuntu


# set the working directory insice the container 

WORKDIR /app

# copy a script file to the container
COPY script.sh .

# make the scripts executable

RUN chmod +x script.sh


# run the scripts when yhe container starts 

CMD ["./script.sh"]

