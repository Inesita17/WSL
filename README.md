# WSL

![image](https://github.com/Inesita17/WSL/assets/127887874/dbac831c-22bd-4ade-ab49-ea00b498dae2)


### <ol>1. Introducción (¿Qué es WSL?)</ol>

El Windows Subsystem for Linux (WSL) es una característica de Windows que permite a los usuarios ejecutar un entorno Linux directamente en un sistema operativo Windows. Con WSL, puedes ejecutar distribuciones de Linux completas, como Ubuntu, Debian, CentOS y otras, dentro de Windows, sin necesidad de una máquina virtual o un arranque dual.

WSL proporciona una capa de compatibilidad que permite ejecutar binarios de Linux en Windows, lo que significa que puedes utilizar herramientas de línea de comandos, scripts y aplicaciones de Linux directamente desde tu entorno de Windows. Esto es especialmente útil para desarrolladores que necesitan trabajar en proyectos que requieren herramientas y entornos específicos de Linux, pero que prefieren utilizar Windows como sistema operativo principal.

Con WSL, puedes acceder a un shell de Linux, instalar paquetes y herramientas de Linux a través de los administradores de paquetes de las distribuciones soportadas, y ejecutar aplicaciones de línea de comandos de Linux como si estuvieras en un sistema Linux nativo. Además, WSL se integra bien con el entorno de Windows, lo que te permite acceder a tus archivos y recursos de Windows desde el entorno de Linux y viceversa.

### <ol>2. Instalación.</ol>

Ejecutamos **wsl --install -d -(distribución de nuestra preferencia)** para instalar 

![image](https://github.com/Inesita17/WSL/assets/127887874/2eeeae03-8324-453a-9e51-5cac070b1fe2)

![image](https://github.com/Inesita17/WSL/assets/127887874/471ff575-681e-4213-9266-2ede27ae45b5)

Una vez instalado **reiniciamos** el sistema.

### <ol>3. Procesos asociados a WSL</ol>

Cuando ejecutas el Windows Subsystem for Linux (WSL), varios procesos están involucrados en su funcionamiento. Algunos de los procesos clave asociados con WSL incluyen:

1. **wsl.exe**: Este es el proceso principal que gestiona la comunicación entre Windows y el entorno de Linux. Se utiliza para iniciar y controlar las distribuciones de Linux instaladas en tu sistema.

2. **init**: Este es el proceso init de Linux dentro de la distribución que has instalado a través de WSL. Es responsable de iniciar y gestionar otros procesos del sistema operativo Linux.

3. **LxssManager.exe**: Este proceso es responsable de gestionar las distribuciones de Linux instaladas en tu sistema. Controla la instalación, configuración y ejecución de las distribuciones de WSL.

4. **Vmmem**: Este proceso está asociado específicamente con WSL 2. Es la máquina virtual ligera que ejecuta el kernel de Linux en segundo plano para proporcionar una mejor compatibilidad y rendimiento.

Estos son solo algunos de los procesos principales asociados con el Windows Subsystem for Linux. Dependiendo de cómo uses WSL y las distribuciones que tengas instaladas, pueden haber otros procesos relacionados.

### <ol>4.Referencias:</ol>

- Sitio oficial de Microsoft sobre WSL: [Windows Subsystem for Linux Documentation](https://docs.microsoft.com/en-us/windows/wsl/)
- Documentación de WSL en la línea de comandos: [WSL Command Line Reference](https://docs.microsoft.com/en-us/windows/wsl/reference)
- Blog de Windows sobre WSL: [Windows Command Line](https://devblogs.microsoft.com/commandline/)
- Comunidad de usuarios de WSL en Reddit: [r/bashonubuntuonwindows](https://www.reddit.com/r/bashonubuntuonwindows/)



