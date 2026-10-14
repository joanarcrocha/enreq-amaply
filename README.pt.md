# FAIR-AMAP: Especificação de Requisitos

[🇬🇧 English](README.md) | 🇵🇹 Português

Trabalho prático n.º 1 da unidade curricular de Engenharia de Requisitos (ENGREQ), Mestrado em Engenharia Informática, ISEP, 2026/2027.

**Data limite de entrega: 15 de novembro de 2026 (Moodle).**

## Contexto

A FAIR Software Solutions é uma startup que desenvolve soluções de software para facilitar a distribuição e venda de produtos alimentares, no contexto da Agenda 2030 para o Desenvolvimento Sustentável da ONU (17 Objetivos de Desenvolvimento Sustentável, https://ods.pt/ods/).

A empresa identificou uma oportunidade de negócio no setor das AMAP/CSA e procura uma equipa que especifique os requisitos funcionais e não funcionais da solução, cobrindo todos os seus processos.

- **AMAP**: Associação para a Manutenção da Agricultura de Proximidade.
- **CSA**: Community Supported Agriculture.

Uma AMAP/CSA é formada por um grupo de consumidores (co-produtores) que apoia ativamente e diretamente um ou mais agricultores e produtores, garantindo a distribuição da sua produção.

## Objetivo

Produzir uma Especificação de Requisitos de Software (SRS) completa, incluindo:

- descrição geral do sistema;
- funcionalidades;
- interfaces externas;
- requisitos não funcionais;
- prioridades;
- estimativa, em horas, do desenvolvimento de cada funcionalidade;
- descrição do processo: método, técnicas aplicadas e respetivas evidências, contexto e tempo dedicado por analista e por tarefa.

O enunciado completo está em [docs/assignment](docs/assignment/engreq_tp1_2026_27_v2_EN.pdf).

## Estrutura do repositório

```
.
├── README.md / README.pt.md
├── docs/
│   ├── assignment/    Enunciado do trabalho
│   ├── elicitation/   Notas das sessões e síntese dos requisitos recolhidos
│   ├── process/       Planeamento, registo de sessões e acompanhamento de tarefas
│   └── srs/           Documento SRS (versão em construção e versão final)
└── artefacts/         Modelos, diagramas, protótipos e outros artefactos de apoio
```

| Pasta | Conteúdo | Ficheiros iniciais |
|---|---|---|
| `docs/elicitation` | Tudo o que vem dos stakeholders e da pesquisa documental | [session-notes.pt.md](docs/elicitation/session-notes.pt.md), [open-questions.pt.md](docs/elicitation/open-questions.pt.md) |
| `docs/process` | Evidência do método seguido, exigida pelo enunciado | [planning.pt.md](docs/process/planning.pt.md), [session-log.pt.md](docs/process/session-log.pt.md) |
| `docs/srs` | Especificação final | por criar |
| `artefacts` | Diagramas, modelos de processos, protótipos | por criar |

## Política de língua

Todo o conteúdo e documentação do repositório é mantido em inglês e português. Cada documento existe em dois ficheiros com o mesmo nome: `nome.en.md` e `nome.pt.md`. Qualquer alteração a um deve ser refletida no outro. O README é a exceção: `README.md` é inglês e `README.pt.md` é português.

## Abordagem

O trabalho segue a metodologia de levantamento de requisitos lecionada na unidade curricular, combinando várias técnicas:

- sessões com stakeholders reais (aulas T) e sessões simuladas com os docentes (aulas PL);
- análise documental e pesquisa de fontes relevantes;
- registo contínuo do progresso neste repositório (planeamento, reuniões, tarefas, artefactos).

Lema orientador do levantamento: **Pessoas, Documentos, Processos**.

## Stakeholders identificados

- Direção da FAIR Software Solutions
- Co-produtores/consumidores
- Distribuidores
- Produtores/agricultores
- Coordenação de voluntários
- Engenharia de sistemas, segurança e requisitos não funcionais
- Coordenador da AMAP

## Equipa

| Nome | Número | Papel |
|---|---|---|
| _por preencher_ | | |

## Convenções

- Uma entrada por sessão de levantamento em `docs/process/session-log`, com data, duração, participantes e técnica usada.
- Commits curtos e descritivos, indicando a área (por exemplo, `elicitation: notes from session 2`).
- Estado do trabalho e responsáveis registados em `docs/process/planning`.
