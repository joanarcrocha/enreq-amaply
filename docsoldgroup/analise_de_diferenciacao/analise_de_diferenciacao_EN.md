# Differentiation Analysis — FAIR-AMAP/CSA Platform

## 1. Objective and scope

This document analyzes how the FAIR Software Solutions solution can differentiate itself from alternatives used to purchase products directly from farmers in the AMAP/CSA context. The analysis considers three types of competition:

- manual processes supported by spreadsheets, forms, and messaging applications;
- general-purpose e-commerce platforms;
- platforms specialized in short food supply chains, food baskets, and CSA.

The conclusions are based on the elicitation notes available in the project and on public information about existing solutions. They represent positioning hypotheses to be validated with producers, co-producers, and coordinators, rather than requirements that have already been approved.

## 2. Problem to solve

An AMAP/CSA is not simply an online store. It is a long-term partnership in which co-producers and producers share the risks, responsibilities, and benefits of agricultural production. In Portugal, the Rede Regenerar Charter of Principles places agroecology, proximity, and food as a common good at the center [1].

However, the project interviews and notes identify a significant administrative burden. Among other tasks, producers have to enter and confirm orders, calculate amounts, communicate basket contents, send date reminders, plan deliveries, and record pickups. Currently, part of this work is carried out through spreadsheets and messages. This fragmentation becomes particularly difficult when a producer supplies several AMAPs, when an AMAP works with several producers, or when deliveries have different frequencies.

The FAIR opportunity therefore consists of reducing administrative work without turning the AMAP relationship into an impersonal one-off purchase.

## 3. Existing alternatives

| Alternative | Strengths | Limitations or opportunity space for FAIR |
| --- | --- | --- |
| Spreadsheets, forms, email, and messaging applications | Low cost, flexibility, and tools already familiar to participants. | Scattered information, repetitive work, higher probability of errors, and limited traceability of commitments, payments, deliveries, and incidents. Multi-producer and multi-AMAP management requires manual consolidation. |
| General-purpose e-commerce | Catalogs, shopping carts, payments, and order management are mature features. | Oriented toward one-off transactions and predictable stock. It does not naturally represent seasonal commitments, risk sharing, variation between abundance and scarcity, volunteering, and community governance. |
| Open Food Network | Open-source platform focused on local food systems. Supports shops, subscriptions, order cycles, payments, reports, and aggregation of multiple producers [2]. | It is a strong reference and covers several fundamental functional needs. FAIR will only differentiate itself if it provides a simpler and more integrated experience for the AMAP lifecycle, group discovery, community management, and Portuguese/European localization. |
| GrownBy | Cooperative solution aimed at farmers, with CSA subscriptions, member management, traditional or customizable baskets, payments, preparation lists, and pickup confirmation [3][4]. | Demonstrates that customization, subscriptions, and pickup confirmation are not differentiators on their own. In the publicly described multi-producer setup, payment is processed through a primary farm [5], leaving room for European models with configurable settlement and invoicing by entity. |

This comparison shows that the advantage cannot rely solely on “selling baskets online.” Many transactional functions are already offered by established solutions.

## 4. Differentiation proposal

### 4.1. An AMAP portal, not just a producer store

The solution should allow users to discover AMAPs by location, products, delivery frequency, production principles, pickup point, and availability. A potential co-producer could compare groups, check available places, join a waiting list, and subscribe to the most suitable offering. The same profile could participate in more than one AMAP.

This approach creates a network effect: it helps existing AMAPs fill their capacity, gives producers visibility, and reduces the entry barrier for co-producers. The objective is not for FAIR to create or control AMAPs, but to facilitate discovery and group operations.

### 4.2. Configuration faithful to the diversity of the AMAP/CSA model

Each group should be able to configure its own rules, including:

