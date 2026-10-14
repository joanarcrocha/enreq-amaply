# FAIR-AMAP: Especificação de Requisitos

Trabalho prático n.º 1 da unidade curricular de Engenharia de Requisitos (ENGREQ), Mestrado em Engenharia Informática, ISEP, edição 2026/2027.

## Contexto

A FAIR Software Solutions é uma startup que desenvolve soluções de software para facilitar a distribuição e venda de produtos alimentares, no contexto da Agenda 2030 para o Desenvolvimento Sustentável da ONU (17 Objetivos de Desenvolvimento Sustentável, https://ods.pt/ods/).

A empresa identificou uma oportunidade de negócio no setor das AMAP/CSA e procura uma equipa que especifique os requisitos funcionais e não funcionais da solução, cobrindo todos os seus processos.

- **AMAP**: Associação para a Manutenção da Agricultura de Proximidade.
- **CSA**: Community Supported Agriculture.

Uma AMAP/CSA é formada por um grupo de consumidores (co-produtores) que apoia ativamente e diretamente um ou mais agricultores e produtores, garantindo a distribuição da sua produção.

## Objetivo do trabalho

Produzir uma Especificação de Requisitos de Software (SRS) completa, incluindo:

- descrição geral do sistema;
- funcionalidades;
- interfaces externas;
- requisitos não funcionais;
- prioridades;
- estimativa, em horas, do desenvolvimento de cada funcionalidade;
- descrição do processo: método, técnicas aplicadas e respetivas evidências, contexto e tempo dedicado por analista e por tarefa.

O enunciado completo está em [docs/enunciado](docs/enunciado/engreq_tp1_2026_27_v2_EN.pdf). A entrega é feita no Moodle.

## Estrutura do repositório

```
.
├── README.md
├── docs/
│   ├── enunciado/     Enunciado do trabalho
│   ├── elicitacao/    Notas das sessões e síntese dos requisitos recolhidos
│   ├── processo/      Planeamento, atas das reuniões e registo de tarefas
│   └── srs/           Documento SRS (versão em construção e versão final)
└── artefactos/        Modelos, diagramas, protótipos e outros artefactos de apoio
```

| Pasta | Conteúdo | Ficheiros iniciais |
|---|---|---|
| `docs/elicitacao` | Tudo o que vem dos stakeholders e da pesquisa documental | [notas-sessoes.md](docs/elicitacao/notas-sessoes.md), [questoes-em-aberto.md](docs/elicitacao/questoes-em-aberto.md) |
| `docs/processo` | Evidência do método seguido, exigida pelo enunciado | [planeamento.md](docs/processo/planeamento.md), [registo-sessoes.md](docs/processo/registo-sessoes.md) |
| `docs/srs` | Especificação final | por criar |
| `artefactos` | Diagramas, modelos de processos, protótipos | por criar |

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

- Um ficheiro por sessão de levantamento, registado em `docs/processo/registo-sessoes.md` com data, duração, participantes e técnica usada.
- Commits curtos e descritivos, indicando a área (por exemplo, `elicitacao: notas da sessão 2`).
- Estado do trabalho e responsáveis registados em `docs/processo/planeamento.md`.
