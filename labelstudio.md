### label studio di install di server dengan IP 
http://172.30.30.136:8080
username&passwordnya: secret j

### installation with docker

# Run latest Docker version
docker run -d -it -p 8080:8080 -v `pwd`/mydata:/label-studio/data heartexlabs/label-studio:latest


