<img width="961" height="701" alt="image" src="https://github.com/user-attachments/assets/d447c6fa-2e37-4f97-b1a7-91de3cd48ee7" />


# Reto_PowerBI_Conexiones_modelo_estrella

Este proyecto forma parte del máster de Data Analytics.  
El objetivo era realizar el modelado de datos de un conjunto de tablas relacionales siguiendo las buenas prácticas de Power BI.

## 🔧 Pasos realizados
1. Carga de las tablas desde Access y CSV.
2. Limpieza y normalización de datos en Power Query.
3. Creación del modelo en estrella, con `FactSales` como tabla de hechos.
4. Generación de una tabla calendario (`DimCalendarcreado`) mediante DAX.
5. Marcado de la tabla calendario como tabla de fechas principal.
6. Ocultación de columnas de unión (`Keys`) para mejorar la legibilidad.
7. Deshabilitación de la tabla `DimCalendar` original para optimizar el modelo.

## 🧠 Tablas principales
- **FactSales**: ventas (tabla de hechos)
- **DimProductFinal**: productos
- **DimChannel**: canales
- **DimStoresFinal**: tiendas
- **DimPromotion**: promociones
- **DimCalendarcreado**: calendario (tabla de fechas)

## 📊 Resultado
El modelo final cumple con las buenas prácticas de Power BI, con relaciones de 1 a muchos, limpieza de campos innecesarios y un modelo estrella completamente funcional.
