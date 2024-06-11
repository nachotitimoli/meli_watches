# Mercado Libre Argentina | Categoría "Joyas y Relojes"

Análisis de ventas, productos y facturación total de un puñado de vendedores de artículos de Joyería y Relojería, categorizados de esa forma en el portal de Mercado Libre.

Fuente de datos: la misma surgió a partir de la conexión establecida con la API de Mercado Libre (https://developers.mercadolibre.com.ar/). Por motivos de seguridad, las claves de acceso han sido eliminadas del .ipynb explicativo.

## Principales conclusiones:

- En primer lugar, puede observarse que, al menos en la muestra aleatoria que fue considerada, la mayoría de los vendedores no eligió la categoría "gold_pro" para ofrecer sus productos. En la teoría, dicha categoría brindaría mayor propensión a la venta, pues otorga planes de financiación a clientes más prolongados. Solo uno de los once sellers se decidió por esta opción. Si focalizamos nuestro análisis sobre esta empresa en particular (GRUPO_AGG), puede verse que la cantidad de visitas que su publicación recibió durante los últimos 90 días fue de apenas 45, ubicándose en el 7mo lugar si se toma como referencia la nominalidad de las ventas potenciales y en el último lugar si se consideran las visitas propiamente dichas. Sin embargo, este dato contrasta con su tasa de conversión o convertion rate (CR): la misma fue de un 6,67%, lo cual la ubica primera entre todos los sellers sujetos a análisis.
Es destacable considerar, que esta empresa durante el mes de marzo no ofreció productos a la venta, lo cual tiene incidencia no solo sobre las visitas que pudo recibir, sino también sobre la CR.
Si bien este dato es estimativo, podría afirmarse que las condiciones preferenciales que ofrece a sus clientes a la hora del pago, estarían otorgándole a priori una ventaja competitiva frente a sellers del mismo tipo.

- En segundo lugar, y a propósito del convertion rate mencionado, puede verse una mejora creciente en los 3 meses bajo análisis. Mientras en feb/24 el mismo rondaba el 0,42%, en abr/24 escaló al 0,91%. Esto tuvo un correlato, a su vez, sobre las ventas, las cuales se incrementaron un 360% en términos nominales en el mismo período.

- Por último, resulta interesante analizar la correlación entre el precio de venta y las visitas recibidas por los productos. Podríamos afirmar que el precio de venta no estaría fijado **únicamente** en virtud de las visitas, ya que la correlación es baja. Por decirlo de otra manera: la cantidad de visitas recibidas por un producto no tendría implicancias inmediatas en el aumento del precio del producto, al menos de lo que se desprende del análisis de esta pequeña muestra de casos.