- commitment duration, calendar, and delivery frequency;
- advance payment, monthly payment, or payment per cycle;
- fixed basket, size variants, and complementary products;
- preferences, exclusions, and authorized substitutions, without promising availability that is incompatible with the harvest;
- maximum capacity, renewal, and waiting list;
- rules for absences, transferring, or donating baskets;
- fees, volunteering, pickup points, and participant responsibilities.

The distinguishing element is to model the commitment between the parties rather than simply repeat orders. The platform should make it explicit that volume and composition may vary throughout the season while maintaining an overall balance across the agreed cycle.

### 4.3. End-to-end multi-producer and multi-AMAP operations

FAIR can differentiate itself through a single console that allows:

- a producer to manage several AMAPs, alternating calendars, and delivery points;
- an AMAP to combine offerings from several producers without losing the origin of each product;
- consolidation of quantities for harvesting, preparation, transport, and distribution;
- allocation of amounts by producer and application of different invoicing rules;
- generation of preparation and distribution lists and confirmation of pickups;
- management of shortages, damage, surpluses, uncollected products, and future compensation.

This flow reduces administrative duplication while preserving direct sales and the identity of each farm.

### 4.4. Simplified payment with legal and financial autonomy

The elicitation notes show that the entity receiving payment and issuing invoices varies: it may be the AMAP itself or each individual producer. The platform should support both models, while clearly showing who sells, who receives payment, and who issues the fiscal document.

A single payment experience for the co-producer, combined with reconciliation, allocation, and reporting by producer, could be a relevant advantage. This hypothesis depends on the legal, fiscal, and technical feasibility of split payments and should be validated before being assumed as an MVP requirement.

### 4.5. Direct relationships and community built into the product

Rather than hiding the farmer behind a platform brand, the solution should strengthen relationships between people:

- producer profiles, production methods, photographs, and certifications;
- news from the farm and explanations for drops or peaks in production;
- automatic notifications about basket contents, location, and delivery date;
- targeted communication by AMAP, delivery, or participant group;
- organization of volunteering shifts and activities;
- group decisions, documents, and rules accessible to members.

Transparency turns a change in basket contents into an understandable consequence of agricultural production rather than a service failure typical of e-commerce.

### 4.6. Adaptation to the Portuguese and European context

Deep localization provides more value than simple translation. Support should be investigated for:

- European Portuguese and local formats;
- GDPR compliance and data minimization by profile;
- relevant payment methods such as SEPA, Multibanco, and MB WAY;
- export or integration with certified invoicing systems and applicable tax obligations;
- international operations with configurable country-specific rules;
- a mobile, accessible interface suitable for users with different levels of digital literacy;
- degraded or offline operation during deliveries in locations with poor connectivity.

### 4.7. Verifiable impact without misleading environmental claims

The platform could present indicators such as distance between production and distribution, percentage of deliveries collected, waste avoided, value paid directly to producers, and subscription stability. These indicators should be based on traceable data and explicit methodologies. Complex environmental metrics, such as avoided emissions, should not be presented without a validated methodology.

## 5. Positioning summary

> For producers, coordinators, and co-producers who want to maintain a local and long-term food relationship, FAIR-AMAP is a platform for discovering and managing agricultural communities that coordinates seasonal commitments, multiple producers, payments, and deliveries. Unlike a general-purpose online store, it preserves risk sharing, the autonomy of each group, and the direct relationship between those who produce and those who consume.

The four pillars of the positioning are:

1. **Discovery and network growth:** geographic portal, availability, and waiting lists;
2. **Faithfulness to the AMAP model:** seasonal commitment, risk sharing, and configurable rules;
3. **Operational efficiency:** multi-producer and multi-AMAP management in a single workflow;
4. **Local trust:** transparency, payments, and compliance adapted to Portugal and Europe.

## 6. Necessary but non-differentiating features

The following capabilities are important for making the solution credible, although they are already common in the market:

- authentication and profile management;
- catalog and offer search;
- subscription to baskets and additional products;
- payments and transaction history;
- notifications and reminders;
- reports, data exports, and preparation lists;
- delivery and pickup records;
- responsive mobile application.

