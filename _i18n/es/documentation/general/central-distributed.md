Básicamente, hay dos maneras de hacer una aplicación de podcast:

1. **Central**: Hay un servidor central (hospedado por la empresa que desarrolla
la aplicación) que comprueba si hay episodios nuevos y te los entrega.
1. **Distribuida**: La aplicación comprueba por sí misma si hay episodios nuevos,
directamente desde los servidores de los publicadores.

AntennaPod utiliza el segundo método. Esto tiene unas cuantas ventajas y
desventajas:

- Como la aplicación busca episodios nuevos, los creadores de la aplicaciones
(como nosotros), no tienen que mantener un servidor central. Esto ahorra un
montón de tiempo y esfuerzo. También ahorra mucho dinero, lo que significa que
no tenemos que depender de anuncios o grandes cantidades de donaciones.
- Como la aplicación no depende de un servidor central para recolectar los
episodios nuevos, AntennaPod seguirá funcionando independientemente de lo que
hagamos en nuestra parte. Utilizando el método centralizado, si la empresa
termina su servidor por cualquier motivo, la aplicación dejará de funcionar.
- Nosotros, como desarrolladores de aplicaciones, no sabemos ni podemos saber a
qué podcasts estás suscrito, qué episodios escucharás o a qué hora lo harás.
Los publicadores de aplicaciones con un servidor central recogen tales datos,
para el detrimento de tu privacidad.
- Algunos publicadores ofrecen canales privados, proveyendo acceso por
adelantado, contenido especial o episodios sin anuncios. Tales canales
requieren un usuario y una contraseña, que AntennaPod le da directamente al
huésped cuando lo pide. Los servicios centralizados muchas veces simplemente no
permiten añadir canales privados. Y si lo hacen, puede que requieran que mandes
tus credenciales a quienes hacen la aplicación.
- Al no tener un punto central de acceso, lo que permitiría a los desarrolladores
eliminar podcasts de su servidor, no hay riesgo de censura.
- Por otro lado, un modelo distribuido significa que solo obtendrás episodios
nuevos cuando actualices un podcast. En AntennaPod, esto ocurre por defecto
cada 12 horas, pero puedes cambiarlo a una frecuencia mayor o menor y también
puedes comprobar manualmente si hay episodios nuevos. Un servidor central puede
comprobar si hay episodios nuevos con mucha frecuencia o incluso ser informado
por los huéspedes de los podcasts en tiempo real. De este modo, las aplicaciones
pueden saber si hay episodios nuevos mucho más rápido, sin tener que comprobar
regularmente todos los podcasts a los que estás suscrito.
- Tampoco es posible que AntennaPod te sirva ningún episodio que haya sido
eliminado por el editor, por ejemplo porque solo mantienen los últimos 10
episodios más recientes en línea. Las aplicaciones que dependen de un servidor
central, pueden servirse de los episodios antiguos incluso si desaparecieron del
canal RSS.
