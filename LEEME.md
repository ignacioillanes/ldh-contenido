# Contenido litúrgico (espejo)

Espejo de [liturgiadelashoras/liturgiadelashoras.github.io](https://github.com/liturgiadelashoras/liturgiadelashoras.github.io), obra de Manuel G. Araujo A.
Alimenta la app Liturgia de las Horas.

Existe para que la app no dependa de un repositorio que no controlamos: si el
original desapareciera o cambiara de estructura, este espejo conserva el archivo
histórico completo.

- Los ficheros se replican **byte a byte**, en codificación windows-1252. No los
  "arregles": la app los descodifica contando con ese formato exacto.
- `.github/workflows/sync-upstream.yml` sincroniza a diario con el original.
  La sincronización es **aditiva**: si el original borra algo, aquí se conserva.
- Los textos litúrgicos son propiedad de las conferencias episcopales
  correspondientes.
