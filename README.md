# RexOS

> O sistema operacional da Agência Rex dentro do Claude Code.

Você acaba de instalar o RexOS. Em alguns minutos, a Rex vai ter uma memória própria,
a identidade visual aplicada em tudo que o sistema gerar, e as skills de GMN, conteúdo,
propostas e prospecção prontas pra rodar com você dirigindo.

Bora voar.

---

## Ligando o sistema

Dois caminhos. Escolhe o que combina contigo.

### Pelo Claude (mais rápido)

Abre o Claude Code em qualquer pasta e cola:

```
Clona o https://github.com/JA201058/RexOS.git, entra nela e roda /instalar.
```

Ele clona, entra na pasta nova e dispara a entrevista de setup. Você só responde.

### Pelo terminal (mais previsível)

```
git clone https://github.com/JA201058/RexOS.git
cd RexOS
code .
```

Na janela do VS Code que abrir: terminal integrado → `claude` → `/instalar`.

---

Quando o `/instalar` terminar, a memória da Rex já está montada. Daí é só usar.

O `/instalar` roda uma vez só. Te entrevista sobre o estado atual da agência,
preenche a memória e configura o sistema. Depois disso, é só operar.

---

## O sistema

**Núcleo** — o jeito de operar o dia a dia. `/abrir` carrega o contexto antes de cada
sessão · `/salvar` faz commit + push no GitHub · `/atualizar` varre o projeto e atualiza
a memória · `/novo-projeto` cria pasta isolada pra cada cliente · `/mapear-rotina`
descobre o que você repete e transforma em skill personalizada.

**GMN e SEO local** — o carro-chefe da Rex. `/montar-gmn` roda o build completo em 6
etapas sequenciais (descrição, posts, produtos, serviços, citações, respostas), com
aprovação a cada etapa · `/responder-avaliacoes` escreve respostas humanas e variadas
pras reviews do Google.

**Conteúdo** — `/carrossel` cria carrossel 1080×1350 com a identidade da Rex (navy e
dourado) · vitrine visual pronta pro Instagram.

**Comercial** — `/proposta` monta a proposta comercial em HTML pronta pra deploy no
Netlify · `/prospectar` extrai e qualifica leads locais (Google Maps) e devolve CRM
formatado.

**Anúncios pagos** — serviço complementar ao orgânico, não o central. `/anuncio-google`
monta a campanha inteira em CSV pronto pra importar no Google Ads Editor · `/anuncio-meta`
estrutura a campanha Meta · `/relatorio-ads` lê os exports de Google + Meta e devolve
relatório semanal com alertas e recomendações.

---

## A tese

IA não é uma ferramenta que a Rex usa. É o sistema operacional em que a Rex roda.

A diferença não é velocidade. É capacidade nova. Cada processo crítico que hoje roda em
open loop (decide → executa → repete cego) vira closed loop dentro do RexOS (decide →
executa → captura → reavalia → ajusta sozinho).

O sistema não substitui você. Vira parte da agência.

---

## Como o RexOS pensa

`_memoria/` é o cérebro. Tudo que importa da Rex mora aqui — quem é a agência, qual
cliente está em foco, o que ficou pendente. O Claude lê isso antes de cada resposta.
Quanto melhor a memória, melhor o sistema.

`identidade/` é o rosto. Cores, fontes, logo, padrão visual. Todo carrossel, slide e
peça que o sistema gera respeita isso.

`marketing/`, `saidas/` e `scripts/` são o resultado. O sistema produz, versiona no
GitHub, fica tudo seu.

---

## Quando precisar

Agência Rex — Marketing e Performance · São Luís, MA
