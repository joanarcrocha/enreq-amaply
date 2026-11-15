# Análise Documental: AMAP Porto

**Projeto:** ENGREQ, plataforma FAIR-AMAP
**Data:** 21/10/2026

## Documentos analisados

| # | Documento | Tipo | Data |
|---|---|---|---|
| 1 | Guia para a entrada de novos consumidores, AMAP Porto | Documento interno | Sem data |
| 2 | Termos e Condições, AMAP UPTEC Baixa (v01) | Documento legal | Sem data |
| 3 | Formulário de encomendas Jul a Dez 2026 (Google Forms) | Formulário em uso | 2.º semestre 2026 |
| 4 | Reportagem do Público "Quando o Porto se enche de frutas e legumes que ainda cheiram a terra" | Artigo jornalístico | 28/09/2023 |

O formulário é a fonte mais atual e mostra como as coisas funcionam hoje. O guia e os termos não têm data e, em alguns pontos, já não batem certo com o formulário. A reportagem é útil para contexto, mas tem 3 anos.

---

## 1. Guia para novos co-produtores

**O que diz**

- A AMAP junta co-produtores (consumidores) e produtores numa relação direta, sem intermediários.
- Funciona por ciclos trimestrais. Até uma semana antes de cada ciclo, os co-produtores recebem por email um formulário com os produtos, preços e periodicidade de cada produtor.
- Depois de submeter, o co-produtor recebe uma cópia por email que "nunca deve ser apagada", para não se esquecer do que encomendou e quanto tem de pagar.
- Quem é novo, ou entra a meio do ciclo, pode pedir uma entrega experimental.
- O pagamento é feito diretamente a cada produtor, antes do início do ciclo (transferência, MBWay ou numerário). É preciso enviar o comprovativo ao produtor ou pôr o nome na descrição da transferência.
- Todos os membros pagam uma quota anual de 10 €. Metade vai para a REGENERAR (rede nacional).
- A distribuição é às terças, das 17h30 às 19h30, na UPTEC Baixa. Quem não puder ir avisa os produtores ou manda alguém de confiança.
- A organização é feita por grupos de trabalho de voluntários, que vão rodando: Equipa Dinamizadora, Acolhimento, Comunicação, Distribuição, Gestão de encomendas e pagamentos, Assembleia e Comissão de festas.
- A comunicação é feita por email e WhatsApp. Os produtores só podem usar os contactos para assuntos da AMAP.

**O que significa para o sistema**

- O co-produtor precisa de um sítio onde consulte a sua encomenda e o que deve a cada produtor. Hoje depende de guardar um email.
- Cada produtor tem de poder definir os seus produtos, preços, periodicidade e forma de pagamento.
- Os pagamentos vão diretamente para os produtores. A plataforma deve ajudar a acompanhar quem pagou, não receber o dinheiro.
- Não há um "administrador" fixo. As permissões devem estar ligadas a papéis que mudam de pessoa ao longo do tempo.
- A gestão das quotas anuais também é uma necessidade (hoje é feita à mão pela Equipa Dinamizadora).
- O grupo de Gestão de encomendas imprime mapas de distribuição. O sistema pode gerá-los automaticamente.

**Dúvidas**

- Fala em distribuição semanal, mas o formulário e a reportagem dizem quinzenal. Qual está certo?
- A quota é chamada obrigatória num ponto e "voluntária" noutro. Quem não paga pode subscrever?
- Como funciona a entrega experimental (preço, quantas, como se pede)?
- O documento não fala num "coordenador". Quem faz esse papel na prática?

---

## 2. Termos e Condições

**O que diz**

- Os responsáveis pelos dados pessoais são os produtores (cada um individualmente).
- Os dados recolhidos são nome, email, telefone e NIF.
- O co-produtor pode pedir acesso, cópia, correção ou eliminação dos seus dados, através do email da AMAP.
- Para subscrever é preciso ter 18 anos ou mais e aceitar os termos ("Li e aceito os termos e condições...").
- O registo pode ser recusado ("não constitui um direito dos utilizadores").
- A subscrição é trimestral. A inscrição só fica confirmada depois de submeter a encomenda e pagar.
- Os cabazes que não forem levantados até às 19h30 ficam no exterior, identificados pelo nome.
- Os produtores podem alterar os termos sem aviso prévio.

**O que significa para o sistema**

- O sistema tem de registar que cada pessoa aceitou os termos, e qual a versão que aceitou.
- Tem de permitir exportar, corrigir e apagar os dados de um co-produtor (RGPD).
- Cada produtor só deve ver os dados das pessoas que lhe compraram.
- Os pedidos de adesão devem poder ser aprovados ou recusados.

**Dúvidas**

- A lista de produtores dos termos não coincide com a do formulário atual. Os termos estão desatualizados?
- O NIF é pedido nos termos, mas não aparece no formulário. Para que é usado? Os produtores passam fatura?
- Durante quanto tempo são guardados os dados? O documento não diz.
- Se o pagamento de alguns produtos é feito por entrega ou depois da pesagem, quando é que a inscrição fica "confirmada"?

---

## 3. Formulário de encomendas (Jul a Dez 2026)

> Só foi possível ler a página 1 de 2.

**O que diz**

- O ciclo é **semestral** (julho a dezembro). O prazo terminou a 4 de julho. Depois disso, é preciso pedir por email.
- Há 13 entregas quinzenais à terça, de 7 de julho a 22 de dezembro.
- Há 4 produtores: Biogoods, Trigo do Umbigo, Cogumelos de Argoncilhe e Quinta da Serrinha.
- Os preços têm formatos diferentes: por mês (cabazes), por unidade (ovos), por kg (frango, mirtilos) e por embalagem (mel, pão).
- As periodicidades também variam: quinzenal, mensal, trimestral, entrega única (feijão) e produtos sazonais (mirtilos só em julho e agosto).
- Os pagamentos variam por produtor: mensal no início do mês, por entrega (cogumelos) ou depois da pesagem (frango).
- Alguns produtos só são confirmados perto da entrega (cogumelos, alguns pães).
- Um produtor avisa que não vai estar em duas datas.
- As quantidades e os pedidos especiais são escritos em campos de "Observações", em texto livre.
- Só o email é obrigatório na página 1.

