# Practica3
En esta práctica podremos observar la instalación de una nueva versión del kernel.

## 1. ¿Cómo hacer un respaldo de una máquina virtual? y ¿cómo levantar ese respaldo?
1.- Seleccionar la máquina que se quiera respaldar.
![1](https://user-images.githubusercontent.com/93893818/166300741-2967d282-9137-4ea2-96c8-7c9cd9f223f3.png)

2) Después, ir a archivo y dar clic en exportar servicio virtualizado
![2](https://user-images.githubusercontent.com/93893818/166301312-c9d72d4f-5f9b-4168-a421-85489334d78c.png)

3) Seleccionar la máquina virtual que se quiere respaldar y dar clic en siguiente.
![3](https://user-images.githubusercontent.com/93893818/166301538-0d8fd852-c70c-4e7e-afcd-359af4a09d0c.png)

4) Seleccionar la carpeta amarilla para escoger la ubicación de la máquina virtual de respaldo. 
![4](https://user-images.githubusercontent.com/93893818/166301615-4ae39195-a533-40bd-b26b-5d63de870fcc.png)

5) Seleccionamos la carpeta donde queremos que se guarde y damos clic en guardar.
![5](https://user-images.githubusercontent.com/93893818/166301740-d4ce7cd3-fd1a-4604-add1-dcbad5712b38.png)

## 2.	Explicar la nomenclatura del kernel.

La nomenclatura de Kernel consta de 3 campos que están separado por un punto "."

El primero campo indica el número de versión del Kernel, el segundo campo indica el numero de la subversión del Kernel, el cual se encuentra dentro de la propia versión y si el numero es par, indica que la versión es estable, si no, la versión es inestable y el ultimo campo indica el nivel de corrección en el que se encuentra.


## 3. Investigar y enlistar los paquetes requeridos para la compilación y ¿cómo instalarlos desde terminal?

Con el comando “sudo apt install gcc libcurses5-dev dpkg-dev” nos permitiraa enlistar los paquetes que se requieren para después instalar la versión del kernel.
![1](https://user-images.githubusercontent.com/88467362/166295970-04124154-880d-49cc-83ae-a88cf38d09e5.png)

## 4. ¿Cómo descargar una versión de kernel desde terminal?

Con “wget” seguido de la dirección de la versión del kernel que de dese , como se muestra en la siguiente imagen.

![2](https://user-images.githubusercontent.com/88467362/166297251-ca708db7-816c-44d7-b6fb-05a88b21c375.png)

## 5. ¿Cómo extraer el código comprimido del kernel desde terminal?

Con “tar Jxvf” seguido del archivo, hacemos que el archivo se pueda extraer. 

![3](https://user-images.githubusercontent.com/88467362/166298582-7075798a-c132-4cfd-adcd-a92bc13a615f.png)

## 6.	¿Cómo configurar el kernel? 

Entrar en el directorio de las fuentes:

![image](https://user-images.githubusercontent.com/88467362/166300927-e4f20bc2-785e-4b2e-bbe2-6a031daa9f4f.png)

## 7. ¿Cómo compilar el código del kernel? 

Paso 1: Instalamos los recursos necesarios:

![image](https://user-images.githubusercontent.com/88467362/166298692-b547abf8-7b45-4723-b3b7-ddc65977c1ba.png)

Paso 2: Instalar el kernel paackage:

![image](https://user-images.githubusercontent.com/88467362/166298729-ff38d5b5-ce89-4516-becf-93b01b23f9ca.png)

Paso 3: Descargar el código fuente del kernel Linux:

![image](https://user-images.githubusercontent.com/88467362/166298760-1047010a-6d59-4192-add8-0124b6ff3c6e.png)

Paso 4: Desempaquetar las fuentes: tar avxf linux-5.8.15.tar.xz

![image](https://user-images.githubusercontent.com/88467362/166298836-e40c7f19-bb9b-4b5a-babc-7f7cb5b3055c.png)

Paso 5: Entrar en el directorio de las fuentes:

![image](https://user-images.githubusercontent.com/88467362/166298892-19e577e9-c152-41ff-bde9-98306b4a6674.png)

Paso 6: Tomar como referencia el kernel que estamos usando:

![image](https://user-images.githubusercontent.com/88467362/166298926-929a08b9-94a6-4017-9364-b962bed4c747.png)

Paso7: Tomar como base los módulos del kernel que están en uso actualmente:

![image](https://user-images.githubusercontent.com/88467362/166298956-f9dbdaf2-83b9-43ea-a0f6-c527f9cf0179.png)

Paso 8: Configuramos nuestro kernel: Marca error porque el archivo es muy pequeño, asi lo vamos a dejar ya que no queremos modificar nada.

![image](https://user-images.githubusercontent.com/88467362/166298982-2d2158eb-d8a4-43ea-9490-2d93573c0b3e.png)

Paso 9: Compilamos el kernel: con el comando “make”

![image](https://user-images.githubusercontent.com/88467362/166299012-10f895bc-2066-456a-b92e-e413eb24635c.png)
![image](https://user-images.githubusercontent.com/88467362/166299028-aa872bc6-36c5-44b2-82ec-8e7c13fd61b8.png)

## 8. ¿Cómo instalar módulos? 

Con “sudo make modules_install” se hace la instalación de los módulos.

![image](https://user-images.githubusercontent.com/88467362/166299082-28b84c51-7fd8-4cce-9a34-1515261dc66e.png)
![image](https://user-images.githubusercontent.com/88467362/166299506-fc2bb87d-dcbd-4d6a-bf78-f0092a83c798.png)
![image](https://user-images.githubusercontent.com/88467362/166299552-4561bd76-2b80-4ee8-94e0-a4a7d8a738a0.png)

## 9. ¿Cómo instalar el kernel?



