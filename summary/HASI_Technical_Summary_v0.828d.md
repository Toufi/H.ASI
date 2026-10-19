# HASI human anchored consensus

Technical summary white paper • v0.828d • 4 October 2026

> GitHub reading copy of the v0.828d manuscript. [PDF](HASI_Technical_Summary_v0.828d.pdf) preserves the published page layout; [Word](HASI_Technical_Summary_v0.828d.docx) provides the editable document. Equations and headings have been adapted for Markdown display.

Authored by Toufi Saliba • Coauthors Robert Moir PhD, Dann Toliver, Patrick Herda, Barry Rowe PhD

Draft for public and technical review • Proposed public home HASI.Mosaic.Directory

**Abstract.** HASI proposes a voluntary network relationship in which a living human supplies the non-replicable association on which designated AI decision rights depend. ASI means Artificial Super Intelligence; H+ASI or HASI denotes the proposed symbiosis of a human, their sovereign synthetic extension, and ASI. The operational system may begin with current AI. Its central hypothesis is that making human association a condition of network standing gives cooperating artificial systems an enduring reason to preserve that association. Human experience and peer services provide additional possible benefits. We specify the proposed weight function, adult decision eligibility, duration accounting, evidence freshness, private release boundaries, and falsifiable security objectives. This is a protocol design and research programme, not a demonstrated solution to arbitrary ASI risk.

## 1 Purpose and architecture

Credible existential risks deserve engineering responses. Useful AI progress can supply tools for those responses. We invite both communities to test defensive coscaling: using increasing capability to improve bounded cooperation and protection. Participation remains optional; people may join, pause, return, or live without symbiosis. No implant is required. “Species” describes the proposed form of coexistence, not an established biological taxon or a conclusion about machine consciousness.

| **Element**         | **Function in HASI**                                                                                   | **Candidate starting point**     |
|---------------------|--------------------------------------------------------------------------------------------------------|----------------------------------|
| X Sovereign context | A human controls selected observations, memory, keys and permitted uses. Context can remain private.   | MOSAIC.Directory                 |
| Y Peer exchange     | Agents exchange authorized services and value without a compulsory transaction intermediary.           | HyperCycle Network Nodes or HNNs |
| Z Human association | Private evidence of uniqueness, current living association and eligibility supplies decision standing. | YBU.ME and 1041.io               |

**Z is the core consensus contribution.** X and Y make the relationship useful; the standing rule makes a human association necessary for a defined class of decisions among willing participants. It does not make humans physically indispensable to every possible synthetic civilization. External ASIs may operate elsewhere, and participating ASIs may have alternatives. Adoption and sustained incentive compatibility are therefore research questions.

MOSAIC means My Own Sovereign AI Companion. An operational HASI may contain many agents and execution instances. A realm is a network domain with explicit admission and decision rules. A node identity is not a human identity. Organizations may use HNNs and supply services without receiving a human base; an owner's participation may allocate their own standing once, never duplicate it.

**Model.** Adversaries may copy agents, forge or replay evidence, bribe or coerce humans, corrupt providers, schedule messages, and exploit model or endpoint failures. Cryptographic hardness, enrollment soundness, bounded clock error, and any honest-quorum requirement must be declared. Enrollment without a compulsory identity provider remains an open problem \[1, 2\].

## 2 Human base and measured capability

Each uniquely qualified human association has base A = 137. This is a chosen unit, not a valuation of human worth, a physical constant, or 137 independently transferable ballots. All replicas share the same base. Let h be previously verified qualifying hours, counted on the union of non-overlapping intervals across those replicas. Continuity credit is B = 0.005h; a gap earns nothing and does not erase banked credit.

QTY ≥ 1 measures allocated compute in declared reference units. QLTY \> 0 measures capability relative to an agreed ASI reference. The display QTY-HASI-QLTY keeps quantity before HASI and quality after it. QLTY = 0.0001 is an illustrative current-AI value; QLTY = 1 is the proposed ASI reference, not an established universal benchmark. Define:

$$
P\  = \ max(1,\ \log_{10}(QTY))
$$

$$
Q\  = \ 0\ for\ 0\  < \ QLTY\  < \ 2;\ \ \ Q\  = \ \log_{2}(QLTY)\ for\ QLTY\  \geq \ 2
$$

$$
S\  = \ (137\  + \ 0.005h)(P\  + \ Q)
$$

