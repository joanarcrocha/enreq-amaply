# Síntese da Análise de Concorrência: Software para AMAP/CSA

## Nota metodológica

Esta síntese, e a análise de concorrência que lhe deu origem, baseiam-se principalmente no que cada site e material público divulga sobre a própria solução. Não houve acesso direto à maioria das plataformas (sem conta de teste, sem demonstração, sem utilização real). Por isso:

- Toda a informação reflete o que cada fornecedor escolhe comunicar publicamente, não uma verificação independente
- Uma funcionalidade pode existir e não estar documentada no site, e uma funcionalidade anunciada pode não corresponder exatamente ao que é entregue na prática
- Números de clientes, de adoção e de poupança são valores comunicados pelo próprio fornecedor, não auditados
- Para algumas soluções (nomeadamente a Amappli e a PROVE) a informação pública disponível é escassa, e isso está assinalado onde relevante

Soluções analisadas (15): Farmigo, LocalLine, Cagette.net, AmapJ, OpenOlitor, Open Food Network, Harvie, Barn2Door, PROVE, CSAware, GrownBy, Clementine, Local Food Marketplace, Eat from Farms, Amappli.

---

## 1. Tipos de concorrente

As soluções dividem-se em grupos de natureza diferente, segundo o que cada site comunica sobre si próprio. Para a AmapJ, a OpenOlitor, a Open Food Network, o GrownBy, a PROVE, a Local Food Marketplace, a Eat from Farms e a Clementine, o site afirma diretamente a sua natureza (empresa comercial, ONG, cooperativa, etc.). Para a Farmigo, a LocalLine, a Harvie, o Barn2Door, o CSAware e a Cagette.net, os respetivos sites não o afirmam de forma explícita; a classificação como SaaS comercial é uma inferência feita a partir do modelo de preços apresentado e da ausência de qualquer menção a estatuto de ONG, cooperativa ou open source.

| Tipo | Soluções | Base |
|---|---|---|
| SaaS comercial (afirmado no site) | Local Food Marketplace, Eat from Farms, Clementine | Afirmado pelo site |
| SaaS comercial (inferido) | Farmigo, LocalLine, Harvie, Barn2Door, CSAware, Cagette.net | Inferência |
| Open source / sem fins lucrativos | AmapJ, OpenOlitor, Open Food Network | Afirmado pelo site |
| Cooperativa de agricultores | GrownBy | Afirmado pelo site |
| Rede com apoio institucional (não é essencialmente um produto de software) | PROVE | Afirmado pelo site |
| Sem informação suficiente para classificar | Amappli | Ausência de dados públicos |

Segundo os respetivos sites, a AmapJ e a OpenOlitor competem principalmente por serem gratuitas ou de baixo custo, e as soluções SaaS competem por profundidade de funcionalidades e apoio ao cliente. A PROVE não é comparável diretamente como produto de software, mas é relevante como referência do contexto português.

---

## 2. Funcionalidades comuns

Funcionalidades que os próprios sites anunciam na generalidade das soluções analisadas:

- Self-service do membro: pausar, trocar ou saltar entregas, atualizar dados de pagamento, sem contacto direto com o produtor
- Pagamento recorrente automático por cartão
- Listas de embalagem ou picking geradas automaticamente por ponto de recolha ou rota
- Exportação de dados em CSV e relatórios de retenção ou churn de membros

Como são funcionalidades anunciadas por praticamente todos os concorrentes, devem ser lidas como requisitos mínimos de mercado, não como diferenciadores, mas sem confirmação de como funcionam de facto em uso real.

---

## 3. Eixos de diferenciação

### Modelo de cabaz

| Modelo | Soluções |
|---|---|
| Fixo, definido pelo produtor | Barn2Door ("Farmer's Choice") |
| Fixo e personalizável, em paralelo | Farmigo |
| Personalizável semana a semana | LocalLine, Harvie, CSAware |
| Personalizável, ainda em fase beta segundo o site | GrownBy |
| Por pontos, com limite por pacote | Eat from Farms |
| Mercado de compra livre, sem cabaz fixo | Cagette.net |

