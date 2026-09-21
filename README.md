# desafio-colaborativo-git
## Perguntas Frequentes (FAQ)

<details>
  <summary>Como funciona o fluxo de aprovação de PRs?</summary>
  <p>Cada Pull Request precisa ser revisado e aprovado por pelo menos um integrante do grupo antes de ser mesclado na branch main.</p>
</details>

<details>
  <summary>Como proceder em caso de conflitos de merge?</summary>
  <p>Caso ocorra um conflito, o responsável pela branch deve atualizar sua branch com as alterações mais recentes da main, resolver as inconsistências localmente e realizar um novo push.</p>
</details>

<details>
  <summary>Quais são os horários de alinhamento do grupo?</summary>
  <p>Nossos alinhamentos síncronos acontecem às terças e quintas-feiras, às 14h, via Discord/Google Meet.</p>
</details>

## Guia de Estilo do Documento

Para manter consistência visual e estrutural entre as contribuições dos membros do grupo, sigam os padrões abaixo.

### Hierarquia de cabeçalhos

- `#` — reservado exclusivamente para o título principal do documento (usar apenas uma vez)
- `##` — usado para grandes seções (ex: Objetivo, Etapas, Critérios de Avaliação)
- `###` — usado para subtópicos dentro de uma seção

### Padrões de sintaxe

- Listas não ordenadas: sempre com `-` (não usar `*` ou `+`)
- Deixar uma linha em branco antes e depois de cada bloco (parágrafo, lista, bloco de código)
- Todo bloco de código deve indicar a linguagem (ex: \`\`\`bash, \`\`\`python), nunca deixar sem identificador

### Exemplos

**Como fazer:**
\`\`\`markdown
## Etapa 1: Preparação

Texto explicando a etapa.

- Item 1
- Item 2
\`\`\`

**O que evitar:**
\`\`\`markdown
### Etapa 1: Preparação
Texto colado sem espaçamento
* Item 1
* Item 2
\`\`\`
