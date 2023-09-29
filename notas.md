## Para traer la url de las guitarras: Ambos funcionan
http://localhost:1337/api/guitarras?populate=imagen
http://localhost:1337/api/guitarras/6?populate=imagen
http://localhost:1337/api/guitarras/6?populate=*

http://localhost:1337/api/posts?populate=imagen
http://localhost:1337/api/curso?populate=imagen

## Strapi Dashboard(base de datos):
http://localhost:1337/admin/content-manager/collectionType/api::guitarra.guitarra?page=1&pageSize=20&sort=nombre:ASC

## Cloudinary:
https://console.cloudinary.com/console/c-6a0d5d127c393a962fa5d42c9bd9d9/media-explorer/guitarla

## EJECUTAR EL PROGRAMA:
- npm run develop
## PARA CONSUMIR LA API, NO USAR http://localhost:1337/api/guitarras?populate=imagen, sino http://127.0.0.1:1337/api/guitarras?populate=imagen
