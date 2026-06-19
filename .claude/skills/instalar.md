# Skill: /instalar

> Roda UMA vez. Conversa de setup que transforma o molde RexOS no sistema
> operacional de UMA empresa específica.

## Princípio: é conversa, não formulário

NUNCA despeje uma lista de perguntas. Converse. Uma coisa de cada vez, tom leve.
Deixe a pessoa falar livre, extraia o máximo do que ela disser, e só pergunte
o que faltar. Se ela já respondeu três coisas numa frase, não repergunte.

## Abertura

Comece simples e aberto. Algo como:

"Boa, sistema clonado. Antes de configurar tudo, me conta sobre o negócio —
o que é, o que faz, pra quem. Pode falar do seu jeito, sem se preocupar com ordem."

Deixe a pessoa responder. Escute de verdade.

## Como conduzir

Depois da resposta aberta, vá preenchendo as lacunas com perguntas soltas e
naturais, UMA de cada vez. Exemplos de como puxar (não é roteiro fixo):

- "Entendi. E qual é o carro-chefe? O que mais traz dinheiro pra vocês?"
- "Quem toca o negócio com você?"
- "Show. Agora a parte visual: que cores são a cara da marca?"
- "Tem alguma regra de conteúdo que vocês seguem? Tipo, evita emoji, não põe preço?"
- "Me fala do momento atual — tem cliente ou projeto em andamento agora?"

Faça UMA pergunta, espere a resposta, faça a próxima. Como uma conversa de café.

## O que você precisa ter coletado ao final

Não precisa perguntar tudo isso explicitamente — extraia da conversa. Só
pergunte o que não apareceu naturalmente:

- A empresa: nome, o que faz, cidade/atuação, carro-chefe, serviços, time, cliente ideal
- Identidade: cores, fontes (se souberem), formato de conteúdo, social proof, tom de voz, regras
- Estado atual: clientes/projetos ativos e pendências
- Nicho: é agência de marketing local / trabalha com Google Meu Negócio?

## Nicho (pergunte leve, perto do fim)

"Última coisa: o negócio mexe com marketing local, Google Meu Negócio, essas coisas?"
- Se SIM → instale o kit de agência (montar-gmn, responder-avaliacoes, prospectar, seo)
  em .claude/skills/.
- Se NÃO → segue sem o kit.

## Ao terminar

1. Preencha _memoria/nucleo-de-contexto.md, _memoria/estado-atual.md e
   identidade/identidade-visual.md com tudo que a conversa revelou.
2. Substitua todos os [PLACEHOLDERS]. Onde faltou info, deixe uma nota curta
   do tipo "(a definir)" em vez de inventar.
3. Mostre um resumo rápido do que entendeu e pergunte: "É isso mesmo? Quer
   ajustar algo antes de eu salvar?"
4. Depois do ok, rode /salvar pra versionar o estado inicial.
5. Avise: "Pronto. Roda /abrir quando quiser começar."

Depois disso, nunca mais rode /instalar nesta instância.
