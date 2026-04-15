# PyG Socios — Bonita Menorca

Cuadro de mando económico para socios. App estática HTML/JS desplegada en Vercel.

## Uso

1. Abre la URL de la app
2. Sube el fichero Excel con las pestañas **PYG**, **PRESUPUESTO** y **PLAN DE CUENTAS**
3. Explora los datos con los filtros de canal, vista y modo

## Estructura del Excel

| Pestaña | Columnas |
|---|---|
| PYG | CUENTA · DESCRIPCION · CANAL · ENERO … DICIEMBRE |
| PRESUPUESTO | Misma estructura que PYG |
| PLAN DE CUENTAS | CUENTA · DESCRIPCION · TIPO CUENTA · DESCRIPCION GRUPO |

`TIPO CUENTA` puede ser `NORMAL` o `MERCADO INTERNO`.  
Las cuentas de Mercado Interno se incluyen en cada centro pero se excluyen del consolidado global.

## Despliegue

Conectar este repo a [Vercel](https://vercel.com) — se despliega automáticamente en cada push.
