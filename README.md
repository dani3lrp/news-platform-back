# news-platform-back
Aplicación capa backEnd que trae las noticias desde https://api.spaceflightnewsapi.net/v4/articles ordenadas y filtaradas en donde el usuario puede agregar noticias a sus favoritos.

Capa front se encuentra en https://github.com/dani3lrp/NewsPlatformFront

Capa persistencia ocupa h2

## Instrucciones de ejecución:

### Capa controller
Descarga la aplicación. En el directorio raíz de esta, abrir terminal y ejecutar:
./gradlew bootRun
### Capa Frontend
Descarga la aplicación capa front (link arriba). En el directorio raíz de esta, abrir terminal y ejecutar
ng serve

## Requisitos
El ordenador de ejecución debe tener instalada maquina virtual Java, NodeJs y Angular

## Ejecutar la Aplicación

1. Postman usando la url `http://localhost:8081/api/v1/news/favorites`.
2. base de datos en memoria H2  `http://localhost:8081/h2-ui/login.jsp`.

Nota: Para acceder a H2, debes colocar `Driver class: org.h2.Driver`, `JDBC URL: jdbc:h2:mem:testdb`, `User Name: sa` y password debe estar vacio.
