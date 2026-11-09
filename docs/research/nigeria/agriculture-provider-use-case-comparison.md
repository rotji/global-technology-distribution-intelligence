# Nigeria Agriculture: Provider and Use-Case Evaluation

**Research snapshot:** 2026-11-09  
**Status:** Comparative desk assessment based on public provider material. Product claims are provider-published unless otherwise stated. No provider has been tested on Nigerian fields and no commercial terms have been confirmed directly.  
**Decision scope:** Identify the strongest agriculture use cases and provider routes that could fit Nigeria, existing farmer/cooperative networks, and the project's zero-upfront-capital constraint.

## 1. Executive assessment

The strongest initial market proposition is not to sell a satellite app to isolated smallholder farmers one by one. It is to test whether an existing farmer organisation, cooperative, aggregator, outgrower programme, agronomist or input-service business can use field-level intelligence across a group of farms.

A credible initial service concept is:

> **Group crop-monitoring and field-prioritisation service:** help an organisation see which member fields or production clusters may need attention, then help its agronomists or extension staff prioritise physical visits and follow-up.

This is a proposed use case, not a proven Nigerian product-market fit. Satellite indicators do not diagnose every cause of crop stress. Field inspection and local agronomic judgement remain necessary before recommending treatment.

### Preliminary provider positioning

| Provider | Most plausible role in this project | Technical fit for group monitoring | Public partnership route | Zero-capital assessment |
|---|---|---|---|---|
| Farmonaut | Individual referrer introducing farmer groups and agribusiness customers | Direct field monitoring; provider says updates arrive every few days, 10 m analysis and radar coverage; crop list includes maize and rice | Public agriculture affiliate programme; 20% recurring commission stated by provider | **Most promising public entry route**, but Nigerian eligibility, payout availability and full terms still need confirmation |
| EOSDA | Reseller or service partner for agronomists, cooperatives and farm-service organisations | Direct crop-monitoring platform and API | Public global reseller programme | **Not zero-capital on published model unless exception exists**: partner purchases hectares before allocating them to customers |
| Cropin | Institutional solution/channel partner for aggregators, processors, lenders, insurers, development programmes and government | Broadest enterprise and programme intelligence in this comparison: field operations, crop/acreage, yield, disease, water stress, sourcing and portfolio risk | Public partner programme with product/deal assistance, training and support | **Unconfirmed and likely higher-friction**: enterprise-oriented; no public proof that an individual Nigerian referrer can join without business or commercial requirements |
| OneSoil | Local agri-service/dealer or agronomist-led service | Strong field-level monitoring, scouting, anomaly detection, weather, productivity zones and precision-ag workflows | Pro dealer route and white-label contact route | **Unconfirmed**: public dealer route exists, but no public referral-only commission or no-purchase terms identified |

**Important:** Farmonaut ranks first only for the *publicly visible low-friction partner entry route*, not as the overall best technology. Cropin may be stronger for large institutional programmes; OneSoil may suit agronomists and service dealers; EOSDA may be technically suitable but commercially difficult under the no-capital constraint.

## 2. Nigerian customer problems worth testing

Nigeria's National Agricultural Development Fund describes its AgGrow programme as targeting 50,000 smallholder farmers, with maize, rice, cassava and soybean among the focus crops, and structured outgrower arrangements connecting farmers to processors. This is evidence that organised, multi-farmer programmes and these crop value chains are relevant institutional contexts; it is not evidence that these organisations currently buy satellite monitoring.

Potential use cases:

### A. Cooperative or association field oversight
- **Buyer/user:** cooperative leadership, field coordinator, agronomist or extension team.
- **Problem hypothesis:** leaders may lack a consistent overview of crop condition across dispersed member farms and may not know where to send scarce field staff first.
- **Possible service:** register field boundaries, monitor crop development and vegetation anomalies, produce a periodic exception list, and route priority locations to field staff for inspection.
- **Value to test:** better prioritisation of field visits and earlier identification of unusual field changes.
- **Critical requirements:** reliable farm boundaries, member consent, crop and planting-date information, field-level validation, clear responsibilities for follow-up.

