# Showz Marketing Analysis - Sprint 9

## Descripción
En este proyecto analicé cómo los clientes usan Showz, la plataforma de venta de entradas, y cómo podemos optimizar el gasto en marketing. Usé **Jupyter Notebook** con Python y SQL para procesar los datos, calcular métricas clave y crear visualizaciones que ayudan a tomar decisiones estratégicas.

## Contexto
Como analista de datos, mi objetivo fue:  
- Entender el comportamiento de los usuarios y sus patrones de compra.  
- Determinar cuándo los ingresos cubren el costo de adquisición de cada cliente.  
- Identificar las fuentes de adquisición más rentables para invertir mejor el presupuesto de marketing.

## Datos
### Visits (`visits_log_us.csv`)
- `Uid`: identificador único del usuario  
- `Device`: dispositivo usado  
- `Start Ts`: inicio de la sesión  
- `End Ts`: fin de la sesión  
- `Source Id`: fuente de anuncios  

### Orders (`orders_log_us.csv`)
- `Uid`: usuario que realizó la compra  
- `Buy Ts`: fecha y hora del pedido  
- `Revenue`: ingresos generados  

### Costs (`costs_us.csv`)
- `source_id`: fuente de anuncios  
- `dt`: fecha  
- `costs`: gasto en marketing  

> Nota: Limpié y preprocesé los datos para evitar inconsistencias y errores.

## Qué hice en el análisis
1. **Visitas y sesiones**  
   - Conté cuántos usuarios visitan Showz por día, semana y mes.  
   - Analicé cuántas sesiones hace cada usuario y la duración promedio.  
   - Identifiqué la frecuencia con la que los usuarios regresan al sitio.

2. **Ventas y comportamiento de compra**  
   - Medí cuánto tardan los usuarios en hacer su primera compra (Conversion 0d, 1d, …).  
   - Calculé el número de pedidos y el ticket promedio por usuario.  
   - Estimé el valor total que cada cliente aporta (LTV).

3. **Marketing y ROI**  
   - Analicé cuánto se gastó en cada fuente de anuncios.  
   - Calculé el costo de adquisición por cliente (CAC).  
   - Evalué qué campañas y fuentes generaron mejor retorno de inversión (ROMI).

4. **Visualizaciones**  
   - Comparé métricas por dispositivo y fuente de anuncios.  
   - Observé cómo cambiaron los ingresos y la actividad de usuarios a lo largo del tiempo.  
   - Detecté tendencias y cohortes de usuarios clave para la optimización.


## Autor
Wendy Julieth Hernández Franco  
[Mi GitHub](https://github.com/wjhernandez)