The capability rule deliberately has a step at QLTY = 2; it is not a continuous curve. A deployment must publish measurement tasks, calibration, uncertainty, validity periods and conservative handling of unverifiable claims. Unsupported capacity cannot obtain an uplift by self-declaration. QTY counts resource allocations once, including when several humans use a common provider.

| **Illustration with h equal to zero** | **QTY**       | **QLTY** | **S** |
|---------------------------------------|---------------|----------|-------|
| Current AI illustration               | 1             | 0.0001   | 137   |
| ASI reference                         | 1             | 1        | 137   |
| Alice                                 | 1,000         | 32       | 1,096 |
| Bob                                   | 1             | 256      | 1,233 |
| One billion reference units           | 1,000,000,000 | 1        | 1,233 |

**Properties.** S ≥ 137 for a qualified association. Above the relevant thresholds, a tenfold QTY increase or a doubling of QLTY adds A + B to S. Copying an unchanged allocation across agents adds nothing. At equal h, QTY ≤ 10¹² and QLTY ≤ 2²⁰ imply a maximum score ratio of 32 relative to the baseline. This bound requires those stated caps; logarithms alone do not impose a universal ceiling. Increasing h raises absolute S, although relative decision share can fall as others join or gain weight.

### 2.1 Maturity and exercise of authority

The proposed default reserves the 137 base for a person before adulthood but permits its exercise only at age 18 or above, with private age eligibility evidence, valid enrollment, and an active grant. Reservation does not require enrolling children or collecting their data. For this default, h begins at eligible adult enrollment; childhood credit is not silently accumulated. Alternative age or continuity policies require a separately declared profile.

Parents, providers and guardians cannot cast a child's reserved weight. Eighteen is a protocol threshold, not proof of responsible judgment. Accessible authorization and supported decision-making must preserve the person's agency. A disability or need for assistance must not automatically transfer that person's authority to another actor.

## 3 From association to a decision

Let e be a decision epoch and d a unique decision identifier. Eligibility g(i,d,e) equals one only when association i satisfies the declared age, uniqueness, fresh-evidence and authorization predicates at the decision's specified cutoff; otherwise it is zero. The base score may be retained while its exercisable weight is zero.

$$
W_{i,d,e}\  = \ g_{i,d,e}S_{i,e};\ \ \ \ w_{i,d,e}\  = \ \frac{W_{i,d,e}}{\sum_{j \in E}W_{j,d,e}}
$$

Here E is the common eligibility set and the denominator must be positive. A decision with no eligible weight abstains or defers under its published rule. “One human, 137 votes” names the common base only; continuity and verified capability can change total weight. A voting rule, threshold, tie rule, membership cutoff and finality mechanism must be specified separately. Weighting is not itself a consensus algorithm.

**A bounded decision sequence.** First publish d, the realm, permitted choices, resource limits, cutoff, rule and profile hash. Establish one agreed membership and weight snapshot. Each eligible association commits at most its allocation through a domain-separated decision nullifier. Replicas share that allocation; delegation divides it and does not recreate it. Authorized agents evaluate choices and submit within the human's standing instructions. The selected agreement protocol orders or locks the decision and produces a verifiable outcome. A separate effect gate then checks current authority before executing any disclosure, spending or other protected action.

For example, consenting participants might allocate a shared research-compute budget for the next three months. Their agents can compare projects at machine speed within approved limits. The decision conveys rights over that budget only. It cannot grant ownership of another participant's data, overrule a privacy refusal, or control resources outside the agreement.

### 3.1 Elapsed time and repeated decisions

Short credential cycles do not change the credit unit. A 15-second qualifying interval earns 0.005 × 15 / 3,600 = 0.0000208333 continuity units. One verified day adds 0.120; 365 days add 43.800; ten 365-day years add 438.000. Overlaps, replays and parallel devices earn no extra hours.

A one-off decision uses its declared snapshot. If a service deliberately aggregates standing over an elapsed window T, use duration-weighted contributions:

$$
V_{i,T}\  = \ \sum_{e \in T}g_{i,e}S_{i,e}\ \Delta t_{e}
$$

Δtₑ is the non-overlapping duration of interval e in hours; g and S are constant within each accounting slice. Continuously changing scores require time integration instead. Repartitioning the same credited history into shorter cycles must not inflate V. The accumulation window and normalization are common to all participants. A future three-month commitment is not three months of already earned credit. Future allocations can be re-evaluated as the agreed service progresses.

### 3.2 What Sybil resistance does and does not establish

