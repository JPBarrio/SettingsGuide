Cicatrizado
====
Cuando una huella tiene un lado superior muy plano, existe el peligro de que se produzcan cicatrices. Esto ocurre cuando hay una línea claramente visible en la parte superior de la impresión, que no pertenece al patrón normal. Esta línea estropea la superficie superior de la huella, que por lo demás es lisa.

Una cicatriz diagonal en la superficie](../images/scarring.jpg)

Las cicatrices se crean por los movimientos de desplazamiento que cruzan la superficie superior. La boquilla caliente raspa la superficie, cortando algo de plástico, derritiendo ligeramente otro plástico, y posiblemente rezumando algo de material extra en las grietas. La cicatriz es puramente visual. No hay ninguna diferencia significativa en la fuerza o la precisión de la impresión. Sin embargo, si se crea una cicatriz en la primera capa, el raspado podría arrancar su capa de la placa de impresión.

Prevención
----
Para evitar las cicatrices, hay que evitar que la boquilla raspe la superficie superior. Puede evitar la superficie superior horizontalmente (peinado), verticalmente (salto) o evitar la necesidad de un movimiento de desplazamiento en absoluto.
* Si ajustas el [Modo de peinado](../travel/retraction_combing.md) a "No en el forro", la boquilla evitará golpear la piel al hacer un movimiento de desplazamiento. Cuando se desplaza a través de un modelo, sólo se le permite viajar a través del relleno y las paredes. Como no está viajando a través de la piel, no debería obtener ninguna cicatriz. Sin embargo, si el movimiento de viaje comienza o termina en la piel o cuando no hay un camino disponible sin golpear ninguna piel, el movimiento de viaje será recto sin golpear nada, y preferiblemente se retraerá también.
* Activar [Z hop](../travel/retraction_hop_enabled.md) para que la boquilla se eleve ligeramente antes de pasar por la superficie. Esto mantendrá cierta distancia entre la boquilla y la superficie, para que la boquilla no raspe. Esto también evitará la cicatriz. Si se utiliza el peinado, la boquilla intentará primero evitar el forro horizontalmente. Si no hay ruta disponible, se retraerá y luego saltará.
* A veces es posible evitar la necesidad de un movimiento de desplazamiento, o hacer que un movimiento de desplazamiento pase sólo por una parte de la piel que aún no se ha impreso, simplemente ajustando los [ángulos de la piel](../top_bottom/skin_angles.md). Cura ordenará las líneas para minimizar el tiempo de viaje, pero no da mucho control sobre este orden. Rotando las líneas de forro, o rotando el modelo, todas las líneas se ajustan de forma diferente, el orden de impresión será diferente y esto hace que los movimientos de desplazamiento sean diferentes. Ahora puede que ya no sea necesario ningún movimiento de desplazamiento. Sin embargo, esto es un proceso de prueba y error para conseguirlo.