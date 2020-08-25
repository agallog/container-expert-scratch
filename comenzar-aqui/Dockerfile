FROM alpine

#creo el app
WORKDIR /app

#add vs copy
COPY myapp.sh /app/

RUN ls /app && chmod +x myapp.sh && apk add --update bash

#ENTRYPOINT es el ocmando que va correr  y va mantener el contenedor arriba
CMD [ "./myapp.sh" ]