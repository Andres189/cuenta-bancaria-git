# Cuenta bancaria — Git y pull requests

**Autor:** Andrés Juárez Garduño

## Cómo correr

    ./correr.sh

## Mis pull requests

| # | Qué cambió |
|---|---|
| 1 | El estado de cuenta muestra cuántos retiros se hicieron y cuántos fueron gratis |
| 2 | README y evidencia de la práctica |

## Boleto de salida

1. ¿Qué diferencia hay entre `git add` y `git commit`?

   Respuesta: git add se usa para preparar los cambios que se hiceron y git commit para guardar esos cambios en un historial.

2. ¿Por qué después del merge en GitHub tu `main` de Ubuntu no tenía el cambio hasta que hiciste `git pull`?

   Respuesta: Por que aun estaba digamos en una version anterior del codigo, hasta que se hizo el git pull ya tenia los cambios en rama main.

3. Abriste un PR y después hiciste otro commit en la misma rama. ¿Qué pasó con el PR?

   Respuesta: En el PR se tien que actualizar a los cambios mas nuevos (ultimo commit).

4. ¿Por qué en un equipo nadie hace cambios directamente en `main`?

   Respuesta: Tendrian muchos problemas a la hora de hacer el merge porque puede que varios esten trabajando en el mismo archivo.