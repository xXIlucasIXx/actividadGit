# actividadGit

# **actividadGit**


## **1 Investigación básica de Git:**


**a**. **¿Qué es Git y para qué se utiliza?**


_Git es un sistema de control de versiones usado en el desarrollo de software. Permite gestionar cambios, trabajar en equipo, crear ramas, fusionar modificaciones y mantener un historial de versiones. Es esencial para el control y colaboración en proyectos de software._ m


**b**. **¿Cuáles son las principales características de Git?**


_Las principales características del git son: el control y almacenamiento de cambios, ramificación y fusión, repositorios distribuidos, gestión de conflictos, historial y etiquetado, velocidad y rendimiento, flexibilidad y escalabilidad, y compatibilidad con diversas plataformas._


**c**. **¿Qué es un sistema de control de versiones?**


_Un sistema de control de versiones es una herramienta que registra y controla los cambios en archivos y proyectos. Permite mantener un historial de modificaciones, trabajar en paralelo y colaborar en el desarrollo de software._


**d**. **¿Cuál es la diferencia entre Git y otros sistemas de control de versiones?**


_Git almacena la historia completa del proyecto como instantáneas, lo que facilita el acceso rápido a versiones anteriores._


_Git deja realizar operaciones sin conexión a un servidor central, lo que nos da flexibilidad y capacidad de trabajar offline._


_Git facilita la creación y gestión de ramas, como la fusión eficiente de cambios entre ellas._


_Git es escalable y ofrece un rendimiento óptimo en proyectos de cualquier tamaño._


_Git cuenta con una amplia comunidad de usuarios y desarrolladores, lo que proporciona recursos y herramientas disponibles._


## **2 Instalación y configuración de Git:**


**a**. **Investiga cómo instalar Git en diferentes sistemas operativos (Windows, macOS, Linux).**


**Windows:**


_-Descargar el instalador de Git desde el sitio web oficial y ejecutarlo._


_-Sigue las instrucciones del asistente de instalación, aceptando los ajustes predeterminados._


_-Git estará disponible en la línea de comandos y se instalará Git Bash, una interfaz gráfica._


**macOS:**


_-Verifica la instalación ejecutando git --version en la Terminal._


_-Si no está instalado, se puede instalar a través de las herramientas de línea de comandos de Xcode._


**Linux (Debian/Ubuntu):**
_


-Abre una terminal y actualiza los repositorios de paquetes con sudo apt update._


_-Instala Git con sudo apt install git._


**b**. **Explica los pasos para configurar tu nombre de usuario y dirección de correo electrónico en Git.**


_-Abrir la terminal._


_-Verifica la configuración actual con el comando_


git config --global --list.


_-Configurar el nombre de usuario con el comando_


git config --global user.name "Tu Nombre".


_-Configurar la dirección de correo electrónico con el comando


git config --global user.email "tucorreo@example.com".


_-Verificar la configuración actualizada con el comando_


git config --global --list.


## **3 Comandos básicos de Git:**
**a**. **Investiga los comandos git init, git add, git commit y git status. Explica qué hacen y cómo se utilizan.**


_-git init: Crea un nuevo repositorio de Git en un directorio._


_-git add: Agrega archivos al área de preparación para incluirlos en el siguiente commit._


_-git commit: Confirma los cambios realizados en el área de preparación y crea un nuevo commit en el historial del repositorio._


_-git status: Muestra el estado actual del repositorio, incluyendo los cambios realizados y los archivos en el área de preparación._


**b**. **Describe los comandos git log y git diff para ver el historial de cambios y las diferencias entre versiones, respectivamente.**


_El comando git log se utiliza para ver el historial de cambios en un repositorio Git. Muestra una lista cronológica de confirmaciones, con detalles como autor, fecha y mensaje descriptivo.
El comando git diff muestra las diferencias entre versiones de archivos en un repositorio Git. Puede mostrar diferencias entre el directorio de trabajo y el área de preparación, o entre confirmaciones específicas. Proporciona opciones para mostrar las diferencias de manera más compacta o detallada._




## **4 Trabajando con repositorios remotos:**


**a**. **Investiga cómo clonar un repositorio remoto con git clone.**


_-Abrir una terminal y navegar hasta el directorio deseado._


_-Obtén la URL del repositorio remoto.
Ejecutar git clone <URL> en la terminal, cambiando <URL> con la URL del repositorio._


_-Tocar el Enter y Git comenzará a clonar el repositorio en tu directorio actual._


_-Si es necesario, proporciona las credenciales de autenticación._


_-Una vez completada la clonación, tendremos una copia local del repositorio remoto._


**b**. **Explica cómo trabajar con ramas utilizando los comandos git branch, git checkout y git merge.**


_-git branch: Crear, listar o eliminar ramas._


_-git branch nombre-rama: Crea una nueva rama._


_-git branch: Lista las ramas existentes._


_-git branch -d nombre-rama: Elimina una rama._


_-git checkout: Cambiar entre ramas o crear una nueva rama y cambiar a ella._


_-git checkout nombre-rama: Cambia a una rama existente._


_-git checkout -b nombre-rama: Crea y cambia a una nueva rama._


_-git checkout -- nombre-archivo: Descarta cambios en   un archivo._


_-git merge: Fusionar cambios de una rama en otra._


_-git merge nombre-rama: Fusiona una rama en la rama actual._




**c**. **Investiga cómo subir tus cambios locales a un repositorio remoto con git push.**


_-Realizar y confirmar cambios locales con git commit._


_-Verificar la configuración del repositorio remoto con git remote -v._


_-Si no vinculaste tu repositorio local al remoto, usa git remote add para agregarlo._


_-Utiliza git push_


<nombre_repositorio_remoto>


<rama_local>:<rama_remota> _para subir tus cambios._


<nombre_repositorio_remoto> _es el nombre del repositorio remoto, como "origin"._


<rama_local> _es el nombre de tu rama local con los cambios._


<rama_remota> _es el nombre de la rama correspondiente en el repositorio remoto.
Git verificará los permisos y posibles conflictos, y subirá tus cambios al repositorio remoto._


## **5 Colaboración en Git:**
**a**. **Investiga cómo trabajar en equipo en un repositorio remoto utilizando ramas y fusiones.**


_-Clonar el repositorio remoto: Cada miembro del equipo clona el repositorio remoto en su máquina local._


_-Crear y cambiar a una nueva rama: Cada miembro crea una nueva rama para su tarea y se cambia a ella._


_-Trabajar en la rama localmente: Los miembros del equipo realizan cambios en la rama específica._


_-Subir la rama al repositorio remoto: Los cambios se suben al repositorio remoto._


_-Solicitar una fusión (pull request): Se solicita la fusión de la rama en el repositorio remoto._


_-Revisar y discutir los cambios: Los miembros revisan y comentan los cambios propuestos._


_-Realizar ajustes y actualizaciones: El autor de la solicitud realiza ajustes en la rama según los comentarios recibidos._


_-Fusionar la rama: La rama se fusiona con la rama principal del repositorio remoto._


**b**. **Explica qué son las solicitudes de extracción (pull requests) y cómo se utilizan para revisar y aprobar cambios.**


_Las solicitudes de extracción son propuestas para fusionar cambios en un proyecto de software. Los desarrolladores crean una solicitud desde una rama con modificaciones hacia la rama principal. Otros revisan el código, hacen sugerencias y plantean preguntas. Después de iteraciones y pruebas, los cambios se aprueban y fusionan en la rama principal. Las solicitudes de extracción mejoran la colaboración y calidad del software antes de la fusión._
