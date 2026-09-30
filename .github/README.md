# abnt-setup-template

escreva trabalhos acadêmicos em markdown seguindo as normas da abnt, com geração automática de pdf via pandoc e github actions.

## / primeiros passos

1. clique em **use this template** no github e crie seu repositório.
2. clone o repositório e edite os arquivos `.md`.
3. crie uma tag de versão e envie:

```sh
git tag 0.1
git push --tags
```

em cerca de dois minutos o pdf formatado aparece na área de releases do repositório.

## / escrevendo

- cada arquivo `.md` numerado é uma parte do texto. os arquivos são unidos em ordem de nome, então `00-`, `01-`, `02-`... definem a ordem no pdf. adicione, renomeie ou remova arquivos à vontade.
- os arquivos de exemplo mostram títulos, citações, notas de rodapé, citações longas, listas, figuras e tabelas. substitua o conteúdo pelo seu.
- adicione `{-}` após um título para deixá-lo sem numeração, ex.: `# introdução {-}`.
- comentários html (`<!-- ... -->`) não aparecem no pdf.

## ~ configuração

o `_config.md` guarda título, autores, resumos, palavras-chave, margens, entrelinhas e recuo. todos os campos são opcionais, então apague os que não usar.

## ~ referências

adicione entradas ao `bibliografia.bib` e cite com `[@chave]`. a seção de referências é gerada no fim do documento e lista apenas as obras citadas. veja a [sintaxe de citação do pandoc](https://pandoc.org/MANUAL.html#citations) para outras formas.

## ~ imagens

coloque as imagens em `_imagens/` e adicione uma linha de fonte logo abaixo de cada figura ou tabela, como mostrado em `02-figuras-tabelas.md`.

## / rodando localmente

instale as dependências listadas em `.github/workflows/conversor.yml` e execute o comando do pandoc que está no mesmo arquivo.
