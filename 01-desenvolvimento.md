# Desenvolvimento

<!--
  Seções numeradas: "#" = seção primária (1), "##" = secundária (1.1),
  "###" = terciária (1.1.1), e assim por diante.
-->

Esta seção mostra a formatação básica do texto em Markdown.

## Formatação de texto

Use *itálico* para termos estrangeiros, como *software* e *design*, e **negrito** para destaques. Termos técnicos ou nomes de arquivos podem ser escritos como `código`.

Notas de rodapé são criadas assim.[^nota]

[^nota]: Este é o texto da nota de rodapé. Ele pode ficar em qualquer lugar do arquivo.

## Citações

As citações seguem o padrão do Pandoc e são formatadas automaticamente em ABNT:

- Citação indireta: [@bezerra2015].
- Citação com página: [@sommerville2018, p. 42].
- Várias obras: [@sommerville2018; @bezerra2015].
- Autor no texto: segundo @bezerra2015, a UML é uma linguagem de modelagem.
- Apenas o ano: Sommerville [-@sommerville2018] afirma que...

Citações diretas com mais de três linhas devem ficar em bloco, usando `>`:

> Citação direta longa, com mais de três linhas, que será exibida com recuo de 4 cm, fonte menor e espaçamento simples, conforme a NBR 10520. Continue o texto da citação normalmente até o final do trecho citado, indicando a fonte ao final [@sommerville2018, p. 10].

## Listas

Lista com marcadores:

- Primeiro item;
- Segundo item;
  - Subitem;
- Último item.

Lista numerada:

1. Primeira etapa;
2. Segunda etapa;
3. Terceira etapa.

### Seção terciária

Use quantos níveis de título forem necessários.
