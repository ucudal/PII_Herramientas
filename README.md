<!-- markdownlint-disable MD033 MD041-->
<img alt="UCU" src="https://www.ucu.edu.uy/plantillas/images/logo_ucu.svg"
width="150"/>
<!-- markdownlint-enable MD033 MD041 -->

# Universidad Católica del Uruguay

## Facultad de Ingeniería y Tecnologías

### Programación II

# Herramientas del curso

## Contenido

1. [Acerca de este documento](#acerca-de-este-documento)

2. [NET 10.0](#net-100)

3. IDE. El IDE —o *integrated development environment*— es la herramienta que
   usamos para escribir el código, compilar, depurar, hacer pruebas, etc. El IDE
   que recomendamos es [Visual Studio Code](#visual-studio-code).

4. Extensiones. En el caso de Visual Studio Code debes instalar
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

> [!IMPORTANT]
> Este documento y otros que usaremos durante el curso asumen que para la
> instalación de las herramientas usas las opciones predeterminadas. No las
> cambies a menos que sepas lo que estás haciendo.

### .NET 10.0

.NET 10.0 es la nueva plataforma unificada de Microsft para el desarrollo de
aplicaciones modernas. Las instrucciones de instalación están disponibles a
través este <a href="https://dotnet.microsoft.com/en-us/download/dotnet/10.0">🌎vínculo de
descarga</a>.

> [!WARNING]
> Puedes descargar el instalador e instalarlo tu mismo siguiendo las
> instrucciones provistas o instalarlo en clase; trae el programa de instalación
> descargado para la próxima clase.

### Visual Studio Code

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

Son complementos que controlan la ortografía en el código y los documentos. <a
href="https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker">🌎Descargar</a>
para :gb: y <a
href="https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-spanish">🌎Descargar</a>
para :es:. Ambos son opcionales.

### GitHub

GitHub es un servicio en línea para desarrollar programas en forma colaborativa.
Está basado en Git e incluye funcionalidad adicional útil para el desarrollo de
algunas competencias de este curso.

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
puede ser necesario ejecutar estos dos comandos **antes** de usar Git por
primera vez:

```bash
brew install --cask git-credential-manager
git config --global credential.helper manager
```

En
![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?logo=windows11&logoColor=white)
Git usa el `Credential Store` la primera vez que uses los comandos que requieren
identificar al usuario; te va a abrir el navegador para solicitar las
credenciales.

### Doxygen

Es un paquete para la generación de sitios web de documentación a partir de
comentarios XML. Las instrucciones de instalación están disponibles en este <a
href="https://www.doxygen.nl/download.html">🌎 vínculo de descarga</a>.

> [!WARNING]
> En
> ![macOS](https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white)
> en lugar de la instalación anterior, puedes usar el comando `brew install
> doxygen`. Puedes ver [aquí](https://formulae.brew.sh/formula/doxygen) más
> información sobre esta fórmula de Homebrew.

> [!WARNING]
> En
> ![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?logo=windows11&logoColor=white)
> puede suceder que durante la instalación no agregue la carpeta donde está
> `doxygen.exe` a la variable de entorno `PATH`. En ese caso debes [modificar
> esa variable de
> entorno](https://learn.microsoft.com/es-es/previous-versions/office/developer/sharepoint-2010/ee537574(v=office.14)#:~:text=Para%20agregar%20una%20ruta%20de%20acceso%20a%20la%20variable%20de%20entorno%20PATH)
> para agregar la carpeta donde está `doxygen.exe`, por ejemplo, `C:\Program
> Files (x86)\doxygen`.
