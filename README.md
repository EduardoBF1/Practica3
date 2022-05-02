# Practica3
En esta práctica podremos observar la instalación de una nueva versión del kernel.

## 1. ¿Cómo hacer un respaldo de una máquina virtual? y ¿cómo levantar ese respaldo?
1) Seleccionar la máquina que se quiera respaldar.

![1](https://user-images.githubusercontent.com/93893818/166300741-2967d282-9137-4ea2-96c8-7c9cd9f223f3.png)

2) Después, ir a archivo y dar clic en exportar servicio virtualizado

![2](https://user-images.githubusercontent.com/93893818/166301312-c9d72d4f-5f9b-4168-a421-85489334d78c.png)

3) Seleccionar la máquina virtual que se quiere respaldar y dar clic en siguiente.

![3](https://user-images.githubusercontent.com/93893818/166301538-0d8fd852-c70c-4e7e-afcd-359af4a09d0c.png)

4) Seleccionar la carpeta amarilla para escoger la ubicación de la máquina virtual de respaldo.
 
![4](https://user-images.githubusercontent.com/93893818/166301615-4ae39195-a533-40bd-b26b-5d63de870fcc.png)

5) Seleccionamos la carpeta donde queremos que se guarde y damos clic en guardar.

![5](https://user-images.githubusercontent.com/93893818/166301740-d4ce7cd3-fd1a-4604-add1-dcbad5712b38.png)

6) Damos clic en siguiente.

![6](https://user-images.githubusercontent.com/93893818/166303590-c0639af2-6a5e-4ba1-83c1-af5a695db498.png)

7) Le damos clic en exportar.

![7](https://user-images.githubusercontent.com/93893818/166303708-ba1feaf9-4c16-49e9-b58a-02afa1d2dad6.png)

8) Esperamos a que se complete de exportar.

![8](https://user-images.githubusercontent.com/93893818/166304430-81f5b39d-a74d-4931-a825-df7596eae4da.png)

9) Al finalizar se visualizará el archivo en la carpeta donde se guardó.

![9](https://user-images.githubusercontent.com/93893818/166304498-7f4c8471-c4a3-4382-83ae-1dcc9ffd9d6f.png)

LEVANTAR EL RESPALDO  DE LA MAQUINA VIRTUAL UBUNTU

1) Dar clic en importar.

![1](https://user-images.githubusercontent.com/93893818/166306017-3aca29a5-d68c-4514-b582-ef4da88ba55b.png)

2) Seleccionar el icono de la carpeta amarilla para seleccionar la máquina virtual de respaldo.

![2](https://user-images.githubusercontent.com/93893818/166306209-aa7a4651-b253-45af-8f32-72d33746c0c7.png)

3) Seleccionamos la máquina virtual de respaldo y le damos clic en abrir.

![3](https://user-images.githubusercontent.com/93893818/166306330-f369fc31-81d7-465b-bf68-fd352b230b72.png)

4) Damos clic en siguiente.

![4](https://user-images.githubusercontent.com/93893818/166306417-5e4b8295-7914-4737-9b86-81183f8b01d8.png)

5) Damos clic en importar.

![5](https://user-images.githubusercontent.com/93893818/166306489-6d7cbf0d-23ca-4805-8306-6b47237876b2.png)

6) Esperar a que se importe.

![6](https://user-images.githubusercontent.com/93893818/166306756-32b1cf69-79b0-465b-b030-4b081d9c9ce4.png)

7) Se ha creado el respaldo

![7](https://user-images.githubusercontent.com/93893818/166306836-2cb83f2f-6d05-4a25-a5ef-1e839e6cfcc7.png)

8) Iniciar la maquina virtual de respaldo dando clic en la flecha verde iniciar o doble click sobre la maquina.

![8](https://user-images.githubusercontent.com/93893818/166306942-7b4addb2-a745-43e2-bce9-4a2ff737a916.png)

9) Listo, se creo el respaldo de la maquina virtual.

![9](https://user-images.githubusercontent.com/93893818/166307022-e6ce7933-c70e-4f6b-a773-2dc8c24537f6.png)


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

Dentro de el archivo donde esta el kernel se aplica el comando “sudo make install” para instalar el kernel.

![image](https://user-images.githubusercontent.com/88467362/166302498-4a74b30f-4dba-4614-8867-c8711c3b11e6.png)
![image](https://user-images.githubusercontent.com/88467362/166302515-16421122-4710-43b3-a0f4-05a91ded2ceb.png)

## 10. ¿Cómo indicarle a la computadora con cuál kernel debe iniciar?

Este es el que tenemos predeterminado

![image](https://user-images.githubusercontent.com/88467362/166302571-63b26023-418d-4285-a93d-9ab9f054639f.png)

Paso 1: hacemos un grep indicando la versión del kernel que queremos poner.

![image](https://user-images.githubusercontent.com/88467362/166302607-4f79348a-1aa2-409d-8162-cd4a1e582472.png)

Paso 2: Copiamos lo del final.

![image](https://user-images.githubusercontent.com/88467362/166302644-c7b383a7-dc6a-4b9b-9542-e93e6d6d7865.png)

Paso 3: Modificamos la variable GRUB_DEFAULT pegando lo que copiamos en el paso anterior abriendo el archivo grub.

![image](https://user-images.githubusercontent.com/88467362/166302689-6302302a-f895-4f87-95ec-0660d09655e0.png)

Paso 4: Actualizar la configuración de grub.

![image](https://user-images.githubusercontent.com/88467362/166302713-0029f18c-a7d7-4773-9a65-0c8cd9e0aa4e.png)

Paso 5: Reiniciamos.

![image](https://user-images.githubusercontent.com/88467362/166302754-e81a78b9-b334-4b3f-9971-a884375467ce.png)

## 11. ¿Cómo verificar el cambio de kernel a partir de consola?

![image](https://user-images.githubusercontent.com/88467362/166302813-e569ac9c-40f2-40bf-9234-04d478cd2a06.png)