Os sites da AmapJ, da OpenOlitor, da Clementine, do Open Food Network, da Local Food Marketplace e da Amappli não especificam o modelo de cabaz com detalhe suficiente, por isso estas soluções não constam nesta tabela.

### Multi-produtor (hub)

Segundo os respetivos sites, suportam vários produtores no mesmo sistema: LocalLine, Open Food Network, Local Food Marketplace, GrownBy, Eat from Farms.
Parecem mais centradas num produtor único: Clementine, Barn2Door (o site da Barn2Door não confirma nem exclui explicitamente o suporte a multi-produtor).

### Inclusão social no pagamento

Apenas os sites da GrownBy e da Local Food Marketplace anunciam integração com programas de benefícios sociais (SNAP/EBT, via parceiro Forage). Nenhum dos sites das soluções europeias analisadas menciona equivalente, o que pode significar que não existe ou apenas que não é um ponto de comunicação relevante nesses mercados.

### Logística avançada

Otimização de rotas por integração externa (Routific, OptimoRoute) anunciada apenas nos sites da LocalLine, da CSAware e da Local Food Marketplace.

### Apoio humano incluído

Os sites da Barn2Door e da Local Food Marketplace destacam-se por anunciarem gestores de conta dedicados e onboarding assistido. As restantes soluções, pelo que os sites comunicam, assumem um modelo self-service puro.

---

## 4. Modelos de custo

Os valores abaixo são os publicados nos respetivos sites à data da análise. Preços podem ter planos adicionais, condições ou descontos não documentados publicamente.

| Modelo | Exemplos |
|---|---|
| Percentagem sobre receita, com mínimo mensal | Farmigo (2%, mín. 150$), CSAware (2%, mín. 100$) |
| Percentagem sobre receita, com teto anual | Cagette.net (2-6%, teto ~468€/ano), Open Food Network (escalonado por volume) |
| Mensalidade fixa por escalão | LocalLine (109-399$), GrownBy (0-95$), Local Food Marketplace (129-249$ versão produtor individual, 149-349$ versão hub/co-op/mercado), Clementine (29$, plano único) |
| Taxa de transação sobre vendas | Harvie (7% + processamento de cartão), Barn2Door (sem taxa sobre vendas, só processamento) |
| Gratuito, com custo de hosting ou financiamento cooperativo | AmapJ (hosting ~40€/ano, valor recomendado pelo próprio site), OpenOlitor (financiamento cooperativo, ~1€/subscrição/mês, exemplo dado pela organização fundadora) |

De um modo geral, e segundo os preços publicados, as soluções europeias sem fins lucrativos (AmapJ, OpenOlitor) têm custos muito inferiores às soluções comerciais norte-americanas, que tendem a cobrar mensalidades fixas elevadas ou percentagens sobre a receita.

---

## 5. Espaço para uma solução de contexto nacional

Os pontos abaixo são conclusões tiradas por ausência de menção nos sites consultados (nenhuma das 15 fichas refere meios de pagamento portugueses, língua portuguesa ou enquadramento fiscal nacional). Ausência de menção não é prova de ausência da funcionalidade, é apenas o que resulta do que está publicamente comunicado.

- Nenhum dos sites analisados menciona meios de pagamento portugueses (MB WAY, Multibanco, débito direto SEPA)
- A AmapJ e a OpenOlitor são gratuitas e open source, mas os respetivos sites não indicam disponibilidade em português nem adaptação ao enquadramento fiscal nacional
- A informação pública sobre a PROVE sugere que, em Portugal, a gestão de circuitos curtos documentada ainda depende de processo humano e manual, sem um produto de software nacional equivalente descrito
- A ausência de equivalente a programas de inclusão social (como o SNAP/EBT) nos sites das soluções europeias pode ou não ser relevante no contexto português; esta análise não permite concluir isso diretamente