### B. Aggregator, processor or outgrower programme
- **Buyer/user:** commodity aggregator, processor, contract-farming operator or sourcing manager.
- **Problem hypothesis:** uncertainty about acreage, crop progress and harvest timing can complicate procurement and logistics planning.
- **Possible service:** monitor production clusters and provide periodic acreage, crop-stage, stress and harvest-readiness signals.
- **Value to test:** improved visibility of expected supply and where field teams should investigate.
- **Critical requirements:** verified grower/plot registry, crop-specific local model performance, forecast uncertainty, integration with actual procurement records.

### C. Agronomist or agricultural service provider
- **Buyer/user:** independent agronomist, farm consultant, input dealer or machinery/service provider.
- **Problem hypothesis:** one agronomist may support many farms and needs a way to identify fields or zones that deserve closer inspection.
- **Possible service:** use satellite maps as a triage layer before physical visits; combine with farmer observations and scouting.
- **Value to test:** more efficient service coverage and a differentiated paid advisory package.
- **Critical requirements:** practical mobile workflow, usable reports, local agronomic interpretation, transparent limits and no unsupported automated diagnosis.

### D. Lender, insurer or development programme
- **Buyer/user:** agricultural lender, insurer, donor-funded programme or government agency.
- **Problem hypothesis:** portfolio-level visibility and independent monitoring of farms can be difficult across many locations.
- **Possible service:** aggregate field and crop-risk signals to support programme monitoring, underwriting or claims review.
- **Value to test:** better risk triage and monitoring coverage.
- **Critical requirements:** stronger validation, auditability, data governance, model performance evidence and institutional procurement. This is a later-stage use case, not the easiest first sale.

## 3. Provider-by-provider assessment

### 3.1 Farmonaut

**What the public material supports**
- Farmonaut says crop data is updated every few days when optical or radar satellites pass; radar is used when optical imagery is blocked by cloud.
- It describes 10-metre field analysis and multiple satellite views, including vegetation, moisture and water-related indices.
- Its FAQ lists 166 crops, including maize and rice.
- The platform can start from a field boundary; the provider describes web/mobile access, PDF reports and an agriculture API.
- Its agriculture affiliate FAQ states 20% of referred users' spend for every month they remain subscribed, with payout on the 5th by bank transfer or PayPal. These are provider-published terms, not independently verified, and availability for a Nigeria-based affiliate still needs confirmation.

**Fit**
- Good candidate for a relatively simple introduction model: an organisation or agronomist identifies farms, the provider supplies the monitoring product, and the referrer earns under the affiliate programme if eligible.
- Could support group-level field monitoring, but confirm whether multiple member fields can be managed efficiently and whether group billing/reporting is supported.

**Risks and gaps**
- Public crop list evidence explicitly names maize and rice, but does not establish model performance for Nigerian varieties, planting calendars or local conditions.
- Satellite indicators are not a substitute for field diagnosis.
- No evidence yet that the affiliate programme permits a partner to recruit or share revenue with an association as a sub-channel.
- Bank-transfer payout details for Nigeria, minimum threshold, tax treatment and lead attribution need confirmation.

**Preliminary decision:** Retain as a leading low-capital *channel hypothesis*, not as a technology winner or confirmed opportunity.

Sources:
- https://farmonaut.com/faqs
- https://farmonaut.com/our-technologies
- https://farmonaut.com/partner
- https://farmonaut.com/contact-us

### 3.2 EOS Data Analytics (EOSDA)

**What the public material supports**
- EOSDA Crop Monitoring is positioned as a precision-agriculture platform that resellers can offer to their customers.
- EOSDA describes technical and marketing support for partners.
- Its published partner workflow says the reseller purchases a desired amount of hectares, invites customers and allocates the purchased hectares among them.
- EOSDA also offers an API for integrating satellite data and crop-monitoring tools into custom or existing GIS applications; pricing is discussed with its team.

**Fit**
- Potentially useful for agronomists, cooperatives, insurers or farm-service businesses that already have paying customers and can bundle monitoring with an existing service.
- API access could support a later technical integration, but API pricing and implementation requirements are unknown.

**Risks and gaps**
- Pre-purchasing hectares conflicts with the project's no-upfront-capital rule unless EOSDA offers an exception or referral-only alternative.
- Need to clarify minimum hectare purchase, expiry, customer allocation, currency, refund/unused-credit treatment and whether a partner can begin with a pilot funded by the end customer.
- No Nigeria-specific crop-model or partner-eligibility evidence established here.

**Preliminary decision:** Defer as a primary zero-capital route unless EOSDA confirms a no-prepurchase referral or customer-funded pilot model. Keep as a technical alternative.

