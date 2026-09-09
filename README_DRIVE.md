# GastosApp V12

Incluye:
- cotizaciones automáticas de ETH/SOL con CoinGecko;
- cotizaciones de ETF/acciones mediante Yahoo Finance, a través de tu Google Apps Script;
- conversión USD/EUR mediante EURUSD;
- símbolo de mercado preasignado para AUM5, VVSM, CNDX, PPFB, QDVE y CIFR;
- histórico de última actualización y fuente;
- copia/sincronización Drive.

## Para activar las cotizaciones de bolsa
En Google Apps Script sustituye el código anterior por `GoogleAppsScript_Code_V12.gs` y crea una **nueva versión del mismo deployment**. No crees otro proyecto ni cambies la URL.

El token ya está incorporado en el archivo `.gs`; no lo publiques ni lo compartas.

La fuente de cotización de bolsa es Yahoo Finance a través del Apps Script. La cotización puede ser retrasada según el mercado. La app conserva el último valor si una fuente no responde.

El S&P 500 EUR (Acc) está identificado como Amundi S&P 500 Swap UCITS ETF EUR Acc, ISIN LU1681048804, ticker Xetra AUM5/AUM5.DE.
