# user-service

Detta dokument beskriver stegen för att bygga, tagga och pusha Docker-image till Docker Hub. Följ dessa instruktioner för att ladda upp din Docker-image.

Bygg image för user-service

1. Navigera till katalogen där din Dockerfile för user-service finns:


# cd ../user-service

2. Bygg Docker-image:

# docker build -t ditt_användar_namn/user-service-compose:1.0 .

Se till att du är inloggad på Docker Hub och använd ditt användarnamn på Docker Hub.

3. Tagga image:

# docker tag ditt_användar_namn/user-service:1.0 ditt_användar_namn/user-service-compose:1.0

4. Pusha image till Docker Hub:

# docker push ditt_användar_namn/user-service-compose:1.0

Om du är inloggad på Docker Hub och klickar på "Repositories" kan du se imagen du har pushat upp.