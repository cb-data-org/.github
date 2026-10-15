# Cerveja Barata

**The cheap beer map:** real beer prices from bars, botecos, supermarkets and depósitos in Brazil, compared per litre,
at [cervejabarata.com.br](https://cervejabarata.com.br).<br>
*O mapa da cerveja barata: preços reais de cerveja em bares, botecos, supermercados e depósitos, comparados em reais
por litro.*

Prices are ranked by price per litre (price ÷ total volume × 1,000 ml), so a can, a long neck, a 600 ml bottle and a
draught compare fairly. They come from electronic receipts (NFC-e) on Preço da Hora Bahia, from bars' own Instagram
accounts and menus, and from people out drinking, and every price shows when it was last checked. Coverage today:
Salvador and Lauro de Freitas (Bahia). The site is free and independent: it sells no beer, and its ranking is not for
sale.

## Open data, API and MCP

- **Open data:** [cervejabarata.com.br/dados](https://cervejabarata.com.br/dados)
  ([in English](https://cervejabarata.com.br/en/data)): each city's prices, places and monthly price index, as CSV and
  JSON, updated with every publish.
- **For developers:** [cervejabarata.com.br/desenvolvedores](https://cervejabarata.com.br/desenvolvedores)
  ([in English](https://cervejabarata.com.br/en/developers)): the static files, a live API with no sign-up, and its
  [OpenAPI description](https://cervejabarata.com.br/api/v1/openapi.json).
- **MCP server:** `https://cervejabarata.com.br/mcp` (streamable HTTP, no sign-up), listed in the official MCP Registry
  as `br.com.cervejabarata/mcp`. Every answer carries the page to cite.
- **For AI agents:** [llms.txt](https://cervejabarata.com.br/llms.txt)
  ([in English](https://cervejabarata.com.br/en/llms.txt)).

## Licence

The data is open under the [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/): credit
"Cerveja Barata (cervejabarata.com.br)" and keep databases made from it open. Receipt prices: Preço da Hora Bahia,
Bahia State Treasury (SEFAZ-BA). Places derived from OpenStreetMap: © OpenStreetMap contributors, ODbL.

## Repositories

- [scrapers](https://github.com/cb-data-org/scrapers): the data collectors, a read-only mirror that runs on GitHub
  Actions. Every request identifies itself as `CervejaBarataBot/1.0 (+https://cervejabarata.com.br/bot)` and obeys
  robots.txt.

## Contact

[contato@cervejabarata.com.br](mailto:contato@cervejabarata.com.br) for questions, corrections and new cities ·
[imprensa@cervejabarata.com.br](mailto:imprensa@cervejabarata.com.br) for the press ·
[bares@cervejabarata.com.br](mailto:bares@cervejabarata.com.br) for bars.

---

Beba com moderação · Se beber, não dirija · Proibido para menores de 18 anos
