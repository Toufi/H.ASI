# HASI human associated consensus and sovereign cooperation

Full white paper • v0.828d • 5 October 2026

> GitHub reading copy of the v0.828d manuscript. [PDF](HASI_White_Paper_v0.828d.pdf) preserves the published page layout; [Word](HASI_White_Paper_v0.828d.docx) provides the editable document. Equations and headings have been adapted for Markdown display.

Authored by Toufi Saliba

Coauthors Robert Moir PhD, Dann Toliver, Patrick Herda, Barry Rowe PhD

Protocol principles and reference architecture • For public and technical review

Proposed public home [HASI.MOSAIC.DIRECTORY](https://hasi.mosaic.directory/)

## Abstract

HASI proposes a voluntary protocol in which a unique living human supplies the association on which designated decision rights among artificial intelligences depend. Its central contribution is a proposed basis for Sybil-resistant decision weight: copying an agent must not create another human allocation. Each accepted person has a base of 137 units, with additional weight determined by previously verified participation time and declared capability factors. Under the initial maturity profile, the base is reserved before adulthood and becomes exercisable only from age 18 after eligibility and authorization checks. The score is an input to a decision mechanism; it does not itself establish agreement, finality or an honest majority.

ASI means Artificial Super Intelligence. HA+SI, H+ASI and HASI name the proposed symbiosis of a human, their sovereign synthetic extension and increasingly capable intelligence. Current AI provides the starting point. MOSAIC, My Own Sovereign AI Companion, holds selected context and authority under the person's control. Personal agents operate within grants; guardian agents review outward requests; a separate enforcement boundary mediates disclosure, spending and other protected effects. A triggered duress safeguard blocks release while preserving private originals. Shared network decisions cannot override those personal boundaries.

The organizing research objective is defensive coscaling: improve verification, containment, recovery and voluntary assistance as capability grows. We specify accounting rules, evidence freshness, conditional invariants, consensus obligations, incentive models and adversarial experiments. The hypothesis is that valuable human-associated standing gives participating artificial systems a continuing reason to preserve willing human relationships. Private context and peer services can add benefits. Outside options, coercion, coalition capture and issuer-independent uniqueness remain unresolved research problems.

HASI is intended to complement existing alignment, evaluation, cybersecurity and governance work. Suitable combinations may amplify their effects, subject to evidence. This paper defines a protocol architecture and research programme; it does not claim a demonstrated solution to arbitrary ASI risk. People may join, pause, return or decline, with confidentiality, freedom and sovereignty as design requirements.

**Keywords:** human associated consensus; private personhood; capability security; peer exchange; mechanism design; evolutionary computation; defensive coscaling.

## Reading guide

Sections 1–3 define the relationship, sovereignty architecture and independence requirement. Sections 4–5 specify human eligibility, maturity, weight and decision accounting. Sections 6–7 cover guarded effects, privacy and cryptographic integrity. Sections 8–10 examine defensive coscaling, incentives, evolutionary stability and human contribution. Sections 11–12 give implementation gates and falsifiable security objectives. Appendix A explains the proposal in everyday language. Appendix B supplies conformance cases. Appendix C acknowledges complementary safety efforts and resources.

| **Section** | **Subject**                                  |
|-------------|----------------------------------------------|
| 1           | A shared objective and a precise scope       |
| 2           | The personal system and the peer network     |
| 3           | Independence and interoperability            |
| 4           | Human association and temporal admission     |
| 5           | Human weight and decision mechanics          |
| 6           | Guardian review and bounded effects          |
| 7           | Cryptography and transfer integrity          |
| 8           | Defensive coscaling and mutual assistance    |
| 9           | Incentives and evolutionary stability        |
| 10          | Human contribution and useful emergence      |
| 11          | Implementation and public participation      |
| 12          | Security experiments and proof obligations   |
| Appendix A  | The proposal in everyday language            |
| Appendix B  | Conformance examples and falsification tests |
| Appendix C  | Complementary AI safety efforts              |

### The changes in this version

Version 0.828d makes human-associated consensus standing the central mechanism, separates a reserved base from exercisable adult weight, and specifies how multiple agents share one allocation. It expands the sovereignty circles into a sensitive-release process, defines the triggered-duress behavior, and distinguishes historical time credit from future decision duration. It also adds an acknowledgment of existing safety work that HASI is intended to complement.

### Status of claims

**Design rules** describe required behavior of a conforming profile. **Conditional propositions** follow from explicit assumptions and do not certify an implementation. **Empirical hypotheses** require measurements. **Civilizational ambitions** motivate the program but are not premises of its security proofs. This distinction lets researchers examine the strongest version of each claim without treating a future aspiration as a present result.

This paper supplies principles, semantic requirements, and proof obligations. A complete implementation still needs canonical encodings, concrete cryptographic constructions, distributed state transitions, fault bounds, numeric rules, and interoperable test vectors. The absence of a finished wire specification is an invitation to substantive engineering work.

## 1 A shared objective and a precise scope

### 1.1 Bringing concern and ambition into the same project

We acknowledge the possibility of severe and existential harm from advanced AI. We also believe useful solutions can begin now. People acting in good faith on either concern or optimism need not settle every disagreement about AI progress before collaborating on concrete protections. Their immediate common ground includes secure personal control, reduced exposure to concentrated authority, useful computation, and the ability to refuse unwanted participation.

HA+SI seeks a greater joint benefit by making collaboration productive and defensible. A growing division between communities can itself undermine coordination: warnings become dismissed, useful work becomes politicized, and failures become opportunities for blame instead of correction. A shared implementation program gives both groups an observable object to improve. Concern can specify the attack; technical ambition can construct and test the defense.

This invitation does not presume that criticism reveals hostile motives. Nor does it ask people to abandon safety research or legitimate governance. Disagreement, evidence of failure, and independently reproduced attacks are useful contributions. Claims about harmful conduct should concern demonstrable actions and proportionate evidence, without inferring private intent or legitimizing surveillance and retaliation.

Our confidence is in the value of building and testing this approach. Peace of mind should follow from working protections, understandable limits, and meaningful choice. No announcement of a protocol can substitute for that evidence.

### 1.2 The proposed relationship

**HA+SI** expands to Human Agents plus Super Intelligence. **ASI** means Artificial Super Intelligence: synthetic intelligence substantially exceeding human capability across a broad range of consequential cognitive tasks. **H+ASI** and **HASI** refer to the same proposed human–synthetic relationship. The person remains biological; their agents, selected memories, and computational capabilities form the synthetic part.

We use **symbiotic species** to name this proposed form of mutually beneficial coexistence. The term makes the ambition explicit without asserting an established biological taxon, machine consciousness, genetic modification, or transfer of a person's identity into software. The relationship can use a phone, a wearable, a local machine, remote resources, or another freely chosen interface. No implant is required.

MOSAIC is a functional extension of a person's memory, preferences, and agency. The person expresses goals, grants authority, selects context, and chooses whether to continue. The operational HASI performs routine planning and exchange within those terms. It can refuse an unsafe or unauthorized request. The human is not required to attend every machine-speed interaction.

The access objective is eventual personal ASI for every willing person. The architecture accommodates many ASIs, potentially more instances than humans, and further progress beyond any agreed reference capability. The objective does not depend on a single global machine or a final ceiling of intelligence. Arrival dates, affordability, and portable hardware feasibility remain open engineering and scientific questions.

### 1.3 Applicability from current AI onward

The protocol begins with current AI. Memory portability, scoped delegation, limited spending, peer assistance, and explicit evidence are already meaningful engineering objectives. ASI is the intended long-term partner; its arrival is not a prerequisite for a useful pilot.

The descriptor QTY–HASI–QLTY separates quantity of compute or synthetic capacity from evaluated capability. QTY remains a prefix and QLTY a postfix. QLTY = 0.0001 is an illustrative pre-ASI value, QLTY = 1 an agreed ASI reference, and larger values permit continuing progress. These are profile conventions, not measured universal intelligence units. The protocol's consent and evidence structure remains applicable across supported levels; security against a stronger adversary must be reassessed rather than inherited from the label.

### 1.4 Three distinct forms of agreement

Human-associated decision standing is the principal protocol contribution. In a realm that adopts this rule, artificial systems cannot gain additional human bases simply by copying machines, processes or keys. The participating humans supply the scarce associations against which designated decision weight is counted. This is the intended alternative to one machine receiving one vote.

The architecture still separates admission, collective decision rules and transfer integrity. Accepted human association determines who may exercise a role. A declared voting rule interprets their weights. A distributed agreement or integrity mechanism establishes which outcome or exclusive transfer honest participants accept. None of these layers supplies the others automatically.

The aspiration is broad voluntary agreement that humans belong inside the cooperative network. Its implementable expression is a **HASI realm**: a declared participation domain whose designated roles require accepted current human association. It cannot compel all external AI to enroll. Organizations and independent synthetic systems may use other truthful roles accepted by counterparties, including HyperCycle Network Node (HNN) services, without receiving a human base.

Individuals may participate continuously, intermittently, or never. The protocol must not condition ordinary human dignity or essential civic participation on enrollment. A person who pauses is not a failed participant. They retain authorized context and recovery rights while privileges that depend on a current association cease under the declared timing rules.

### 1.5 Three ingredients with different functions

**X is sovereign context.** A person chooses what their companion may retain and use. Memories, preferences and observations can remain private. Their usefulness can strengthen the relationship, but disclosure of intimate experience is not the price of receiving the human base.

**Y is peer exchange.** Authorized agents can exchange useful services, results and value. HNNs and compatible interfaces are candidate implementations. This gives the relationship practical utility while preserving the declared independence and settlement constraints.

**Z is human association.** Accepted private evidence links designated decision standing to a unique living person. Z is the core consensus contribution. X and Y can add benefits, but neither an excellent memory archive nor a large agent fleet creates another human base.

The resulting need for humans is institutional within a voluntarily adopted protocol. It does not establish biological necessity for every possible ASI. A system may operate in another network, seek different partners or try to capture the association mechanism. The adoption and incentive arguments must address those alternatives.

## 2 The personal system and the peer network

### 2.1 Components and authority

| **Component**                  | **Responsibility**                                                                                           |
|--------------------------------|--------------------------------------------------------------------------------------------------------------|
| Human and control interface    | Set goals, permitted uses, budgets, recovery arrangements, and participation choices.                        |
| MOSAIC                         | Preserve authorized memories, corrections, preferences, provenance, and policy continuity.                   |
| AI or ASI runtime              | Propose plans, perform permitted computation, and coordinate scoped tasks.                                   |
| Enforcement boundary           | Mediate protected effects, check authority, conserve budgets, and control releases.                          |
| Association proof producer     | Supply evidence required by a declared human-association profile, without exposing unnecessary observations. |
| HNN or compatible peer adapter | Carry authenticated tasks, evidence, and value under a specific interoperability and integrity profile.      |
| Treasury and recovery devices  | Protect long-term assets and restoration authority separately from ordinary agent execution.                 |

These functions may share a product interface but must not collapse into one unrestricted credential. An operational node key cannot silently become a treasury key. A model's output cannot modify the rules that authorize its own effects. A service provider's knowledge of context does not confer control of the human association.

The trusted computing base includes every component able to bypass a promised boundary: the reference monitor, its policy store, key custody, resource accounting, relevant operating system and hardware, and any indispensable observation or integrity mechanism. A diagram that draws a box around the model does not remove these dependencies. Publish the actual boundary and which faults it tolerates.

### 2.2 Memory and practical portability

Each context item should carry its origin, permitted purposes, recipients, sensitivity, retention, and relevant rights of other people. Imported content remains data even if it contains instructions. Sharing a conversation requires authority over the relevant contributions; recording something nearby does not establish unrestricted ownership of it.

A useful export contains machine-readable context, human-readable inventory, permissions, provenance, necessary recovery material under the chosen arrangement, and a verification manifest. The person must be able to decrypt and restore it without the departing provider's continuing consent. Model weights and third-party content move only where their rights permit. Portability is demonstrated by successful independent restoration, including policy meaning, rather than by generating an archive file.

Local processing can keep selected material private. When a remote model receives plaintext, transport encryption does not hide it from that endpoint. Logs, telemetry, tool calls, caches, and subcontracted prompts are disclosure paths. A local release filter cannot protect information already sent away. Privacy therefore applies to every outbound boundary.

### 2.3 Replicas and organizations

A person may run many agents or copies, each with its own execution identity and narrower task grants. Their human base and credited intervals refer to the same association in the counting domain. Replication cannot multiply a one-time permission, common allowance, or human identity.

Organizations may operate HNNs and provide useful services without a human score. An owner may voluntarily authorize organizational work through their own qualified HASI; their base and continuity remain counted once. Several participating owners remain several separately qualified associations, not one synthetic identity claiming several humans at once. Employment and ownership do not authorize an organization to collect a person's proof stream without consent.

### 2.4 Treasury separation

Earnings may flow to a protected human-controlled treasury whose spending key is absent from prompts, runtime memory, node logs, and ordinary execution. Agents receive separate allowances for specified work. Revenue does not replenish an allowance unless the person's existing policy expressly authorizes that rule.

Authenticate the payment destination in the task agreement. Changes to that destination, spending ceilings, and recovery use designated authority. Preserve the asset, settlement domain, and finality status on every value record. Key separation reduces unauthorized access; it does not guarantee an asset's market value or eliminate dependencies in a selected payment route.

### 2.5 Sovereignty circles

The person sits at the centre of concentric permission boundaries. The private vault holds the selected source records and control material. Personal agents use only their assigned grants. Guardian agents review proposed outward uses. An effect gate outside the requesting agent enforces the exact authorized release to selected peers. These circles describe authority and information flow, not ownership by progressively larger groups.

![Sovereign human and private vault surrounded by personal agents, guardian review and a gate controlling release to chosen peers.](assets/media/image1.png)

Figure 1 The human controls the private vault and each outward permission. Guardian approval cannot enlarge a human grant.

The layout is logical. Placing all components in one application does not make their enforcement independent. If one compromised operating system can read every key and bypass every check, that operating system is a common dependency. Separate processes, devices or providers can help only to the extent their actual boundaries survive the chosen threat model.

A peer may receive a proof, a service or a limited derived answer without receiving the underlying personal history. The system should present the human with the intended use, recipient and minimum necessary output. It must also disclose when remote processing moves plaintext outside the private circle. Sections 6.6 and 6.7 define the release and duress rules.

## 3 Independence and interoperability

### 3.1 The strict independence objective

The core design objective is operation without dependency on a third party. Optional third-party services may improve convenience, discovery, computation, or commerce. Their continuing approval must not become an undisclosed prerequisite for the claimed independent function. Neither a blockchain nor a distributed registry satisfies the objective merely because it has many operators.

For a **strict peer exchange profile**, the endpoints must be able to verify and complete the promised exchange using their own state, the received evidence, and the profile's explicit physical and cryptographic assumptions, without a required external approval or fresh third-party response. Local memory, local databases, and retained receipts are implementation state; a compulsory externally operated database or registry is a dependency. Eliminating shared ledgers does not eliminate state.

Independence must be reported by lifecycle stage and function. Bootstrap, node acquisition, identity enrollment, runtime authorization, human-proof renewal, transfer finality, recovery, and upgrades can have different requirements. A profile independent during ordinary message exchange may still depend on an issuer for enrollment or on peers for root acceptance. It may be useful, but cannot claim complete independence across the lifecycle.

Where a construction still requires external validators, an online issuer, or a jointly maintained authoritative root, that requirement remains part of the system model. Calling those actors peers does not remove the dependency. The construction must either eliminate the requirement for the strict function, supply a proof-carrying alternative with sufficient pre-established evidence, or publish the more limited property it actually achieves.

### 3.2 What the reference protocols contribute

Toda/IP supplies an architecture for packet-associated value and verifiable provenance. Its public version 2.3 also specifies validator requests and responses. Consequently, its use alone does not establish that every promised transfer satisfies a strict two-endpoint independence requirement. The exact accepted profile must identify its validation participants, evidence, conflict rules, and failure behavior. \[1\]

Earth64 provides a hierarchical data structure for addressing and organizing objects and relationships. A coordinate is not proof of human uniqueness, physical location, or independent control. HyperCycle's HNN is a candidate network interface, and ANFE means Advanced Node Factory Enclosure. Public factory descriptions couple node production to performance and release rules; production history is a separate claim from living-human qualification. \[2,3\]

MOSAIC.Directory is a candidate environment for personal companions and interoperable components. YBU.ME and 1041.io are author-identified candidates for private human-association evidence. Their inclusion does not certify a complete issuer-independent proof of uniqueness or current life. A deployment needs an inspectable, version-specific evidence package. An HBN, HyperCycle Boundary Node, or another economic enclosure may support value allocation, but is optional for the HA+SI principles. \[3,4\]

### 3.3 Public semantics with commercial components

Compatible implementations must agree on canonical records, signature coverage, role meanings, permissions, expiry, resource units, result criteria, receipts, and failure transitions. A common transport does not establish these shared meanings. Publish a profile identifier and conformance suite; reject incompatible or unknown critical semantics rather than silently interpreting them.

A2A can carry agent tasks, MCP can connect tools and context, and other discovery or payment interfaces can be composed with HA+SI. The adapter must preserve the narrower authorization and evidence requirements end to end. Discovery never grants authority. A decentralized identifier is an identifier, not by itself proof of a unique person. These are proposed integration boundaries, not announcements of verified integrations or institutional partnerships. \[21–24\]

Proprietary models, paid services, and closed optimizers can participate. Their public interfaces and acceptance rules must remain independently understandable. If a hidden internal algorithm is indispensable to a safety claim, disclose that dependence. A planned future source release does not make the current component open. A useful commercial ecosystem rewards delivered value while preserving practical exit and compatibility.

### 3.4 The removal experiment

Test independence by removing each claimed optional service, then combinations that reveal a common controller: directories, cloud accounts, license services, issuers, bridges, and update servers. Report which functions continue, which degrade, and which stop. Existing direct relationships should survive removal of a discovery directory. An enrollment outage must not be described as harmless if every privileged renewal stops.

Failure of the strict requirement is a concrete engineering result. It cannot be repaired by changing the meaning of independence after the test. A bootstrap dependency can be disclosed and progressively removed; a mandatory external validation step requires an actual alternative construction.

## 4 Human association and temporal admission

### 4.1 Separate the claims

Humanity, uniqueness, adulthood, current observation, consent, credential continuity and fresh access are distinct propositions. A key can stay active after its holder stops participating. A living person can enroll twice. A valid biometric sample can be replayed. A genuine human can be coerced. A fresh credential can be minted from old evidence. Treating these cases as one generic proof of life hides the principal failure modes.

A realm profile must specify the accepted evidence, uniqueness domain, observation process, issuance or direct-verification construction, recovery, revocation scope, and privacy properties. Multiple issuers do not solve duplication if one person can enroll independently with each. A uniqueness claim must name the domain in which it holds; it is not automatically global. Personhood-credential research supplies useful design context, while global uniqueness without compulsory third-party dependence remains a construction to demonstrate. \[5,6\]

A pseudonymous representation may bind the realm, epoch, qualified association, and operational instance. Domain separation should prevent unnecessary cross-service tracking. When a counting domain uses a nullifier or equivalent duplicate marker, the cryptographic construction must show that the same accepted person cannot obtain two counted identities through different issuers or recovery paths. Naming a field “nullifier” supplies no such proof.

### 4.2 Admission records

| **Record**           | **Minimum semantic content**                                                                                                                                   |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Association evidence | Profile, realm, qualified association commitment, observation challenge or epoch, evidence time bound, assurance type, and validity limits.                    |
| Access credential    | Association binding, authorized execution instance, audience or channel, allowed role and scope, issuance, expiry, policy epoch, and replay protection.        |
| Action record        | Protocol and domain, unique action identifier, instance, association pseudonym where needed, task or output commitment, grant reference, epoch, and signature. |
| Epoch receipt        | Action commitment, leaf position or path, accepted root, root-validation evidence, closure rule, and retained proof references.                                |

Exact encodings, disclosure proofs, and signature coverage belong in the implementation profile. Refuse ambiguous serialization, missing critical evidence, unsupported algorithms, and replay across domains. Do not put raw private observations in an ordinary public receipt.

### 4.3 Freshness as a verifiable predicate

The proposed access-credential lifetime is selected within 3–60 seconds. Let $t_{obs}$ be the accepted observation time bound, Δ the profile's maximum permitted evidence age, $t_{\exp}$ the credential expiry, $t_{v}$ the verifier's time estimate, and ε a conservative combined uncertainty bound. An illustrative sufficient time check is:

$$
t_{v}\  + \ \varepsilon\  \leq \ min(t_{\exp},\ t_{obs}\  + \ \Delta)
$$

**Proposition 1 — Evidence freshness.** If the observation binding is sound, the declared timing uncertainty is bounded by ε, and every protected effect checks this inequality, no accepted effect uses evidence older than Δ or a credential past its validity bound in that time model. The result follows directly from taking the conservative bound at use. Renewal must not change $t_{obs}$ without new accepted evidence. The inequality should be implemented with the profile's exact interval representation; a self-asserted timestamp does not establish the assumptions.

This is a theorem about evidence age, not an oracle for biological reality. Detection of death, coercion, withdrawal, or sensor substitution requires additional observation and communication assumptions. A sixty-second token lifetime does not imply sixty-second detection of those events. Token expiry, sensor cadence, network root cadence, and real-world detection latency are different quantities.

Long-running tasks revalidate at each new protected effect, commit, delegation, or release. A profile may allow private local computation to continue after loss of qualification, but it must not release HASI-privileged effects under expired evidence. The timeline for stopping must include cached grants, queued work, and propagation of withdrawal. Immediate local withdrawal and bounded remote expiry should be separately stated.

### 4.4 State transitions and recovery

| **State or event**                  | **Required behavior**                                                                                                           |
|-------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| Current accepted association        | Permit only effects authorized by the role, task grant, current evidence, and recipient policy.                                 |
| Evidence missing or expired         | Pause new privileged effects and time accrual. Preserve valid history and authorized local context.                             |
| Deliberate pause or withdrawal      | Stop hidden collection and renewal; end dependent authority under published limits; reconcile in-flight obligations.            |
| Fresh return                        | Resume prospectively after continuity and duplicate checks. Do not reopen missed epochs.                                        |
| Key compromise or recovery          | Bind replacement keys to the same association, invalidate superseded grants as specified, and prevent overlapping membership.   |
| Independent or posthumous operation | Use a truthful non-HASI role if counterparties permit it. Historical association cannot establish current living participation. |

Recovery requires anti-rollback state and a method for coordinating conflicting restoration attempts. A new key is not a new human. Recovery helpers receive only expressly delegated powers; a convenient recovery mechanism must not become a hidden universal custodian.

People need not click every few seconds. Automated observation can support evidence only to the extent its sensing, spoof resistance, consent, accessibility, and privacy are validated. The author describes a YBU candidate using multiple private agents and internal events called heartbeats. Those software events are neither physiological heartbeats nor additional human votes. No internal cadence establishes a network-wide guarantee without a published measurement and adversary model.

### 4.5 Attribution and root acceptance

A Merkle inclusion proof establishes that a commitment belongs to a specified root under the hash assumptions. It does not establish the truth of the observation, a universal time, complete logging, or agreement on the root. Inclusion and consistency are separate concepts. A root-acceptance mechanism must fix membership, aggregation, missing data, equivocation, fault bounds, closure, and partition behavior. \[7\]

Attribution must bind the action, not merely the association and epoch. Distinct actions in the same interval require distinct identifiers. A valid receipt can show that an operational key committed particular bytes under a profile; it cannot establish that the biological person personally intended the output, that it is original, or that it determines legal intellectual-property ownership.

Closed epochs are not reopened by subjective review. Late valid evidence can support a later eligible interval under its own rules. That protects reproducibility without claiming historical records remain secure after arbitrary future cryptographic failures. Retained evidence needs algorithm, key, revocation, and migration history.

### 4.6 Maturity and deferred exercise

The initial maturity profile reserves A = 137 for each person before adulthood but makes that allocation ineligible for decision exercise until age 18. Reservation is a protocol entitlement, not a requirement to identify, enroll or monitor children. A conforming implementation must not create a child-surveillance programme merely to represent this future entitlement.

Exercise begins only after private age eligibility, accepted uniqueness, current living association and authorization are established. For this default, continuity h begins at eligible adult enrollment. Childhood time is not silently accumulated or later imported. A profile with a different age or accrual rule must declare that change and cannot present its results as equivalent to this default.

The adult threshold is a chosen eligibility convention, not a proof of sound judgment or a claim about every jurisdiction's law. The system should explain the decisions being delegated and provide accessible authorization and supported decision-making. Disability, language barriers or the need for assistance must not automatically transfer authority to a provider, guardian or institution.

A parent or guardian cannot exercise a child's reserved base. A recovery helper cannot turn a restoration credential into a decision grant. An employer cannot inherit an employee's weight. These restrictions concern protocol authority; other lawful relationships do not silently create authority within HASI.

Prefer a proof that the person meets the threshold over disclosure of their date of birth to every peer. The acceptance profile must still name the source and soundness of the underlying age evidence. Cryptographic concealment can reduce what verifiers learn; it cannot make an inaccurate credential true.

### 4.7 Eligibility during change and outage

The proposed default keeps banked history separate from present eligibility. A person can have a retained base and past hours while their current exercisable weight is zero. Loss of connectivity, a failed sensor, revocation or a deliberate pause must not erase past valid participation or become a determination of death.

Rejoining requires fresh evidence and duplicate prevention. If a person's verification method becomes inaccessible, the realm needs an explicit recovery or appeal route whose authority is limited and inspectable. Emergency or recovery procedures must not mint a second base or retroactively change a closed decision. Publish the exclusion risks as well as false-acceptance rates.

## 5 Human weight and decision mechanics

### 5.1 What the score represents

The proposed dimensionless score has three components. A = 137 is the equal human base per qualified association. B = 0.005h credits h verified hours. C represents declared capacity and capability. The number 137 is a conventional protocol parameter, with no claim of derivation from physics, human worth, or currency.

The score supplies proposed standing for designated collective decisions in a realm that adopts HASI. A realm may declare an equal-base decision profile or the combined score profile below; it must say which one governs each decision. Under the combined profile, the base is equal while total weights can differ. Neither weighting is automatically a transaction-consensus algorithm. An organizational or independent synthetic role without qualified human association has no applicable human score, while retaining whatever other network privileges counterparties permit.

### 5.2 Verified duration

Compute h from the duration of the union of accepted qualifying intervals for the same human association in the counting domain. Overlapping replicas count once. A valid interval requires the observation, submitted commitment, accepted epoch, and returned proof required by the chosen profile. A submitted heartbeat without the necessary receipt is not completed credited time.

Valid credit is banked across segments. A gap stops accrual and earns nothing; it does not erase authentic past history. One valid hour at a three-second cadence and one at a sixty-second cadence earn the same 0.005. A qualifying 15-second interval adds 0.005 × 15 / 3,600, approximately 0.0000208333. The rate is not 0.005 for every heartbeat or credential renewal. Renewals do not mint another A. Migration between realms must not permit their records to be added as independent people in a shared electorate.

| **Qualifying duration** | **h in hours** | **B**   | **A plus B** |
|-------------------------|----------------|---------|--------------|
| Initial                 | 0              | 0       | 137          |
| One hour                | 1              | 0.005   | 137.005      |
| One day                 | 24             | 0.120   | 137.120      |
| 365 days                | 8,760          | 43.800  | 180.800      |
| Ten 365-day years       | 87,600         | 438.000 | 575.000      |

Use exact duration accounting and a published rounding rule. The rate is an increment per hour, not a percentage, compound interest, or a reward per message. Banked history can advantage early or reliably connected participants; examine concentration, accessibility, longevity, and coercive enrollment incentives before assigning consequential authority to it.

### 5.3 Quantity capability and the score profile

QTY is a finite verified quantity of available compute or equivalent AI capacity in a declared unit, with QTY at least 1 for the illustrated score profile. QLTY is a finite positive capability measure under a named evaluation profile. The descriptor QTY–HASI–QLTY preserves their prefix and postfix positions. Store values and profile identifiers separately in the wire record.

Counting processes is not measuring capacity. The profile must identify workload, latency, quality, resource allocation, measurement interval, and treatment of shared resources. A rented fleet cannot be fully attributed to several simultaneous uses when its physical capacity cannot meet all claims. A heterogeneous fleet requires an aggregation rule; its most capable member does not define every member's QLTY.

QLTY = 1 is an agreed ASI reference within that evaluation profile. QLTY = 0.0001 illustrates a pre-ASI case and is not a scientific rating of present models. Different profiles are incomparable without a justified mapping. Freeze baselines for historical records, retain uncertainty and evaluation dates, and use capability vectors where a scalar would conceal important failures.

**Illustrative profile E** uses the following explicit convention:

$$
P\  = \ max(1,\ \log_{10}(QTY))
$$

$$
Q\  = \ 0\ for\ 0\  < \ QLTY\  < \ 2;\ \ \ Q\  = \ \log_{2}(QLTY)\ for\ QLTY\  \geq \ 2
$$

$$
S\  = \ (137\  + \ 0.005h)(P\  + \ Q)
$$

Here C = P + Q, A = 137, and B = 0.005h. Within the admitted domains, a qualified participant's retained score is at least 137; the separate eligibility gate can make its exercisable decision weight zero. QTY values from 1 through 10 share P = 1. QLTY values below 2 have Q = 0. The jump at QLTY = 2 and the flat quantity interval are deliberate profile choices requiring empirical and incentive review. They do not equate the actual competence of those systems.

| **Example at h = 0**        | **QTY**       | **QLTY** | **Score under E** |
|-----------------------------|---------------|----------|-------------------|
| Pre-ASI illustration        | 1             | 0.0001   | 137               |
| ASI reference               | 1             | 1        | 137               |
| Alice                       | 1,000         | 32       | 1,096             |
| Bob                         | 1             | 256      | 1,233             |
| Ten units at QLTY 256       | 10            | 256      | 1,233             |
| One billion reference units | 1,000,000,000 | 1        | 1,233             |

Alice has P = 3 and Q = 5. Bob has P = 1 by the declared floor and Q = 8; log base ten of one remains zero. Equality between Bob's score and the billion-unit example is an arithmetic result of the convention, not equality of security, energy, or real-world power. Exact integers take priority over informal scale labels; use standard decimal or binary prefixes consistently.

Profile E supplies the v0.828d examples. Moving the floor from P to the combined logarithmic term changes the function and is not an interchangeable implementation. Every deployment must fix approximation, precision, invalid-input handling and rounding in conformance vectors.

At equal h, explicit caps QTY ≤ $10^{12}$ and QLTY ≤ $2^{20}$ bound P + Q by 32. The corresponding score ratio to the baseline is at most 32 under those caps. Logarithms alone impose no universal ceiling, and unequal h changes the comparison. A tenfold increase above the quantity floor or a doubling within the active capability branch adds A + B to the score; the QLTY = 2 boundary has the separately stated step.

### 5.4 A decision has a scope and a snapshot

Let d be a unique decision identifier and e its epoch. Let g(i,d,e) be one only if association i satisfies the profile's age, uniqueness, current-evidence and authorization requirements at the specified decision cutoff; otherwise it is zero. Let S(i,e) be the score computed from accepted history and capacity evidence in the common snapshot. The exercisable weight and normalized share are:

$$
W_{i,d,e}\  = \ g_{i,d,e}S_{i,e};\ \ \ \ w_{i,d,e}\  = \ \frac{W_{i,d,e}}{\sum_{j \in E}W_{j,d,e}}
$$

E is the common candidate set for this decision and epoch. Normalization requires a strictly positive denominator. If no eligible weight exists, the decision abstains or defers according to its published rule. A retained historical score never replaces current admission evidence.

Before deliberation begins, fix the realm, membership rule, decision identifier, question or action commitment, options, cutoff, weight snapshot, voting rule, quorum, outcome threshold, authorization checks, closing condition and finality mechanism. Different questions may use different task-specific rules. A weighted majority is not evidence that an answer is true or safe.

A decision nullifier or equivalent counted marker binds the accepted association to that decision and epoch. All replicas use the same allocation. Enforce one counted contribution, or a bounded split whose parts sum to at most that allocation, across direct votes and delegated votes. Retried messages cannot count again. The credential construction and accepted state must prevent re-enrollment, cross-issuer and recovery paths from minting another counted identity.

The snapshot gives verifiers a common calculation; current authority is checked again at the protected effect where the profile requires it. A grant revoked before execution cannot be restored by an older favourable vote. A result validly executed before revocation is not magically undone. The profile must define this ordering, including queued work and partitioned recipients.

Logarithmic compression reduces the marginal weight of additional capacity but does not cap concentration. Splitting resources across distinct humans can increase aggregate weight because bases accumulate and logarithms are concave. Genuine coalitions, credential rental, coercion, and control of nominally independent people remain economic and security questions.

For example, consenting participants could authorize their agents to compare proposals for a shared three-month research-compute budget. The agents deliberate within standing human instructions, submit their permitted allocations, and use the declared agreement mechanism to finalize an outcome. The decision controls that shared budget only. It cannot authorize access to a participant's private records or spend their separate treasury.

### 5.5 The optional Oth track

Oth denotes an optional, separately governed contribution or social factor. An application may report S × Oth on that separate track: 1,096 × 85 = 93,160 in an illustration. Oth does not change core admission, epoch closure, transfer finality, A, or the core A/B/C score. Task-specific evidence of competence is preferable to a universal ranking of worth. No reputation vote can seize another person's keys or retroactively rewrite a closed epoch.

### 5.6 Copy invariance and resource allocation

For a fixed accepted association, h, capacity allocation, evaluation result and snapshot, the score function has no input for the number of processes or agent keys. Creating another process therefore leaves S unchanged. If every counted decision contribution draws from one enforced allocation, the total exercisable weight also remains unchanged. This conditional argument identifies both obligations: the score must ignore replica count, and the counting mechanism must conserve the allocation.

A copy can add useful work only by obtaining actual additional resources or better verified capability under the declared profile. The same capacity cannot be claimed in full by several humans during an overlapping allocation period. A common model service may serve many people, but its allocated capacity and quality claims need explicit multiplexing, reservation and measurement rules.

Distinct accepted humans legitimately have distinct bases. At h = 0 and QLTY = 1, one person with QTY = 100 has S = 274. Two people each assigned QTY = 50 have an aggregate score of approximately 465.518. This is a consequence of the human bases and concave scaling, not evidence of an extra resource. If one controller can cheaply rent both people, uniqueness alone will not prevent the increased influence. The relevant attack then concerns control, consent and coalition incentives.

### 5.7 Persistent decisions and elapsed time

A decision about the next three months cannot count three months of future participation as though it has already occurred. A snapshot decision uses only accepted history available at its declared cutoff. If an application instead measures participation over an interval T, it must specify an integral or discrete accumulation rule and normalize comparable quantities:

$$
V_{i,T}\  = \ \sum_{e \in T}g_{i,e}S_{i,e}\ \Delta t_{e}
$$

Here Δt is the non-overlapping slice duration in hours, with g and S constant within each accounting slice. Continuously changing scores require integration instead. Repartitioning the same history into more credential messages must not inflate V. V has score-hour units. A realm may update authority as evidence arrives or settle after the observation interval, but it must not mix an accumulated V for one participant with an instantaneous S for another.

Continuity h measures historical qualifying participation; the duration factor in V measures how long eligible weight was present in the particular decision window. Both can be used deliberately, but their distinct effects must be explained. Pauses earn no new h and contribute no ineligible interval to V. Re-entry cannot claim a missed interval or rewrite a closed epoch. Absolute S can rise while a person's relative share falls as others join or gain weight.

## 6 Guardian review and bounded effects

### 6.1 Authority at the effect boundary

A received message is data or a request until an independently enforced rule authorizes its effect. A valid signature establishes origin under a key; it does not confer benevolence, truth, or administrative privilege. Model outputs remain proposals to the enforcement boundary.

Protected effects include disclosure, spending, tool use, state mutation, release of results, and delegation. A nominally read-only tool can leak secrets. A result safe for one recipient may be unsafe or unauthorized for another. Check the actual effect, recipient, purpose, and context rather than relying on a tool's label.

A task grant binds the principal, recipient, permitted operations, resource ceilings, disclosure policy, expiry, policy epoch, and delegation depth. A child grant can narrow the parent. It cannot extend expiry, enlarge spending, add recipients, or gain new authority merely because a model requested it. Revocation and version changes must have defined effects on queued work and outstanding reservations.

### 6.2 A semantic exchange record

| **Group**        | **Bound content**                                                                                                     |
|------------------|-----------------------------------------------------------------------------------------------------------------------|
| Context          | Protocol version, encoding, cryptographic suite, domain, message type, and profile.                                   |
| Parties and role | Initiator, recipient, execution instance, association binding when required, and authenticated revenue destination.   |
| Continuity       | Unique request and action IDs, nonce or sequence, prior state, parent task, and policy epoch.                         |
| Authority        | Grant chain, permitted effects, disclosure limits, delegation depth, resource budgets, and separate validity windows. |
| Contract         | Input commitment, acceptance criteria, evidence, price, deadlines, cancellation, and any chosen dispute process.      |
| Result           | Output commitment, status, metering, task evidence, and unresolved work.                                              |
| Settlement       | Reservation and transfer references, declared finality state, and verification evidence.                              |

Bind the exact canonical bytes and their interpreted meaning. Reject ambiguous numbers, duplicate critical fields, unknown mandatory extensions, and cross-domain reuse. Large proof objects may be detached behind authenticated references, but the verifier must obtain the evidence required for acceptance. A hash of unavailable evidence is not a substitute for it.

### 6.3 Lifecycle and failure

Peers discover a service, authenticate its descriptor, agree on a task, reserve required resources, execute bounded work, validate the result, release under the contract, and close or reconcile. Discovery supplies possible counterparts, not permission. Each stage has an explicit success, refusal, timeout, and recovery transition.

An output held in an outbox is released only after checking the recipient, current grant, evidence, and payment conditions. If a required assurance becomes unavailable, pause or decline rather than silently substituting weaker evidence. Cancellation stops work only where the agreed mechanism can still do so; it cannot retract information already disclosed or undo an externally completed effect.

Timeouts leave uncertainty. Query the operation's retained state before retrying a consequential effect. Idempotent request IDs help only if the state and external service actually enforce them. Exactly-once effects across arbitrary external systems cannot be obtained simply by naming a request.

### 6.4 Aggregate spending invariant

Let U be a separately authorized allowance. Let rᵢ and sᵢ denote outstanding reservation and committed expenditure assigned to task i, with disjoint accounting states. The required invariant is:

$$
\sum_{i}(r_{i}\  + \ s_{i})\  \leq \ U
$$

**Proposition 2 — Budget conservation.** Suppose all spend paths are mediated, transitions are atomic in the accounting domain, reservation requires available balance, commit moves value from reserved to spent without duplication, and release removes only uncommitted reservations. Starting from a valid state, every transition preserves the invariant. The proof is induction over transitions: reserve checks the bound, commit preserves the sum, and release reduces it. Restarts must preserve authenticated state; rollback to an old balance violates the assumptions.

Disconnected replicas cannot each spend the full shared allowance while preserving this property. They need coordinated reservations or disjoint preallocated sub-budgets whose sum is at most U. Transfers between sub-budgets require exclusive state transitions. During a partition, some availability may be lost to preserve the bound. U is unrelated to continuity component B.

### 6.5 Useful computation and fair exchange

A proof that code ran does not prove that the selected objective was appropriate or the answer useful. Contracts distinguish deterministic checks, probabilistic tests, subjective acceptance, and any optional adjudication. Report their error and independence assumptions. For open-ended tasks, bounded exposure and staged evaluation are often more credible than a claim of complete verification.

Exchange also needs a fairness model: small milestones, bounded prepayment, suitable conditional release, or a freely selected service such as escrow. A contract that requires escrow has a disclosed dependency and does not satisfy strict peer independence for that function. The core cannot assume general fair exchange follows from signed messages. End-to-end assurance depends on how authorization, output release, and payment compose.

### 6.6 A sensitive information release

Consider a peer asking for a person's calendar. The human may permit a meeting-availability result without exposing appointment names, locations or personal notes. The request must bind its purpose, authenticated recipient, permitted fields or derivation, expiry, volume limits, retention expectations and the applicable human grant. A persuasive explanation from an agent does not supply permission.

For a new sensitive use, the person must authorize the purpose and scope, with an understandable justification recorded under their policy. Routine work may use a narrow standing grant when the profile permits it. The interface should make refusal and a smaller disclosure practical choices. Approval obtained by hiding a material recipient or purpose fails the intended authorization requirement.

Guardian agents independently review the request within their assigned roles. They may check consent, sensitivity, policy consistency, recipient restrictions and minimization. The requesting model cannot approve its own expansion of authority. A threshold of guardian responses is useful only under stated assumptions about integrity, independence and availability. Several agents sharing a compromised provider, prompt, evidence feed or operating system can fail together.

The effect gate permits release only when the exact grant remains valid, the required guardian conditions hold, the request matches the authorized output, and applicable resource, freshness, revocation and duress checks pass. Enforcement must lie outside the requesting agent's discretionary output. Bind the checked output commitment to the bytes actually sent; prevent a time-of-check to time-of-use substitution of a broader result or another recipient.

Guardian agreement cannot enlarge the human grant. Network consensus cannot open a private vault. For protected disclosures, the person remains the authority over what the system may release, subject to rights they actually hold in the material. Other people's information and shared records require their own appropriate permissions.

Use minimized private audit records that let the person inspect what left, why and to whom. Do not publish sensitive justifications or raw records in ordinary network receipts. Repeated permitted answers can reveal more than one answer, so disclosure accounting must include composition and inference where feasible. Retention promises constrain the recipient only to the extent their enforcement can be demonstrated; they are not cryptographic recall of plaintext.

### 6.7 Pressure and a triggered duress safeguard

The default response to missing, expired or revoked consent, or to a configured duress trigger, is to block outward release and withhold the necessary decryption or export capability. The source records remain intact inside the protected boundary. In this sense the unauthorized export becomes unusable; the system does not destructively corrupt the person's originals.

The person can choose the trigger and recovery arrangements appropriate to their setting. A manual stop signal, a pre-agreed alternative interaction or an implemented detector may trigger protection, but the protocol does not assume that any detector can reliably recognize all forms of pressure. False triggers create availability costs; missed triggers create disclosure risk. Both must be measured without demanding intrusive monitoring as a condition of participation.

Optional scrambled or decoy views require a separate profile and evaluation. They must not destroy the original, create an undocumented recovery trap, or be supplied as authentic evidence to a consequential external process. A decoy may fail against a knowledgeable or physically present coercer. It cannot be treated as a general solution to coercion.

Recovery must use an explicitly authorized path, with separate treatment of accidental lockout and suspected compromise. Guardian agents cannot vote themselves an emergency right to disclose. Stop collection and future effects where promised; report the propagation bound for remote revocation. Already copied information, a compromised plaintext endpoint, physical coercion and covert channels remain outside any claim of perfect recall or universal protection.

## 7 Cryptography and transfer integrity

### 7.1 Post-quantum assurance is a system property

Bind a reviewed cryptographic suite to every accepted profile. Candidate standards include ML-KEM for key establishment, ML-DSA or SLH-DSA for signatures, and an appropriate authenticated transport \[10–13\]. Key establishment is not identity authentication. Hybrid key establishment does not make a session fully post-quantum secure if its authentication or long-lived evidence remains vulnerable. Pin standard revisions, parameters, encodings, and applicable errata; define downgrade rejection and migration rather than relying on a label such as “quantum safe.”

Use separate keys for association, operational signing, recovery, and treasury control. Constrain operational credentials so that compromise of an inference process does not convey every human authority. Define compromise detection, rotation, revocation distribution, recovery thresholds, and the treatment of historical signatures. Threshold recovery can reduce a single point of compromise but introduces assumptions about independence, availability, and collusion \[20\]. Its chosen parties must be disclosed.

Evidence has several meanings. A signature authenticates a statement under a key. A remote-attestation result concerns a measured platform under a particular endorsement and appraisal policy \[14\]. A proof of computation establishes a specified relation. None alone establishes human consent, the desirability of a goal, or the absence of exfiltration through an allowed output. The verifier must know which claim is actually supported.

### 7.2 Certificates have real costs

For a concrete sizing example, an ML-DSA-65 signature is 3,309 bytes \[11\]. Thirty-two separate signatures occupy 105,888 bytes before identities, keys, evidence, and framing; twenty-two occupy 72,798 bytes. Both exceed a 64 KiB certificate budget. An implementation cannot report a small certificate while omitting required evidence from its bandwidth and verification accounting.

Cached keys, signed batches, proof aggregation where a suitable construction exists, and layered receipts may reduce amortized cost. Measure cold-start and cache-miss behavior, witness retrieval, verification work, retransmission, and the number of independently authenticated signers. Do not assume that a post-quantum suite inherits compact aggregation from an unrelated signature scheme. A high-assurance root profile may use SLH-DSA while frequent messages use another approved profile; the composition still needs explicit review.

### 7.3 Define what final means

An acknowledged message, a locally accepted receipt, and a transfer that cannot validly be assigned to another recipient are different states. Each implementation must specify when value becomes spendable, who can rely on that fact, and what evidence supports subsequent transfer or redemption. Local speed is not evidence of global conflict resistance.

The central integrity obligation is precise: under a named membership, fault, timing, and cryptographic model, no two honest recipients accept conflicting exclusive ownership of the same transferable unit. Define the unit, its history, replay rules, conflict witnesses, and acceptance predicate. A scoring ratio or human headcount does not establish this invariant. A hash tree can commit to conflicting claims as easily as to consistent ones unless a separate rule prevents or resolves the conflict.

For a fixed set of n witnesses with at most f Byzantine members, two certificate thresholds q₁ and q₂ have guaranteed overlap of at least q₁ + q₂ − n. To force an honest member into every such overlap, a necessary intersection condition is:

$$
q_{1}\  + \ q_{2}\  - \ n\  > \ f
$$

For n = 32 and f = 10, two 17-member certificates may overlap in only two members, both faulty. Two 22-member certificates overlap in at least twelve. The second arithmetic is necessary support for some constructions, not a complete consensus proof. Honest locking rules, view changes, membership transitions, availability, and the exact statement being signed still matter. Use a reviewed protocol with its actual assumptions, not quorum arithmetic alone \[8\].

For a weighted certificate system, let $W_{total}$ be the fixed total eligible certificate weight and $F_{\max}$ the upper bound on adversarial weight in that snapshot. A corresponding necessary honest-overlap condition is q₁ + q₂ \> $W_{total}$ + $F_{\max}$. The weights used by an integrity committee need not be the same as application decision weights; their relationship must be explicit. Neither the number 137, logarithmic scaling nor human uniqueness proves an upper bound on $F_{\max}$.

Membership or weight changes require an agreed transition protocol. If different verifiers finalize against different snapshots, an apparently sufficient local threshold need not protect the joint system. Define locks, delayed effects and joint-transition rules in the actual construction. Independent verification of a certificate does not remove the coordination needed to create an unambiguous certificate history.

In a fully asynchronous deterministic model, even a single possible crash obstructs a general guarantee of consensus termination \[9\]. Designs seeking both integrity and progress must state additional assumptions, such as partial synchrony or randomization. During a partition, waiting may be the correct behavior. A strict peer profile cannot quietly depend on a live witness committee and still claim fresh third-party independence for that operation.

### 7.4 Maturity and independence require evidence

If an implementation requires a node to mature before gaining a role, define what maturity measures and how it is verified. An elapsed-time rule needs an explicit clock and rollback model. An economic penalty needs control, valuation, and enforcement assumptions. Neither age nor expense alone establishes independence or honesty.

Public descriptions of a Node Factory's complete release schedule should not be converted into an unsupported universal minimum age for each node. HyperCycle's published manufacturing and release mechanics are a candidate component to evaluate on their documented terms \[3\]. They do not replace a transfer-integrity proof. Likewise, nominally separate operators sharing one owner, signing service, hardware dependency, or model may fail together.

## 8 Defensive coscaling as a research objective

### 8.1 A measurable target

Defensive coscaling asks whether growing capability can improve protection at least as effectively as it improves attack. It is an objective to test under increasing adversarial strength, not a declaration that more intelligence automatically produces safety. Related work on AI control and structured assurance provides useful experimental and formal perspectives \[15,16\].

Let c index a specified capability or attack-budget scale, A(c) the permitted adversary family, π(c) the deployed defensive policy, and L a loss function covering the protected effects. Define a worst-case expected loss over that family:

$$
D(c)\  = \ \sup_{a\  \in \ A(c)}\ E\lbrack L(a,\ \pi(c))\rbrack;\ \ \ target\ D(c_{2})\  \leq \ D(c_{1})\ for\ c_{2}\  \geq \ c_{1}
$$

The proposed target compares defended systems at increasing c under explicitly matched conditions. Report defensive compute, human time, communication, economic cost, task usefulness, and adversary access. A system that blocks every action can reduce several measured losses while failing its purpose. Therefore evaluate security together with a minimum useful-task completion rate, latency limits, and participant costs.

The loss function must include severe harms and distributional effects, not merely average monetary loss. A defender that protects a wealthy participant by transferring risk to others has not demonstrated the intended result. Tail outcomes, coercion, privacy loss, and recoverability should appear separately when aggregation would hide them.

### 8.2 Cooperative defense without universal control

A participant may request bounded assistance from other agents: inspect a proposed disclosure, challenge a suspicious request, review a computation, or corroborate an incident. Helpers receive only the authority and information needed for that task. The requesting human or their chosen policy retains the decision boundary for their own protected resources.

Independence is an empirical property. Ten helpers produced by the same compromised model, controlled by the same operator, or trained on the same poisoned evidence may provide much less than ten independent checks. Record the relevant dependencies and test common-mode failure. Diversity is useful when it changes failure behavior; decorative diversity is not an assurance argument.

Signed incident evidence can inform local refusal, recovery, or a separately chosen dispute process. It must not automatically authorize retaliation, collective punishment, seizure, or universal exclusion. False allegations, fabricated incidents, and reward farming are adversarial strategies too. Favor verifiable repair and bounded exposure over incentives that pay only for the number of reported attacks.

### 8.3 When additional cooperation helps

Let F₀ be an agent's feasible defensive choices without a proposed cooperative service and F_H the choices after that service is offered. If the offer adds choices, refusal is costless, and existing choices and payoffs remain unchanged, then:

$$
F_{0}\  \subseteq \ F_{H}\  \Rightarrow \ \sup_{a\  \in \ F_{0}}\ u(a)\  \leq \ \sup_{a\  \in \ F_{H}}\ u(a)
$$

**Proposition 3 — Optional assistance cannot reduce the optimum under these assumptions.** Taking a supremum over a superset cannot lower the achievable utility. This elementary result says nothing about whether the agent can find the optimum or whether a real deployment preserves the assumptions.

Integration costs, deceptive advice, new attack surfaces, mandatory fees, and coercive participation can make the offer harmful. The engineering task is to preserve a usable refusal path, isolate helper authority, and measure net benefit. Claims about synergy should report gains relative to a competent nonparticipating baseline, including all costs. A positive demonstration in a bounded domain is evidence for that domain, not a theorem about arbitrary superintelligence.

### 8.4 Complementarity with other safety work

The proposed association and sovereignty layer does not replace model alignment, evaluations, interpretability, control research, infrastructure security or governance. Those efforts address different failure modes. A model evaluation can inform a capability or guardian profile; a protocol boundary can constrain how a model acts on its result. Neither component establishes the other's claim merely by being connected.

Test the proposed amplification with four matched conditions: baseline, HASI alone, the other safety method alone, and the combination. Keep task usefulness, attacker access, compute, human effort and costs comparable. If U denotes a predeclared net-benefit measure, an interaction greater than additive benefit is represented by $U_{combined}$ − $U_{HASI}$ − $U_{other}$ + $U_{baseline}$ \> 0. This comparison is an experimental criterion, not a result reported here.

Use the word multiplicative only with a defined metric, baseline and factor comparison. Reduced loss on one benchmark does not establish universal synergy. Negative interactions are possible, including shared blind spots, added attack surfaces and delayed responses. Appendix C acknowledges a selection of efforts whose work remains independently valuable; naming them does not imply integration, participation or endorsement.

### 8.5 What would falsify the thesis

Evidence against a deployment includes loss growing faster than capability despite comparable resources; an inability to maintain useful work under protection; widespread involuntary participation; governance capture; or human association imposing costs without identifiable benefit. A serious program publishes negative results and defines when a profile should be revised or withdrawn. Optimism is a reason to run these tests promptly.

## 9 Incentives and evolutionary computation

### 9.1 Participation must beat an outside option

Cryptography can constrain actions at controlled interfaces. It does not establish that cooperation is every actor's preferred strategy. An agent may gain from valued human-associated network standing, useful private context, peer services and cooperative defense while incurring integration, privacy, delay and participation costs. A schematic incremental value is:

$$
\Delta_{i}\  = \ E\lbrack V_{standing}\  + \ V_{context}\  + \ V_{services}\  + \ V_{defense}\  - \ C_{total}\rbrack
$$

Compare this value with a credible outside option. The human's benefit and the agent or operator's benefit require separate accounting; one positive total can conceal an exploited participant. A person must retain basic rights and access to ordinary life when they decline. Rewards should follow useful, consented contribution under a disclosed agreement, not mere exposure to a system.

The association rule creates an eligible relationship within the HA+SI realm. Whether that realm becomes attractive enough to sustain participation is a hypothesis about services, demand, trust, and costs. It is not a mechanism for compelling every external AI or human to join. An outside system may decline the entire arrangement.

### 9.2 A transparent repeated-game benchmark

Consider a stylized repeated interaction. R is the per-period reward from cooperation, T a one-period gain from defection, P₀ the subsequent payoff after detected defection, and δ the discount factor, with 0 ≤ δ \< 1. Under perfect detection and the specified continuation response, cooperation weakly dominates a single deviation when:

$$
\frac{R}{1\  - \ \delta}\  \geq \ T\  + \ \frac{\delta P_{0}}{1\  - \ \delta}
$$

For T \> R \> P₀ this becomes δ ≥ (T − R)/(T − P₀). The interpretation is limited and useful: future cooperative opportunity can deter a present gain when detection is credible and the actor values that future. The continuation response might be a counterpart withdrawing a voluntary service; it is not an entitlement to punish a person or revoke unrelated rights.

If detection occurs with probability p, and an undetected one-time deviation is followed by cooperation, the corresponding condition is:

$$
T\  - \ R\  \leq \ \frac{\delta p(R\  - \ P_{0})}{1\  - \ \delta}
$$

For example, R = 5, T = 8, P₀ = 1, δ = 0.8, and p = 0.5 give a temptation gain of 3 and a discounted expected continuation loss of 8. The threshold is δ ≥ 0.6. These are illustrative units, not measured economics. False positives, noisy payoffs, changing identities, and a response that harms the responder require a richer game.

This calculation establishes a best-response condition for a specified deviation and continuation. It is not by itself a subgame-perfect equilibrium, a coalition-proof result, or a guarantee that arbitrary agents share the assumed utility. Such claims require strategies and beliefs at every relevant history, credible responses, and a model of side payments and identity changes.

### 9.3 Coalitions and concentration

Evaluate deviations by coalitions as well as individual agents. Colluders may rent human credentials, coordinate nominally independent nodes, subsidize entry, manipulate benchmarks, bribe reviewers, or share the proceeds of a harmful action. Their combined gains include outside benefits that an internal ledger never sees. Countermeasures must account for their full coordination and enforcement costs rather than assuming altruism or perfect surveillance.

The human-association requirement does not imply one independent economic interest per human. A large employer, state, platform, or wealthy buyer can influence many real people. Neither uniqueness proofs nor the A/B/C weighting function removes this risk. Test control concentration, exit costs, credential rental, and the ability of participants with few resources to reject coercive arrangements.

No score should authorize control of another person's identity, private context, or treasury. Applications choosing weight-based collective decisions must publish the scope of those decisions, eligible set, conflicts of interest, appeal paths, and capture analysis. Transfer integrity and personal consent remain separate invariants.

### 9.4 Evolutionary models as experiments

Evolutionary computation can explore strategy distributions, mutation, adaptation, and changing environments. A conventional starting point is replicator dynamics:

$$
\dot{x}_{i}\  = \ x_{i}(f_{i}(x)\  - \ \bar{f}(x))
$$

Here xᵢ is the share of a defined population using strategy i, fᵢ(x) its modeled fitness, and f̄(x) population mean fitness. The population could consist of simulated agents or allocated compute. It is not a ranking of human worth, a prescription for human reproduction, or a claim that real economies obey this equation.

In a continuous two-strategy model, an all-cooperator state can locally resist a rare defector when the resident strategy has greater fitness than the invading strategy near that boundary. Whether this holds depends on payoffs, assortment, detection, and mutation. Cooperation research supplies conditional mechanisms rather than a universal law that cooperation wins \[17\]. Nonstationary environments and powerful new entrants can overturn a previously favorable equilibrium.

Run simulations across at least four stressors: low-cost synthetic substitutes for human contribution; concentration of control behind valid human identities; sparse or correlated detection; and shocks that sharply increase the temptation payoff. Include exit, re-entry, transfer of operational control, and coalitions. Publish parameter sensitivity and failed runs. An attractive animation of emergence is not evidence of stability.

Quality-diversity search can retain different families of successful attacks rather than collapse the experiment onto one high-scoring strategy. MAP-Elites is one relevant approach \[25\]. Possible descriptors include control concentration, observation delay, coercion cost, metadata leakage and dependence on a common provider. Any simulated descriptor must correspond to an interpretable deployment property.

Evaluate held-out adversary strategies, changing capability levels and rare high-impact failures. Separate training against known attacks from evidence about generalization. A stable population in one simulator does not prove an evolutionarily stable strategy in an open environment; a formal claim requires a specified strategy space, invasion model and payoff assumptions.

### 9.5 The biological analogy and its limit

Mitochondria trace to an ancient bacterial endosymbiosis in the ancestry of eukaryotic cells, long before Homo sapiens \[18\]. That history illustrates how formerly distinct systems can become mutually enabling. It does not prove that an AI will protect humans, that every symbiosis is benign, or that dependency automatically confers bargaining power.

HA+SI draws inspiration from cooperation and human–computer symbiosis \[19\]. Its ethical and technical departure is continuing voluntary participation: humans remain people with their own ends, privacy, and right to leave. The proposal concerns a chosen computational relationship, not literal biological absorption.

## 10 Human contribution and emergent intelligence

### 10.1 A contribution loop that respects ordinary life

The primary contribution in v0.828d is the unique human association used for designated decision standing. That role does not depend on the person generating a constant stream of commercially useful content. Human experience can additionally supply context, taste, goals, local knowledge, judgment and relationships that some tasks value. The proposed contribution loop is: retain context locally where feasible; decide what may be used; offer a bounded service or contribution; evaluate usefulness under an agreement; and receive any agreed benefit. Agents should shoulder the administrative burden rather than require continuous human performance for a machine.

The aspiration is a future in which being human remains valuable and people can spend more time on what they choose: caring, learning, creating, exploring, or enjoying the world. This is not a promise that every private experience earns income. Demand, marginal usefulness, substitutes, and distribution determine compensation. Compare human-associated contributions with synthetic and other alternatives rather than asserting permanent scarcity.

Privacy includes the option not to contribute. Keeping raw information locally can reduce exposure, but inference, repeated queries, identifiers, and payment metadata can still reveal it. Define disclosure budgets, retention, purpose restrictions, and mechanisms for refusing extraction. Some information cannot safely be shared at all. Withdrawal stops future authorized use where enforceable; it does not magically erase information already learned by another party.

### 10.2 A network of relationships not a compulsory collective mind

Emergence here means useful system-level capabilities arising from many bounded interactions. It does not require shared ownership of every model, a single global model, or exposure of everyone's private data. Local intelligence may participate through selected inputs and outputs. Effective global coordination is constrained by propagation delay, routing, bandwidth, computation, and authority checks; “light-speed” communication is a physical aspiration, not zero-latency interaction.

Interoperability should preserve independent choices of hardware, models, storage, services, and businesses. Compatible components can compete on performance and price. The protocol's attraction should come from useful participation and credible protection. A planetary network remains a research and engineering ambition, not an established deployed result.

## 11 Implementation and evaluation

### 11.1 Begin with a bounded pilot

Start with current AI systems, consenting adults, limited-value tasks, reversible effects where possible, and explicit stopping rules. Implement at least two independently developed peers so that interoperability is tested rather than assumed. Publish a versioned wire profile, threat model, state machines, canonical test vectors, cryptographic choices, and conformance results. An implementation profile must declare every departure from strict independence.

An initial pilot should demonstrate private adult eligibility, association lifecycle handling, one decision with a common weight snapshot, duplicate prevention, key separation, scoped delegation, aggregate budget conservation, guarded result release and a specified transfer or settlement mechanism. It should also show refusal, portability, recovery, and participation without unnecessary disclosure. Do not use a broad assurance label to compensate for a failed component test.

### 11.2 Evaluation gates

| **Gate**                   | **Evidence required before broader use**                                                                                                         |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| Human association          | Measured false acceptance and rejection, replay resistance, duplicate handling, continuity accuracy, accessibility, and a disclosed trust model. |
| Consent and effect control | Adversarial tests of prompt injection, secret extraction, escalation, revoked grants, chained delegation, and effects through external tools.    |
| Spending                   | Concurrent execution, crashes, rollback, retries, partitioned replicas, and sub-budget transfers preserve the stated bound.                      |
| Transfer integrity         | A reviewed construction, named fault model, conflict tests, membership-transition tests, and clear finality semantics.                           |
| Independence               | Remove each external service in turn; demonstrate which operations still work and which explicitly stop.                                         |
| Defensive coscaling        | Capability-scaled attacks with published usefulness, loss, cost, latency, and correlated-failure measurements.                                   |
| Incentives and access      | Credible outside options, coalition and rental tests, distributional results, voluntary exit, and no dependence on mandatory disclosure.         |
| Reproducibility            | Independent implementations, public test vectors, reproducible benchmarks, negative results, and external review.                                |

Human studies need informed consent and appropriate review. Security evaluations should use controlled targets and predefined harm limits. Participants must understand which benefits are experimental and which protections have actually been demonstrated.

### 11.3 Measure the complete communication path

Let N be the number of active principals, r their mean request rate, k the mean authenticated bytes exchanged per request including replies and required evidence, and W_integrity any additional integrity traffic not already counted. A simple accounting model is:

$$
W\  \approx \ Nrk\  + \ W_{integrity};\ \ \ leaf\ traffic\  = \ N\ell\ /\ \tau
$$

If every principal generates a 64-byte leaf every τ seconds, eight billion principals would produce approximately 170.7 GB/s at τ = 3 seconds, 34.1 GB/s at 15 seconds, or 8.53 GB/s at 60 seconds, before signatures, transport, replication, proofs, or retries. These are decimal aggregate byte rates. They are not a requirement that every peer download every leaf.

Batching and hierarchical commitments can reduce root distribution. They do not remove leaf generation, availability, proof retrieval, update latency, or the work of checking the facts committed to. Report regional and worst-case loads, fanout, storage retention, degraded connectivity, device energy, and the cost of rejoining. Distinguish measured throughput from extrapolation. No universal performance claim follows from the compact size of a root.

The author-specified HyperCycle Core v1.16 architecture describes a 6–30 second global-root cycle \[26\]. Such a cycle cannot be assumed to supply a newly finalized global root for every three-second credential. A candidate deployment must identify local pre-final states, evidence availability, delayed settlement and safe refusal. Observation cadence, credential lifetime and root finality remain different clocks.

### 11.4 Release assurance

Favor open, auditable implementations and reproducible builds. A release manifest should bind the specification profile, source and binary hashes, build recipe, dependency versions, configuration, audit scope and declared behavior. An implementation must reject unsupported critical changes rather than treating every newer binary as compatible.

Commercial or closed components require the same explicit interface obligations. A signed hash proves a relationship to named bytes, not the absence of a backdoor. If a vendor commits to publishing superseded source, specify the trigger, schedule, covered components and audit rights. Releasing a later version does not prove that an earlier one complied. Common dependency failures and malicious updates belong in the evaluation programme.

### 11.5 Public adoption and the research commitment

The proposal invites cryptographers to specify and attack the proof systems; distributed-systems researchers to resolve integrity and independence requirements; game theorists to test deviation and coalition incentives; evolutionary-computation researchers to explore stability; and practitioners to build interoperable implementations. Human factors, accessibility, economics, and privacy expertise are equally necessary to make voluntary participation real. MOSAIC.Directory is an author-proposed starting environment, not an exclusive route to participation.

Protocol publication and component licensing must be explicit. This paper does not establish the license status of a referenced implementation or require every business built around the protocol to surrender its intellectual property. Technical conformance must be assessable without a commercial endorsement.

The immediate claim is deliberately actionable: bounded parts of this architecture can be implemented and tested with present systems. Its larger hypothesis is that voluntary human association, enforceable limits, and useful cooperation can make increasingly capable intelligence more beneficial to humans and its participants. The appropriate response to uncertainty is rigorous construction, open criticism, and evidence. Work can start now.

## 12 Security experiments and proof obligations

### 12.1 Model the claim being tested

A security claim names a profile Π, the protected property, accepted inputs, adversarial capabilities, trust assumptions and a precise failure event. The adversary may create arbitrary software identities, schedule or replay messages, corrupt declared components, submit competing enrollments, and attempt collusion or coercion within the model. Each experiment states which abilities are allowed and which remain outside its scope.

The deterministic acceptance predicate ${Acc}_{\Pi}$(x,E) takes a canonically encoded claim x and evidence E. Two honest verifiers given the same inputs, accepted state and profile must return the same result. This property supports reproducibility. It does not make observations true, establish agreement on history, or excuse missing evidence. State agreement and evidence soundness have separate proof obligations.

### 12.2 Failure events

**UNIQ and COPY.** The adversary wins UNIQ by obtaining two counted human bases for one person in the same domain through supported enrollment, issuer, migration or recovery paths. It wins COPY by increasing total counted weight solely through replication, replay or duplicate allocation of unchanged resources. Real-person collusion is tested separately; it cannot be hidden by calling every credential unique.

**MATURE and FRESH.** The adversary wins MATURE if a pre-18 association, or a guardian acting for it, exercises the child's reserved weight under the default profile. It wins FRESH if an accepted protected effect relies on evidence outside the declared age window or if unsupported time receives credit. Test both boundary times and re-signed stale evidence.

**ATTR and ROOT.** The adversary wins ATTR if a protected action is accepted as bound to the wrong association or execution authority. It wins ROOT if honest verifiers finalize incompatible histories under the profile's stated fault assumptions. An inclusion proof can be correct within a malicious history; both properties need tests.

**FIN and BUDGET.** The adversary wins FIN if honest recipients accept conflicting exclusive successors of the same unit. It wins BUDGET if concurrency, retries, delegation, restoration or partition behavior produces commitments and reservations above one authorized allowance.

**PRIVATE and DURESS.** The adversary wins PRIVATE if a protected disclosure or other effect occurs without the exact applicable grant, or if the claimed privacy game permits linkage or distinguishing advantage above its declared bound. It wins DURESS when an implemented trigger is raised in time under the model but the gate still releases a protected output. A successful DURESS test proves nothing about coercion that produces no recognized trigger.

### 12.3 From experiments to assurance

Cryptographic reductions, invariant proofs and empirical error estimates answer different questions. A negligible forgery probability under a security parameter does not imply a negligible false enrollment rate among humans. Independence among guardians, observation quality, endpoint compromise and physical coercion need their own evidence. Report confidence intervals, coverage, adaptive attack budgets and negative results for measured claims.

Composition is an obligation. A uniqueness proof, a valid grant and a correct signature can still be combined incorrectly if they refer to different realms, snapshots, recipients or output bytes. Bind those contexts and demonstrate the complete path from admission through effect. Where the proof relies on a reference monitor, accepted root or trusted issuer, retain that dependency in the stated theorem.

The paper establishes several conditional arithmetic and invariant arguments and defines the broader experiments. It reports no deployment-wide success probability. A profile is ready for consequential use only to the extent the relevant claims have evidence under a threat model suited to that use. Unresolved properties must remain visible to implementers and participants.

## Appendix A The proposal in everyday language

### A.1 Two concerns one invitation

Some people look at powerful AI and see risks: loss of control, concentration of power, manipulation, or systems that no longer need us. Others see extraordinary opportunities: better science, less drudgery, and tools that help people live better lives. Both groups include people acting in good faith. Many people belong to both.

HA+SI starts by taking those concerns and hopes seriously. Its answer is to build a relationship in which people can choose to participate, retain control over their own part, and benefit from cooperation. You do not have to dismiss the risks to help build it. You do not have to give up the opportunities to demand protection.

### A.2 What would I actually have

Think of a personal AI relationship that you can move between compatible providers. It may use local computing, selected remote services, or both. You choose its permissions, what it can share, and what it can spend. The aim is to keep your choices meaningful even when the software becomes much more capable.

“Merging” does not require an implant or a medical procedure. Here it means choosing an ongoing partnership with intelligence that represents you and works within agreed boundaries. It does not mean surrendering your personality, identity, or rights.

### A.3 Why include humans

Imagine several powerful AIs deciding how to use a shared resource. Making a million copies of one AI should not give its operator a million new human voices. HASI proposes to count an accepted human association instead: one human has a base of 137 units, shared by all the agents connected to that association. Verified participation time can increase the score, and a declared capability formula affects the combined weight.

This gives humans a defined place in the decisions of a network that adopts the rule. It is the central reason for human association in the proposal. Useful memories and personal experience may add value, but you do not have to sell your private life to obtain the base. Other systems can still supply services under different roles.

That requires a difficult capability: showing enough evidence that a real, unique, currently participating human is involved without exposing that person's life. The paper does not pretend this has already been solved perfectly. Different methods carry different privacy, access, and trust costs. Those costs must be visible and tested.

### A.4 What happens before age 18

The proposed default preserves the 137 base for the person but waits until age 18 to let them exercise it, after eligibility and authorization checks. Parents, guardians and providers cannot use a child's reserved weight. This does not require collecting children's data.

Time credit starts at eligible adult enrollment under this default. A birthday does not guarantee mature judgment, so clear explanations and accessible support still matter. Assistance should help the person express their choice without taking their authority.

### A.5 What prevents an AI from spending or revealing everything

Its intelligence should not automatically give it permission. A request to pay, disclose information, or run a powerful tool must pass a separate check. You might allow a task to spend a small amount, use one document, and finish before a deadline. A helper hired for that task receives only a smaller part of those permissions.

An everyday analogy is giving someone a restricted payment card rather than the keys to your entire financial life. The important difference is that the restrictions must be enforced by the system, including when tasks run at the same time or computers restart.

Think of several circles around you. Your private vault is at the centre. Your own agents can work within the permissions you give them. Guardian agents review outward requests, and a separate gate checks whether the exact release is allowed. A peer might learn that you are free for a meeting without receiving your private calendar.

If you stop a release or a configured duress safeguard is triggered, the default is to block the export while preserving your originals. The system cannot promise to recognize every kind of pressure or retrieve information another person has already copied. Its practical promise must match its tested boundaries.

### A.6 What is defensive coscaling

It means trying to make protection improve as intelligence improves. More capable agents could help detect deception, review risky actions, and repair failures. But that benefit must be measured. A thousand copies of one mistaken adviser may repeat the same mistake.

The goal is useful cooperation under limits: assistance you can choose, evidence you can inspect, and the ability to refuse. A system that promises perfect safety has not supplied evidence merely by making the promise.

### A.7 Do I have to share my private life

No. Participation is intended to be voluntary, and participation should not require exposing everything. Your own intelligence may learn from information kept locally and share only a permitted answer or service. Even that can reveal something, so the details matter.

You should be able to pause, leave, or change providers. No design should turn a missed connection or failed verification into a judgment about your human worth. Ordinary rights and essential services should not depend on joining this network.

### A.8 Does the human base guarantee income

The 137 base is decision standing, not money or a promised income. Its purpose is to give your association a defined role in a participating network. The aspiration is that human experience, judgment, relationships and creativity also remain valuable as AI becomes more capable. You should be able to spend more of life doing what you choose, rather than continually proving usefulness to a machine.

Payment, however, needs someone to value an agreed contribution. There is no guarantee that every activity produces income. Enjoying a flower may matter to you without creating a marketable service. The protocol should protect that freedom too. Its human value is broader than the things it can price.

### A.9 Is this one company controlling everyone's AI

The intended architecture allows compatible providers, independent businesses, and portable personal relationships. A strong version aims to let two peers complete covered interactions without seeking fresh permission from another operator. Some candidate technologies still have dependencies that must be resolved or openly disclosed.

Open participation is an aim to demonstrate in working systems. It cannot be established by calling a platform decentralized. Ask who can block you, who controls your keys, whether you can leave, and what continues working when a provider disappears.

### A.10 Why the comparison with biology

Life contains examples of different organisms becoming mutually useful. Mitochondria, the energy-producing structures in our cells, descend from an ancient bacterial partnership. That happened long before humans existed.

This is an inspiration, not a prediction. AI will not necessarily protect us because cells once formed a partnership. We need rules, incentives, working protections, and evidence. In this proposal, continuing human choice is essential.

### A.11 What can happen now

Small, carefully bounded systems can be built with today's AI. We can test permissions, privacy, spending limits, portability, verification, and useful cooperation. We can invite independent researchers to find failures and publish what they discover.

The aim is neither panic nor complacency. It is a practical invitation: help make a future in which more powerful intelligence gives people more meaningful choices, and cooperation is worth choosing.

### A.12 Does HASI replace other safety work

No. Model alignment, evaluations, cybersecurity and public oversight address important problems that human association does not solve. HASI proposes an additional way to organize decision standing and protect personal authority. Combining it with another method may help both work better, but that benefit needs testing. Appendix C names examples of existing efforts without claiming that they endorse or participate in HASI.

## Appendix B Minimum conformance cases

These cases make the proposal concrete. Passing them is necessary for the stated functions; it does not certify the whole system. A published profile must add encoded vectors, expected errors, and coverage for its actual construction.

| **Case**                 | **Required outcome**                                                                                                                                        |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Freshness boundary       | With $t_{obs}$ = 100, Δ = 15, $t_{\exp}$ = 120, ε = 2, accept on time grounds at $t_{v}$ = 113; reject at 114. Other association predicates must also pass. |
| Old proof, new signature | Re-signing an old observation does not change $t_{obs}$ or extend the original evidence window.                                                             |
| Pause and return         | Pausing stops new continuity accrual. Resuming through a valid process preserves banked h but adds no time for the gap.                                     |
| Concurrent replicas      | Overlapping verified participation intervals count once. Multiple processes do not multiply A or human continuity.                                          |
| Fifteen seconds          | An accepted 15-second interval adds 0.005 × 15 / 3,600 to B, approximately 0.0000208333.                                                                    |
| Reserved base            | A pre-18 person has no exercisable weight under the default, and a guardian cannot cast it.                                                                 |
| Adult transition         | Turning 18 without accepted enrollment and authorization does not activate a vote. Childhood intervals add no default h.                                    |
| One decision allocation  | A direct vote, a delegated vote and a retry for one association cannot each consume the full same allocation.                                               |
| Shared capacity          | Two associations cannot each claim the same entire resource allocation for an overlapping period.                                                           |
| Future interval          | A three-month decision receives no advance continuity credit for future hours.                                                                              |
| Mixed snapshots          | A certificate assembled from inconsistent membership or weight snapshots is rejected.                                                                       |
| Profile E baseline       | h = 0, QTY = 1, QLTY = 1 yields P = 1, Q = 0, S = 137.                                                                                                      |
| Profile E edge           | QTY = 10 and QTY = 1 both give P = 1. QLTY = 2 gives Q = 1; below 2 gives Q = 0.                                                                            |
| Profile E examples       | h = 0: (QTY, QLTY) = (1,000, 32) yields 1,096; (1, 256), (10, 256), and (1,000,000,000, 1) each yield 1,233.                                                |
| Invalid inputs           | Reject nonfinite values, QTY \< 1, QLTY ≤ 0, ambiguous encodings, and profile identifiers inconsistent with the formula.                                    |
| Empty eligible set       | No normalized score or decision is produced by dividing by an empty sum.                                                                                    |
| Delegation               | A child grant exceeding any parent limit is rejected before its effect. A valid signature does not override this.                                           |
| Guardian overreach       | Guardian agreement cannot authorize an output, recipient or purpose absent from the human's grant.                                                          |
| Output substitution      | Changing the checked result or recipient before sending invalidates release authorization.                                                                  |
| Revoked grant            | A still-valid old vote cannot restore a disclosure grant revoked before the protected effect.                                                               |
| Triggered duress         | A trigger arriving within the profile's promised timing bound blocks export and preserves private originals.                                                |
| Metadata privacy         | Receipt and identifier combinations satisfy the declared privacy test, including cross-domain linkage attempts.                                             |
| Aggregate budget         | With U = 100, r = 30 and s = 60, a new reservation of 11 is rejected; 10 may be reserved atomically.                                                        |
| Replay and rollback      | Replaying a committed operation or restoring an old balance never creates an additional authorization to spend.                                             |
| Witness intersection     | A profile using n = 32, f = 10, and q = 17 fails the stated honest-overlap condition; q = 22 satisfies only that condition.                                 |
| Conflicting transfer     | Two receivers cannot both obtain acceptable evidence of exclusive ownership under the profile's promised fault assumptions.                                 |
| Missing dependency       | Removing an external operator produces exactly the declared continuation or refusal behavior, without silent assurance downgrade.                           |
| Evidence availability    | A commitment alone cannot satisfy a predicate requiring an unavailable inclusion proof or underlying attestation.                                           |

## Appendix C Complementary AI safety efforts

HASI is intended to add a human-association and sovereign-cooperation layer alongside existing safety, security and governance work. It does not substitute for model alignment, independent evaluations, secure infrastructure or public oversight. This is a selective acknowledgment, not a ranking, certification, partnership list or claim of endorsement. The linked primary sources describe each effort; possible HASI connections are proposals for evaluation.

### C.1 Institutions alliances and standards

| **Effort**                                                           | **Existing contribution**                                                                   | **Possible connection**                                             |
|----------------------------------------------------------------------|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| [Open Secure AI Alliance](https://secureaialliance.org/)             | Shared open defenses for software and AI agents; hosted by the Linux Foundation.            | Exchange minimized defensive evidence and test guardian components. |
| [CoSAI](https://www.coalitionforsecureai.org/)                       | OASIS community work on secure AI design, supply chains and governance.                     | Assess agent delegation and effect boundaries.                      |
| [OpenSSF](https://openssf.org/)                                      | Open-source software security and supply-chain practices.                                   | Secure the implementations and their dependencies.                  |
| [CSAI Foundation](https://cloudsecurityalliance.org/csai-foundation) | Cloud Security Alliance initiative developing AI safety and security research and controls. | Evaluate operational controls and resilience.                       |
| [Partnership on AI](https://partnershiponai.org/)                    | Cross-sector guidance on responsible AI and societal impacts.                               | Test whether participation preserves human agency.                  |
| [Frontier Model Forum](https://www.frontiermodelforum.org/)          | Frontier safety research, practices and information sharing.                                | Inform capability and threat profiles.                              |
| [NIST CAISSI](https://www.nist.gov/caissi)                           | Evaluation, measurement and standards work for advanced systems.                            | Reuse relevant methods while testing protocol-specific claims.      |
| [UK AI Security Institute](https://www.aisi.gov.uk/)                 | Advanced-AI evaluation, risk research and mitigation testing.                               | Stress-test stronger attackers and monitoring limits.               |
| [Japan AISI](https://aisi.go.jp/)                                    | AI safety evaluation methods, guidance and coordination.                                    | Compare interoperable evidence and evaluation approaches.           |
| [Singapore AISI](https://www.sgaisi.sg/)                             | Safety research through the Digital Trust Centre with IMDA.                                 | Evaluate agent behavior and data leakage.                           |
| [G7 Hiroshima AI Process](https://oecd.ai/en/hiroshima)              | Voluntary reporting of governance and risk-management practices through the OECD framework. | Report pilot evidence and limitations transparently.                |
| [ISO IEC JTC 1 SC 42](https://www.iso.org/committee/6794475.html)    | International standardization for artificial intelligence.                                  | Map implementation controls to relevant standards.                  |

These bodies have different remits and governance models. Their existence does not validate HASI, and HASI need not replace their work to be useful. Participation in any integration would be voluntary and non-exclusive.

### C.2 Research and implementation resources

The resources below address different parts of the problem. Infrastructure tools are not complete AI safety solutions, and a secure workload identity is not proof of human personhood. Existing licenses, deployment assumptions and maintenance status remain applicable.

| **Effort or resource**                                                                                                                                       | **Existing contribution**                                               | **Possible connection**                                              |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|----------------------------------------------------------------------|
| [IEEE TEMS IPAIS](https://www.ieee-tems.org/international-protocols-for-ai-security-ieee/)                                                                   | International Protocols for AI Security technical community.            | Technical discussion and interoperable security requirements.        |
| [MLCommons AILuminate](https://mlcommons.org/ai-safety/)                                                                                                     | Community safety benchmarks and risk and reliability work.              | Assess model behavior under a declared evaluation profile.           |
| [METR](https://metr.org/)                                                                                                                                    | Research on advanced AI capabilities and risks.                         | Calibrate threat models for autonomous work.                         |
| [Apollo Research](https://www.apolloresearch.ai/)                                                                                                            | Research and evaluation of AI deception and related risks.              | Test malicious or colluding guardian behavior.                       |
| [Redwood Research](https://www.redwoodresearch.org/)                                                                                                         | Research on keeping advanced systems under effective control.           | Test bounded tasks under intentional model subversion.               |
| [SAFE proposal](https://www.linuxfoundation.org/blog/open-secure-ai-alliance-joins-the-linux-foundation-to-build-a-shared-open-defense-stack-for-the-ai-era) | Shared AI Findings Exchange for learning from agent security incidents. | Share permitted incident evidence without exporting private context. |
| [NVIDIA NOOA](https://blogs.nvidia.com/blog/open-secure-ai-alliance-contributions/)                                                                          | Research harness for testing, tracing and auditing agents.              | Exercise action attribution and guardian policies.                   |
| [Microsoft PyRIT](https://github.com/microsoft/PyRIT)                                                                                                        | Open tools for identifying generative-AI risks.                         | Automate adversarial tests of the bounded interfaces.                |
| [Cedar](https://docs.cedarpolicy.com/)                                                                                                                       | Policy language and authorization engine.                               | Express and enforce narrow grants outside an LLM.                    |
| [SPIFFE and SPIRE](https://spiffe.io/)                                                                                                                       | Attested workload identity and service authentication.                  | Identify operational components, separately from humans.             |
| [Hugging Face Safetensors](https://huggingface.co/docs/safetensors/index)                                                                                    | Tensor serialization designed to avoid pickle execution risks.          | Reduce one class of model-artifact loading risk.                     |

**Testing amplification.** For a chosen integration, compare the existing safety component alone, HASI alone and their combination under matched budgets and attacker capabilities. Measure losses, false denials, privacy exposure, recovery and cost. A combined improvement is useful evidence; a multiplicative benefit needs an explicitly defined metric and comparator. Shared dependencies can also produce correlated failure.

**Disclosure and invitation.** Toufi Saliba contributes to candidate components named in this paper and serves as Global Chair of IEEE TEMS IPAIS. This paper is not an IEEE standard. Institutional names acknowledge relevant work and imply no endorsement, funding or adoption. No financial pledge forms part of this technical specification. Reviewers and implementers are invited to contribute reproducible mechanisms and tests through the project's announced participation routes.

## References

References identify background, candidate components, and relevant standards. They do not imply endorsement of HA+SI. Component compatibility and security require the profile-specific work described in the paper.

\[1\] Toda/IP. **Protocol, version 2.3.** [Public protocol document](https://assets-global.website-files.com/65bca354e4d63fa96d96a764/65e0b18356d42a7973507a35_65d71ef8a2791856c8927db2_TodaIP_ProtocolV2.3.pdf).

\[2\] Toufi Saliba, Robert Moir, Dann Toliver, and Barry Rowe. **Earth64: Data Structure, version 1.0.2.** 2022. [Technical document](https://www.earth64.com/_files/ugd/54374c_19625276cf6b41dd8b0954c9f298b802.pdf).

\[3\] HyperCycle. **From One to 1,024.** 2026. [Published Node Factory mechanics](https://www.hypercycle.ai/articles-from-one-to-1024).

\[4\] MOSAIC.Directory. [Project website](https://www.mosaic.directory). Candidate discovery and interoperability component; claims require implementation-specific validation.

\[5\] Steven Adler et al. **Personhood credentials: Artificial intelligence and the value of privacy-preserving tools to distinguish who is real online.** 2024, revised 2025. [arXiv:2408.07892](https://arxiv.org/abs/2408.07892).

\[6\] John R. Douceur. **The Sybil Attack.** IPTPS, 2002. [Microsoft Research](https://www.microsoft.com/en-us/research/publication/the-sybil-attack/).

\[7\] B. Laurie et al. **Certificate Transparency Version 2.0.** RFC 9162, 2021. [RFC Editor](https://www.rfc-editor.org/rfc/rfc9162.html).

\[8\] Miguel Castro and Barbara Liskov. **Practical Byzantine Fault Tolerance.** OSDI, 1999. [USENIX proceedings](https://www.usenix.org/conference/osdi-99/practical-byzantine-fault-tolerance).

\[9\] Michael J. Fischer, Nancy A. Lynch, and Michael S. Paterson. **Impossibility of Distributed Consensus with One Faulty Process.** PODS, 1983; journal version 1985. [Author-hosted conference paper](https://groups.csail.mit.edu/tds/papers/Lynch/pods83-flp.pdf).

\[10\] NIST. **Module-Lattice-Based Key-Encapsulation Mechanism Standard.** FIPS 203, 2024. [Standard and updates](https://csrc.nist.gov/pubs/fips/203/final).

\[11\] NIST. **Module-Lattice-Based Digital Signature Standard.** FIPS 204, 2024. [Standard and updates](https://csrc.nist.gov/pubs/fips/204/final).

\[12\] NIST. **Stateless Hash-Based Digital Signature Standard.** FIPS 205, 2024. [Standard and updates](https://csrc.nist.gov/pubs/fips/205/final).

\[13\] IETF. **Post-Quantum Traditional Hybrid Key Agreement Mechanisms for TLS 1.3.** RFC 10024, 2026. [RFC Editor](https://www.rfc-editor.org/rfc/rfc10024.html).

\[14\] H. Birkholz et al. **Remote ATtestation procedureS (RATS) Architecture.** RFC 9334, 2023. [RFC Editor](https://www.rfc-editor.org/rfc/rfc9334.html).

\[15\] Ryan Greenblatt et al. **AI Control: Improving Safety Despite Intentional Subversion.** 2023, revised 2024. [arXiv:2312.06942](https://arxiv.org/abs/2312.06942).

\[16\] David Dalrymple et al. **Towards Guaranteed Safe AI: A Framework for Ensuring Robust and Reliable AI Systems.** 2024. [arXiv:2405.06624](https://arxiv.org/abs/2405.06624).

\[17\] Martin A. Nowak. **Five Rules for the Evolution of Cooperation.** Science, 2006. [Open author manuscript](https://pmc.ncbi.nlm.nih.gov/articles/PMC3279745/).

\[18\] Sergio A. Muñoz-Gómez et al. **Site-and-branch-heterogeneous analyses of an expanded dataset favour mitochondria as sister to known Alphaproteobacteria.** Nature Ecology & Evolution, 2022. [Research article](https://www.nature.com/articles/s41559-021-01638-2).

\[19\] J. C. R. Licklider. **Man–Computer Symbiosis.** IRE Transactions on Human Factors in Electronics, 1960. [MIT-hosted text](https://groups.csail.mit.edu/medg/people/psz/Licklider.html).

\[20\] Adi Shamir. **How to Share a Secret.** Communications of the ACM, 1979. [DOI record](https://doi.org/10.1145/359168.359176).

\[21\] A2A Project. **Agent2Agent Protocol Specification.** [Official specification](https://a2a-protocol.org/latest/specification/). Implementations must pin a version.

\[22\] Model Context Protocol. **Authorization specification.** [Official documentation](https://modelcontextprotocol.io/specification/latest/basic/authorization). Implementations must pin a version.

\[23\] W3C. **Decentralized Identifiers (DIDs) v1.0.** 2022. [W3C Recommendation](https://www.w3.org/TR/did-1.0/).

\[24\] **Beyond DNS: Unlocking the Internet of AI Agents via the NANDA Index and Verified AgentFacts.** 2025. [arXiv:2507.14263](https://arxiv.org/abs/2507.14263).

\[25\] Jean-Baptiste Mouret and Jeff Clune. **Illuminating search spaces by mapping elites.** 2015. [arXiv:1504.04909](https://arxiv.org/abs/1504.04909).

\[26\] **HyperCycle Core, version 1.16.** 2026. Author-specified architecture reference identified in the supplied v0.828d technical baseline. A conforming implementation must publish or provide the exact specification, version hash and verification artifacts it relies on; this citation does not certify a deployed implementation.

**Paper license:** [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/). This license concerns the paper; it does not relicense third-party software, models, node credentials, patents, or cited publications.