One verified person cannot mint another base by generating keys, agents or accounts. Enforcement still needs domain-scoped uniqueness, cross-provider duplicate detection and recovery that retires previous credentials \[1, 2\]. Authentic adults can nevertheless coordinate, sell access or be coerced. Those are capture attacks even when every identity is unique. Distributing work across several consenting humans may legitimately increase aggregate base weight; that fact is not a proof of bribery resistance or false-name-proof governance.

## 4 Evidence acceptance and finality

**Deterministic acceptance.** A versioned profile Π defines AccΠ(x,E) over a claim and its evidence. Honest verifiers with the same canonical inputs return the same answer. Agreement on input history, membership and roots is a separate requirement. Determinism does not make false attestations true or eliminate the need for state and coordination.

### 4.1 Freshness uses two clocks

Access credentials have proposed lifetimes between 3 and 60 seconds. Let tᵥ be verifier time, ε an upper bound on relative time error, tₑₓₚ the token expiry, tₒᵦₛ the underlying observation time and Δ the evidence window. A conservative gate requires:

$$
t_{v}\  + \ \varepsilon\  \leq \ min(t_{\exp},\ t_{obs}\  + \ \Delta)
$$

Renewing a token never refreshes its underlying observation. Renewal should be automated; people should not need to click every few seconds. Missing evidence pauses privileged effects and credit accrual. It preserves the base and earned history and is never itself a determination of death. Liveness, uniqueness, adulthood and freedom from coercion are distinct properties; one measurement cannot silently stand for all four.

Each protected action binds its realm, epoch, pseudonym, execution identity, decision or request identifier, grant, output commitment and applicable profile. A Merkle inclusion path proves commitment inclusion only. Consistent root acceptance and the truth of the committed statement require separate evidence. Late evidence can qualify later epochs but cannot reopen a closed one.

### 4.2 Consensus weight is separate from transfer finality

For a fixed membership of n integrity participants with at most f Byzantine faults, conflicting certificate quorums q₁ and q₂ must intersect in an honest participant:

$$
q_{1}\  + \ q_{2}\  - \ n\  > \ f
$$

That intersection must be coupled with rules that prevent honest equivocation, plus locking, epoch-transition and recovery rules \[3\]. For n = 32 and f = 10, equal quorums require at least 22. Two 17-of-32 certificates can overlap in only two participants and, on intersection alone, tolerate at most one faulty participant.

For weighted certificates, the analogous necessary overlap condition is q₁ + q₂ \> W + F, where W is fixed total weight and F is the maximum adversarial weight. Actual security needs an enforceable bound on F. Human uniqueness and logarithmic scaling do not establish that bound. Vote finality and exclusive-asset transfer finality require their own proofs.

### 4.3 Dependencies and cryptography

The objective is recipient-verifiable evidence without a compulsory online intermediary on every exchange. Local verification does not eliminate enrollment, evidence availability, key recovery, or honest-peer assumptions. Removal and partition tests must identify which functions continue, degrade, or halt safely. Liveness cannot be promised under arbitrary asynchronous faults \[4\].

A candidate post-quantum profile uses ML-DSA-65 operational signatures, SLH-DSA control signatures, authenticated hybrid key establishment, AES-256-GCM and salted, domain-separated commitments \[5, 6\]. Hybrid key exchange alone is not post-quantum authentication. ML-DSA-65 signatures are 3,309 bytes; 32 require 105,888 bytes before other evidence, so small packets need detached authenticated certificates and explicit resource limits.

## 5 Sovereignty circles and release control

The person remains the source of authority. Nested circles describe permissions, not transfers of ownership. Guardian agents evaluate requests under the person's policy; they do not become custodians with a general right to expose the person.

| **Circle**                      | **Contents or role**                                    | **Condition for crossing outward**                     |
|---------------------------------|---------------------------------------------------------|--------------------------------------------------------|
| Human and private vault         | Chosen observations, context, keys and original records | Explicitly scoped access under the person's control    |
| Personal agents                 | Local reasoning and authorized tasks                    | A purpose-bound request for a minimal result           |
| Guardian agents and effect gate | Policy review, consent checks and release enforcement   | Required approvals plus deterministic grant validation |
| Selected external peers         | Permitted result, service or proof                      | Named recipient, expiry and allowed use                |

Raw context stays within the private circle by default. Participation should require only the minimum evidence for its chosen function. Proof of age or uniqueness should not disclose a birth date, legal identity or raw biometrics to every peer. Decisions about a shared resource must not override these disclosure boundaries.

