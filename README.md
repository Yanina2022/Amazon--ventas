
# Amazon--ventas
Proyecto 
Proyecto ventas AMAZON- a modo de tablero informativo sobre las ventas realizadas en los EEUU. en el año 2025.

Acerca del conjunto de datos
Descripción
Este conjunto de datos contiene 250 registros de transacciones de ventas de Amazon, incluidos detalles sobre los productos vendidos, los clientes, los métodos de pago y los estados de los pedidos.

Columnas Descripción: ID de pedido:
identificador único para cada pedido (por ejemplo, ORD0001).

Fecha - Fecha del pedido.

Producto: nombre del producto comprado.

Categoría - Categoría de producto (Electrónica, Ropa, Electrodomésticos, etc.).

Precio - Precio de una sola unidad del producto.

Cantidad: número de unidades compradas en el pedido.

Ventas totales: ingresos totales del pedido (precio × cantidad).

Ubicación del cliente: ciudad en la que se encuentra el cliente.

Método de pago: modo de pago (tarjeta de crédito, tarjeta de débito, PayPal, etc.).

Estado: estado del pedido (Completado, Pendiente o Cancelado).

Este conjunto de datos se puede utilizar para el análisis de ventas, la información sobre el comportamiento del cliente y la visualización de tendencias de ingresos. 🚀

# En este dashboard para comenzar a obtener información de los graficos se comenzó ante todo con la limpieza de los datos con PYTHON, donde se verifico la existencia de valores nulos y duplicados , luego al subir la base de datos a POWER BI se realizaron métricas en POWER QUERY para obtener valores totales y precio promedio para concluir con los graficos.

se inicio con 3 tarjetas , ventas totales en dinero, cantidad de ventas y el precio promedio de los productos.
 
Del lado izquierdo se colocaron 2 segmentadores para seleccionar fecha de las ventas y lugar de origen(estado de los EEUU) donde se realizo la compra de los productos

En el centro 2 graficos , ventas por fecha en un grafico de líneas y ventas por producto en grafico de barras invertidas.

En el pie del tablero, se realizaron 2 graficos de barras, uno de columnas apiladas donde se puede observar las ventas realizadas por tipo de pago y en el segundo, de barras invertidas, el estado de los pedidos.

Para finalizar , en ultimo lugar se coloco un mapa para visualizar los Estados de los EEUU donde se realizado la compra de los productos.

Para concluir se incluyo un botón para borrar todos los segmentadores.

INFORMACION OBTENIDA MAS RELEVANTE-INSIGHTS DE VALOR:

1- Las ingresos de dinero totales fueron de USD$243.845
2- La cantidad de ventas fueron de 714.
3- El precio promedio de los productos fue de USD$ 344. 
4- El mes de febrero fue el mas favorable, donde mas ingresos se registro, con un monto de USD$ 11.400.
5- El producto mas vendido ha sido en el sector de los Refrigeradores con un valor de USD$ 78.000 y en segundo lugar las Laptop con ingresos de USD$ 58.400.
6- El método de pago mas utilizado por los clientes ha sido PayPal con valores de USD$ 69.600, en segundo lugar las tarjetas de crédito con ingresos de dinero de USD$ 61.000, dejando en ultimo lugar las tarjetas de debito con USD$ 31.900.
7- Los pedidos completados han sido del %88, los pendientes del %85 y los cancelados del %77 .
8- El lugar donde mas ventas se han registrado ha sido en Houston con 89 productos vendidos por el valor de USD$ 28.390.

RECOMENDACIONES-SUGERENCIAS-PROPUESTAS PARA AEREAS DE MEJORA:
💡 1. Potenciar productos con mayor rendimiento,fortalecer campañas de marketing y stock en productos como refrigeradores y laptops, ya que lideran en los ingresos.
Ya que estos productos muestran alta demanda y buen ingreso económico.

📅 2. Analizar y replicar las promociones, publicidad o condiciones especiales que se aplicaron en febrero,ya que fue
 el mes más rentable .
 Puede haber habido campañas exitosas, eventos comerciales o comportamientos estacionales.

💳 3. Optimizar y priorizar métodos de pago preferidos
 Favorecer el uso de PayPal y tarjetas de crédito, con promociones o facilidades, ya que concentran la mayoría de ingresos.


🧾 4. Mejorar la gestión de pedidos pendientes y cancelados , habría que
 Revisar procesos logísticos y de atención al cliente para reducir los pedidos pendientes  y cancelados
Un porcentaje tan alto afecta la experiencia del cliente y los ingresos .

📍 5. Enfocar distribución y campañas en Houston,Priorizar envíos, stock y promociones ya que fue la ciudad donde mas ventas han habido.
 Puede ser un mercado clave que responda bien a nuevos lanzamientos o descuentos.

💰 6. Revisar el precio promedio Evaluar si el precio promedio de USD$344 se alinea con el poder adquisitivo y la competencia. Posiblemente introducir opciones más económicas o mejores productos en cuanto a su calidad.
