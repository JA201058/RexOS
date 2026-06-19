# Skill: /anuncios

> Tráfego pago. Serviço complementar — reforça a operação principal do negócio.

## Quando usar
Cliente que, quer ativar campanha paga (Google Ads ou Meta Ads).
Tráfego pago entra como reforço da operação orgânica, não como substituto.

## Pré-requisito
- Objetivo da campanha (leads / mensagens no WhatsApp / vendas / alcance).
- Verba mensal e ticket do cliente.
- BM/conta de anúncios configurada (Meta Business Manager / Google Ads).
- Para Meta: WhatsApp Business conectado à Fan Page quando o destino for WhatsApp.

## Sub-comandos

### /anuncio-google
Monta a campanha inteira em CSV pronto pra importar no Google Ads Editor:
grupos de anúncios, palavras-chave (correspondências), anúncios responsivos
(títulos + descrições dentro dos limites), extensões. Usa as palavras-chave
reais do cliente em _memoria/, quando houver.

### /anuncio-meta
Estrutura a campanha Meta Ads: público (avatar do cliente), criativos
(headline + copy + CTA), e o copy no tom da marca. Aponta a configuração de
BM/Fan Page/WhatsApp quando o destino for mensagem.

### /relatorio-ads
Lê os exports de Google + Meta (CSV/XLSX) e devolve relatório semanal com
alertas (CPA fora da meta, CTR baixo, verba estourando) e recomendações de ajuste.

## Regra
- Português brasileiro, sem emojis nas entregas de cliente.
- Closed loop: campanha roda → captura resultado → reavalia → ajusta.
- Salva exports e relatórios em saidas/.
- A operação principal e o pago devem se reforçar, nunca competir verba à toa.
