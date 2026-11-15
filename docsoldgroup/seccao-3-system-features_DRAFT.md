# 3 System features

The functional requirements are organized by system feature, the major services provided by the platform. The "Actor" column shows who performs the action.

- 3.1 Accounts and profiles
- 3.2 AMAP discovery and membership
- 3.3 AMAP management
- 3.4 Order periods and offers
- 3.5 Subscriptions and orders
- 3.6 Payments and invoicing
- 3.7 Deliveries and communication

## 3.1 Accounts and profiles

### 3.1.1 Description

Allows any person to create an account on the platform, choosing an initial profile (Producer or Co-Producer), and to manage their personal data. Producers can describe how they produce. All other features depend on this one.

Priority: High.

### 3.1.2 Stimulus/Response Sequences

| # | Stimulus | Response |
|---|---|---|
| 1 | The User fills in their personal data and chooses an initial profile (Producer or Co-Producer) | The system creates the account with that profile |
| 2 | The User adds the other profile to the same account | The system adds the profile to the existing account (to be confirmed) |
| 3 | The Producer uploads certificates, photos or descriptions of their production | The system shows them on the Producer's profile |
| 4 | The User edits their personal data | The system updates the data |
| 5 | The User asks to delete their profile | The system deletes the personal data, except the data that must be kept by law |

### 3.1.3 Functional Requirements

| ID | Actor | Requirement | Source | Priority |
|---|---|---|---|---|
| RF-01 | User | Create an account with an initial profile (Producer or Co-Producer) and add the other profile later (to be confirmed) | Hipótese (acumular perfis); Análise de Diferenciação §6; T&Cs AMAP UPTEC Baixa ("registo na plataforma"); Guia AMAP Porto §4 (produtores e coprodutores nos mesmos grupos de trabalho) | |
| RF-05 | User | View and edit their personal data | T&Cs AMAP UPTEC Baixa (§8, §9); Hipótese para o produtor | |
| RF-06 | User | Leave an AMAP and delete their profile and personal data, respecting the legal retention obligations | Hipótese; T&Cs AMAP UPTEC Baixa (§9); Hipótese para o produtor | |
| RF-12 | Producer | Upload certificates, photos or descriptions of their production | Sessão com o Diretor (Q9) | |

## 3.2 AMAP discovery and membership

### 3.2.1 Description

Allows Users to find AMAPs near them, see their details and ask to join as a Producer or as a Co-Producer. The AMAP Coordinator accepts or rejects each request. A User can belong to more than one AMAP.

Priority: High.

### 3.2.2 Stimulus/Response Sequences

| # | Stimulus | Response |
|---|---|---|
| 1 | The User searches for AMAPs near a location | The system shows the AMAPs on a map and in a list, ordered by distance |
| 2 | The User selects an AMAP | The system shows its details: Producers, offers, pick-up location and schedule |
| 3 | The User asks to join the AMAP as a Producer or as a Co-Producer | The system shows the AMAP terms and conditions and privacy policy |
| 4 | The User accepts them and declares to be at least 18 years old | The system records the acceptance and sends the request to the AMAP Coordinators |
| 5 | The Coordinator accepts the request | The system adds the User as a member of the AMAP and notifies them |
| 6 | The Coordinator rejects the request | The system notifies the User, with the reason if the Coordinator gives one |

### 3.2.3 Functional Requirements

