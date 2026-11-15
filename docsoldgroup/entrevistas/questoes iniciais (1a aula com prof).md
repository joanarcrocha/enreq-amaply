# General
- software to facilitate the distribution and sale of food products
- Comply with: Adopted by all United Nations Member States in 2015, which comprises 17 Sustainable 
Development Goals (https://ods.pt/ods/).
- An AMAP or CSA, is formed by a group of consumers who  actively and directly support one or more farmers and producers, ensuring the distribution of their produce.

# Opportunities
- FAIR Software Solutions has recently identified a business opportunity in the AMAP/CSA field

# Stakeholders
- Director of FAIR Software Solutions
- Co-Producers/Consumers
- Distributors
- Producers/Farmers
- Volunteer coordination
- System Engineering, Security, Non-functional requirements
- AMAP Coordinator

# Questions:
- What must each type of user be able to do?
- What are the problems with current AMAP/CSA software that this software  specifically should solve? 
- What are the main needs the system is supposed to solve?
- Which external systems/interfaces are required, such as payment providers, email, maps, or authentication?
- What are the absolute 'must-have' features for the first release (MVP), and what can be left for future versions?
- What is the expected volume of users and data in the first year to help us define scalability and performance requirements?



# Definitions
- AMAP: Association for the Maintenance of Local Farming
- CSA: Community Supported Agriculture



# Question 1:
_what this software should address (or something like that)?_
- 1 - communication between producers and consumers and 2 - facilite payment processes. we call "co-producers" and not consumers (they are also engaged in the production process).
- Co-producer --> Can support farmers (investement) and commit to buy all/part the production
- The software should be able to have multiple producers and multiple co-producers/customers

# Question 2:
_sobre tipos de users_
- Existem varios tipos de AMAPs, com regras distintas
- os farmers já sabem o que têm de produzir no próximo ano (por exemplo), fica definido com os co-producers(?)
- os consumers sabem todos os producers by name
- the farmer creates the offers (eg wine, vegetables, foods) and the quantities. e o co-producer diz que quer x produto em y quantidade durante z tempo.
- pedir cestos em avancado 
- Offer / Deliver

# Question 3: *
_Monetização e Espírito AMAP: O movimento AMAP rejeita a mercantilização pura e comissões predatórias sobre os alimentos. Como pretende a startup rentabilizar o serviço (e.g., subscrição fixa por grupo AMAP paga via quotas, financiamento de impacto social, modelo *freemium*, ou taxa administrativa fixa por co-produtor)?_
- there are different models
- csa fee for year for suport nao acredita nesta solucao , minima fee for order 
- Business model: free models exists, annual rate, the best model should be based on transactions (a minimum fee) and volume of co-producers. The system should support small producers (maybe begin with a free / very small rate to kick off?)

# Question 4:
_something about the cycles_
- sazonal
- Farmers drop off produce at a specific location, where co-producers come to pick up the food. Co-producers need to be notified of location!

# Question 5
- pagina web csa internacial sugere a mais proxima , e ao contactar se nao houver vagas fica em lista de espera , 
- vai ver qual é a csa mais proxima ou qual a que lhe interessa e contrata - tipo procura se tem vagas ou pode ir para uma lista de espera
- subscrição de ofertas por parte do co-producer

# Question 6: *
_Público-Alvo Primário: Na primeira fase, o foco prioritário é a captação de agricultores que queiram iniciar uma AMAP, a formalização de grupos informais já existentes, ou atrair o grande público consumidor para o modelo CSA?_
- o foco é agilizar o processo e ter a capacidade de monetizar para um portal de csas
- dinamizar o mercado de csa "Portal de csa" 
foco NAO é fazer csas
- Em Portugal existem só algumas dezenas de CSA
- solução internacional
- queremos "facilitar"
- perfil de utilizadores que filtra oq ele gosta
- Cabazes de produtos
- 2 tipos consumidores:
  - Biológicos (por causa dos alimentos em si)
  - Ideológico porque trabalham diretamente com agricultores

# Question 7
_Quando ha uma falha (seja dos produtores ou consumidores)_
- player importante gestao da csa 
- ha ciclos de abundancia e ciclos de escassez. quem faz um compromisso ja sabe que a partida ha entregas mais pequenas e maiores. o software deve ter em conta as quantidades ao longo do ano e no fim deve haver um equilíbrio.
- o software permite por noticias e coisas do genero (e a uma proximidade muito grande entre produtores e consumidores). por isso estes ajustes sao normais e há compreensao de ambos os lados.

# Question 8
(não houve)

# Question 9
_Quantificação de Sustentabilidade: Como o software deve refletir o compromisso com os ODS da ONU? Espera-se que a plataforma calcule e mostre indicadores aos utilizadores (ex.: km alimentares poupados, emissões de CO₂ evitadas, percentagem de desperdício evitado, remuneração digna por hora de trabalho agrícola)?_
- reducing poverty, creating a more sustainable society, natural resources, ...
- os afrmers podem/devem fazer upload de certificates (ou em casos mais pequenos fotos, descrições, ...)
- some KPIs could be interesting! (nice to have)


# Question 10
_Que entidade emite a fatura?_
- depende das configurações legais da CSA. as vezes a CSA está fully registered. outras vezes a CSA é muito pequena e paga-se diretamente ao farmer (e ele emite o invoice).
- tentar otimizar o payment system (podemos ver que soluções poderiam existir para evitar centenas de pagamentos)
- 


# perguntas que falharam:
- quem são os interessados?
- Quem paga?
- processo desde da origem ?
- quais são os documentos envolvidos?
- como se desenrola o processo de ponta a ponta?

**Lembrar: PESSOAS - DOCUMENTOS - PROCESSOS**