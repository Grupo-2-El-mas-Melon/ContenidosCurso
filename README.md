# ContenidosCurso

> Hemos creado una carpeta en una ramificacion para que cada uno haga sus ejercicios
> **SIEMPRE TRABAJAR** DESDE NUESTRA PROPIA RAMA => Comprobar con `git branch` y `git checkout RamificacionNombre`
> TODOS LOS DIAS MIENTRAS HAYA CAMBIOS => `git pull` en la RAMA PRINCIPAL (MAIN) con `git checkout main`

## ¿Como se ha realizado? Poned estos comandos

1. `git add .`
2. `git branch RamificacionNombre` => En vez de Nombre, cada uno pondrá el suyo.
3. `git branch` => Por comprobar
4. `git checkout RamificacionNombre`
5. `git add .`
6. `git commit -am "Hemos añadido un archivo de prueba"`
7. `git push origin RamificacionNombre` => Para subir los cambios en nuestro Branch
8. `git checkout main` => Para volver a la rama principal
9. `git pull` => Para ver los cambios de los compañeros
10. `git merge RamificacionNombre`=> Para fusionar los cambios de nuestra rama a la principal (Deberia ser de alguien superior)
11. `git push` => Siempre que haya cambios o se finalice una actividad
12. `git rebase main `=> En la rama creada (RamificacionNombre). Esto va a hacer que se actualice con la main (con el resto de cambios)

EN CASO DE QUE HAYA ERROR, VOLVER A EMPEZAR ELIMINANDO TU RAMA => `git branch -D RamificacionNombre`
