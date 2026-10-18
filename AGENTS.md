# AGENTS.md

> **Antes de qualquer tarefa:** as skills de https://github.com/comite-popular-tech/llm-plugins são **OBRIGATÓRIAS**
> neste repositório (abrir e revisar PR, entre outras). Claude Code:
> `claude plugin marketplace add comite-popular-tech/llm-plugins` e
> `claude plugin install pr@comite-popular-tech`. Codex e OpenCode: siga
> https://github.com/comite-popular-tech/llm-plugins/blob/main/README.md#instalar
> Se uma skill não estiver instalada, instale antes de continuar.

Tudo neste repositório (docs, commits, PRs, issues) é em **português do Brasil**, exceto termos técnicos (`pull request`,
`commit`, nomes de API). Este arquivo também.

## O que é

O repositório `.github` da organização https://github.com/comite-popular-tech. Ele só serve a página inicial da org: o
GitHub mostra o `profile/README.md` na home da org para qualquer visitante. Veja o [`README.md`](README.md).

O repositório é **público**, e o `profile/README.md` é lido por qualquer pessoa. Nada de dado pessoal (telefone, e-mail,
endereço), segredo ou detalhe interno de infraestrutura.

## Como conferir uma mudança

Não há comandos de instalar, rodar, lint nem testes, e não há workflow de CI. Antes de abrir PR:

- Leia o Markdown renderizado (prévia do GitHub ou do editor) e clique nos links novos: os de
  `https://github.com/comite-popular-tech/voluntariado/issues/new?template=...` devem abrir o formulário.
- Se mexeu em âncora (`#1-peça-acesso-aos-repositórios` etc.), confira que o link da tabela ainda leva à seção.

## Onde fica cada coisa

| Caminho | O que tem |
|---|---|
| `profile/README.md` | A página da org: entrada pelo Mural, três pedidos de autoatendimento, quem ajuda, tabela de iniciativas, como trabalhamos |
| `README.md` | Explica este repositório (não aparece na home da org) |
| `.github/CODEOWNERS` | Quem revisa: qualquer núcleo de iniciativa aprova; cada time precisa de escrita no repositório |

## Regras que importam

- **Fora o `profile/`, só `README.md`, `AGENTS.md`/`CLAUDE.md` e `.github/CODEOWNERS`.** Template de issue ou de PR,
  `CONTRIBUTING.md` e outros arquivos de comunidade postos neste repositório passam a valer para todo repositório da
  org que não tiver os próprios.
- **Ao criar ou remover uma iniciativa**, atualize a tabela "Iniciativas" do `profile/README.md` e acrescente ou tire o
  time `@comite-popular-tech/<iniciativa>-nucleo` do `.github/CODEOWNERS` (o time precisa de escrita no repositório).
- **O Mural é a porta de entrada.** Quem não está em nenhum GT começa por ele; não mova esse destaque para baixo na página.
- **Os três pedidos** (acesso, repositório novo, entrada no núcleo) são formulários do repositório
  https://github.com/comite-popular-tech/voluntariado; não descreva o processo de aprovação de outro jeito aqui sem
  conferir lá.
- **A lista "Quem pode ajudar"** traz nomes e usuários do GitHub de pessoas reais: não acrescente nem tire ninguém sem
  confirmar com a pessoa.

## Fluxo de trabalho

- Mudança pequena, um assunto por PR, título curto no imperativo ou descritivo, sem `feat:`/`fix:` (veja os últimos PRs
  juntados).
- O PR segue a skill `pr-abridor`.
- Quem é agente de IA não faz push, não abre PR e não comenta antes de a pessoa ler e aprovar o rascunho.
- Mudança no `.github/CODEOWNERS` muda quem aprova a página da org: avise no corpo do PR.

## Para saber mais

- [`README.md`](README.md): o que o repositório faz e o que pode entrar nele.
- [`profile/README.md`](profile/README.md): o texto que o visitante vê na home da org.