Sources:
- https://eos.com/partnership/
- https://eos.com/faq/
- https://aws.amazon.com/marketplace/pp/prodview-kjjsypgp2uhkk

### 3.3 Cropin

**What the public material supports**
- Cropin describes an enterprise agriculture intelligence platform combining field records, satellite, weather, climate and enterprise data.
- Its current public material describes crop/acreage detection, crop progression, yield and production forecasts, disease/crop-health signals, water and nutrient indicators, weather/climate risk, and land-use change.
- It positions use cases around production programmes, sourcing, procurement, traceability, sustainability, lending, insurance and government/development programmes.
- Its partner page advertises product and deal assistance, training, transparency and growth support. It does not publish an individual referral commission or complete zero-capital terms.

**Fit**
- Strong candidate for an institutional buyer rather than a single smallholder: aggregators, processors, food companies, development programmes, lenders, insurers and government agencies.
- Could fit a network-based approach where an association or programme introduces a cluster of growers and Cropin provides an enterprise solution.
- Broadest scope of the four for connecting plot-level monitoring to regional production and sourcing decisions.

**Risks and gaps**
- Enterprise scope may imply longer sales cycles, procurement, integration, data onboarding and implementation resources.
- Cropin's global scale claims do not prove model accuracy for a specific Nigerian crop, state, variety or season.
- The partner page's existence does not prove that an individual without a registered company can become a partner or earn commission.
- The current public product language includes some new platform/agent capabilities; distinguish generally available production functions from pilots or expanding features during provider diligence.

**Preliminary decision:** Highest-priority provider to qualify for institutional and aggregator use cases, but not yet a zero-capital-qualified opportunity.

Sources:
- https://www.cropin.com/partner-with-us/
- https://www.cropin.com/platform/
- https://www.cropin.com/domains/agriculture/
- https://www.cropin.com/solutions/

### 3.4 OneSoil

**What the public material supports**
- OneSoil describes field monitoring, scouting, NDVI and other vegetation indices, anomaly detection, weather, productivity analysis, soil sampling, field trials and variable-rate application maps.
- It has web, mobile and API access.
- Its help centre identifies farmers, agronomists, consultants, researchers, machinery/service dealers and agricultural-data businesses as user groups.
- The help centre says prospective OneSoil Pro dealers should contact support; it describes dealers in 15 countries. A white-label contact route has also been published.

**Fit**
- Particularly relevant to an agronomist or agri-service provider who wants to use field monitoring and scouting as part of a service.
- Could fit a regional service model better than an enterprise-wide forecasting programme.
- Its free mobile layer and Pro trial may help evaluate workflows, but this does not establish free commercial use or a free reseller licence.

**Risks and gaps**
- Dealer route is not the same as a referral affiliate programme; commission, margins, required purchases, territory, customer ownership and payout are unknown.
- Confirm whether the relevant features and supported crop workflows are suitable for Nigerian crops and farm sizes.
- Variable-rate maps and machinery integration may be less useful where customers do not have compatible equipment.

**Preliminary decision:** Strong technical candidate for agronomist/service-provider workflows; commercial qualification remains open.

Sources:
- https://onesoil.ai/en/platform
- https://help.onesoil.ai/en/articles/5237693-what-is-onesoil
- https://onesoil.ai/en

## 3.5 Nigeria-specific evidence: EOSDA / Agroxchange

A material Nigeria-specific case study was identified after the initial comparison. EOSDA published a case study describing **Agroxchange Technology as its exclusive white-label partner in Nigeria** for EOSDA Crop Monitoring. EOSDA says Agroxchange used NDVI and NDRE to monitor crop development and NDWI to assess soil moisture, with a customised web platform and mobile scouting app. EOSDA also states that its cloud deployment helped avoid additional server hardware as workload scaled.

**Why this changes the assessment**
- EOSDA is not merely a technically relevant global platform; there is published evidence of a Nigerian white-label deployment and a local partner relationship.
- This strengthens its relevance for Nigerian institutional, consulting and farm-finance use cases.
- It does **not** prove that EOSDA currently accepts new individual Nigerian partners, that Agroxchange's arrangement is open to others, or that a no-prepurchase/referral route exists.
- The case study is provider-published and describes a specific partner implementation. It is not independent verification of current model accuracy, current commercial terms or general availability.

