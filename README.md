# Pushing and Pulling to and from Docker Hub steps

## Getting an image from Docker Hub
### docker run --rm -p 3333:3333 rocker/verse
### docker pull rocker/verse 
### Log in on https://hub.docker.com/
1. Click on Create Repository.
2. Choose a name (e.g. verse_gapminder) and a description for your repository and click Create.
3. Log into the Docker Hub from the command line
4. docker login --username=yourhubusername --email=youremail@company.com
5. Check the image ID using: docker images
6. and tag your image

docker tag bb38976d03cf yourhubusername/verse_gapminder:firsttry

7. Push your image to the repository you created

docker push yourhubusername/verse_gapminder


```
## Docker hub repo link
https://hub.docker.com/repository/docker/jehanne123/sca_school_assignment
