### installation with docker

# Run latest Docker version
docker run -it -p 8080:8080 -v `pwd`/mydata:/label-studio/data heartexlabs/label-studio:latest

# Now visit http://localhost:8080/
