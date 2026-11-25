# How to use
Reduced revision notes for Service Design (3009, Prof. Pradeep Yammiyavar). All 8 lectures in short form. For full explanations and slides, open "Service Design - Detailed Notes".

# UNIT 1 — SERVICES (L1–L2)

# 1.1 Systems, services, product vs service
- Designers handle (1) real-world systems made by humans (railways, hospitals, banks) and (2) the ITC systems at the back that run them. They design new, renovate/innovate and upgrade systems (simple/complex, sub-systems, integrated, embedded, nested).
- SERVICE: organised, coordinated activities fulfilling needs; an INTANGIBLE activity that solves a problem/gives value; customer interacts with a provider (person, product/system, or both). Many services run as systems. e.g., bank account, taxi, flight booking, tea at a café, IIITDMJ admission.
| Product | Service |
| I OWN it | I USE it, don't own |
| One-to-one | One-to-many |
| Designer controls it | Many actors; can't control all |
| Exists in isolation | Needs people, processes, partners |
| Value through the product | Value in EXPERIENCE over time |
- Becomes STRUCTURAL when it needs COORDINATION (many actors), CONTINUITY (over time), TRUST (mostly invisible) — healthcare, banking, government = large service systems.
- SERVICE CYCLE: ENTICE → ENTER → EXPERIENCE → EXIT → EXTEND (attract, orient, use, retain). Repetitive → CONSISTENCY + RELIABILITY, yet NOVEL each time; end-to-end and holistic, with human agents.

[FIG:fig/sd_000_24.jpg|The service cycle: entice → enter → experience → exit → extend]
# 1.2 Service design — definition and value exchange
- DEFINITION: planning and organising the PEOPLE, INFRASTRUCTURE and PROCESSES of a service so the experience is COHERENT for the customer and EFFICIENT for the business.
- Objective: more USEFUL, USABLE, DESIRABLE for clients; EFFICIENT, EFFECTIVE for organisations. Designs FRONTSTAGE with BACKSTAGE. Output: implementable designs (documents, mock-ups, metrics) + operational changes. People, PROPS (touchpoints), processes. Holistic — new and existing services.
- SD = UI + UX + IxD + CX + PD + Design Management. "These don't happen by chance; they have to be built in."
- Value exchange: provider gives money, labour, information, material, infrastructure, energy → SERVICE ← customer pays; value comes through EXPERIENCE. Approach: human-centred, collaborative, interdisciplinary, iterative (research, prototyping, visualisation).
- Examples: platform services (rides, delivery), consumer services (salon, gym, laundry, tutoring), India's 3-tier health system, e-commerce types (B2B, B2C, C2C, C2B, B2G), citizen–government layers (experience, touchpoints, delivery, foundations, mandate), community and business services (banking, insurance, transport, telecom).

