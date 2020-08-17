# springBootDockerTest
building docker image from maven


1. Run: ./mvnw spring-boot:build-image -Dspring-boot.build-image.imageName=docker_image
2. Run: docker run -p 8080:8080 -t docker_image

then by using curl check result:
C:\Users\aleks>curl http://localhost:8080/test
Docker test
