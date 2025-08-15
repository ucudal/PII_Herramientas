<img alt="UCU" src="https://www.ucu.edu.uy/plantillas/images/logo_ucu.svg"
width="150"/>
# Universidad Católica del Uruguay
## Facultad de Ingeniería y Tecnologías
### Programación II


# Herramientas del curso

<!-- <h2 id="content">Contenido</h2> -->
## Contenido

<!-- 1. <a href="#about">Acerca de este documento</a> -->

1. [Acerca de este documento](#acerca-de-este-documento)

2. [NET 8.0](#net-80)

3. IDE. El IDE —o *interactive development environment*— es la herramienta que
   usamos para escribir el código, compilar, depurar, hacer pruebas, etc. El IDE
   que recomendamos es [Rider](#rider) pero en computadoras con menores
   presentaciones puede tener mejor desempeño [Visual Studio Code](#vscode).

4. Extensiones. Ambos IDE soportan extensiones. En el caso de Rider no necesitas
   instalar ninguna; al contrario, puedes [desinstalar o
   inhabilitar](#extensiones-innecesarias-de-rider) las que no usamos para
   mejorar el desempeño. En el caso de Visual Studio Code debes instalar
   necesariamente estas [extensiones](#extensiones-de-visual-studio-code).

5. [GitHub](#github)

6. [Git](#git)

7. [Doxygen](#doxygen)

---

### Acerca de este documento

Este documento contiene la lista de herramientas que usaremos en el curso, con
los vínculos a los sitios oficiales de descarga. Puedes instalar las
herramientas tanto en
![windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)
como en
![macOS](https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white);
en caso de usar otro sistema operativo, consulta a los profesores.

### .NET 8.0

.NET 8.0 es la nueva plataforma unificada de Microsft para el desarrollo de
aplicaciones modernas. Las instrucciones de instalación están disponibles a
través este <a href="https://dotnet.microsoft.com/download">🌎vínculo de
descarga</a>.

> [!WARNING]
> Puedes descargar el instalador e instalarlo tu mismo siguiendo las
> instrucciones provistas o instalarlo en clase; trae el programa de instalación
> descargado para la próxima clase.

### Rider

Rider es un IDE multiplataforma para desarrollo en .NET desarrollado por
JetBrains que puede ser utilizado con una licencia académica.

> [!WARNING]
> Debes usar tu cuenta de correo de la UCU del dominio @correoucu.edu.uy para
> crear tu cuenta en JetBrains.

Para obtener tu licencia debes crear primero una cuenta en JetBrains
[aquí](https://www.jetbrains.com/community/education/#students).

Esta licencia te dará acceso a varios productos; a menos que en tu trabajo o en
otros cursos uses otras herramientas de JetBrains, deberás instalar solamente
Rider a través de este <a
href="https://www.jetbrains.com/shop/download/RD/2024100">🌎vínculo de
descarga</a>.

Luego de que instales Rider deberás activarlo:

<img src="./Assets/Rider activation.gif" width="666" height="500"/>

### Visual Studio Code

> [!TIP]
> Instala Visual Studio Code solamente si tienes problemas de desempeño en tu
> computadora con Rider. Si decides instalar Visual Studio Code y has instalado
> antes Rider, deberías desinstalar Rider.

Es un editor de código fuente desarrollado por Microsoft para Windows, Linux y
macOS. Incluye soporte para la depuración, control integrado de Git, resaltado
de sintaxis, completado inteligente de código, etc. Es personalizable, por lo
que podrás cambiar el tema del editor, los atajos de teclado y las preferencias.
Es gratuito y de código abierto. Las instrucciones de instalación están
disponibles a través de este <a
href="https://code.visualstudio.com/download">🌎vínculo de descarga</a>.

> [!WARNING]
> Puedes descargar el instalador e instalarlo tu mismo siguiendo las
> instrucciones provistas o instalarlo en clase; trae el programa de instalación
> descargado para la próxima clase

### Extensiones de Visual Studio Code

> [!WARNING]
> Es necesario instalar las siguientes extensiones **luego** de instalar Visual
> Studio Code. Debes estar conectado a Internet durante el proceso de
> instalación. Abre el vínculo de descarga y haz clic en el botón Install.

#### Extensiones de C# Dev Kit

Es un complemento para editar, compilar, y depurar código C#. <a
href="https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit">🌎Descargar</a>

#### Extensión de GitHub

Es un complemento para interactuar con pull requests de GitHub. Los pull request
son un mecanismo por el cual un programador pide a otro que revise sus cambios
antes de incorporarlos definitivamente en un repositorio de código compartido.
<a
href="https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github">🌎Descargar</a>

#### Extensión de GitHub History

Es un complemento que nos permite ver gráficamente las ramas de nuestro
proyecto, las historia de nuestros archivos y las información de los commits. <a
href="https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory">🌎Descargar</a>

#### Extensión de indicadores de cobertura en los márgenes

Es un complemento para mostrar en los márgenes del editor la cobertura del
código. Es útil para saber el código que no se ejecuta durante las pruebas. Es
opcional. <a
href="https://marketplace.visualstudio.com/items?itemName=ryanluker.vscode-coverage-gutters">🌎Descargar</a>

#### Extensión de íconos

Es un complemento que incluye un conjunto de íconos para las extensiones de
archivos más comunes. Es opcional. <a
href="https://marketplace.visualstudio.com/items?itemName=jtlowe.vscode-icon-theme">🌎Descargar</a>

#### Extensión de corrector ortográfico

Son complementos que controlan la ortografía en <a href="https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker">🌎Descargar</a> para :gb: y <a href="https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-spanish">🌎Descargar</a>para :es:. Ambos son opcionales.

### Extensiones innecesarias de Rider

Puedes desinstalar o inhabilitar estas extensiones de Rider, porque no las
usaremos en este curso.

* AWS Core

* AWS Toolkit

* Azure Toolkit

* JetBrains AI Assistant

* SpecFlow

* Database Tools and SQL

### Github

GitHub es un servicio en línea para desarrollar programas en forma colaborativa. Está basado en Git e incluye funcionalidad adicional útil para el desarrollo de algunas competencias de este curso.

> [!WARNING]
> El código de los programas en GitHub que crees y las interacciones en marco
> del desarrollo colaborativo de esos programas es público.

Los profesores veremos el código y las interacciones en GitHub de todos los
alumnos; eventualmente modificaremos ese código o participaremos en las
interacciones. Los profesores también proveeremos código en GitHub. Debes crear
una cuenta en GitHub, o puedes usar una cuenta que ya tengas creada. Ya sea que
crees una cuenta nueva, o que uses una que ya tengas, ten en cuenta que deberás
usar la misma cuenta a lo largo de todo el curso. Los profesores te
preguntaremos el nombre de usuario de <a
href="https://github.com/join">GitHub</a>.

### Git

Para poder gestionar los repositorios de GitHub a través de aplicación de
escritorio o de la consola, se requiere instalar Git SCM. Las instrucciones de
instalación están disponibles a través de este <a
href="https://git-scm.com/downloads">🌎vínculo de descarga</a>.

Hemos visto que en
![macOS](https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white)
puede ser necesario ejecutar estos dos comandos:

```bash
brew install --cask git-credential-manager
git config --global credential.helper manager
```

### Doxygen

Es un paquete para la generación de sitios web de documentación a partir de comentarios XML.

> [!TIP]
> Las instrucciones de instalación están disponibles en [esta
> página](https://www.doxygen.nl/download.html) en la sección "A binary
> distribution for Linux x86-64", "A binary distribution for Windows" o "A
> binary distribution for Mac OS X 10.14 and later"; usa la que corresponda
> según el sistema operativo que tengas.

<a href="https://www.doxygen.nl/download.html">🌎 Instalación</a>

> [!WARNING]
> En
> ![macOS](https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white)
> en lugar de la instalación anterior, puedes usar el comando `brew install
> doxygen`. Puedes ver [aquí](https://formulae.brew.sh/formula/doxygen) más
> información sobre esta fórmula de Homebrew.

> [!WARNING]
> En
> ![windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)
> puede suceder que durante la instalación no agregue la carpeta donde está
> `doxygen.exe` a la variable de entorno `PATH`. En ese caso debes [modificar
> esa variable de
> entorno](https://learn.microsoft.com/es-es/previous-versions/office/developer/sharepoint-2010/ee537574(v=office.14)#:~:text=Para%20agregar%20una%20ruta%20de%20acceso%20a%20la%20variable%20de%20entorno%20PATH)
> para agregar la carpeta donde está `doxygen.exe`, por ejemplo, `C:\Program
> Files (x86)\doxygen`.
