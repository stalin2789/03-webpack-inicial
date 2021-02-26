# 03-webpack-inicial

Proyecto inicial para crear aplicaciones usando webpack.

###Notas:
Recuerden reconstruir los módulos de Node
```
npm install
````
y para reconstruir el build, recuerden:
````
npm run build
````

1. Verificar que se tenga instalado node y npm
node --version
npm --version

2. npm init //Esto nos lleva a crear el package.json el cual es primordial para saber toda la configuracion de la aplicacion
3. npm install webpack webpack-cli --save-dev //ingresar este comando para que se instale webpack
4. en scripts agregar la clave: 
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "build": "webpack"

5. npm run build   //Ejecuta comando webpack con la configuracion por defecto
6. Creamos el archivo webpack
7 npm i -D html-loader html-webpack-plugin //Instalamos los dos paquetes
8. npm i -D webpack-dev-server //para developer mode para auto compilar
9. Un monton de comandos más :')
