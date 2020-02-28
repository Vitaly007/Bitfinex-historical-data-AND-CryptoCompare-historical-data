# BitFinex historical data & CryptoCompare historical data

## BitFinex historical data

In this folder you will find 1 minute candles (open/close/highest/lowest/volume) from bitfinex for the pairs:

*  **BSV/USD**
*  **BTC/USD**
*  **EOS/USD**
*  **ETC/USD**
*  **ETH/USD**
*  **IOT/USD**
*  **LTC/USD**
*  **NEO/USD**
*  **TRX/USD**
*  **XLM/USD**
*  **XMR/USD**
*  **XRP/USD**
*  **XTZ/USD**

## CryptoCompare historical data
In this folder you will find 1 hour candles (open/close/highest/lowest/volume) from cryptocompare (general data) for the pairs:

*  **ADA/USD**
*  **BCH/USD**
*  **BNB/USD**
*  **BSV/USD**
*  **BTC/USD**
*  **CRO/USD**
*  **DASH/USD**
*  **DOGE/USD**
*  **EOS/USD**
*  **ETC/USD**
*  **ETH/USD**
*  **HT/USD**
*  **LINK/USD**
*  **LTC/USD**
*  **MIOTA/USD**
*  **NEO/USD**
*  **TRX/USD**
*  **XEM/USD**
*  **XLM/USD**
*  **XMR/USD**
*  **XRP/USD**
*  **XTZ/USD**

The Bitfinex's format is [timestamp (UTC/milliseconds)],[open price],[close price],[highest price],[lowest price],[volume].

The CryptoCompare's format is [timestamp (UTC/seconds)],[open price],[close price],[highest price],[lowest price],[volume].

The Bitfinex API allows to receive up to 10000 records per request.  The CryptoCompare API allows to receive up to 2000 records per request. You can find the response from the Bitfinex and CryptoCompare (general data) servers in the "currency" folder in each currency pairs. Zero-volume candles removed from data. It takes time to receive data from the servers from the start of trading. The use of this project is to offer you a quick and easy way, to access the historical data, and relieve the servers from much of requests.

The data are provided as-is without any warranty. Use it at your own risk.

### donation
* **BTC**: 1FGkbBPpRCjbzPPx6X96geAivNsdhNWh8f
* **LTC**: LgY9fvUXi4W23MfBuhEGSfZd5Bwg6LJRFG
* **ETH**: 0xdb83f7cdf8348c4e273fcee9252d29a142908e45

Thank you :)