**Revised decision:** Raise EOSDA's Nigeria market-fit evidence, but keep its zero-capital status unresolved and its standard reseller pre-purchase requirement as a material barrier. The next question is whether EOSDA offers a referral, sub-channel or customer-funded pilot arrangement distinct from its published prepaid-hectare reseller model.

Source: https://eos.com/blog/case-study-evidence-based-agriculture/

## 4. Matching providers to use cases

| Use case | First provider to investigate | Alternative | Reason for the order | Main unresolved test |
|---|---|---|---|---|
| Cooperative field monitoring | Farmonaut | OneSoil | Farmonaut has a public affiliate route and explicit maize/rice references; OneSoil has field monitoring and dealer route | Multi-field group workflow, local crop validation and association channel permissions |
| Agronomist-led scouting service | OneSoil | Farmonaut | OneSoil explicitly serves agronomists/consultants and has scouting workflows; Farmonaut offers periodic satellite views and advisory | Nigerian dealer/referral terms, local agronomic usefulness |
| Aggregator/outgrower supply visibility | Cropin | Farmonaut / EOSDA | Cropin explicitly covers acreage, yield, harvest readiness and sourcing-region decisions | Nigerian crop-specific accuracy, onboarding cost and partner eligibility |
| Lender/insurer portfolio monitoring | Cropin | Farmonaut | Cropin's public positioning explicitly includes underwriting and portfolio risk; Farmonaut describes farm risk products | Auditability, model validation, procurement and regulatory/data requirements |
| Precision input application | OneSoil | EOSDA | OneSoil describes productivity zones and variable-rate application maps; EOSDA offers crop-monitoring tools/API | Equipment compatibility, service economics and actual local adoption |

These are research priorities, not validated product recommendations. Provider choice may differ by buyer, crop, farm scale and service model.

## 5. Zero-capital partnership filter: current status

| Requirement | Farmonaut | EOSDA | Cropin | OneSoil |
|---|---|---|---|---|
| Public partner route exists | Yes | Yes | Yes | Yes |
| Individual in Nigeria explicitly confirmed eligible | Not yet | Not yet | Not yet | Not yet |
| Referral-only route explicitly published | Yes, agriculture affiliate | Not established | Not established | Not established |
| No mandatory purchase explicitly established | Affiliate appears referral-based; confirm full terms | No; published reseller flow buys hectares | Unknown | Unknown |
| Commission/margin published | 20% recurring (provider-published) | Not in reviewed source | Not in reviewed source | Not in reviewed source |
| Nigeria payout method confirmed | No | No | No | No |
| Association/sub-channel revenue sharing confirmed | No | No | No | No |
| Current project classification | Promising lead; unverified | Potential capital conflict | Enterprise partner lead; unverified | Dealer lead; unverified |

## 6. Existing Nigerian network alignment

Use existing network records as *potential introduction routes*, not as confirmed channels.

- **COA-FARMERS:** potentially relevant for farmer-group and commodity associations, subject to verifying its current structure, active member groups and decision-makers.
- **NAMCON:** potentially relevant where mechanisation cooperatives and farm-service operations are involved; confirm actual reach into the selected crop clusters.
- **AFAN:** potentially relevant for farmer access, but confirm the specific state/chapter and authorised leadership because similarly named entities and competing claims exist.
- **PLACOM:** potentially relevant to Plateau commodity marketing and cooperative development; validate whether it has access to active producer groups and whether the use case fits its mandate.

Do not start with a generic request to distribute a referral link. The proposition should be a defined service for the network's members, with a clear member benefit, a provider-delivered technical service, and an agreed commercial or programme arrangement.

## 7. Recommended validation sequence

### Stage 1 — Choose one bounded pilot hypothesis
Start with one crop cluster and one organisation type. A sensible research candidate is maize or rice growers organised through a cooperative, aggregator or outgrower programme. Do not assume Plateau is the best location without evidence of an accessible, active group and suitable field data.

### Stage 2 — Ask each provider the same technical questions
1. Do you currently support the selected crop and its varieties in Nigeria? Which model/product specifically?
2. What minimum field size, field-boundary quality and data are required?
3. Can one account monitor many dispersed smallholder plots under one organisation?
4. Can the organisation receive consolidated maps, alerts, reports or dashboards?
5. What is the revisit/update frequency in the rainy season and under persistent cloud?
6. What is the demonstrated accuracy or known limitation for crop classification, stress detection, yield or harvest timing in Nigeria?
7. Which outputs require field validation before action?
8. Can the provider run a no-cost demonstration using a sample set of Nigerian field boundaries?

