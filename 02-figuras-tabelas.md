# Figuras e tabelas

<!--
  Coloque as imagens na pasta _imagens/ e referencie pelo caminho relativo.
  O texto entre colchetes vira a legenda ("Figura 1 – ...").
  A linha "Fonte: ..." logo abaixo é obrigatória pela ABNT e é posicionada
  automaticamente sob a figura/tabela.
-->

## Figuras

A Figura 1 apresenta um exemplo de imagem inserida no texto.

![Arquitetura geral do sistema](_imagens/arquitetura.png)

Fonte: Autores.

Para controlar o tamanho da imagem, adicione a largura entre chaves:

![Diagrama de casos de uso](_imagens/UML.png){width=70%}

Fonte: Adaptado de @bezerra2015.

## Tabelas

A Tabela 1 apresenta um exemplo de tabela. A legenda é escrita em uma linha iniciada por `Table:` antes da tabela, e o alinhamento das colunas é definido pelos `:` na linha de separação.

Table: Exemplo de tabela

| Código | Categoria  | Descrição                                   |
|:------:|:----------:|:--------------------------------------------|
| RF01   | Funcional  | O sistema deve permitir o cadastro de usuários. |
| RF02   | Funcional  | O sistema deve permitir a busca de itens.   |
| RNF01  | Segurança  | O sistema deve estar em conformidade com a LGPD. |

Fonte: Autores.

## Listas de definição

Úteis para glossários e descrições de termos:

**MVP**
: *Minimum Viable Product* — versão mínima do produto para validação.

**UML**
: *Unified Modeling Language* — linguagem padrão de modelagem de sistemas.
