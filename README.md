# Desafio Github Markdown

O desafio proposto pela DIO consiste em escrever um texto no formato Markdown .md utilizando suas principais tags e sintaxes.

---

## Introdução

Este documento demonstrará algumas das principais **tags e sintaxes do Markdown utilizadas no GitHub**.

---

## 1. Títulos (Headings)

No Markdown usamos o símbolo `#` para criar títulos que possuem 6 níveis.

# Título nível 1
## Título nível 2
### Título nível 3
#### Título nível 4
##### Título nível 5
###### Título nível 6

Quanto mais `#`, menor será o título.

---

## 2. Texto em Negrito e Itálico

Podemos destacar palavras no texto com o uso das seguintes tags:

- **Negrito** usando `**texto**`
- *Itálico* usando `*texto*`
- ***Negrito e itálico*** usando `***texto***`

Exemplo:

Este texto tem **negrito**, *itálico* e ***negrito com itálico***.

---

## 3. Listas

### Lista não ordenada

Usamos `-` ou `*`.

- Item 1
- Item 2
- Item 3
  - Subitem

O espaço na frente do traço a torna sub-lista.

### Lista ordenada

Usamos números seguidos de um ponto.

1. Primeiro item
2. Segundo item
3. Terceiro item

---

## 4. Links Externos

Para criar links usamos a seguinte sintaxe Palavra entre `[]` e link entre `()`.

Exemplo:

[Visitar GitHub](https://github.com)

---

## 5. Imagens

A sintaxe é parecida com a de links, mas começando com `!` na frente da palavra entre `[]` e link entre `()`.

Exemplo:

![Logo do GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

---

## 6. Código

### Código em linha

Usamos crase entre o trecho de código:

Exemplo:

`print("Olá mundo")`

### Bloco de código

Usamos três crases entre o trecho de código:

```python
print("Olá mundo")
```

---

## 7. Citações

Para criar citações usamos `>`.

>Markdown é muito utilizado para documentação em projetos de programação.

## 8. Tabelas

As tabelas em Markdown são criadas usando barras verticais `|` para separar colunas e traços `-` para definir o cabeçalho.

Exemplo:

| Nome | Linguagem | Uso |
|------|-----------|-----|
| Ana | Python | Dados |
| João | Java | Backend |
| Maria | JS | Frontend |

## 9. Linha horizontal

Usamos três traços `---`.

Exemplo:

Texto antes da separação.

---

Texto depois da separação.

---

## 10. Emojis no GitHub

O GitHub suporta emojis usando `:`.

Exemplo:

:rocket:
:computer:
:book:

---

## 11. Checklist

Usamos `[ ]` com o texto para criar questões não marcadas e `[x]` com o texto para criar questões marcadas.

Exemplo:

- [x] Tarefa concluída
- [ ] Tarefa pendente
- [ ] Outra tarefa

---

## 12. Blocos de Alerta

No GitHub podemos criar blocos de destaque para chamar atenção para informações importantes.

Exemplo:

> [!NOTE]
> Este é um bloco de nota usado para informações importantes.

> [!TIP]
> Este bloco mostra uma dica útil para o leitor.

> [!IMPORTANT]
> Este bloco destaca algo que o usuário precisa saber.

> [!WARNING]
> Este bloco alerta sobre possíveis problemas.

> [!CAUTION]
> Este bloco indica algo que deve ser feito com cuidado.

---

## 13. Tabelas mais Complexas

Também podemos colocar formatação dentro das tabelas, como código, negrito e links.

Exemplo:

| Tecnologia | Tipo | Exemplo de Código |
|-----------|------|-------------------|
| Python | Backend | `print("Olá Mundo")` |
| JavaScript | Web | `console.log("Olá Mundo")` |
| SQL | Banco de dados | `SELECT * FROM usuarios;` |

---

## 14. Âncoras (Links Internos)

Podemos criar links para partes do próprio documento.

O GitHub automaticamente transforma títulos em âncoras navegáveis.

Exemplo:

## Sumário

- [Introdução](#introdução)
- [Tabelas](#tabelas)
- [Conclusão](#conclusão)

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

---

16. Badges (Indicadores de Projeto)

Badges são pequenos indicadores visuais usados em READMEs.

Exemplo:

![GitHub](https://img.shields.io/badge/GitHub-Repository-black)

![License](https://img.shields.io/badge/license-MIT-blue)

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

---

17. ## Diagramas com Mermaid

O GitHub permite criar **diagramas diretamente em arquivos Markdown** utilizando a ferramenta chamada **Mermaid**.  

Ela é muito útil para representar **fluxos de sistemas, processos, algoritmos e arquiteturas de software** dentro da documentação.

### Exemplo de Fluxograma de Sistema

```mermaid
graph TD
    A[Usuário faz login] --> B[Sistema valida os dados]
    B --> C{Login válido?}
    C -->|Sim| D[Usuário acessa o sistema]
    C -->|Não| E[Sistema exibe mensagem de erro]
```

### Explicação do Diagrama

Neste exemplo foi criado um **fluxograma simples de autenticação de usuário**.

- `graph TD` define que o diagrama será um **fluxo de cima para baixo (Top Down)**.
- `A --> B` representa uma **ligação entre duas etapas do processo**.
- `{Login válido?}` representa um **ponto de decisão no fluxo**.
- `|Sim|` e `|Não|` representam os **possíveis resultados da decisão**.

### Utilização em Projetos

Diagramas Mermaid são muito usados em projetos para:

- Documentar **fluxos de funcionamento do sistema**
- Representar **arquitetura de software**
- Explicar **processos de algoritmos**
- Criar **documentação técnica mais visual**

---

## Conclusão

O Markdown é uma linguagem bastante simples usada para formatação de textos em plataformas como **GitHub**, **GitLab** e **documentação técnica**. Ele facilita a leitura e organização de conteúdos em projetos de software.