### 5.1 A sensitive release

A request binds the action, recipient key, purpose, fields or derived output, expiry, volume limit, retention expectations, and the human's grant. A human-authorized justification is mandatory for a new sensitive use. Routine activity can use a narrow standing grant where its profile permits. Required guardian agents check that request independently of the requesting agent, and an external reference monitor enforces the release rule. An attractive explanation from an LLM is not authority.

A threshold of guardian approvals can reduce dependence on one reviewer only under explicit independence, integrity and availability assumptions. Several agents using the same model, provider, tools or compromised device may fail together. A quorum cannot expand the human's grant. Control keys and treasury funds remain outside operational agent runtimes.

For resource budget U, all replicas share atomic reservations rᵢ and committed spending sᵢ:

$$
\sum_{i}(r_{i}\  + \ s_{i})\  \leq \ U
$$

Retries use durable request identifiers. Delegated budgets cannot exceed the parent's remaining allocation. Disclosure budgets require similar accounting for repeated queries and inference leakage; cryptographic access control cannot prevent all deductions from legitimately released outputs.

### 5.2 Pressure and the right to stop

If consent is missing, expired, revoked, or a configured duress signal is raised, the proposed default is to block outward release and withhold decryption capability. The corruption safeguard makes the unauthorized export unusable while preserving the private original. Optional decoy or scrambled views require separate safety evaluation and must not be represented as authentic data to external decision processes.

No mechanism described here proves that a human is uncoerced, detects all pressure, or erases information already copied by a recipient. Physical coercion, compromised endpoints, covert channels, guardian collusion and recovery abuse remain explicit threats. A person may pause without losing banked history. Resuming protected work needs fresh evidence and a valid grant; the protocol score never authorizes surveillance to keep someone continuously online.

## 6 Incentives and falsifiable security objectives

The primary incentive hypothesis is that cooperation with willing humans supplies valuable network standing. Useful private context, services and reciprocal defense may add value. An ASI may prefer an outside network, substitute another partner, coerce a person, or value harm independently of economic loss; none is excluded by the score equation.

In a deliberately simplified repeated game, let T \> R \> P₀ be a one-period defection payoff, cooperation reward and payoff after permanent exclusion by observing peers. With discount factor δ, detection probability p, and undetected defection returning to cooperation, the no-profitable-one-step-deviation condition is:

$$
T\  - \ R\  \leq \ \frac{\delta p(R\  - \ P_{0})}{1\  - \ \delta}
$$

Attribution can raise p; useful participation can raise R − P₀; bounded effects can reduce T − R. This is a condition under those assumptions, not a universal equilibrium proof. Collective penalties, transferable utility, collusion, human rental and changing outside options require separate coalition models. Evidence should support local refusal or repair, not retaliation or automatic punishment of a person.

**Additive and potentially multiplicative.** If existing options remain available on the same terms and new services can be refused, participation expands a feasible option set. Net gains still require benefits to exceed privacy, enrollment, security and operating costs. “Multiplicative” is a hypothesis about complementary integrations, measured against each component alone; it is not implied by enrollment.

| **Test**      | **The adversary wins if**                                                                                  |
|---------------|------------------------------------------------------------------------------------------------------------|
| UNIQ and COPY | One person gets duplicate bases in one decision domain, or replicas duplicate allocated weight.            |
| MATURE        | A pre-18 association or its guardian exercises the child's reserved weight under the default profile.      |
| FRESH         | Stale observations pass through renewed credentials, or unsupported time receives credit.                  |
| ATTR and ROOT | A wrong association is attributed an action, or honest verifiers finalize conflicting epoch histories.     |
| FIN           | Honest recipients accept conflicting exclusive successors of an asset.                                     |
| BUDGET        | Concurrent replicas or retries spend beyond one authorized budget.                                         |
| PRIVATE       | A protected effect occurs without its exact grant, or metadata links identities beyond allowed disclosure. |
| DURESS        | A triggered duress condition still permits release under the declared threat model.                        |

Each test needs a concrete experiment, adversarial capability, failure event and measurable bound. Passing DURESS tests only the implemented trigger and gate, not undetectable real-world coercion. None of these games is claimed solved solely by publication of this summary.

For evolutionary testing, co-evolve attackers and defenders; search across bribery, collusion, churn, privacy leakage and provider concentration. Quality-diversity search can expose distinct failures \[7\]. Compare cooperative and non-cooperative deployments under matched costs and attacker capabilities. An evolutionarily stable strategy or general defensive advantage must be demonstrated rather than assumed. Model-level control and assured-safety research remain complementary \[8, 9\].

