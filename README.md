# Desafio Colaborativo 4

Repositório para praticar colaboração, controle de versão e revisão de documentos usando Git e GitHub.

## Objetivo

Manter um documento colaborativo organizado, consistente e fácil de revisar. Cada contribuição deve seguir o padrão de escrita definido neste guia.

## Como Participar

1. Consulte as issues e escolha uma tarefa disponível.
2. Crie uma branch para a sua alteração.
3. Edite o documento seguindo o guia de estilo.
4. Revise o conteúdo e teste os links adicionados.
5. Registre a alteração em um commit objetivo.
6. Abra um pull request para discussão e revisão.

### Comandos básicos

```bash
git clone https://github.com/Lettify/desafio-colaborativo-git.git
cd desafio-colaborativo-git
git switch -c nome-da-branch
git add README.md
git commit -m "docs: atualiza documentação"
git push -u origin nome-da-branch
```

## Guia de Estilo do Documento

### Hierarquia de cabeçalhos

- `#` deve ser usado uma única vez, exclusivamente no título principal.
- `##` deve identificar as grandes seções do documento.
- `###` deve identificar subtópicos dentro de uma seção.

### Padrões de sintaxe

- Use listas não ordenadas com `-`, sem misturar `*` ou `+`.
- Deixe uma linha em branco antes e depois de parágrafos, listas e blocos de código.
- Identifique a linguagem em todo bloco de código, como `bash`, `python` ou `markdown`.
- Use textos de link objetivos e descrições que expliquem a finalidade do destino.
- Prefira frases curtas e revise ortografia, pontuação e concordância.

### Exemplo recomendado

````markdown
## Etapa 1: Preparação

Leia as instruções antes de iniciar a edição.

- Confira a issue relacionada.
- Crie uma branch para a tarefa.
````

### Exemplo a evitar

````markdown
### Etapa 1: Preparação
Texto colado sem espaçamento
* Item 1
* Item 2
````

## Checklist de Revisão

- [ ] O título e os cabeçalhos seguem a hierarquia definida.
- [ ] As listas usam o marcador `-`.
- [ ] Existe uma linha em branco entre os blocos.
- [ ] Os blocos de código informam a linguagem.
- [ ] Os links têm descrições claras e estão funcionando.
- [ ] O texto foi revisado antes do pull request.

## Recursos & Ferramentas Úteis

### Referências de Markdown

| Recurso | Finalidade |
| --- | --- |
| [Markdown Guide](https://www.markdownguide.org/basic-syntax/) | Consulta rápida da sintaxe básica de Markdown. |
| [Sintaxe do GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github) | Consulta dos recursos de formatação compatíveis com o GitHub. |

### Visualizadores de Git

| Recurso | Finalidade |
| --- | --- |
| [Learn Git Branching](https://learngitbranching.js.org/) | Simulação interativa de branches, commits, merges e rebases. |
| [Visualizing Git](https://git-school.github.io/visualizing-git/) | Visualização do histórico e dos efeitos dos comandos Git. |

### Simuladores de Terminal

| Recurso | Finalidade |
| --- | --- |
| [JSLinux](https://bellard.org/jslinux/) | Experimentação com sistemas Linux e comandos diretamente no navegador. |
| [Webminal](https://www.webminal.org/) | Prática de comandos Linux em um terminal online. |

### Atalhos do Repositório

| Recurso | Finalidade |
| --- | --- |
| [Código do projeto](https://github.com/Lettify/desafio-colaborativo-git) | Acesso aos arquivos, branches e informações gerais do desafio. |
| [Issues](https://github.com/Lettify/desafio-colaborativo-git/issues) | Registro e acompanhamento de tarefas, dúvidas e problemas. |
| [Pull requests](https://github.com/Lettify/desafio-colaborativo-git/pulls) | Revisão e discussão das alterações antes da integração. |
| [Histórico de commits](https://github.com/Lettify/desafio-colaborativo-git/commits/main/) | Consulta das alterações realizadas na branch principal. |