| ID | Actor | Requirement | Source | Priority |
|---|---|---|---|---|
| RF-02 | User | Search for AMAPs by proximity (to be confirmed) | Hipótese a confirmar; Sessão com o Diretor (Q5); Entrevista Biogoods (produtor abastece 4 AMAPs) | |
| RF-18 | Co-Producer | View the details of an AMAP (Producers, offers, pick-up location and schedule) | Sessão com o Diretor (Q2, Q4, Q5); Guia AMAP Porto §3; T&Cs AMAP UPTEC Baixa (Distribuição); Entrevista Luísa Marques | |
| RF-03 | User | Express interest in joining an AMAP (to be confirmed) | Hipótese a confirmar; Sessão com o Diretor (Q5); Entrevista Biogoods; Reportagem Público 2023; Formulário de encomendas (a confirmar) | |
| RF-04 | User | Accept the AMAP terms and conditions and privacy policy when joining that AMAP, declaring to be at least 18 years old | T&Cs AMAP UPTEC Baixa; Notas Jorge p.5 ("direitos e deveres de produtores e co-produtores") | |
| RF-20 | Co-Producer | Join more than one AMAP at the same time | Entrevista Biogoods | |
| RF-34 | AMAP Coordinator | Accept or reject membership requests from Co-Producers | T&Cs AMAP UPTEC Baixa ("não constitui um direito dos utilizadores"); Guia AMAP Porto §4 (Acolhimento); Sessão com o Diretor (Q5) | |
| RF-35 | AMAP Coordinator | Accept or reject membership requests from Producers | Guia AMAP Porto §0; Entrevista Biogoods; Sessão com o Diretor (Q9) | |

## 3.3 AMAP management

### 3.3.1 Description

Allows a User to create an AMAP and configure how it works. Whoever creates the AMAP becomes its Coordinator. Coordination can be shared with other members and handed over, since these tasks are usually rotated. The rules decided by the AMAP members in assembly are configured here. An AMAP can have several Producers and several Co-Producers.

Priority: High.

### 3.3.2 Stimulus/Response Sequences

| # | Stimulus | Response |
|---|---|---|
| 1 | The User creates an AMAP with its data | The system creates the AMAP and makes the User its Coordinator |
| 2 | The Coordinator defines the pick-up location and the distribution schedule | The system shows them in the AMAP details |
| 3 | The Coordinator chooses whether invoicing and payments are made directly to each Producer or through the AMAP (TO BE DISCUSSED) | The system applies this choice to all Producers of the AMAP |
| 4 | The Coordinator defines an annual membership fee | The system records the fee for each member |
| 5 | The Coordinator adds another member as Coordinator | The system gives that member the Coordinator permissions |
| 6 | The Coordinator leaves the role | The system allows it only if the AMAP keeps at least one Coordinator |
| 7 | The Coordinator adds a document or a useful link | The system makes it available to all members of the AMAP |

### 3.3.3 Functional Requirements

| ID | Actor | Requirement | Source | Priority |
|---|---|---|---|---|
| RF-07 | User | Create a new AMAP, automatically becoming its Coordinator | Entrevista Biogoods; Guia AMAP Porto (introdução); Sessão com o Diretor (Q6) | |
| RF-32 | AMAP Coordinator | Add other members as Coordinators of the AMAP | Hipótese; Guia AMAP Porto §4 | |
| RF-33 | AMAP Coordinator | Leave the Coordinator role, as long as the AMAP keeps at least one Coordinator | Guia AMAP Porto §4 (rotação); Hipótese (mínimo de 1) | |
| RF-39 | AMAP Coordinator | Configure the AMAP rules (pick-up location and distribution schedule) | Hipótese; Entrevista Biogoods; Sessão com o Diretor (Q2) | |
| RF-40 | AMAP Coordinator | Choose whether invoicing and payments are made directly to each Producer or through the AMAP as an intermediary (the same for all Producers of that AMAP; through the AMAP only if the AMAP has its own tax number) | Hipótese (Análise de Diferenciação H4); Entrevista Biogoods; Sessão com o Diretor (Q10); Notas Jorge p.3 e p.4. O Guia AMAP Porto prevê só a forma direta (sem intermediários); a plataforma suporta as duas | |
| RF-41 | AMAP Coordinator | Provide a central repository of AMAP documents and useful links | Hipótese; Entrevista Luísa Marques; Guia AMAP Porto §4 | |
| RF-42 | AMAP Coordinator | Record an annual fee per member (Producers and Co-Producers), if applicable | Guia AMAP Porto §2 | |
| RF-47 | System | Support AMAPs with several Producers and several Co-Producers at the same time | Sessão com o Diretor (Q1); Entrevista Biogoods | |

