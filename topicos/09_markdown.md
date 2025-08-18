# 📄 O Que é Markdown?

Markdown é uma **linguagem de marcação leve** que permite formatar texto simples de forma fácil e legível. Ele é convertido para HTML (ou outros formatos) para visualização. Sua simplicidade e portabilidade o tornam ideal para diversas aplicações, especialmente em ambientes de desenvolvimento e análise.

### Conceitos Básicos e Sintaxe

Vamos explorar os elementos essenciais do Markdown:

#### 1. Cabeçalhos
Use `#` para criar cabeçalhos. Quanto mais `#`, menor o nível do cabeçalho.

```markdown
# Título Principal (H1)
## Subtítulo (H2)
### Seção (H3)
#### Subseção (H4)
```

#### 2. Parágrafos e Quebras de Linha
Basta digitar o texto normalmente. Para uma nova linha, pressione `Enter` duas vezes (criando um novo parágrafo) ou adicione dois espaços no final da linha seguido de `Enter` para uma quebra de linha simples.

```markdown
Este é um parágrafo.

Este é outro parágrafo.
```

#### 3. Ênfase (Negrito e Itálico)
* **Itálico:** Use um asterisco simples (`*texto*`) ou um sublinhado simples (`_texto_`).
* **Negrito:** Use dois asteriscos (`**texto**`) ou dois sublinhados (`__texto__`).
* **Negrito e Itálico:** Use três asteriscos (`***texto***`).

```markdown
*Texto em itálico* ou _Texto em itálico_
**Texto em negrito** ou __Texto em negrito__
***Texto em negrito e itálico***
```

#### 4. Listas
* **Listas Não Ordenadas:** Use asteriscos (`*`), hífens (`-`) ou sinais de adição (`+`).

    ```markdown
    * Item 1
    * Item 2
        * Subitem 2.1
        * Subitem 2.2
    ```

* **Listas Ordenadas:** Use números seguidos de um ponto.

    ```markdown
    1. Primeiro item
    2. Segundo item
    3. Terceiro item
    ```

#### 5. Links
Use `[texto do link](URL)`.

```markdown
[Visite o Google](https://www.google.com)
```

#### 6. Imagens
Use `![texto alternativo](URL da imagem)`.

```markdown
![Logo do Markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)
```

#### 7. Blocos de Código e Código Inline
* **Código Inline:** Use um acento grave simples (`` `código` ``).
* **Blocos de Código:** Use três acentos graves (```` ``` ````) antes e depois do bloco. Você pode especificar a linguagem para destaque de sintaxe.

    ```markdown
    Para um código inline, use `print("Hello, World!")`.

    ```python
    def fibonacci(n):
        a, b = 0, 1
        for _ in range(n):
            print(a)
            a, b = b, a + b
    ```
    ```

#### 8. Citações em Bloco
Use o sinal de maior que (`>`).

```markdown
> "A simplicidade é a sofisticação máxima."
> - Leonardo da Vinci
```

#### 9. Linhas Horizontais
Use três ou mais hífens (`---`), asteriscos (`***`) ou sublinhados (`___`).

```markdown
---
```

#### 10. Tabelas
Crie tabelas usando hífens para as colunas e barras verticais (`|`) para separar as células.

```markdown
| Coluna 1      | Coluna 2      | Coluna 3      |
|---------------|---------------|---------------|
| Linha 1, Cel 1| Linha 1, Cel 2| Linha 1, Cel 3|
| Linha 2, Cel 1| Linha 2, Cel 2| Linha 2, Cel 3|
```

### Ferramentas e Aplicações no Dia a Dia do Analista de Sistemas

* **Editores de Texto:** Muitos editores de código (VS Code, Sublime Text, Atom) têm suporte a Markdown com preview em tempo real.
* **Plataformas de Controle de Versão:** GitHub, GitLab, Bitbucket usam Markdown para READMEs, wikis e comentários em pull requests.
* **Sistemas de Documentação:** Ferramentas como o Sphinx, MkDocs e Docusaurus podem gerar documentação complexa a partir de arquivos Markdown.
* **Geradores de Relatórios:** Scripts podem converter Markdown para PDF, HTML ou outros formatos para relatórios formais.
* **Jupyter Notebooks:** Suportam Markdown para adicionar descrições, explicações e títulos em análises de dados.
* **Ferramentas de Diagramação:** Algumas ferramentas como o Mermaid e PlantUML permitem gerar diagramas (fluxogramas, diagramas de sequência) usando sintaxe Markdown ou sintaxes similares que podem ser embutidas em arquivos Markdown.

### Exercícios Práticos
1.  **Crie um README.md para um Projeto Fictício:** Imagine um projeto de software. Crie um arquivo `README.md` que inclua:
    * Um título principal com o nome do projeto.
    * Uma breve descrição.
    * Uma seção de "Requisitos" (lista não ordenada).
    * Uma seção de "Instalação" (bloco de código com comandos).
    * Um link para a documentação (fictícia).
    * Uma tabela simples com "Status" e "Responsável".
2.  **Escreva um Trecho de Documentação de Requisitos:** Crie um arquivo Markdown que detalhe um requisito de software, utilizando cabeçalhos, parágrafos, e talvez uma lista ordenada para os passos.

### Conclusão
Dominar o Markdown é uma habilidade valiosa para qualquer Analista de Sistemas. Ele simplifica a criação de documentação clara e padronizada, agiliza a comunicação da equipe e se integra perfeitamente com as ferramentas de desenvolvimento e controle de versão. Invista tempo para praticar e explorar suas capacidades!

---

### Perguntas e Discussão
* Quais outras ferramentas de documentação vocês já utilizaram e como o Markdown se compara a elas?
* Quais cenários específicos do dia a dia de um analista de sistemas vocês veem o Markdown sendo mais útil?



## Links Úteis 🔗

### Recursos Internos (Markdown)

* [Conceitos de Markdown](https://www.google.com/search?q=./markdown.md)


### Recursos Externos (Markdown)

* [Markdown Guide (Guia Completo)](https://www.markdownguide.org/)
* [Markdown Cheatsheet (Folha de Dicas Rápida)](https://www.markdownguide.org/cheat-sheet/)
* [Exemplo de Documentação Técnica no GitHub](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)

---

### [ricardotecpro.github.io](https://ricardotecpro.github.io/)
