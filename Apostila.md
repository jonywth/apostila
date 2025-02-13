# Apostila - Markdown

## Introdução

* O que é Markdown e por que utilizá-lo no Github?  

Markdown é uma linguagem de marcação criada para facilitar a escrita e a leitura de documentos de texto puro. Com uma sintaxe intuitiva e fácil de aprender, o Markdown permite adicionar formatação a um documento usando caracteres comuns, como asteriscos e sublinhados, em vez de usar uma interface de formatação como o Microsoft Word. E utiliza-ló em Github é bom pois os beneficios são: Simplicidade, Compatibilidade, Facilidade de Leitura, Interatividade e o seu Padrão amplamente utilizado. 
[fonte](https://dev.to/nugguet/o-que-e-markdown-e-como-usa-lo-4a0h)🔎


* Vantagens do Markdown para documentação e publicações.   

  
Simplicidade: A sintaxe do Markdown é intuitiva e fornece uma maneira natural de formatar texto sem comandos complexos.

Portabilidade: Como um formato de texto simples, os arquivos Markdown podem ser abertos e editados em qualquer editor de texto em várias plataformas.

Conversão: Documentos Markdown podem ser facilmente convertidos em HTML ou outros formatos, tornando os versáteis para conteúdo web.

Documentação: Ideal para escrever arquivos readme, documentação, artigos e notas devido às suas capacidades de formatação limpa.

Controle de Versão: Sendo texto simples, os arquivos Markdown funcionam bem com sistemas de controle de versão como o Git, rastreando mudanças de forma eficaz.
[fonte](https://www.markdowntoolbox.com/pt/blog/raz%C3%B5es-para-usar-markdown/)🔎

## Elementos Básicos do Markdown

* Cabeçalhos  
Para por cabeçalhos basta apenas utilizar a hastag, e pode se usar mais de uma, para tipos diferentes de titulo. 

# Exemplo 1
## Exemplo 2
### Exemplo 3
#### Exemplo 4
##### Exemplo 5


* Parágrafos e quebras de linha  
No Markdown, para criar parágrafos, basta escrever o texto normalmente e deixar uma linha em branco entre eles. Para quebras de linha, use dois espaços no final da linha e pressione Enter.

```
Exemplo de parágrafo:
```
Para criar parágrafos, você só precisa escrever o texto normalmente e deixar uma linha em branco entre as partes. Por exemplo:

**Este** é um parágrafo.

**Este** é outro parágrafo.

```
Exemplo de quebra de linha:
```
Quebras de linha: Se você quiser forçar uma quebra de linha dentro do mesmo parágrafo, adicione dois espaços no final da linha e depois pressione Enter. Por exemplo:  

Linha 1 com quebra no final.  
Linha 2.

 * Linhas horizontais  
  No Markdown, para criar uma linha horizontal, você pode usar três ou mais hífens (---), asteriscos (***) ou underscores (___), seguidos de uma linha em branco.
  ```
  Exemplo:
```
---
***
___


* Comentários invisíveis  
 Para adicionar um comentário invisível (que não será mostrado quando o texto for renderizado), você usa as tags de comentário HTML. Qualquer texto colocado entre <!-- e --> será tratado como um comentário e não aparecerá na versão final do documento. Isso é útil para deixar notas ou informações para quem está editando, sem que elas sejam visíveis para quem ler o conteúdo.

## Formatação de Texto

* Ênfase (negrito, itálico, riscado)  
```
No Markdown, para dar ênfase ao texto, você pode usar as seguintes opções:
```
Negrito: Coloque o texto entre dois asteriscos ou dois underscores:

**texto em negrito** ou __texto em negrito__

Itálico: Coloque o texto entre um asterisco ou um underscore:

*texto em itálico* ou _texto em itálico_

Riscado: Coloque o texto entre dois til (~):

~~texto riscado~~

Essas são as formas para adicionar negrito, itálico e riscado ao texto no Markdown.

* Citações e blocos de citação  
No Markdown, você pode usar citações e blocos de citação da seguinte maneira:

Citações Simples:  
Para citar algo diretamente no texto, você usa o sinal de maior que (>) seguido do texto da citação.
```
Exemplo:
```
(>) Isto é uma citação.

Resultado

> Isto é uma citação.  

Bloco de Citação:  
Você pode criar um bloco de citação utilizando o > na frente de várias linhas, para citar um trecho maior.
```
Exemplo:
```
(>) Este é um exemplo de  
(>) bloco de citação.  
(>) Ele pode se estender por várias linhas.

Resultado:

> Este é um exemplo de  
> bloco de citação.  
> Ele pode se estender por várias linhas.

* Exibição de comandos no texto  
No Markdown, para exibir comandos ou trechos de código, você usa:

Código em linha:  
Para inserir um comando ou código em linha (sem formatação de bloco), coloque o texto entre crases simples (`).
```
Exemplo:
```
Use o comando npm install para instalar pacotes.

Bloco de Código:  
Para criar um bloco de código, utilize três crases (```) antes e depois do trecho de código. Você pode também especificar a linguagem após as três crases para destaque de sintaxe.
 ```
 Exemplo:
 ```
 const x = 10;  
console.log(x);  
Esse é o jeito simples de exibir comandos e código em Markdown!

## Trabalhando com Listas
* Listas ordenadas e não ordenadas  
**Não Ordenadas**  
Para criar uma lista não ordenada, use asterisco (*), sinal de mais (+) ou sinal de menos (-) seguidos de um espaço.
```
Exemplo:
```

* Item 1
* Item 2
* Item 3

**Ordenadas:**  
Para criar uma lista ordenada, basta usar números seguidos de ponto e espaço.
```
Exemplo:
```
1. Primeiro item
2. Segundo item
3. Terceiro item


* Listas de tarefas  
No Markdown, para criar listas de tarefas (checkboxes), você usa o formato - [ ] para uma tarefa não concluída e - [x] para uma tarefa concluída. 
```
Exemplo:
```
- [ ] Tarefa 1
- [x] Tarefa 2 (concluída)
- [ ] Tarefa 3  
Isso cria uma lista de tarefas interativa (em ambientes que suportam Markdown com interação, como o GitHub).

* Listas com numeração não sequencial  
No Markdown, para criar listas com numeração não sequencial, você pode simplesmente usar números seguidos de ponto, mas não precisa seguir uma ordem exata — o Markdown irá numerar automaticamente. 
```
Exemplo:
```
1990\.  
1994\.

## Links e Referências
* Criando links simples e com referência  
No Markdown, você pode criar links simples e links com referência da seguinte maneira:

Link Simples:
Use o formato "["Texto do Link"]" "("URL")" para criar um link direto.
```
Exemplo:
```
[Google](https://www.google.com)

Link com Referência:  
Crie o link usando uma referência de marcador, que pode ser definida em outro lugar no documento. A sintaxe é [Texto do Link][nome] no link e [nome]: URL para a referência.

"["Google"]" "["1"]"

[1]: https://www.google.com

* Criando âncoras para navegação no documento  
  No Markdown, para criar âncoras para navegação dentro do próprio documento, você usa links para cabeçalhos. Isso permite que você crie links que direcionam para diferentes seções ou tópicos do mesmo documento.

**Passo a passo:**  
Crie um cabeçalho com um título (usando #).
Use um link para o cabeçalho com a hashtag # seguida do nome do cabeçalho em letras minúsculas e com hífens no lugar dos espaços.

## Seção 1
[Ir para Seção 1](#seção-1)

## Imagens e Mídias  

**Imagens Locais:**

Para imagens armazenadas no seu computador ou projeto, use o formato "!["texto alternativo"]"(caminho/para/imagem).
```
Exemplo:
```
"![Minha Imagem]"(imagens/exemplo.jpg)  
![Minha Imagem](imagens/exemplo.jpg)


**Imagens Externas:**  
Para imagens hospedadas na web, basta colocar a URL da imagem entre parênteses.

Exemplo:

"![Logo do Markdown]"(https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

Resultado:

![Logo do Markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

* Criando imagens clicáveis (com links)  
  No Markdown, para criar imagens clicáveis (com links), você combina a sintaxe de link e imagem. O formato é:

[![Texto alternativo da imagem](URL da imagem)](URL do link)
[![Logo do Markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)](https://www.markdownguide.org)


## Trabalhando com Código

* Código Inline:

Para incluir código em linha (dentro do texto), use crases simples (`).
```
Exemplo:
```
Use o comando `npm install` para instalar pacotes.

Código em Blocos:  
Para blocos de código (com várias linhas), use três crases (```) antes e depois do código. Você também pode especificar a linguagem para destaque de sintaxe.

* Uso de destaque para diferentes linguagens

Para destacar o código de diferentes linguagens de programação, você pode especificar a linguagem logo após as três crases (```). Isso ativa o destaque de sintaxe para a linguagem escolhida.
```
Exemplo de Código com Destaque:
```

```javascript
const x = 10;
console.log(x);

Resultado (com destaque de sintaxe para JavaScript):
```javascript
const x = 10;
console.log(x);

```
Exemplos para outras linguagens:
```
```python
print("Olá, mundo!")

Resultado (com destaque para Python):
```python
print("Olá, mundo!")

````

## Elementos Avançados

Para criar tabelas e definir alinhamentos, você utiliza uma sintaxe simples com pipe (|) e hífen (-).

Tabelas:  
A estrutura básica de uma tabela é:

| Coluna 1 | Coluna 2 | Coluna 3 |
|----------|----------|----------|
| Dado 1   | Dado 2   | Dado 3   |
| Dado 4   | Dado 5   | Dado 6   |

Alinhamentos:  
Você pode definir o alinhamento das colunas usando dois pontos (:) nas linhas de separação.

Alinhar à esquerda: :---  
Alinhar ao centro: :---:  
Alinhar à direita: ---:

| Alinhado à Esquerda | Alinhado ao Centro | Alinhado à Direita |
|:-------------------|:------------------:|------------------:|
| Dado 1             | Dado 2            | Dado 3            |
| Dado 4             | Dado 5            | Dado 6            |

* Notas de Rodapé

Para criar notas de rodapé, você usa uma sintaxe simples com colchetes e um identificador. A sintaxe básica é:

Adicionar a nota de rodapé no texto com um identificador entre colchetes.
Definir a nota de rodapé no final do documento, associando o identificador ao conteúdo da nota.

Este é um exemplo de nota de rodapé[^1].

[^1]: Esta é a nota de rodapé explicativa.

* Emojis e badges 
  
Emojis:  
Os emojis podem ser inseridos utilizando os códigos Unicode, ou os atalhos de emoji, que são reconhecidos em plataformas como GitHub.

Exemplo: 

:D    (Rosto sorridente)  
:thumbsup: (Polegar para cima)  
:heart: (Coração) 

Badges:  
As badges (selos ou ícones) geralmente são usadas para mostrar status, como versões de projetos ou integração com serviços. Eles são imagens que você adiciona via link.

Exemplo:

![badge](https://img.shields.io/badge/Status-Active-green)

*  Integração com HTML 
  
Você pode integrar HTML para personalizar elementos que não são facilmente alcançados com a sintaxe padrão. Isso permite maior controle sobre a formatação, como usar estilos, classes e atributos.

Exemplo de Uso de HTML em Markdown: 
1. Inserir Títulos com Formatação HTML:
   
   <h1 style="color: blue;">Título Personalizado</h1>

2. Adicionar Parágrafos com Estilo:  

<p style="font-size: 18px;">Este é um parágrafo com estilo personalizado.</p>

3. Incluir Imagens com Atributos HTML:   

<img src="imagem.jpg" alt="Imagem Personalizada" width="300" />


Observações:
HTML funciona em qualquer lugar no Markdown (dentro de textos, listas, etc.), mas nem todos os visualizadores de Markdown podem renderizar HTML de forma igual.
A integração com HTML permite usar recursos como div, span, style, entre outros, para maior flexibilidade.  

## Publicação no GitHub

* Criando um repositório 

Passos para Criar um Repositório:  
Crie uma conta no GitHub, se ainda não tiver.  
Crie um novo repositório:  
Vá para a página inicial do GitHub.  
Clique no botão "New" ou "Novo" (geralmente no canto superior direito).  
Preencha o nome do repositório, descrição e escolha se deseja que seja público ou privado.  
Marque a opção "Initialize this repository with a README" para adicionar um arquivo README.md (onde você pode escrever em Markdown).  
Adicionar arquivos Markdown:  
No repositório recém-criado, clique em "Add file" e selecione "Create new file".  
Crie um arquivo com a extensão .md (por exemplo, documentacao.md).  
Escreva o conteúdo em Markdown.  
Commite o arquivo: Depois de adicionar o conteúdo Markdown, clique em "Commit new file" para salvar. 

* Enviando o arquivo Markdown  

Passos para Enviar um Arquivo Markdown para o GitHub:

Crie um repositório (caso ainda não tenha feito isso) no GitHub.
  Clone o repositório (usando Git) para sua máquina local:

Crie ou edite seu arquivo Markdown (por exemplo, meuarquivo.md) no seu computador.

Adicione o arquivo ao repositório local:

Faça o commit do arquivo:  
Envie o arquivo para o repositório no GitHub:

Alternativa (via interface web do GitHub):  
Vá para o seu repositório no GitHub.  
Clique em "Add file" e depois em "Upload files".  
Arraste e solte seu arquivo .md ou clique em "Choose your files" para selecionar.  
Após o upload, clique em "Commit changes" para salvar no repositório.  


* Visualizando o documento diretamente no GitHub

Para visualizar um documento Markdown diretamente no GitHub, basta seguir estes passos:

Crie ou faça upload de um arquivo .md (por exemplo, README.md ou documentacao.md) no seu repositório do GitHub.

Acesse o repositório no GitHub.

Clique no arquivo .md que você quer visualizar. O GitHub automaticamente renderiza o conteúdo Markdown e exibe o documento formatado na interface.

Exemplo:

Se você tiver um arquivo README.md, ao abrir o repositório, o GitHub exibirá automaticamente o conteúdo deste arquivo, interpretando o Markdown.  

O conteúdo de títulos, listas, links e imagens será mostrado de forma formatada.  

**Resultado:**
O GitHub renderiza o arquivo, permitindo que você veja o conteúdo de forma clara e organizada, com todo o poder do Markdown (como negrito, listas, cabeçalhos, etc.).

Isso é tudo que você precisa para visualizar seu documento Markdown diretamente no GitHub!