# instructions

## setup

'''
docker build -t my-apache2 .
docker run -dit --name web_app -p 80:80 my-apache2
'''

## cleanup

'''
docker ps -a
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
docker images
docker rmi *id*
'''