They should be treated as competitive parity requirements rather than as the main differentiation message.

## 7. Recommended priority for the Minimum Viable Product (MVP)

To test the value proposition without attempting to cover the entire ecosystem in the first version, the following is recommended:

1. AMAP search portal, including their producers, offerings, pickup points, and available places;
2. cycle, capacity, subscription, and waiting-list management;
3. base basket, additional products, and simple preferences/exclusions;
4. calendar, notifications, and communication of production changes;
5. quantity consolidation and preparation lists by producer and pickup point;
6. payment recording and pickup confirmation;
7. absence workflow with basket transfer or donation;
8. separate financial exports by producer.

Split payments, integrated invoicing, complete offline operation, advanced volunteering features, and calculated environmental indicators should be introduced only after technical and legal validation, unless subsequent elicitation classifies them as mandatory.

## 8. Differentiation risks

| Risk | Consequence | Proposed mitigation |
| --- | --- | --- |
| Replicating features already available on other platforms | Weak reason to switch and high development costs. | Validate AMAP-specific workflows and measure the reduction in administrative work compared with the current process. |
| Introducing excessive flexibility in baskets | Moves the model closer to a supermarket and increases complexity for the producer. | Allow each AMAP to limit choices and prioritize actual harvest availability. |
| Excessively centralizing the commercial relationship | Loss of producer autonomy, trust, and identity. | Keep origin, pricing, rules, data, and responsibilities transparent. |
| Charging disproportionate commissions | Rejection by the community and reduced agricultural income. | Transparent pricing model, with a minimal progressive fee or an initial free period for small producers. |
| Attempting to support every variant from the beginning | A complex product that is difficult to learn and maintain. | Configurable core with simple presets and evolution based on pilot groups. |
| Making unsupported sustainability claims | Loss of credibility and risk of misleading environmental claims. | Use only auditable indicators, published methodology, and consented data. |

## 9. Validation hypotheses and metrics

Before consolidating the positioning, FAIR should test the following hypotheses:

| Hypothesis | Validation method | Suggested initial indicator |
| --- | --- | --- |
| Integrated management reduces the workload of producers and coordinators. | Pilot with an AMAP that currently uses spreadsheets and messages. | Reduction in weekly administrative time and the number of duplicate records. |
| The portal facilitates membership without undermining the AMAP model. | Discovery and registration test with potential co-producers. | Registration completion rate and demonstrated understanding of the seasonal commitment. |
| Multi-producer management reduces errors. | Comparison of deliveries before and during the pilot. | Fewer discrepancies between quantities ordered, prepared, delivered, and invoiced. |
| Participants accept the monetization model. | Interviews and experiments with different plans. | Adoption rate and platform cost as a percentage of the amount paid to the producer. |
| Integrated notifications replace manual work. | Measurement of communications during the pilot. | Fewer individual messages and fewer forgotten baskets. |

## 10. Conclusion

FAIR-AMAP's sustainable differentiation does not lie in a single feature, but in the coherent integration of discovery, seasonal commitment, community, multi-producer operations, and local adaptation. The solution will have a greater probability of adoption if it saves farmers time, facilitates coordination and payments, and simultaneously makes the relationship of trust between producers and co-producers more visible — rather than less visible.

## References

1. Rede Regenerar, [Charter of Principles for AMAP/CSA in Portugal](https://amap.movingcause.org/carta-de-principios/).
2. Open Food Network, [Software Platform](https://openfoodnetwork.org/software-platform/).
3. GrownBy, [Platform and features for farmers and CSA](https://coop.grownby.com/).
4. GrownBy Help, [How customizable shares work](https://support.grownby.com/en/csa/how-custom-shares-work).
5. GrownBy Help, [Supported CSA models](https://support.grownby.com/en/csa/csa-types-overview).