**O que significa para o sistema**

- A duração do ciclo tem de ser configurável (já houve ciclos trimestrais e agora é semestral).
- Não existe um modelo único de produto ou de pagamento. Cada produtor tem regras próprias e o sistema tem de as suportar.
- Produtos de peso variável (frango) só têm preço final depois da pesagem.
- As quantidades devem ser campos próprios e não texto livre. Hoje alguém tem de ler as observações e interpretar à mão.
- O produtor deve poder indicar faltas, ausências e disponibilidade por data de entrega, e avisar os co-produtores.

**Dúvidas**

- O cabaz é pago por mês, mas as entregas são quinzenais. Em setembro há 3 entregas. Quem paga 32 €/mês recebe 2 ou 3 cabazes?
- O ciclo passou a semestral de vez? Porquê?
- O que acontece se alguém quiser sair ou alterar a encomenda a meio do ciclo?
- O que está na página 2 do formulário?

---

## 4. Reportagem do Público (2023)

**O que diz**

- A AMAP Porto existe desde outubro de 2016.
- Tem cerca de 30 co-produtores (34 na altura), e cerca de 93 pessoas alimentam-se a partir dela.
- A distribuição é quinzenal e o ciclo é trimestral, alinhado com as estações do ano.
- O pagamento pode ser feito no início do trimestre ou em parcelas.
- O risco é partilhado: "As pessoas compreendem quando, porventura, não há um certo produto, ou vem menos ou mais do que o esperado".
- A organização é horizontal, sem hierarquias e sem intermediários.
- Os produtores também vendem fora da AMAP (mercados locais).
- Em 2023 os produtores eram outros: Obra d'Horta, Quinta do Pinheiral, Biogoods, Masseira, Cogumelos do Migaas e Quinta da Serrinha.

**O que significa para o sistema**

- A escala é pequena. O importante não é o desempenho, é ser simples, barato e fácil de usar por voluntários.
- A plataforma não deve parecer um intermediário (sem comissões, sem "loja online").
- Os produtores mudam ao longo do tempo. Tem de ser fácil adicionar e retirar produtores.
- Quando falta um produto, não há reembolso automático. O sistema deve informar, não compensar.

**Dúvidas**

- Quando falta um produto, há alguma compensação ou fica mesmo assim?
- A plataforma deve servir só a AMAP Porto ou também outras AMAP da rede?

---

## 5. Requisitos identificados

Lista inicial, a validar com a AMAP. Entre parênteses está o documento de origem.

**Co-produtores e membros**

1. O sistema deve permitir pedir adesão à AMAP, com aprovação por um membro responsável. (Termos)
2. O sistema deve registar a aceitação dos termos e a versão aceite. (Termos)
3. O sistema deve permitir atribuir papéis aos membros por um período (ex.: grupo de Distribuição neste ciclo). (Guia)
4. O sistema deve registar o pagamento da quota anual de cada membro. (Guia)

**Ciclos e produtos**

5. O sistema deve permitir criar ciclos com duração configurável e um calendário de entregas. (Guia, Formulário)
6. O sistema deve permitir que cada produtor publique os seus produtos, com preço, unidade e periodicidade. (Guia, Formulário)
7. O sistema deve suportar preços por mês, por unidade, por kg e por peso variável. (Formulário)
8. O sistema deve permitir que o produtor indique faltas de produtos e datas em que não estará presente. (Formulário)

**Encomendas**

9. O sistema deve permitir que o co-produtor encomende produtos de vários produtores numa única subscrição. (Formulário)
10. O sistema deve ter campos de quantidade, em vez de texto livre. (Formulário)
11. O sistema deve fechar as encomendas no fim do prazo, permitindo exceções aprovadas. (Formulário)
12. O sistema deve permitir que o co-produtor consulte a qualquer momento o que encomendou e quanto deve a cada produtor. (Guia)

**Pagamentos**

13. O sistema deve calcular o valor a pagar a cada produtor. (Guia, Formulário)
14. O sistema deve mostrar os dados de pagamento de cada produtor (IBAN, MBWay). (Guia)
15. O sistema deve permitir que o produtor marque um pagamento como recebido. (Guia)
16. O sistema deve permitir que o produtor registe o peso real e calcule o valor final. (Formulário)

**Distribuição e comunicação**

17. O sistema deve gerar a lista de distribuição de cada data. (Guia)
18. O sistema deve permitir que o co-produtor avise que não vai levantar, ou que outra pessoa vai por ele. (Guia)
19. O sistema deve permitir enviar avisos aos co-produtores de um produtor ou de um ciclo. (Formulário)

**Dados pessoais**

20. O sistema deve permitir exportar, corrigir e apagar os dados de um co-produtor. (Termos)
21. Cada produtor só deve ver os dados dos co-produtores que lhe compraram. (Guia, Termos)

**Não funcionais e restrições**

22. O sistema deve ser fácil de usar por pessoas sem formação técnica. (Reportagem, Guia)
23. O sistema deve ter um custo baixo, compatível com uma associação financiada por quotas de 10 €. (Guia)
24. O sistema não deve receber pagamentos nem cobrar comissões, para respeitar o princípio de não haver intermediários. (Guia, Reportagem)
25. O sistema deve cumprir o RGPD. (Termos)
