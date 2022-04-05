# Qué es Git?

Es un software para el manejo de control de versiones de nuestro código. Una de las cosas por las cuales los desarrolladores utilizan, por encima de otros sistemas, es por su velocidad. Es ágil y sencillo.

A diferencia de SVN, por ejemplo, Git hace honor a su nacimiento, siendo un sistema de control de versiones distribuido. Así como existe el repositorio central (o remoto) del proyecto, cada desarrollador posee en su equipo lo que se conoce como repositorio local. Esto ayuda de gran manera a tener un control más ordenado, preciso, y además, reduce el porcentaje de error.

## Fases en el repositorio 

Existen algunos pasos con el fin de lograr completar las fases y tener los estados comentados en el punto anterior. Para entender cómo funcionan estos pasos o comandos veremos nuevos conceptos de Git.

- *Add*: este método nos permite agregar los cambios realizados, es decir, cambia el estado de nuestros archivos de “Modificado” a “Preparado”, pasa los archivos del working directory al staging area.
- *Commit*: realiza el cambio de nuestros archivos en estado “Preparado” a “Confirmados”, lo que quiere decir que los deja finalmente en el repositorio de git.

- *Push*: este comando se utiliza para subir todos los cambios hecho al repositorio en git hub

## Qué son las ramas y cómo funcionan 

Las ramas son las líneas de desarrollo únicas que se encuentran dentro del repositorio y nos ayudan a tener mayor control. Un repositorio debe tener al menos una rama. Por convención, la rama principal es denominada *“máster”*. 

Para el desarrollo del módulo de usuarios, deberíamos trabajar de una forma en la que no dañemos el que tenemos funcionando de forma correcta, en este caso, el módulo de productos. Por ello, se creó el concepto de ramas.

## Estos son algunos de los comandos para las ramas:

|Comando|Explicación|
|-|-|
| *git branch*|enumerará todas las ramas disponibles en su código|
|*git merge*|Permite, desde la rama *master*, fusionar todos los cambios de una rama de función en la rama maestra.|
|*git checkout* (Nombre de a rama)|Sirve para colocarse en la rama que deseas|

![Git](https://www.adictosaltrabajo.com/wp-content/uploads/2020/01/intergracionportada.png)

[Regresar](README.md)