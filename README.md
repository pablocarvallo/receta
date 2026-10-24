# Mi cápsula diaria

App personal para iPhone que cuenta las cápsulas de un preparado magistral, descuenta una por día y avisa cuándo mandar a hacer la receta (al quedar 12, 10 y 5 cápsulas).

Abrir en Safari en https://pablocarvallo.github.io/receta/ y elegir Compartir → «Agregar a inicio».

Los datos se guardan solo en el dispositivo.

## Panel Casa

Al final de la app está la tarjeta «Panel Casa». Con «Pegar código» (el código se copia en Panel Casa → Conexiones), la app publica en el buzón privado de GitHub las cápsulas que quedan, el día de la última toma y si la receta está pedida, en el hito «Cápsula · panel». Así se ve en Panel Casa. Se publica cada vez que cambia algo; «Desconectar» deja de publicar y vacía el hito.

El módulo es el mismo en todas las apps conectadas y se copia desde el repositorio casa con `python3 herramientas/conectar-apps.py`.