## 3.4 Order periods and offers

### 3.4.1 Description

Allows the Coordinator to open an order period with its delivery dates, and the Producers to create their offers (baskets and individual products) for that period. Offers are created for each period because products and prices change with the season. Once the offers are ready, the period is announced to the Co-Producers.

Priority: High.

### 3.4.2 Stimulus/Response Sequences

| # | Stimulus | Response |
|---|---|---|
| 1 | The Coordinator creates an order period with a start and an end date | The system asks for the delivery frequency |
| 2 | The Coordinator chooses the frequency (weekly, every two weeks, every three weeks, monthly) or picks the dates on the calendar | The system generates the delivery calendar for the period |
| 3 | The Coordinator sets the order deadline and opens the period | The system notifies the Producers of the AMAP |
| 4 | The Producer creates an offer for the period (for a basket, listing its typical products) | The system links the offer to the period |
| 5 | The Producer edits or removes an offer | The system updates the offers of the period |
| 6 | The Coordinator announces the period | The system notifies the Co-Producers and shows the offers |

### 3.4.3 Functional Requirements

| ID | Actor | Requirement | Source | Priority |
|---|---|---|---|---|
| RF-36 | AMAP Coordinator | Open an order period, with an order deadline, start and end dates and delivery dates (weekly, every two weeks, every three weeks, monthly or custom dates on the calendar), and announce it to the Co-Producers | Guia AMAP Porto §1 e §4; Entrevista Biogoods | |
| RF-08 | Producer | Create an offer (basket or individual product) for an order period, with name, description, photo, quantity (by weight or by unit), price and delivery frequency, and, for baskets, the typical products of the season | Sessão com o Diretor (Q2); Entrevista Luísa Marques; Guia AMAP Porto §1 | |
| RF-09 | Producer | Edit and remove offers already created | Hipótese | |

## 3.5 Subscriptions and orders

### 3.5.1 Description

Allows Co-Producers to subscribe to the offers of an open order period. A subscription is a commitment for the whole period: the Co-Producer shares the agricultural risk and accepts that quantities vary with the harvest. Co-Producers can also order extra products outside the subscription. Producers and Coordinators can see the orders received. When subscribing to a basket, Co-Producers can mark the typical products they would rather not receive. These preferences are indicative only and are not meant for allergies.

Priority: High.

### 3.5.2 Stimulus/Response Sequences

| # | Stimulus | Response |
|---|---|---|
| 1 | The Co-Producer selects offers and quantities in an open period | The system shows the total amount and the conditions of the seasonal commitment |
| 2 | The Co-Producer marks the typical products of a basket they would rather not receive (TO BE DISCUSSED) | The system saves the choices for that subscription, pre-filled from the previous period |
| 3 | The Co-Producer submits the subscription | The system records it and sends a confirmation by email |
| 4 | The Co-Producer checks their subscription | The system shows its status and content |
| 5 | The Co-Producer asks for an extra product (TO BE DISCUSSED) | The system sends the request to the Producer |
| 6 | The Producer checks their subscribers | The system lists, for each delivery, what each Co-Producer ordered and their food preferences |
| 7 | The Coordinator checks the orders | The system shows all orders of the period |

### 3.5.3 Functional Requirements

