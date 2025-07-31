# PetMind - Análisis Exploratorio de Datos
Este análisis explora cómo las compras repetidas impactan las ventas de **PetMind**, una empresa minorista de productos para mascotas.

## Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas del último año y contiene las siguientes columnas:

- **product_id**: Identificador único del producto.
- **category**: Categoría del producto (Alimentos, Vivienda, Juguetes, Equipos, Medicamentos, Accesorios).
- **animal**: Tipo de animal (Perro, Gato, Pez, Pájaro).
- **size**: Tamaño del animal (Pequeño, Mediano, Grande).
- **price**: Precio del producto.
- **sales**: Ventas totales por producto.
- **rating**: Calificación del producto (1 a 10).
- **repeat_purchase**: Si el producto fue comprado repetidamente (1 = Sí, 0 = No).

## Técnicas Empleadas
1. **Limpieza de Datos**: 
   - Imputación de valores faltantes.
   - Conversión de datos a tipos correctos (e.g., `category`, `animal`, `size`).
   - Reemplazo de valores atípicos y faltantes según las consideraciones del dataset.
2. **Análisis Visual**: 
   - Gráficas de distribución de ventas, categorías y tipo de compra.
   - Análisis de la relación entre compras repetidas y ventas mediante boxplots y histogramas.
3. **Estadísticas Descriptivas**: 
   - Análisis de ventas por categorías, tipo de mascota y tamaño del producto.

## Hallazgos Clave
1. **Compras Repetidas**:
   - El 60.4% de las ventas corresponden a compras repetidas.
   - Las categorías **"Equipment"** y **"Food"** tienen la mayor cantidad de compras repetidas.
2. **Distribución de Ventas**:
   - La mayoría de las ventas ocurren en el rango de precios medios, con una concentración alrededor de los 1000 USD.
   - Las ventas de productos de lujo tienen una baja frecuencia.
3. **Relación entre Compras Repetidas y Ventas**:
   - Las compras repetidas representan el 59% del total de ingresos, con una dispersión menor en los montos de ventas repetidas comparado con las ventas no repetidas.
4. **Impacto por Categoría y Tamaño**:
   - Los clientes con **gatos** como mascotas y productos de tamaño **pequeño** son los más asiduos compradores.
   - Las compras repetidas son más frecuentes en productos de tamaño pequeño y mediano.

## Recomendaciones
- **Estrategia de Ventas**: Focalizar las campañas en productos de bajo precio y tamaño pequeño, con buenas calificaciones, para incrementar las compras repetidas.
- **Diversificación de Productos**: Aumentar la oferta de productos en el rango de precio medio (alrededor de 1000 USD) y mantener una oferta premium de lujo.