# 1.3 Characteristics, risks, elements
| IHIP characteristic | Example |
| Intangible | Haircut, online class |
| Simultaneous production & consumption | Doctor's consultation |
| Heterogeneous | Two waiters serve differently |
| Perishable | Empty train seat lost |
- Risks in describing services: oversimplification, incompleteness, subjectivity, biased interpretation.
| Group | Elements |
| STRUCTURAL | Delivery system (blueprint, positioning); facility design (servicescapes, layout); location; capacity planning (queuing) |
| MANAGERIAL | Information (technology, scalability); quality (measurement, recovery, six-sigma); service encounter (triad, culture, outsourcing); capacity & demand (yield, queues) |
- Hundreds of UX points (dry cleaner's box too big for the Metro).

# 1.4 Five principles, commerce vs service, origin
| Principle (constraints, not a process) | Meaning |
| User-centred | From users' view, research not assumption |
| Co-creative | All stakeholders (frontline, backstage, IT, legal) participate |
| Sequencing | Sequence of interrelated actions over time |
| Evidencing | Make intangible visible (blueprints, maps, personas, prototypes) |
| Holistic | Whole ecosystem in scope |
- COMMERCE = transaction (pay → get goods); SERVICE = investing in the EXPERIENCE around it (friction with marketing/sales).
- Satisfaction = EXPECTATION vs EXPERIENCE: match → satisfied; less → dissatisfied; more → DELIGHTED (pre-service → service → post-service).
- Designing a service = aesthetics/front end, to please; SERVICE DESIGN goes "underground", aims at delight, reshapes operations and business model. Marketing sells (no personas); SD handles experience, creates personas, plans people, processes, touchpoints.
- Origin: LYNN SHOSTACK, 1982 HBR "How to Design a Service" — introduced the SERVICE BLUEPRINT. 1991 Köln school teaches SD; 2000s government, healthcare, finance.

# 1.5 SD vs UX vs CX vs PD vs DT; layers
| Discipline | Scope | Focus | Artefacts |
| Service design | End-to-end, channels, over time, backstage | Align front & back stage | Blueprints, journey & stakeholder maps |
| UX | One digital product/interface | Usability, interaction | Wireframes, prototypes, usability tests |
| Product design | Product features | Right product | Specs, prototypes |
| Design thinking | Mindset & process | Method | Varies |
| CX | Perception across all touchpoints | Measure & improve experience | VoC, NPS, journey maps |
- Outside-in: experiences → interactions → touchpoints → procedures → systems. Nesting SD ⊃ CX ⊃ UX ⊃ UI; strategic → operational: SD → CX → UX → IxD → UI.
- Layers: MACRO (social system, policy), MESO (organisation strategy), MICRO (person-to-person operations).
- Core tools: personas, journey maps, service blueprints, stakeholder & ecosystem maps, service prototypes.

[FIG:fig/sd_005_25.jpg|Service design ⊃ CX ⊃ UX ⊃ UI]
# 1.6 Ecosystem, skills, research areas, ITIL, mini project
- Ecosystem sets BOUNDARY CONDITIONS; too many variables for a math model. Inputs (politics, economy, expectations, regulation, societal needs, technology) → PEOPLE at centre surrounded by policy, technology & data, partners, institutions & culture, funding, operations → outcomes (value, performance, equity, trust, impact), inside shifting context (political cycle, markets, social, tech, environment, global events).
- Skill pyramid: high (education, knowledge services) → medium (business, health, trade, transport, public admin) → low (agriculture, manufacturing, HORECA). Skills decide cost; ROI higher in skilled services; scalable in numbers, geography, economic strata. Map external variables (SWOT).
- Research areas (Waseda): function realisation, provider–receiver interaction, service value, provider & receiver activities, provider environment, organisation science, system management, environmental factors.
- ITIL: service STRATEGY at centre → DESIGN → TRANSITION → OPERATION, wrapped in CONTINUAL IMPROVEMENT. CS meaning of "system design" = computer systems (OSI 7 layers).
- Mini project: pick-up laptop/phone repair service for Jabalpur institutions (team of 4, DT steps, refer IKEA Kitchen Planner).

# UNIT 2 — SYSTEMS (L3–L4)

# 2.1 System basics and modelling
- SYSTEM: interrelated components (subsystems) working to an outcome. INFORMATION SYSTEM: collects, processes, stores, outputs information for business tasks. Aggregation of objects with relationships between ATTRIBUTES. ENTITY = object of interest; ATTRIBUTE = property; STATE = description of entities, attributes, activities.
| System | Entities | Attributes | Activities |
| Traffic | Cars | Speed, size, direction | Driving, parking |
| Bank | Customers | Accounts | Withdraw, deposit |
| Inverter | Transformer, PCB, batteries | Voltage, frequency | Storing, converting |
- Types: natural, artificial, information. State pairs: complex/simple, chaotic/orderly, controlled/self-governing, adaptive/closed, static/dynamic, continuous/discrete. Whole > sum of parts.
- Levels: meta (universe; e-governance) → super (galaxy; search engines) → system (solar system; network clusters) → sub-system (earth–moon; LAN) → objects (earth; departments).
- MODEL = analogy + SIMPLIFICATION: user (persona, journey), physical (scale model), mathematical (queue equations). No unique model; designers may enrich visually. Attribute change → relationship change → whole system changes. OOP: objects in CLASSES with methods. BOUNDARY cuts links → input–output function.
- DETERMINISTIC (fully set by inputs — calculator) vs STOCHASTIC (probabilistic — delivery time). Most design systems are stochastic but users expect deterministic.

# 2.2 Characteristics, analysis, systems thinking
- Interrelated subsystems; FUNCTIONAL DECOMPOSITION; SYSTEM BOUNDARY; AUTOMATION BOUNDARY (manual vs automated/AI).
- System ANALYSIS = WHAT it should do; system DESIGN = HOW parts are implemented; ANALYST solves business problems with IT (design managers increasingly do this).
- Systems thinking: identify system, subsystems, functions, boundaries, inputs/outputs, relationships, data patterns/AI tokens. Enterprise layers: business → information → technology; UX at overlap of tech, business, design.
| Conventional thinking | Systems thinking |
| Cause obvious | Indirect, not obvious |
| Others to blame | We create our own problems |
| Short-term fix = long-term success | Quick fixes backfire |
| Optimise parts | Improve RELATIONSHIPS among parts |
| Many independent initiatives | Few coordinated sustained changes |
- Roots: systems theory (Bertalanffy), economics, sociology (Luhmann), ecology (Capra, Meadows), communication (Bateson), chaos theory (Mandelbrot, Prigogine). Example: college-gate traffic — fix timings, drop-off bay, not just blame drivers.
- Usability engineer (ISO) tasks: gather requirements; define usability goals; model interactions; design UI; heuristic evaluation, task analysis; test & certify quality; work with software teams.

# 2.3 Information systems and phases
- IS components: PEOPLE, PROCEDURES, DATA, SOFTWARE, HARDWARE. Supersystem: CRM (sales, accounts, product info, support) + finance + manufacturing + HR. Designer = front end; IT = back end; FULL-STACK developer integrates.
| Level (library) | User | Information |
| Strategic | Director | Budget, expansion, digitisation |
| Tactical | Librarian | Borrowing trends, losses, staff, orders |
| Operating | Clerk, student | Issue/return, notices, daily stats |
| IS type | Does |
| TPS | Records transactions (ATM withdrawal) |
| MIS | Reports from TPS for control |
| EIS | Strategic info for executives |
| DSS | "What if" decision support (AI-related) |
- Good IS: expandable, flexible, modular, secure, viable, common database, reliable, usable. Analyst skills: technical (computers, languages, networks, DBMS, OS, CASE) + business (processes, structure, culture). Job titles: analyst, system designer, architect · UX/IxD/HCI-AI designer, information architect.
| Phase | Activities |
| Planning | Problem, scope, feasibility, schedule, staff, launch |
| Analysis | Gather info, requirements, discovery prototypes, priorities, alternatives |
| Design | Network, interfaces, database, controls, design prototypes |
| Implementation | Build, test, convert data, train, install |
| Monitoring (services) | Feedback, metrics, course correction, firefighting |

# UNIT 3 — SERVICE DESIGN METHODS & TOOLS (L5–L6)

# 3.1 Field research and methodology
- Field data (maternity counselling ward): ethnography, interviews, co-creation, photo/media, field notes → sticky wall → MAPS & DIAGRAMS → system levels (clinic → municipality → insurance, national plans, NGOs).
- Methodology: real-world physical services → mapped, analysed, modelled → computing/virtual services → integrated → designed service system. L5–6 tools: personas, journey maps, blueprints, stakeholder/ecosystem maps, prototypes. L7–8: IS analysis, UML, OOP, JavaScript, Figma, AI tools.
- AI maps need ground-level data; IoT is a role for service designers; complexity mapped in LEVELS 1–5.

# 3.2 Personas and empathy map
- PERSONA: fictional profile of a user type — name, photo, demographics, goals, challenges, personality, motivations, channels. Gives focus, empathy, consistency, shared understanding. Built from research (survey, observe, find similarities). e.g., Maya Sharma 24 book blogger; Karan 20 engineering student.
- Lene Nielsen's 10 steps: collect data → hypothesis → accept hypothesis → number of personas → describe → situations → organisation acceptance → disseminate → scenarios → ongoing adjustment.
| Empathy map | Asks |
| Think & feel | Worries, aspirations |
| Hear | Friends, boss, influencers |
| See | Environment, market |
| Say & do | Public behaviour |
| Pain | Fears, frustrations |
| Gain | Wants, success measures |

# 3.3 Journey, story, ecosystem and stakeholder maps
- JOURNEY MAP: existing = how users experience now; new = how users must be guided, with emotions flowing positively. No standard format — tell a STORY visually. Steps: goals → research → empathy map → touchpoints & channels → team brainstorm → sketch → refine → share. Rows: stages, needs/activities, expectations, EMOTION curve, opportunities. (Booking.com guest experience map.)
- USER STORY MAP: time left→right; ACTIVITIES (backbone) → TASKS (walking skeleton) → STORIES by priority, sliced into RELEASES.
- ECOSYSTEM MAP (NN/g home buying: buyer at centre, family, agent, banks, inspector, builder, seller…). Assignment: campus ecosystem for a new student (hostel, mess, library, medical, bank, transport, etc.).
- STAKEHOLDER MAP (motivation / give-and-take matrix): roles and relationships; influence × interest quadrant; find partners and blockers; concentric (core staff → customers → constituents → suppliers, alliances).

[FIG:fig/sd_030_26.jpg|Ecosystem map — buying a home (NN/g)]
[FIG:fig/sd_031_27.jpg|Stakeholder map]
# 3.4 Service blueprint
- Maps tasks as they happen/should happen; deeper than a journey map; one persona, one journey; HIGH-altitude (overview) vs LOW-altitude (detailed management tool).
| Row | Restaurant |
| Physical evidence | Menu, table, bill |
| 1 Customer actions | Orders food |
| — line of interaction — | |
| 2 Frontstage actions | Waiter takes order |
| — line of visibility — | |
| 3 Backstage actions | Chef cooks |
| — line of internal interaction — | |
| 4 Support processes | Inventory, supplier |
- Extended (Izac Ross): quality measures, emotional journey, time, digital/devices, apps, data, partners. Legend: arrow across line = value exchange; direction = dependency; double arrow = agreement needed.
- 6 STEPS: identify process → customer segments → map customer view → map onstage/backstage/technology → link to support functions → add evidence at each step.
| Journey map | Service blueprint |
| User's experience: does, thinks, feels | Service behind it: processes, people, systems |
| Find experience opportunities | Find bottlenecks, improve delivery |
- TASK FLOWS link blueprint to back-end (first modelling skill): "find a service", "book a slot". Flowchart symbols: oval start/end, parallelogram I/O, rectangle process, diamond decision; SWIM LANES for many actors. Prototypes: storyboards, role-play, walkthroughs, co-creation.
- Figma design system (7): tokens → base components → variants/states → patterns → documentation → publish library → govern & scale. System-design awareness: latency/throughput, CAP theorem, load balancing, caching, sharding, replication, scaling; NGINX, Redis, CDNs, S3, Docker/Kubernetes, Kafka; microservices, circuit breaker; health checks, failover, monitoring.

[FIG:fig/sd_034_28.jpg|Anatomy of a service blueprint (Izac Ross)]
[FIG:fig/sd_035_29.jpg|Journey map vs service blueprint]
[FIG:fig/sd_040_30.jpg|Task flows: finding a service, booking a slot]
# UNIT 4 — SYSTEMS ANALYSIS & MODELLING (L7–L8)

# 4.1 Front end–back end, information modelling, where to start
- Integration: activity analysis → swim-lane work process → back-end workflow (e.g., username creation). AI calls these WORKFLOWS (tasks). Tools: checklists, top-down analysis, grid charts, decision tables, system flowcharts, DFDs, CASE.
- Modelling steps: collect data → identify components, entities, attributes, activities → structure & relate. Two methods: IS MODELLING (detailed real-world analysis — designer's strength) and UML (direct entry to OOP); knowing both = easy "handshake" with CS teams.
- Block diagram: INPUT → PROCESS → OUTPUT with goals, feedback, controllable/uncontrollable factors; system map = nodes + connections.
- Start on the FIELD with users and context; understand the organisation (strategy, vision, goals); functional chart (CEO → marketing, purchase, finance, personnel managers).
| Information level | Who | Nature | Example |
| Strategic | Top management | Condensed, unstructured | Open new branches? |
| Tactical | Middle | Summarised | Vendor rating, stock levels |
| Operational | Line managers | Detailed, structured | Reorder list, daily ledger |
- Data sets → database → tables; designer visualises information hierarchy at CEO level.

[FIG:fig/sd_040_31.jpg|Integrating front end with back end]
# 4.2 Context diagram, DFD, levelling, rules
- Notations: context diagrams, document flow diagrams, DFDs, E-R diagrams.
| DFD element | Symbol | Rule |
| Process | Circle/rounded rectangle | Number + verb name; ≥1 input & output |
| Data flow | Arrow | Noun name |
| Data store | Open rectangle "D1" | Number + noun |
| External entity | Square | Noun |
- Document flow (offices passing paper) → LOGICAL DFD (processes + stores) by iteration; designers must get this right (handshake with back end).
- CONTEXT DIAGRAM = FIRST step: whole system as ONE process (process 0) + all external entities; draws the boundary. Mess management: students (rebates/payments ↔ bills), vendors (requisitions ↔ supplies, payments), mess secretary (rate, menu), chief warden (overdue bills), mess manager (daily items).
- LEVELLING: expand process p into p.1…p.n (1 Billing → 1.1 daily rate, 1.2 student bills, 1.3 reconcile, 1.4 meals; 2 Stores; 3 Perishables). New external entity must be added at context level.
- KEY DFD RULES: no pure-decision process · no loops · no crossing lines · top-down from context · DATA CONSERVED (process transforms, never creates) · data read from a store must have been written · data can't trigger processes · DFD ≠ flowchart (no sequence/decisions) · no flow between two external entities · numbering p.1…p.n · flows in/out preserved when levelling · new stores may appear lower down · NO NEW EXTERNAL ENTITIES when levelling · ≤ 7 processes per level · every process ≥ 1 input & 1 output.
- Small example: Vendor → invoice → "stores issuing approval" (check delivery) → approved bill → Accountant; updates inventory register. Questions: many vendors, same names, multiple invoices?
- Analysis steps: requirements → study current system → physical document flow → derive logical system → current logical DFD → new system model (feasibility) → new logical DFD + rules + DATA DICTIONARY.

[FIG:fig/sd_050_32.jpg|Context diagram — mess management system]
[FIG:fig/sd_050_33.jpg|Expanded DFD for the hostel mess]
# 4.3 Hostel billing case, E-R, UML, AI, 7 steps
- Hostel billing: blueprint at level 0 (personas/journey or storyboard) → info sources (users; forms, receipts, registers; admin tree: chief warden → wardens → mess secretary, manager, accountant, store keeper, cook; rule books; hardware/software) → document flow → three teams: PURCHASE (daily/occasional/bi-weekly buys → verify → monthly payment), MESS ACCOUNTS (extras, rebates → daily rate → bills → receipts → overdue), STORES (menu → issue items → stock register → reorder) → logical DFDs → context → levelling.
| E-R element | Symbol | Meaning |
| Entity | Rectangle | Noun (Vendor, Item, Order) |
| Relationship | Diamond | Verb (supplies, placed with) |
| Attribute | Oval | Property (vendor code, qty) |
- DFD focus = PROCESSES; E-R focus = DATA. CARDINALITY 1:1, 1:N, N:M. Used for database design, information architecture and UI screen sequences (burger → fries? → drink? → pay). Advanced attribute types/EER = IT experts.
- UML: use cases = ovals; actors = stick figures (college registration, ACME bank — "insufficient funds" extends withdraw). OOP chart: classes with attributes and links.
- AI: non-agentic (input → LLM → output) vs agentic (plan, tools, evaluate, revise) vs AI agents (goal → plan → act → evaluate → feedback). Patterns: multi-agent, self-reflection, tool use, CodeAct, agentic RAG, ReAct. LLM: tokens → embeddings → transformer → prediction.
- SYSTEMS APPROACH (7 steps): (1) define THE problem; (2) understand & define the system (entities, boundaries, activities); (3) find variables; (4) relate variables; (5) choices to improve; (6) costs (ROI + ROB) and risk; (7) reconfigure components. e.g., laptop pickup: downtime → loaner pool, daily pickup route, app booking.

[FIG:fig/sd_052_34.jpg|E-R diagrams: entity, relationship, entity]