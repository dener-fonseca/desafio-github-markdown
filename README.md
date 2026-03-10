# Desafio Github Markdown

O desafio proposto pela DIO consiste em escrever um texto no formato Markdown utilizando suas principais tags e sintaxes.

Este documento demonstrará algumas das principais **tags e sintaxes do Markdown utilizadas no GitHub**.

---

## Introdução

Markdown é uma linguagem de marcação leve (Lightweight Markup Language) usada para formatar textos usando símbolos simples como `#`, `*`, `|` entre outros.

O markdown utiliza a extensão de arquivo `.md` que é bastante utilizada em documentação de projetos, arquivos README, wikis e guias técnicos.

Ela foi criada em 2004 pelo programador John Gruber com colaboração do também programador Aaron Swartz.

---

## 1. Títulos

No Markdown usamos o símbolo `#` para criar títulos que possuem 6 níveis.

Exemplos:

# Título nível 1
## Título nível 2
### Título nível 3
#### Título nível 4
##### Título nível 5
###### Título nível 6

Como é a sintaxe:

```
# Título nível 1
## Título nível 2
### Título nível 3
#### Título nível 4
##### Título nível 5
###### Título nível 6
```

Quanto mais `#`, menor será o título.

---

## 2. Formatação de Texto

Podemos destacar palavras no texto com o uso das seguintes tags:

### Negrito

Usamos `**` entre palavras.

Exemplo:

**Negrito**

Como é a sintaxe:

`**Negrito**`

### Itálico

Usamos `*` entre palavras.

Exemplo:

*Itálico*

Como é a sintaxe:

`*Itálico*`

### Negrito e Itálico

Usamos `***` entre palavras.

Exemplo:

***Negrito e Itálico***

Como é a sintaxe:

`***Negrito e Itálico***`

---

## 3. Listas

Podemos criar listas no texto com o uso das seguintes tags:

### Lista não ordenada

Usamos `-` ou `*`.

- Item 1
- Item 2
- Item 3
  - Subitem

Como é a sintaxe:

```
- Item 1
- Item 2
- Item 3
  - Subitem
```

O espaço na frente do traço a torna sub-lista.

### Lista ordenada

Usamos números seguidos de um ponto.

1. Primeiro item
2. Segundo item
3. Terceiro item

Como é a sintaxe:

```
1. Primeiro item
2. Segundo item
3. Terceiro item
```

---

## 4. Links Externos

Para criar links usamos a seguinte sintaxe palavra entre `[]` e link entre `()`.

Exemplo:

[Visitar GitHub](https://github.com)

Como é a sintaxe:

`[Visitar GitHub](https://github.com)`

---

## 5. Imagens

A sintaxe é parecida com a de links, mas começando com `!` na frente da palavra entre `[]` e link entre `()`.

Exemplos:

![Logo do GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

Como é a sintaxe:

`![Logo do GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)`

---

## 6. Código

Códigos devem ser colocados entre crases para ter sua formatação anulada em textos em formato markdown.

### Código em linha

Usamos crase entre o trecho de código:

Exemplo:

`print("Olá mundo")`

Como é a sintaxe:

```
`print("Olá mundo")`
```

### Bloco de código

Usamos três crases entre o trecho de código, porém em linhas separadas:

```
print("Hello World")
print("Olá mundo")
```

Como é a sintaxe:

```
(```)
print("Hello World")
print("Olá mundo")
(```)
```

---

## 7. Citações

Para criar citações usamos `>` na frente do trecho de texto.

>Markdown é muito utilizado para documentação em projetos de programação.

Como é a sintaxe:

`>Markdown é muito utilizado para documentação em projetos de programação.`

## 8. Tabelas

As tabelas em Markdown são criadas usando barras verticais `|` para separar colunas e traços `-` para definir o cabeçalho.

Exemplo:

| Nome | Linguagem | Uso |
|------|-----------|-----|
| Ana | Python | Dados |
| João | Java | Backend |
| Maria | JS | Frontend |

Como é a sintaxe:

```
| Nome | Linguagem | Uso |
|------|-----------|-----|
| Ana | Python | Dados |
| João | Java | Backend |
| Maria | JS | Frontend |
```

## 9. Linha horizontal

Usamos três traços `---` para criar uma linha horizontal.

Exemplo:

Texto antes da separação.

---

Texto depois da separação.

Como é a sintaxe:

```
Texto antes da separação.

---

Texto depois da separação.
```

---

## 10. Emojis no GitHub

O GitHub suporta emojis usando `:`.

Exemplos:

:rocket:
:computer:
:book:

Como é a sintaxe:

```
:rocket:
:computer:
:book:
```

---

## 11. Checklist

Usamos `[ ]` com o texto para criar questões não marcadas e `[x]` com o texto para criar questões marcadas.

Exemplo:

- [x] Tarefa concluída
- [ ] Tarefa pendente
- [ ] Outra tarefa

Como é a sintaxe:

```
- [x] Tarefa concluída
- [ ] Tarefa pendente
- [ ] Outra tarefa
```

---

## 12. Blocos de Alerta

No GitHub podemos criar blocos de destaque para chamar atenção para informações importantes.

Exemplos:

> [!NOTE]
> Este é um bloco de nota usado para informações importantes.

Como é a sintaxe:

```
> [!NOTE]
> Este é um bloco de nota usado para informações importantes.
```

> [!TIP]
> Este bloco mostra uma dica útil para o leitor.

Como é a sintaxe:

```
> [!TIP]
> Este bloco mostra uma dica útil para o leitor.
```

> [!IMPORTANT]
> Este bloco destaca algo que o usuário precisa saber.

Como é a sintaxe:

```
> [!IMPORTANT]
> Este bloco destaca algo que o usuário precisa saber.
```

> [!WARNING]
> Este bloco alerta sobre possíveis problemas.

Como é a sintaxe:

```
> [!WARNING]
> Este bloco alerta sobre possíveis problemas.
```

> [!CAUTION]
> Este bloco indica algo que deve ser feito com cuidado.

Como é a sintaxe:

```
> [!CAUTION]
> Este bloco indica algo que deve ser feito com cuidado.
```

---

## 13. Tabelas mais Complexas

Também podemos colocar formatação dentro das tabelas, como código, negrito e links.

Exemplo:

| Tecnologia | Tipo | Exemplo de Código |
|-----------|------|-------------------|
| Python | Backend | `print("Olá Mundo")` |
| JavaScript | Web | `console.log("Olá Mundo")` |
| SQL | Banco de dados | `SELECT * FROM usuarios;` |

Como é a sintaxe:

```
| Tecnologia | Tipo | Exemplo de Código |
|-----------|------|-------------------|
| Python | Backend | `print("Olá Mundo")` |
| JavaScript | Web | `console.log("Olá Mundo")` |
| SQL | Banco de dados | `SELECT * FROM usuarios;` |
```

---

## 14. Âncoras (Links Internos)

Podemos criar links para partes do próprio documento.

O GitHub automaticamente transforma títulos em âncoras navegáveis.

Exemplo:

## Sumário

- [Introdução](#introdução)
- [Tabelas](#tabelas)
- [Conclusão](#conclusão)

Como é a sintaxe:

```
- [Introdução](#introdução)
- [Tabelas](#tabelas)
- [Conclusão](#conclusão)
```

### Explicação

Quando criamos um título como `## Introdução`, automaticamente ele vira `#introducão` e pode ser utilizado no sumário como link `[Introdução](#introdução)`.

Letras maiúsculas são transformadas em minúsculas como em `## Introdução` que vira `#introducão`.

Espaços viram hífen como em `## Banco de Dados` que vira `#banco-de-dados`.
.

Caracteres especiais são removidos como em `## Introdução!` que vira `#introdução`.

---

## 15. Sumário Automático

Podemos criar um índice para navegar pelo documento.

Isso facilita a navegação em documentos grandes.

Exemplo:

# Sumário

- [Introdução](#introdução)
- [Listas](#listas)
- [Tabelas](#tabelas)
- [Conclusão](#conclusão)

Como é a sintaxe:

```
- [Introdução](#introdução)
- [Listas](#listas)
- [Tabelas](#tabelas)
- [Conclusão](#conclusão)
```

---

16. Badges (Indicadores de Projeto)

Badges são pequenos indicadores visuais usados em READMEs.

Exemplos:

![GitHub](https://img.shields.io/badge/GitHub-Repository-black)

Como é a sintaxe:

`![GitHub](https://img.shields.io/badge/GitHub-Repository-black)`

![License](https://img.shields.io/badge/license-MIT-blue)

Como é a sintaxe:

`![License](https://img.shields.io/badge/license-MIT-blue)`

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

Como é a sintaxe:

`![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)`

---

## 17. Recursos de Escape e Formatação Especial

Além das formatações comuns, o Markdown também possui recursos que permitem **anular formatações**, **quebrar linhas**, **ocultar conteúdo** e **mostrar código literal**.  

Esses recursos são muito úteis principalmente quando estamos **explicando a própria sintaxe do Markdown em documentação ou exercícios**.

### Escapar caracteres especiais

Para evitar que um símbolo seja interpretado como formatação, podemos usar a **barra invertida `\`** antes do caractere.

Exemplo de uso:

\# Isto não será interpretado como título  

\* Isto não será interpretado como itálico  

Como é a sintaxe:

```
\# Isto não será interpretado como título  

\* Isto não será interpretado como itálico  
```

Assim o Markdown mostra os símbolos normalmente sem aplicar a formatação.

### Mostrar código com crase

A **crase (`)** permite mostrar código ou sintaxe sem aplicar formatação.

Exemplo de uso:

`# Isso seria um título sem não tivesse crase.`

Como é a sintaxe:

```
`# Isso seria um título sem não tivesse crase.`
```

Esse recurso é muito usado para explicar **comandos, funções ou sintaxe de programação**.

### Blocos de código

Quando precisamos mostrar **várias linhas de código**, usamos **três crases ```** para criar um bloco de código.

Exemplo de uso:

```
# Título
## Subtítulo
```

Como é a sintaxe:

```
(```)
`# Isso seria um título sem não tivesse crase.`
(```)
```

Nesse caso o Markdown exibirá o conteúdo exatamente como foi escrito.

### Quebra de linha

No Markdown existem três formas comuns de quebrar linha.

A primeira forma é deixar **uma linha em branco entre parágrafos**.

Exemplo de uso:

Primeira linha

Segunda linha

Como fica a sintaxe:

```
Primeira linha
(Linha em branco)
Segunda linha
```

A segunda forma é adicionar **dois espaços no final da linha** antes de pressionar Enter.

Exemplo de uso:

Primeira linha  
Segunda linha  

Como fica a sintaxe:

```
Primeira linha(2 espaços)
Segunda linha(2 espaços)
```

A terceira forma é adicionando a tag HTML <br> no final da primeira linha.

Exemplo de uso:

Primeira linha

Segunda linha

Como fica a sintaxe:

```
Primeira linha<br>
Segunda linha
```

### Ocultar partes do texto

Podemos ocultar conteúdo usando **comentários HTML**.

Exemplo de uso:

<!-- Este texto não aparecerá no documento renderizado -->

Como é a sintaxe:

`<!-- Este texto não aparecerá no documento renderizado -->`

Esse recurso é útil para colocar **anotações no arquivo sem que apareçam para quem está lendo**.


### Texto riscado

Podemos marcar texto removido usando `~~`.

Exemplo de uso:

~~Este texto foi removido~~

Como fica a sintaxe:

`~~Este texto foi removido~~`

Esse recurso indica **informações desatualizadas ou corrigidas**.


### Conteúdo oculto expansível

Também é possível esconder partes do texto usando a tag HTML `<details>`.

Exemplo de uso da sintaxe:

```
\<details>  
\<summary>Clique para expandir\</summary>

Conteúdo oculto que aparece quando o usuário clicar.

\</details>
```

Esse recurso é muito usado em **documentações grandes e arquivos README**.

---

## 18. Observações

O Markdown também permite utilizar **HTML dentro do documento**.

Isso acontece porque muitos renderizadores de Markdown, incluindo o GitHub, suportam **tags HTML misturadas com Markdown**.

Essa funcionalidade é útil quando precisamos de **formatações que não existem no Markdown padrão**.

Exemplos:

<p>Este é um parágrafo usando HTML dentro do Markdown.</p>

<b>Texto em negrito usando HTML</b>

<i>Texto em itálico usando HTML</i>

Como fica a sintaxe:

```
<p>Este é um parágrafo usando HTML dentro do Markdown.</p>

<b>Texto em negrito usando HTML</b>

<i>Texto em itálico usando HTML</i>
```

Também podemos usar HTML para criar elementos mais complexos como estilização, caso o documento permita.

### Observação importante

Apesar de suportar HTML, é recomendado usar **Markdown sempre que possível**, pois ele mantém o documento **mais simples e fácil de ler**.

O HTML deve ser usado apenas quando for necessário adicionar **formatações ou estruturas que o Markdown não possui**.

---

## Conclusão

O Markdown é uma linguagem bastante simples usada para formatação de textos em plataformas como **GitHub**, **GitLab** e **documentação técnica**. Ele facilita a leitura e organização de conteúdos em projetos de software.
