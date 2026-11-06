# Feed SUPE

Paquete del Feed SUPE para `feed_supe.exe`.

- `feed.bin`: programa, panel web y librerías, **cifrado** con la contraseña
  del operador. Sin la contraseña no se puede leer. No lleva credenciales: cada
  máquina las guarda junto al `.exe` y se editan desde el panel web.
- `version.json`: versión publicada y su sha256. El lanzador lo consulta cada
  6 horas (o con "Buscar actualizaciones") y avisa si hay una nueva.