### Stage 3 — Ask the same commercial questions
1. Can a Nigeria-based individual become a referral/channel partner without a registered company?
2. Is there any fee, deposit, prepaid hectare, minimum sale, paid training or certification?
3. Can the provider contract, bill, onboard and support the end customer directly?
4. What commission or margin applies, and when is it paid?
5. Can a cooperative/association be registered as a referral source or distribution partner?
6. Can the partner share an agreed portion of revenue with the network, and is sub-referral explicitly permitted?
7. What are the Nigerian payout methods, currency, minimum threshold and tax documentation requirements?
8. How are leads protected and attributed?

### Stage 4 — Validate the network before proposing a pilot
1. Confirm an active organisation and an authorised decision-maker.
2. Establish the number and location of active growers, crop mix and season.
3. Identify who currently provides agronomic/extension support.
4. Determine the real cost of the problem and who would pay.
5. Obtain consent and a sample of usable field boundaries before any provider demo.
6. Define how field alerts would trigger physical inspection and who is responsible for it.

### Stage 5 — Decision gates
- **Proceed to provider demo:** crop/region fit and multi-field workflow demonstrated.
- **Proceed to commercial qualification:** no-upfront-capital terms and Nigeria eligibility confirmed.
- **Proceed to network pilot design:** a real organisation, authorised sponsor, member value and follow-up process validated.
- **Defer:** any essential requirement remains unknown, or the route requires capital the project does not have.
- **Reject:** provider cannot support the crop/use case or requires prohibited upfront expenditure.

## 8. Current decision

1. **Do not select a single provider yet.** Preserve the four-provider comparison.
2. **Prioritise Cropin for institutional/aggregator qualification** because its public product scope most directly addresses production, sourcing and portfolio decisions.
3. **Prioritise Farmonaut for low-capital channel qualification** because it is the only one of the four with a clearly published referral affiliate model and stated recurring commission.
4. **Prioritise OneSoil for agronomist-led service evaluation** because its public workflows explicitly include scouting and agronomist/service-dealer users.
5. **Keep EOSDA as a technical alternative but defer reseller activation** unless the pre-purchase requirement can be removed or funded by a confirmed customer.
6. **Do not contact providers or networks until the user explicitly authorises outreach.**

No partnership, Nigerian eligibility, local model performance, network access, customer demand, revenue or commission payout is confirmed by this assessment.

## 9. Source register

All accessed 2026-11-09 unless the page states a publication date.

- Farmonaut FAQ and affiliate terms: https://farmonaut.com/faqs
- Farmonaut technology overview: https://farmonaut.com/our-technologies
- Farmonaut partnership page: https://farmonaut.com/partner
- Farmonaut contact/partnership routes: https://farmonaut.com/contact-us
- EOSDA partner programme: https://eos.com/partnership/
- EOSDA API and product FAQ: https://eos.com/faq/
- EOSDA reseller listing: https://aws.amazon.com/marketplace/pp/prodview-kjjsypgp2uhkk
- Cropin partner programme: https://www.cropin.com/partner-with-us/
- Cropin platform: https://www.cropin.com/platform/
- Cropin agriculture domain: https://www.cropin.com/domains/agriculture/
- Cropin solutions: https://www.cropin.com/solutions/
- OneSoil platform: https://onesoil.ai/en/platform
- OneSoil dealer information (published 2026-01-30): https://help.onesoil.ai/en/articles/5237693-what-is-onesoil
- Nigeria National Agricultural Development Fund, AgGrow/FISP: https://nadf.gov.ng/nadf-farm-input-supply-program-fisp/

## 10. Research limitations

- This is desk research, not product testing or independent agronomic validation.
- Provider pages are self-published and may change.
- No current Nigerian customer references or independently measured Nigerian model-accuracy results were established in this pass.
- No provider has confirmed the project's eligibility, commercial terms or willingness to work through a farmer organisation.
- The NADF programme is used only as evidence that organised grower programmes and selected crop value chains are relevant; it is not evidence of a sales lead or endorsement.
- Network records remain unverified leads. No outreach has been initiated.
