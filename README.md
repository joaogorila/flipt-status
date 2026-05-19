# Status do Flipt

> Monitoramento em tempo real dos serviços do [Flipt](https://app.flipt.com.br) — backend, frontend, banco, WhatsApp e provedores externos.

Página pública: **[status.flipt.com.br](https://status.flipt.com.br)**

## Como funciona

Esta página de status é gerada pelo [Upptime](https://upptime.js.org/) — open-source, hospedado no GitHub. Os health-checks rodam a cada 5 minutos via GitHub Actions e o histórico de uptime fica versionado neste repositório (pasta `history/`).

**Por que GitHub e não Vercel/Railway?**
A status page é o único lugar que **precisa funcionar quando tudo o resto cai**. Hospedar no mesmo provedor que monitora é tiro no pé. GitHub Pages tem infra completamente isolada do Vercel/Railway.

## Serviços monitorados

| Serviço | URL |
|---|---|
| Backend API (Railway) | https://api.flipt.com.br |
| Frontend (Vercel) | https://app.flipt.com.br |
| WhatsApp QR (Evolution) | https://evolution-api-production-ac01.up.railway.app |
| Meilisearch | https://meilisearch-production-d32f.up.railway.app |
| Telnyx (Voice) | https://api.telnyx.com |
| Disparo Pro Voice | https://gateway.disparopro.com.br |
| Disparo Pro SMS | https://apihttp.disparopro.com.br |

## Reportar um incidente

Abrir uma [issue](../../issues/new) no repositório com a label `incident`. O Upptime cria timeline automaticamente.