| ID | Actor | Requirement | Source | Priority |
|---|---|---|---|---|
| RF-19 | Co-Producer | Subscribe to a Producer's offer, with a defined quantity and duration (configurable duration) | Sessão com o Diretor (Q2); Entrevista Biogoods; Guia AMAP Porto §1 | |
| RF-21 | Co-Producer | When subscribing to a basket, mark the typical products they would rather not receive and add a note (indicative only, not for allergies). The choices of the previous period are pre-filled | Entrevista Luísa Marques; Entrevista Biogoods; Formulário de encomendas (a confirmar) | |
| RF-24 | Co-Producer | View the status and content of their subscription request | Guia AMAP Porto §1; Entrevista Luísa Marques; T&Cs AMAP UPTEC Baixa (Confirmação de inscrição) | |
| RF-28 | Co-Producer | Receive the order confirmation by email | Entrevista Luísa Marques; Guia AMAP Porto §1 | |
| RF-48 | System | Allow extra orders outside the subscription, including structured requests for specific products | Entrevista Biogoods; Entrevista Luísa Marques (pedido estruturado é hipótese) | |
| RF-50 | System | Explicitly represent the seasonal commitment and the shared agricultural risk | Hipótese (Análise de Diferenciação H2); Reportagem Público 2023; Guia AMAP Porto | |
| RF-10 | Producer | View the product preferences and exclusions registered by the Co-Producers for each of their baskets | Entrevista Luísa Marques | |
| RF-13 | Producer | View the subscribers of their offers and what each one ordered, per delivery | Hipótese; Entrevista Biogoods; Entrevista Luísa Marques | |
| RF-37 | AMAP Coordinator | View the orders received | Entrevista Biogoods | |

## 3.6 Payments and invoicing (TO BE DISCUSSED ALL THIS SECTION)

### 3.6.1 Description

Calculates how much each Co-Producer owes and supports the payment, either directly to each Producer or through the AMAP, depending on the AMAP configuration. It covers payments made in the app and manual payments (bank transfer or cash), which the Co-Producer declares and the Producer confirms.

Priority: High.

### 3.6.2 Stimulus/Response Sequences

| # | Stimulus | Response |
|---|---|---|
| 1 | The Producer defines their payment rule (accepted methods, deadline, instalments) | The system applies it to their offers, unless an offer has an exception |
| 2 | The Co-Producer submits a subscription | The system calculates the amount owed to each Producer |
| 3 | A product is missing or an extra product is delivered | The system adjusts the amount owed |
| 4 | The Co-Producer chooses a payment method and, if allowed, to pay in instalments | The system shows the amount and the payment details |
| 5 | The Co-Producer pays in the app | The system records the payment as done |
| 6 | The Co-Producer declares a manual payment (transfer or cash) | The system marks it as declared and notifies the Producer |
| 7 | The Producer confirms the payment received | The system marks it as paid |
| 8 | A payment is still pending | The system reminds the Co-Producer of the amount to pay |
| 9 | The Producer issues an invoice | The system makes it available to the Co-Producer |

### 3.6.3 Functional Requirements

| ID | Actor | Requirement | Source | Priority |
|---|---|---|---|---|
| RF-16 | Producer | Define the default payment rule (accepted methods, deadline and whether instalments are accepted) and exceptions per offer | Guia AMAP Porto §2; Entrevista Luísa Marques; Reportagem Público 2023; Formulário de encomendas (a confirmar). Parcelas: Hipótese (ver RF-30) | |
| RF-44 | System | Automatically calculate the amount each Co-Producer owes to each Producer, with adjustments for missing or extra products | Entrevista Biogoods; Entrevista Luísa Marques; Formulário de encomendas (a confirmar) | |
| RF-25 | Co-Producer | View at any time how much they owe to each Producer (to be confirmed) | Entrevista Luísa Marques; Guia AMAP Porto §1 | |
| RF-29 | Co-Producer | Choose the payment method among those accepted by the Producer and pay in the app (e.g. MB Way, bank transfer) or in cash on delivery. When the AMAP is the intermediary, pay the total to the AMAP; otherwise, pay each Producer (to be confirmed) | Entrevista Luísa Marques; Sessão com o Diretor (Q10); Guia AMAP Porto §2; Reportagem Público 2023. Pagamento direto na app é hipótese. O destino do pagamento (produtor ou AMAP) depende da configuração da AMAP (ver RF-40) | |
| RF-30 | Co-Producer | Choose to pay the subscription at once at the start of the period or in instalments during the period, when the Producer allows it (to be confirmed) | Hipótese; Reportagem Público 2023 ("pagos aos produtores no início do trimestre, ou em parcelas") | |
| RF-31 | Co-Producer | Declare a payment that is not automatic in the app (manual transfer or cash), giving their name in the transfer description or sending proof of payment (to be confirmed) | Guia AMAP Porto §2 | |
| RF-17 | Producer | Confirm the receipt of payments that are not automatic in the app | Hipótese; Guia AMAP Porto §2; Entrevista Luísa Marques | |
| RF-45 | System | Remind the Co-Producer of the amounts still to pay until the Producer confirms the payment | Hipótese; Entrevista Luísa Marques | |
| RF-15 | Producer | Issue an invoice to the Co-Producer (base case: each Producer invoices individually) | Entrevista Biogoods; T&Cs AMAP UPTEC Baixa | |

