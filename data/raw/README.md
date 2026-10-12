# data/raw

Datos originales del Banco de la República, sin modificar. Fuente: portal *Series estadísticas históricas de Colombia* → Producto Interno Bruto → "PIB por demanda", fila **"1. PIB reportado"** (cifras DANE).
Consultado el 12 de octubre de 2026.

| Archivo | Serie | Unidad | Cobertura |
|---|---|---|---|
| `pib_base2005_trimestral.csv` | PIB trimestral, base 2005 | Miles de millones de pesos, valores constantes de 2005 | I-2000 a IV-2017 |
| `pib_base2015_trimestral.csv` | PIB trimestral, base 2015 | Miles de millones de pesos, valores constantes de 2015 | I-2005 a II-2026 |

Notas:

- Ambas son series **desestacionalizadas** (la opción "Constante - desestacionalizado" del portal, que es la única de precios constantes que ofrece).
- El portal no entrega la serie anual directamente. El PIB anual se calcula en el notebook sumando los cuatro trimestres de cada año.
- Los valores coinciden exactamente con los Excel descargados con "Exportar" del portal el 12 de octubre de 2026.
- El Banco de la República solo ofrece el PIB de estas bases de forma trimestral (no anual) y desestacionalizada.
- Enlace de los datos: https://uba.banrep.gov.co/htmlcommons/SeriesHistoricas/producto-interno-bruto.html
