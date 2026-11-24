# Feed SUPE

Paquete del Feed SUPE para `feed_supe.exe`.

- `feed.bin`: programa, panel web y librerías, **cifrado** con la contraseña
  del operador. Sin la contraseña no se puede leer.
- `lanzador.bin`: el lanzador, **cifrado** con la misma
  contraseña.
- `version.json`: versión publicada y su sha256. El lanzador lo consulta cada
  6 horas (o con "Buscar actualizaciones") y avisa si hay una nueva.