<h1>Sistema de Registro</h1>
"Para este proyecto, se integraron datos de cuatro fuentes distintas (tiendas 1 a 4) mediante técnicas de concatenación, asegurando la estandarización de formatos de fecha y la consolidación de métricas financieras en un único conjunto de datos centralizado."

Tras la unión, se ejecutó un proceso de limpieza integral que incluyó la normalización de formatos temporales y la eliminación de registros duplicados, asegurando que el análisis posterior represente la realidad global de la empresa.

1. Ventas por Ciudad/Región (Gráfico de barras morado/verde)
Interpretación: Existe una concentración masiva del mercado en Bogotá y Medellín. Bogotá triplica prácticamente a la segunda ciudad más importante.

Conclusión de negocio: Alura Store es un negocio principalmente capitalino. Si se busca crecer, hay un potencial enorme "dormido" en ciudades intermedias como Pereira o Barranquilla, o se debe reforzar la logística en el núcleo central.

2. Ingresos por Categoría (Gráfico de barras azul horizontal)
Interpretación: Electrónicos y Electrodomésticos son los motores financieros de la tienda.

Conclusión de negocio: Aunque se vendan menos unidades que en "Libros", el valor de estos productos genera el mayor flujo de caja. Es la categoría crítica para la rentabilidad.

3. Distribución de Métodos de Pago (Gráfico de torta)
Interpretación: El 73.1% de los clientes usa Tarjeta de crédito. Nequi aparece como una alternativa digital relevante con el 20.1%.

Conclusión de negocio: El negocio depende del financiamiento. Es vital tener una pasarela de pagos que nunca falle para tarjetas y, quizás, crear promociones específicas para Nequi para captar a ese 20%.

4. Top 10 Vendedores (Tabla)
Interpretación: Felipe Santos lidera en ventas totales con una calificación sólida (4.07). Sin embargo, nota que Rafael Acosta tiene una calificación casi igual con menos ventas.

Conclusión de negocio: Se pueden crear programas de mentoría donde Felipe enseñe a cerrar ventas y Rafael (u otros con alta nota) enseñen sobre atención al cliente.

5. Relación Precio vs. Calificación (Gráfico de puntos)
Interpretación: La correlación es prácticamente cero. Hay productos de 3 millones con calificación 5 y productos de 100 mil con calificación 1 (y viceversa).

Conclusión de negocio: El precio no garantiza satisfacción. La calidad percibida es independiente de cuánto paga el cliente. No tengas miedo de vender productos caros, siempre que la calidad se mantenga.

6. Relación Precio vs. Cuotas (Gráfico con línea roja)
Interpretación: La línea roja es casi plana.

Conclusión de negocio: Sorprendentemente, la gente no pide más cuotas solo porque el producto sea más caro. Hay gente comprando cosas baratas a muchas cuotas y cosas caras a pocas. El comportamiento financiero es variado.

7. Matriz de Correlación (Mapa de calor)
Interpretación: Ves los cuadros rojos con 1.00 entre Precio, Costo de envío y Total_Venta. Esto es obvio (a más precio, más venta total). Lo interesante es el 0.00 con la Calificación.

Conclusión de negocio: Los datos confirman matemáticamente que nada de lo que vendes (ni el precio ni el envío) está afectando la nota del cliente. La satisfacción depende de factores que no están en esta tabla (como tiempo de entrega o servicio post-venta).

Insights de Negocio:

Dominio de Mercado: Bogotá representa el núcleo de ingresos, sugiriendo una oportunidad de expansión en ciudades de la costa y el eje cafetero.

Perfil de Pago: El cliente de Alura Store es altamente digital y bancarizado (93% entre Tarjeta y Nequi).

Satisfacción Independiente: La calidad percibida no está ligada al valor monetario, lo que permite una estrategia de precios flexible.


Para ejecutar el sistema, debes poner:
```npm install react```
