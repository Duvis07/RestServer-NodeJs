# RestServer-NodeJs

## Usuarios
## Post,Get -->http://localhost:8080/api/usuarios
## Body{
    "nombre": "sofkaU",
    "google":true,
    "correo":"sofkausofka@gmail.com",
    "password":"123456",
    "rol":"ADMIN_ROLE"

}

![image](https://user-images.githubusercontent.com/96325513/207944108-5b87bfde-a918-4289-a513-d14a2e69e456.png)


## Delete, Update -->http://localhost:8080/api/usuarios/id 
## heards--> x-token + token para poder eliminar un usuario de la bd

 ## Login-->http://localhost:8080/api/auth/login
## Body{
 "correo":"sofkausofka@gmail.com",
 "password":"123456"
}

![image](https://user-images.githubusercontent.com/96325513/207943946-200d3552-fdad-4df5-a9ee-127c12297f89.png)



## Autenticacion con google  
## post-->http://localhost:8080/api/google
## Body{
    "id_token":"token de google"
}

![image](https://user-images.githubusercontent.com/96325513/207945225-b302f2f3-d719-42a5-a30c-81ab27f4a0aa.png)


## Categorias
## Get, Post-->http://localhost:8080/api/categorias + token en los headers
## Body{
    "nombre":"categoria 1",
}

![image](https://user-images.githubusercontent.com/96325513/207944396-d018a2ba-115c-4616-99e9-488bc3b217d4.png)


## Delete, Put-->http://localhost:8080/api/categorias/id


## Productos

## Get, Post-->http://localhost:8080/api/productos + token en los headers
## Body{
    "nombre":"producto 1",
    "precio":100,
    "descripcion":"descripcion del producto",
    "disponible":true,
    "categoria":"id de la categoria"
     "usuario": "id del usuario"
}

![image](https://user-images.githubusercontent.com/96325513/207944853-97b64d90-2744-4b21-b627-03a6f461a38b.png)



## Buscar

## Get-->http://localhost:8080/api/buscar/coleccion/termino + token en los headers
 
## Body{
   {
    "coleccion": "productos",
    "termino": "cebolla"
}

![image](https://user-images.githubusercontent.com/96325513/207944602-330b6e17-ea6f-4d5a-af6e-8ebf9fb63b32.png)



## Subir archivos

## Post-->http://localhost:8080/api/upload 

![image](https://user-images.githubusercontent.com/96325513/207941281-fbe5fbf5-e700-4f8c-8942-f16d5672c151.png)


## Actualizar imagen de las colecciones

## Put -->http://localhost:8080/api/uploads/usuarios/63974647ac7dff650c38f287

![image](https://user-images.githubusercontent.com/96325513/208129075-00f56731-aa14-481e-ad1a-b8200b5b3f43.png)


## Mostrar imagenes de las colecciones

## Get -->http://localhost:8080/api/uploads/usuarios/63974647ac7dff650c38f287

![image](https://user-images.githubusercontent.com/96325513/208137972-8b3ba551-c415-48c8-9b4a-d0f7060c0cc2.png)


