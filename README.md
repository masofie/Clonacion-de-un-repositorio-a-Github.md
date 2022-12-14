# Clonación de un Repositiorio en Github

Lo primero que hay que saber es que la clonación la vamos a utilizar para poder acceder a nuestro repositorio 
en cualquien lugar donde estemos .

![6.png](./img/6.png)


Osea trabajar desde otro lugar , donde originalmente no se ha hecho el trabajo .Si quieres saber mas sobre la clonacion puedes consultar al siguiente enlace : 

**Enlace** : (**https://docs.github.com/es/repositories/creating-and-managing-repositories/cloning-a-repository**)

## Pasos a seguir para la Clonación 

#### Posicionamiento y Crer directorio

Lo primero que hay que hacer es posicionarmos en nuestra carpeta de Github . Y creamos un directorio con el nombre que quireas .

**`mkdir "nombre de la carpeta"`**

#### Copiar enlace en Github 

Para la clonacion lo primero que hay que hacer es ir a nuestro repositorio en Github y copiamos nuestro enlace .

![2.png](./img/2.png)

#### Comando para la clonacion 

Después ejecutamos el siguiente comando para clonar nuestro repositorio de Github

**`git clone "enlace copiado anteriormente"`**

![1.png](./img/1.png)

## Clonación creada 

Como podemos ver se ha clonado correctamente el repositorio . Para eso utilizamos los siguientes comandos .

Hacemos un **`ls`** ; para ver lo que hay en el directorio.
Después nos vammos al repositorio con el comando **`cd "directorio"`**
Luego hacemos un **`cat REAME.md`** y con eso podemos ver lo qye hay en el archivo .

Como podemos ver ahí esta clonado correctamente .

![3.png](./img/3.png)

# Configuración de los Parametros Globales 

Para hacer esto hay que ir a la carpeta de configuración de Git , y vamos a utilizar el terminal .
Y ejecutamos el comando **`code .gitconfig`** , este fichero esta oculto y por eso empieza por un punto . Si lo quieres buscar 
desbes utilizar el comando **`ls -la`** y te mostrara los ficheros ocultos ·

Aqui lo podmeos ver aqui tenemos la imagen de nuestro fichero de coonfiguración 

![4.png](./img/4.png)

Y también nos abre el fichero porque le dijimos que utilice el Visual Studio Code **(code)**

![5.png](./img/5.png)
