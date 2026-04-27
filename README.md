# Git Flow
 
Git Flow es un modelo de ramificación para Git creado por Vincent Driessen. Define una estructura clara de ramas y reglas sobre cómo deben interactuar entre sí, con el objetivo de organizar el desarrollo de software de forma ordenada y predecible.
 
## ¿Cómo funciona?
 
El modelo gira en torno ramas de larga duración, en este casi siendo: **main**, que siempre refleja el código en producción, **laboratory** que es un ambiante de pruebas estable, y **integration** donde se integra el trabajo en curso.
 
A partir de estas, se crean ramas temporales según la necesidad: para desarrollar nuevas funcionalidades, para preparar un lanzamiento o para corregir errores críticos en producción. Cada tipo de rama tiene un origen y un destino definidos, lo que evita mezclas accidentales de código.