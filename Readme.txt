

# Image bauen
docker build -t htmltest .

# Image starten
docker-compose up

#Image taggen
docker tag testhtml peterdahm/test:dev

#Image pushen
docker push peterdahm/test:dev