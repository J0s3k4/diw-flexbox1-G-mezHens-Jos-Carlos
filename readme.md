Este proyecto es una web con contenido básico principal y de pie, su propósito es la solicitud de una beca para el Erasmus+.

## Su estructura es:

Actividad4_Esqueleto/
|-Styles/
| └── estilos.css
├───── index.html
└───── readme.md

## Se abre:

Usando un plugin de Live Server para vs code

## Se compruea:

Se comprueba con "control +" o con "control -" para ir viendo como se adapta el contenido

## La creación:

El flexbox distribuye concretamente la marca y el menú de la cabecera, así como el texto y los enlaces del pie.

flexwrap wrap permite que los elemento salten de línea cuando NO hay espacio

frelgrow 1 asegura que el pie se mantenga siempre en la parte inferior

los tamaños relativos con rem y vh facilitan la adaptación a distintos dispositivos sin que el contenido se ponga feo

en enlace actual se selecciona semánticamente con [aria-current="page"], sin añadir más clases para no abultar el html

# Contraste cabecera/pie

Contrast Ratio: 10.69 (supera el mínimo exigido 4.5:1)
AA: 4.5
AAA: 7.0
Cumplen los estándares
