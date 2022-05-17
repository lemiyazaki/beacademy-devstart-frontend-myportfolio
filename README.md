# Sprint 3: HTML, CSS e Javascript
## HTML
### Introdução
- HTML = Estrutura básica de uma página na internet
- Itens de HTML são considerados “elementos”
- Nome do arquivo: letras minúsculas, -, sem caracteres especiais
- Comentários: &lt;!-- comment --&gt;
- Elemento HTML = tag abertura + conteúdo + tag fechamento
- Imagem = elemento vazio (elemento com auto fechamento)
- VScode: ctrl + shift + P → HTML: Open Preview
- VScode: digitar ! → html document base
### Atributos:
- informações extras → ex.: atributos de imagem
- configurações
- booleanos → T/F → ex.: input
### Atributos Globais:
- class: classificar tags
- hidden: boolean
- title: título para o elemento → acessibilidade!
- id: identificador de elementos → pode aparecer apenas uma vez
- tabindex: permite navegação entre elementos com tab
- style: permite colocar CSS
### Aninhamento de tags:
- hierarquia → ex.: parágrafos (&lt;em&gt; e &lt;strong&gt; são filhos de &lt;p&gt;, que é filho de &lt;body&gt;, etc)
- fluxo de leitura → de cima para baixo
- posicionamento dos elementos
  - inline → elementos de linha → ex.: &lt;p&gt; (só há quebra de linha com o &lt;br/&gt;)
  - block → elementos com quebra de linha → ex.: &lt;h1&gt;
### Caracteres Reservados:
- alguns caracteres não conseguem ser lidos
- precisam ser utilizados com expressões regulares → &nbsp para espaço em &lt;p&gt;
- &lt; → &lt
- &gt; → &gt
### Semântica:
- significado às coisas
- dar nome e identificar sessões da página
- header → cabeçalho, block content
- nav → navegador, menus
- section → bloco de sessão
- article → cards, blogs
- aside → container, lateral
- footer → rodapé
### Títulos:
- formatação inicial parte do user agent → font-size
- h1, h2, h3, h4, h5, h6 → decrescente
- h1 → section hero → aparece uma vez por página → utilizar h2 para o restante
- b → bold, mas não possui semântica
- i → negrito, não possui semântica
### Listas:
- ol → lista ordenada
- ul → lista não ordenada
- VScode: li*5 → abre 5 x &lt;li&gt;&lt;li/&gt;
### Citações:
- blockquote
- cite → fonte bibliográfica → ajuda na semântica da página
- q → short inline quotation
