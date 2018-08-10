# Curso de Git y GitHub Profesional

## Tabla de Contenido

  - [Introducción](#introducción)
  - [Ventajas de Git](#ventajas-de-git)


## Introducción

### Qué es un control de versiones?
  Un sistema que registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo. Este tipo de sistemas nos permiten volver en el tiempo y salvar nuestro trabajo.

  La idea con este curso es ser capaces de crear un proyecto del cual tendremos siempre las versiones que modificamos a lo largo del desarrollo.

  Los tipos de sistemas de control son:

#### `Local Computer:`
  Solo vive en nuestro computador.
  
  <div align="center">
    <img src="static/git-local.png">
    <small><p>Sistema de Control Local</p></small>
  </div>

#### `Centralizado:`
  No depende únicamente de un computador en el que se trabaja, sino que depende del súper servidor en donde se almacena la información. El servidor provee las copias a sus hijos, pero solo guarda los cambios en un solo lugar.

  <div align="center">
    <img src="static/git-centralizado.png">
    <small><p>Sistema de Centralizado</p></small>
  </div>

#### `Sistema de control distribuido:`
   Cada uno de los que participan en el proyecto, tienen copia del proyecto que se realiza, por eso no dependemos de un solo computador que almacene toda la información.

   <div align="center">
    <img src="static/git-distribuido.png">
    <small><p>Sistema de Distribuido</p></small>
  </div>

### Qué es GIT?
  Git es un Sistema de control de Versiones Distribuido.

### Quien fue el creador de GIT?
  El creador fue `Linus Torvalds` todo por un polemica, el core de Linux entre (1991-2002) se manejaba con un control de versiones llamado `BitKeeper` (Privativo), la relación entre la comunidad y la compañia que desarrollaba `BitKeeper` se vino abajo y dejo de ser gratuita. Por esa razón la comunidad de Linux y Linus Torvalds, desarrollaron su propio control de versiones llamado GIT.



<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>

## Ventajas de GIT
  Las ventajas mas significativas de usar GIT como sistema de control de versiones es:

### - Velocidad:
  Puedes trabajar fluidamente desde tu computador.

### - Diseño Sencillo:
  El codigo es robusto con las herramientas necesarias, como viajar en el tiempo.

### - Fuerte apoyo en el desarrollo no lineal:
  No trabaja de manera lineal, la linea del tiempo tiene bifurcaciones de manera independiente al proyecto principal.
  
### - Completamente distribuido:
  Cada quien puede tener una copia del proyecto.

### - Capaz de manejar grandes proyectos:
  Es capaz de manejar proyectos muy grandes como linux y demas.

### - Git almacena referencias:
  Git almacena referencias a los archivos que no se han cambiado.
  Cualquier trabajo es local, puedes trabajar en cualquier parte incluso sin internet.

### - Git tiene integridad:
  No puedes perder información durante su transmisión o sufrir corrupción de archivos sin que Git lo detecte.
  Git almacena con `SHA-1`:
  ```sha
    24b9da6552252987aa493b52f8696cd6d3b00373
  ```
  Estos hacen referencias a una instantanea o cambios.

<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>