## 3.7 Deliveries and communication

### 3.7.1 Description

Supports everything that happens around each delivery: the delivery calendar, the basket content announced in advance, notifications, absences, pick-up confirmation, baskets not picked up and quality problems. It also lets Producers share news about their production, keeping the close relationship between Producers and Co-Producers.

Priority: High.

### 3.7.2 Stimulus/Response Sequences

| # | Stimulus | Response |
|---|---|---|
| 1 | The Co-Producer checks the delivery calendar | The system shows the delivery dates of the period |
| 2 | Before a delivery, the Producer indicates the basket content | The system notifies the Co-Producers with the content and the pick-up location |
| 3 | The Co-Producer cannot go to a delivery and signals their absence | The system asks what happens to the basket and informs the Producer and the Coordinator |
| 4 | The Coordinator asks for the distribution list of a delivery | The system lists what each Co-Producer receives |
| 5 | The Co-Producer picks up the basket and confirms it | The system marks the basket as picked up |
| 6 | The distribution time ends | The system flags the baskets not picked up, identified by name |
| 7 | The Co-Producer reports a problem with a product | The system records the incident and the compensation agreed |
| 8 | The Producer publishes news about the production | The system shows it to the AMAP members |

### 3.7.3 Functional Requirements

| ID | Actor | Requirement | Source | Priority |
|---|---|---|---|---|
| RF-23 | Co-Producer | View the delivery calendar of the season | Entrevista Luísa Marques; Guia AMAP Porto §1 | |
| RF-14 | Producer | Indicate the basket content for each delivery (products, quantities, total weight) | Entrevista Biogoods; Entrevista Luísa Marques; Sessão com o Diretor (Q7) | |
| RF-22 | Co-Producer | View in advance what the basket will contain (products, quantities, total weight) | Entrevista Luísa Marques | |
| RF-43 | System | Automatically notify the Co-Producer of the basket content and pick-up location | Entrevista Biogoods; Sessão com o Diretor (Q4) | |
| RF-26 | Co-Producer | Signal an absence from a delivery and choose what happens to the basket | Entrevista Biogoods; Entrevista Luísa Marques; Guia AMAP Porto §3 | |
| RF-38 | AMAP Coordinator | Generate the distribution list for each delivery (what each Co-Producer receives) | Guia AMAP Porto §4 | |
| RF-27 | Co-Producer | Confirm the pick-up of their basket at the pick-up point | Entrevista Luísa Marques; Entrevista Biogoods | |
| RF-51 | System | Flag the baskets not picked up after the distribution time, identified by name | T&Cs AMAP UPTEC Baixa | |
| RF-46 | System | Track the balance of quantities delivered over the period (abundance vs scarcity) | Sessão com o Diretor (Q7); Entrevista Biogoods | |
| RF-49 | System | Record product quality incidents and the corresponding compensation | Hipótese; Entrevista Luísa Marques | |
| RF-11 | Producer | Publish news about their production | Sessão com o Diretor (Q7) | |