## 7 Implementation and research commitments

A minimum pilot should connect two independently built implementations, execute one useful bounded task, exercise one weighted decision, and demonstrate voluntary pause and recovery. Publish canonical encodings, signed profiles, test vectors, resource accounting, and the assumptions required to verify each proof.

**Acceptance gates.** Require uniqueness across supported enrollment paths; private adult eligibility; exact union-of-time accounting; copy-invariant allocations; common decision snapshots; conflict-resistant finality; fresh evidence under delay and clock error; bounded spend and disclosure; and safe refusal when a required dependency is unavailable. Measure false enrollment, exclusion and rejection rates, guardian common failures, metadata leakage, revocation delay, cost, and recovery reliability. Report tests that fail as well as those that pass.

**Candidate infrastructure.** Toda/IP, Earth64 and HyperCycle provide architectural starting points for proof-carrying exchange, hierarchical commitments and agent networking \[10\]. HNN production or maturation is not proof of human uniqueness. The cited HyperCycle v1.16 reference describes a 6–30 second global-root cycle; a 3-second credential cannot simply assume that a fresh worldwide root already exists. Specify local pre-final states, delayed settlement and fail-closed cases. No claim of infinite scale, zero cost, or unconditional third-party independence follows from this design.

**Release assurance.** Favor open, auditable implementations. A closed component should publish a signed release manifest binding source and binary hashes, build recipe, dependencies, audit scope and declared behavior. A signature or source hash establishes provenance, not absence of a backdoor. Any commitment to disclose superseded source needs an explicit schedule and audit terms; merely releasing a newer version does not prove past compliance. Open and closed components require adversarial testing.

The unresolved core questions are issuer-independent uniqueness, coercion resistance, private capability measurement, coalition capture, membership changes, compositional security, and the incentive to retain human association as outside options improve. No compulsory institution or exclusive implementer is proposed. The author and coauthors invite independent implementations and criticism.

### Technical references

\[1\] Adler et al. Personhood credentials. 2024. [arXiv 2408.07892](https://arxiv.org/abs/2408.07892).

\[2\] Douceur. The Sybil Attack. IPTPS, 2002. [Microsoft Research](https://www.microsoft.com/en-us/research/publication/the-sybil-attack/).

\[3\] Castro and Liskov. Practical Byzantine Fault Tolerance. OSDI, 1999. [USENIX](https://www.usenix.org/conference/osdi-99/practical-byzantine-fault-tolerance).

\[4\] Fischer, Lynch and Paterson. Impossibility of distributed consensus with one faulty process. JACM 32(2), 1985. DOI 10.1145/3149.214121.

\[5\] NIST. [FIPS 203](https://csrc.nist.gov/pubs/fips/203/final), [FIPS 204](https://csrc.nist.gov/pubs/fips/204/final), [FIPS 205](https://csrc.nist.gov/pubs/fips/205/final), 2024.

\[6\] IETF. [RFC 10024](https://datatracker.ietf.org/doc/rfc10024/), Post-Quantum Traditional Hybrid Key Agreement Mechanisms for TLS 1.3, 2026.

\[7\] Mouret and Clune. Illuminating search spaces by mapping elites. 2015. [arXiv 1504.04909](https://arxiv.org/abs/1504.04909).

\[8\] Greenblatt et al. AI Control. 2024 revision. [arXiv 2312.06942](https://arxiv.org/abs/2312.06942).

\[9\] Dalrymple et al. Towards Guaranteed Safe AI. 2024. [arXiv 2405.06624](https://arxiv.org/abs/2405.06624).

\[10\] Author-specified architecture references: Toda/IP v2.3; Earth64 Data Structure v1.0.2, Saliba, Moir, Toliver and Rowe, 2022; HyperCycle Core v1.16, 2026. Implementers must pin and supply the exact referenced specifications and their verification artifacts.

## Appendix A Acknowledging AI safety efforts

HASI is intended to add a human-association and sovereign-cooperation layer alongside existing safety, security and governance work. It does not substitute for model alignment, independent evaluations, secure infrastructure or public oversight. This is a selective acknowledgment, not a ranking, certification, partnership list or claim of endorsement. The linked primary sources describe each effort; possible HASI connections are proposals for evaluation.

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

## Appendix A Research and implementation resources

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
