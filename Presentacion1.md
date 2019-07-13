name: inverse
layout: true
class: center, middle, inverse
---
name: Inicio

.left-column[
<image src="http://www.ulsac.edu.mx/imagenes/unam1complejocopytz2.gif" width="140px">
<image src="http://www.mdcbq.posgrado.unam.mx/img/logo.png" width="160px">
<image src="http://rsg-mexico.iscbsc.org/images/RSG_logo_transparente_2.png" width="140px">
]

.right-column[
#Curso de Estadística con R
[Biol. Homobono Fuentes Luis Eloy]
[luis.homobono@ciencias.unam.mx](mailto:luis.homobono@ciencias.unam.mx)
]
---
template: inverse

## Introducción

---
name: historia
layout: false
.left-column[
## Breve historia

]
.right-column[

- R es un lenguaje basado en S de AT&T (John Chambers & Rick Becker)<br>

- La mezcla S y Scheme para generar R en la universidad de Auckland (**Robert Gentleman** & **Ross Ihaka**, 1995)
   -  R esta escrito en C y Fortran
   -  GNU General Public License (freely available)<br>
   
- Creación del R Development Core Team y el CRAN (1997)<br>

- Versión mas antigua. Versión 0.49 (23 de abril de 1997)<br>

- Versión 3.4.0 (21 de abril de 2017)<br>

```
> contributors()
```
]

---
name: historia
layout: false
<br>
<image src="IMG/TIOBE_rating.png" href="https://www.tiobe.com/tiobe-index/" width="800px">
---
name: que_es
layout: false
.left-column[
  ## ¿Qué es R?
<br><br>
<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Rlogo-unofficial-vector-editable.svg/725px-Rlogo-unofficial-vector-editable.svg.png" width="160px">
]
.right-column[

**R** es un **lenguaje de programación** para la **estadística** y el **modelado de datos**.
	
R tiene las siguientes características:

- Es elegante y versatil

- Sintaxis diseñada para trabajar con datos

- Capacidades gráficas altamente potentes

- Facil y eficiente manipulación de datos

]

---
name: que_es
layout: false
.left-column[
  ## ¿Qué es R?
<br><br>
<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Rlogo-unofficial-vector-editable.svg/725px-Rlogo-unofficial-vector-editable.svg.png" width="160px">
]
.right-column[
<br>
**Desventajas** 
 - El intérprete R no es rápido cuando se confronta con grandes cantidades de código R puede ser lenta.
 - R está configurado para realizar cálculos vectorizados y no cálculos escalares (elemento por elemento).
<br>
]

---
template: inverse

## ¿Dónde comienzo?
---
name: instalacion

.left-column[
  ## Instalación
### - Windows
]
.right-column[
Lo primero es identificar donde descargamos R para instalarlo: 

```
https://cran.r-project.org/bin/windows/base/
```
<image src="IMG/R_for_windows.png" width="590px">
]
---
name: instalacion2

.left-column[
  ## Instalación
### - MAC
]
.right-column[
Lo primero es identificar donde descargamos R para instalarlo: 

```
https://cran.r-project.org/bin/macosx/
```
<image src="IMG/R_for_MAC.png" width="590px">
]
---
name: instalacion3

.left-column[
  ## Instalación
### - Linux
]
.right-column[

Abrimos una terminal de linux (Ctrl + Alt + T) y dentro de esta, dependiendo del sistema operativo:

<image src="IMG/ubuntu-logo.png" width="18px"> Ubuntu
```remark
$ sudo apt-get install r-base
```
<image src="IMG/fedora.png" width="18px"> Fedora
```remark
$ su -c 'yum install R'
```
<image src="IMG/archlinux.png" width="18px"> Arch Linux
```remark
$ sudo pacman -S r
```
]
---

.left-column[
  ## ¿Cómo funciona?
  ### - Ejecutar desde el cmd/terminal 
  ### - Entornos graficos
]
.right-column[
#### Desde Windows:

- Opcion A:

 Inicio > Simbolo del sistema

- Opcion B:

 Buscar > CMD > R


#### Desde MAC/Linux:
1. Se abre la terminal


## Se ejecuta:
```bash
R
```
]

---
.left-column[
  ## ¿Cómo funciona?
  ### - Entornos graficos
]
.right-column[
### RGui

Ambiente gráfico del interprete, sus caracteristicas son:
- Capacidad para hacer y editar código
- Consola del interprete

<image src="https://www.oreilly.com/library/view/r-in-a/9781449358204/httpatomoreillycomsourceoreillyimages2182916.png" width="380px" align="middle">

]

---
.left-column[
  ## ¿Cómo funciona?
  ### - Entornos graficos
]
.right-column[
### RStudio

Ambiente gráfico integrado, se basa en diversos compartimentos:
 - Consola para editar código
 - Ventana de datos e historial
 - Ventana de la Consola
 - Ventana de gráficas y archivos

<image src="http://www.sthda.com/sthda/RDoc/images/rstudio.png" width="380px" align="middle">
]
---
.left-column[
<br>
<image src="https://www.rstudio.com/wp-content/uploads/2016/09/RStudio-Logo-Blue-Gray-250.png" width="150px" align="middle">
]
.right-column[
<br> <br>

- Provee acceso directo al código en R.

- Uso para proyectos que requieren interacción directa con el código o manipulacion de datos compleja

- Importando desde el ambiente grafico


<image src="https://support.rstudio.com/hc/en-us/article_attachments/206327917/data-import-environment.png" width="550" align="rigth">

]

---

name: code_start
template: inverse

## Bibliografía Recomendada

---

.left-column[
  ## Obtener ayuda
   ### - Interna

]

.right-column[
 

 - **FAQ on R:** [https://cran.r-project.org/doc/FAQ/R-FAQ.html](https://cran.r-project.org/doc/FAQ/R-FAQ.html)

 - **FAQ on R for Windows:**  [https://cran.r-project.org/bin/windows/base/rw-FAQ.html](https://cran.r-project.org/bin/windows/base/rw-FAQ.html)

 - **R Manuals:** [https://cran.r-project.org/manuals.html](https://cran.r-project.org/manuals.html)

 - **R Help Mailing Lists**  [http://www.r-project.org/mail.html](http://www.r-project.org/mail.html)


]



---

.left-column[
  ## Obtener ayuda
   ### - Interna
   ### - Externa

]

.right-column[
 
### Para R

 - **R-Forge:**  [http://r-forge.r-project.org/](http://r-forge.r-project.org/)

 - **R Graph Gallery:**  [http://addictedtor.free.fr/graphiques/](http://addictedtor.free.fr/graphiques/)

 - **RSeek**  [(http://www.rseek.org](http://www.rseek.org) 


### Para estadística

 -  **Probabilidad y Estadistica para ingeniería y ciencias**
 *Warpole &bull; Myers &bull; Myers. 9th Ed*

### Para todo
 - **Google**  [www.google.com](www.google.com) 

]

---
name: last-page
template: inverse

## Gracias por Todo!

Visita mi: <br>
<br>[Twitter](https://twitter.com/evo_eloy)
<br>[Facebook](https://www.facebook.com/Luis.Eloy.Hom)
<br>[GitHub](https://github.com/Luis-Prot)


Slideshow created using [remark](http://github.com/gnab/remark).

