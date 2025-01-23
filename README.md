<h1 align="center"> Laboratorio 1 - Ciclos de Vida del Desarrollo del Software </h1>

![Logotipo creado con IA en base al curso](https://github.com/user-attachments/assets/033c5ab3-8b04-4f81-8f8d-5157a81a3d6e)

## Colaboradores
- Nicole Dayan Calderón Arévalo
- Andrés Felipe Chavarro Plazas

## Descripción del Laboratorio
Laboratorio 1 de la materia de Ciclos de Vida del Desarrollo del Software, en el cual aprendemos y profundizamos en el uso y buen manejo del sistema de control de versiones Git Hub.
En este laboratorio ponemos en practica comandos de git hub para conexión y acciones desde el repositorio local al remoto, tambien entendemos la funcionalidad de estos. A la par de este aprendizaje de la herramienta, empezamos a adquirir conocimientos y habilidades necesarios para el trabajo en equipo en la vida laboral.

## :hammer:I. Parte Individual
En esta primera parte del laboratorio, desarrollado individualmente, se busca aprender la creación de repositorios(local y remoto), conectarlos y realizar diferentes acciones con los comandos desde ellos.
Los solicitado a realizar en esta parte es:
1. Crear un repositorio local
2. Agrega un archivo de ejemplo al repositorio, en mi caso el README.md
3. Averiguar para qué sirve y como se usan estos comandos `git add y git commit -m “mensaje”`
4. Abrir una cuenta de github, si ya existe, enlazarla con el correo institucional
5. Crear un repositorio vacío en GitHub
6. Configurar el repositorio local con el repositorio remoto
7. Subir los cambios, teniendo en cuenta el punto 3
8. Configurar el correo en git local

## :rocket:Desarrollo
### :desktop_computer:Creación y configuración de repositorios
Para crear el repositorio local el primer paso fue crear una `nueva carpeta 📁` con el nombre que asigne a mi repositorio local

![imagen de referencia del repo local](https://github.com/user-attachments/assets/f10b7888-8f87-40f7-8203-ea76f60252e0)

Para efectos practicos el paso siguiente que realice fue crear el repositorio en Git
**_Me apoyo con imagenes de repositorios adicionales que cree para ilustrar el mismo proceso debido a que no fotodocumente la creación de este_**

![imagen del repo vacio recien creado](https://github.com/user-attachments/assets/39e65794-9559-479e-91fa-6fc1775c3c17)

Al crear el repositorio vacio en Git, se encuentran unas instrucciones para configurarlo con el repositorio local, estas las segui totalmente incluida la creación del read me desde consola. 

Entonces abri la consola de mi equipo y desde alli me dirigi a el repositorio local `Laboratorio1_CVDS`
![imagen de paso 1 de enlace de repos](https://github.com/user-attachments/assets/eb904bc4-bad6-4690-875b-d99a8f0ea0e8)

Seguido de esto aplique todos los comados entregados por Git y mencionados anteriormente
![image](https://github.com/user-attachments/assets/920f8d96-7440-47a6-b3e1-d8838accf9b6)

De esta forma desarrolle los punto 1,2,5,6 y 7 en un mismo proceso simple, configurando correctamente los repositorios
![imagen del repo](https://github.com/user-attachments/assets/d65fef6b-330b-429e-898d-5290b0bf6113)

### :pencil:Puntos adicionales
- Comandos `git add y git commit -m “mensaje”`

El comando **git add** nos permite subir los cambios realizados en el directorio de trabajo a la staging area, esto nos permite reservar una instantanea del proyecto antes de confirmar totalmente los cambios.
El comando **git commit -m "mensaje"** se utiliza para guardar los cambios en el respositorio y con `-m` podemos adicionar un mensaje sobre dicho commit.

- Enlazar mi cuenta de la universidad
![imagen de las cuentas de mi git](https://github.com/user-attachments/assets/93de00bb-e8d6-4bf2-9eea-4fd3af3c9d26)

- Configurar el correo desde local
![imagen de configuración del correo](https://github.com/user-attachments/assets/87baf204-f9e0-4c1c-9c1a-3eaae5dc6141)

Finalmente habre desarrollado completamente la primera parte del laboratorio adquiriendo nuevos aprendizajes sobre manejo de repositorios en GitHub.

## II. Parte En Parejas
- Owner: Nicole
- Collaborator: Andrés

### Conflicto inicial



### Conflicto con IDE's
Al realizar el mismo procedimiento para generar un conflicto, volvemos a la misma situación presentada en la anterior parte. Sin embargo, ahora se nos pide solucionar haciendo uso de algún editor o IDE que nos brinde una herramienta para resolver el problema. En este caso, usamos IntellIJ con su funcionalidad de Git integrada.

Cuando el conflicto se genera, nos dirigimos al IDE en la parte de Git. En esta, nos detecta que previamente ya está el commit realizado, por lo que únicamente tenemos que subirlo al repositorio remoto. No obstante, al intentarlo nos abre una pestaña de confirmación donde al mismo tiempo se rechaza el push por el conflicto generado, dándonos opciones para solucionarlo según lo que nos sea conveniente, dichas opciones son hacer rebase para sobreponer los cambios del commit en contra del repositorio, o la otra opción que de hecho elegimos, hacer un merge entre las dos versiones del documento con el fin de generar otra versión con los elementos que queremos que se mantengan.

Acto seguido, aparece la pantalla que  nos da la opción del merge manual y se abre otra ventana especial. En esta, hay tres columnas con distintas versiones del archivo, en la derecha la versión que se encuentra en el repositorio, a la izquierda la versión que genero el conflicto y en el centro la versión que quedaría al seleccionar las líneas de código que queremos mantener. 

De este modo, pudimos solucionar el conflicto de modo que fue posible hacer el push al repositorio.
