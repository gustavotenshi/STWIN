# STWIN

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.22676355-blue)](https://doi.org/10.5281/zenodo.22676355)
[![Zenodo](https://img.shields.io/badge/Zenodo-Official_publication-blue)](https://zenodo.org/records/22676356)
[![Manuscript version](https://img.shields.io/badge/Manuscript-v1.0-green)](STWIN_Paper_EN.md)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey)](https://creativecommons.org/licenses/by/4.0/)

**Subluminally Transported Wormhole Infrastructure Networks**

A conceptual framework for interstellar infrastructure based on the subluminal transport of traversable wormhole mouths.

STWIN explores a question: **if controllable traversable wormholes are physically possible, how could they function as a persistent communication and transport network between stellar systems?**

The central idea separates **the time required to install a connection** from **its operational latency after installation**. A probe would make the first journey at a speed below that of light, carrying one wormhole mouth. If the connection survived the journey and remained usable, subsequent interactions could travel through its internal path.

> **Status:** conceptual research and a conditional theoretical architecture. The paper does not present a demonstrated technology or an engineering design realizable under current physics. The physical feasibility of the required components is a foundational assumption of the model.

**Official academic publication:** [view the Zenodo record](https://zenodo.org/records/22676356). **DOI:** [10.5281/zenodo.22676355](https://doi.org/10.5281/zenodo.22676355).

To read the manuscript in this repository, open the [full English paper](STWIN_Paper_EN.md) or download the [Word version](STWIN_Paper_EN.docx). The manuscript identifies itself as **version 1.0 — September 2026**.

**Follow the research:** see the [master research roadmap](STWIN_Master_Research_Roadmap_EN.md) in English and the [first temporal conclusion — NER/SNT](<STWIN-T1 — Network Epoch Reset and Forward-Time Operational Principle.md>) in English. The next defined step is **SRP-2.1 — Two-Mouth Causal Model**.

## Contents

- [About the project](#about-the-project)
- [Repository contents](#repository-contents)
- [Current research status](#current-research-status)
- [Getting started](#getting-started)
- [How the architecture works](#how-the-architecture-works)
- [Key concepts](#key-concepts)
- [Example: Proxima Centauri](#example-proxima-centauri)
- [Capability levels](#capability-levels)
- [Assumptions and limitations](#assumptions-and-limitations)
- [Reading guide](#reading-guide)
- [Research agenda](#research-agenda)
- [Contributing](#contributing)
- [Publication and versioning](#publication-and-versioning)
- [References and citation](#references-and-citation)
- [License](#license)

## About the project

STWIN treats hypothetical connections between stellar systems as infrastructure: stellar systems are nodes, traversable connections are edges, and probes install new network endpoints.

The paper's proposed contribution is **architectural**. Transporting a wormhole mouth already appears in the literature discussed in the manuscript; STWIN organizes that scenario around deployment, latency, capacity, redundancy, causal safety, and network expansion.

The material is intended for readers interested in relativity, gravitation, interstellar communication, and network theory. Familiarity with special and general relativity helps with the technical sections, while the introduction presents the proposal conceptually.

## Repository contents

| File | Contents |
| --- | --- |
| [README.md](README.md) | English project overview, reading guide, and contribution instructions. |
| [STWIN_Paper_EN.md](STWIN_Paper_EN.md) | English manuscript with 21 sections, equations, a case study, and references. |
| [STWIN_Paper_EN.docx](STWIN_Paper_EN.docx) | Word version of the paper. |
| [Master research roadmap](STWIN_Master_Research_Roadmap_EN.md) | English research program, version 1.0, covering 30 research domains (SRP-0 through SRP-29), questions, dependencies, and progress states. |
| [Roadmap in Word](STWIN_Master_Research_Roadmap_EN.docx) | English Word version of the roadmap. |
| [Original Portuguese roadmap](STWIN_Master_Research_Roadmap_PT-BR.docx) | Original Portuguese document retained for reference. |
| [NER/SNT temporal conclusion](<STWIN-T1 — Network Epoch Reset and Forward-Time Operational Principle.md>) | English note on Network Epoch Reset, STWIN Network Time, and the Forward-Time Operational Principle. Identified in the text as STWIN-C3. |

This is a documentation repository. It currently contains no software, simulators, experimental datasets, runtime dependencies, or automated test suite.

## Current research status

The [master roadmap](STWIN_Master_Research_Roadmap_EN.md) records the following state of the program:

| Research item | Status |
| --- | --- |
| STWIN v1 conceptual paper | Published. |
| Initial question about proper-time differences | Concluded at the conceptual level. |
| Network Epoch Reset and Forward-Time Operational Principle | Conceptually adopted. |
| STWIN Network Time | Architecture selected; mathematical formalization pending. |
| Physical realization of NER/SNT | Open. |
| SRP-2.1 — Two-Mouth Causal Model | Next defined step. |
| Moving-mouth dynamics, energy, capacity, and networks | Future investigations. |

### First temporal conclusion

The [NER/SNT note](<STWIN-T1 — Network Epoch Reset and Forward-Time Operational Principle.md>) adopts an architecture in which each mouth retains its relativistic history and proper time. The two endpoints are not required to accumulate equal amounts of proper time.

At activation, **Network Epoch Reset (NER)** establishes a logical operational reference. **STWIN Network Time (SNT)** organizes infrastructure events without replacing local clocks. The **Forward-Time Operational Principle** requires, for each admissible traversal:

```text
T_out = T_in + δ_W, with δ_W > 0
```

The note distinguishes **STWIN-COM**, for communication, from **STWIN-TRANS**, for matter transport. Seconds or less are an architectural target for communication; transport could tolerate larger positive latencies. These values are not demonstrated capabilities.

**Scope of the conclusion:** NER/SNT defines a logical layer and an operational requirement. The correspondence between this ordering and physical causal structure still needs to be demonstrated. Redefining clocks does not change the geometry or, by itself, eliminate closed timelike curves. The hypothesis of *Active Wormhole Compensation* also remains open.

The conclusion's filename uses the prefix **STWIN-T1**, while its title and the roadmap use **STWIN-C3**. Both refer to the note linked above.

### Next question — SRP-2.1

With one mouth on Earth and another at Proxima Centauri, what physical condition guarantees that a traversal satisfying `T_out > T_in` in SNT is also future-directed in the causal structure of spacetime?

The roadmap defines the scope as **two mouths, one message, and causal structure**. This step should model the mouth worldlines, entry and exit events, and the relationship between SNT and physical causality. Multi-node networks and advanced energy, transport, and security requirements belong to later stages.

## Getting started

### Read on GitHub

Open the [Markdown manuscript](STWIN_Paper_EN.md). To read or edit it in a word processor, download the [`.docx` file](STWIN_Paper_EN.docx) and open it in a compatible application.

### Get a local copy

With Git installed:

```sh
git clone https://github.com/gustavotenshi/STWIN.git
cd STWIN
```

You can also download the repository through **Code → Download ZIP** on GitHub without installing Git.

Open `STWIN_Paper_EN.md` in a text editor or Markdown viewer. The manuscript's equations use LaTeX notation; rendering depends on your viewer's support. Reading the documents requires no package installation, build process, or environment variable configuration.

## How the architecture works

1. **Preparation:** two connected mouths, `W_A` and `W_B`, start near each other in the origin system.
2. **Deployment:** `W_A` remains at the origin while a probe carries `W_B` to another system at a speed `v < c`.
3. **Destination installation:** the probe decelerates and places the remote mouth in a stable operational configuration.
4. **Operation:** if the geometry remains traversable and causally admissible, signals — and, under additional assumptions, matter — pass through the connection.
5. **Expansion:** nodes with industrial capacity and the ability to provision new mouths could send further probes and extend the network.

The manuscript also discusses a **remote-generation** variant in which the probe would create a mouth at the destination. This variant requires additional assumptions and should be distinguished from the baseline architecture of transporting an already connected mouth.

## Key concepts

| Concept | Meaning in STWIN |
| --- | --- |
| Causal installation cost | Time required to physically deliver a new endpoint to its destination. |
| Distance amortization | Reusing an installed connection for successive communications or traversals. |
| Topological network distance | Cost of traversing network connections, which may differ from the route through exterior space. |
| Chronology-safe deployment | Constraints on trajectories and connections intended to avoid closed timelike curves. |
| Recursive expansion | New nodes provision and launch missions to install further connections. |

The simplified relationships used in the paper are:

```text
Deployment time:          T_deploy ≈ D / v
Light propagation time:   T_light  = D / c
Low-latency condition:    τ_W ≪ D / c
```

Here, `D` is the exterior distance between systems, `v` is the probe's cruise speed, `c` is the speed of light, and `τ_W` represents the connection's effective traversal latency. The deployment estimate neglects acceleration and braking.

**Latency and capacity are distinct quantities:** even a hypothetical low-latency connection could have severe limits on bandwidth, energy, or matter flow.

## Example: Proxima Centauri

The manuscript's case study assumes an approximate distance of **4.24 light-years**. At constant cruise speed, deployment times in the origin frame would be:

| Cruise speed | Approximate deployment time |
| --- | ---: |
| `0.01c` | 424 years |
| `0.10c` | 42.4 years |
| `0.20c` | 21.2 years |
| `0.50c` | 8.48 years |

In this model, a light signal through exterior space would still take approximately **4.24 years one way**, or **8.48 years for a question and an immediate reply to return**. A STWIN connection's latency would depend on the hypothetical wormhole geometry; the project does not establish a physically realizable value.

These figures are illustrative estimates reproduced from the paper. They exclude acceleration, deceleration, and the transported mouth's stability requirements. At relativistic speeds, the probe's proper time also differs from the elapsed time in the origin frame.

## Capability levels

The paper distinguishes five capabilities, each with its own requirements:

| Level | Hypothetical capability |
| --- | --- |
| I | Classical signal transmission. |
| II | Quantum-state transfer with preservation of coherence. |
| III | Microscopic matter transit, such as atoms and molecules. |
| IV | Macroscopic cargo, equipment, and robot transport. |
| V | Biological or crewed transport under tolerable conditions. |

The feasibility of one level does not demonstrate the feasibility of the next. A connection capable of transmitting signals may be unsuitable for transporting matter or living organisms.

## Assumptions and limitations

STWIN's conclusions depend on the ability to:

- Create or obtain a macroscopic traversable wormhole.
- Accommodate and transport one of its mouths in a probe.
- Preserve the connection during acceleration, cruise, braking, and large spatial separation.
- Control the supporting energy and the geometry's backreaction to signals or matter.
- Maintain a configuration globally consistent with causal constraints.
- Achieve useful transmission or transport rates.

The manuscript identifies negative energy and its quantum constraints, throat stability, temporal offsets between mouths, possible closed timelike curves, and gravitational backreaction from traffic as central obstacles.

In the paper's formulation, **ordinary quantum entanglement is not a controllable faster-than-light communication channel**. Its discussion of ER=EPR and theoretical traversability models does not provide a method for building macroscopic connections between stars.

The first deployment still requires a subluminal journey in the baseline scenario. Subsequent low latency is a conditional consequence of the postulated connection, with no experimental demonstration in the project.

## Reading guide

To follow the program, the suggested sequence is **conceptual paper → NER/SNT temporal conclusion → master roadmap**, focusing on the next question, SRP-2.1. All three documents are linked under [Repository contents](#repository-contents). The paper, conclusion, and roadmap are available in English; the original Portuguese roadmap is also retained.

The sections below belong to the [full manuscript](STWIN_Paper_EN.md):

| Interest | Sections |
| --- | --- |
| Understand the proposal and its scope | Abstract and 1–3: introduction, assumptions, and architecture. |
| Follow the illustrative calculations | 4–5: distance amortization and the Proxima Centauri case study. |
| Examine the physical obstacles | 6–9: chronology, negative energy, entanglement, and capacity. |
| Understand transport and deployment requirements | 10–11: capability levels and probe requirements. |
| Explore networks and expansion | 12–15: topologies, failures, recursive expansion, and the first crossing. |
| Examine operational implications | 16–17: translocation, identity, security, and governance. |
| Assess open questions | 18–19: falsifiability and research milestones. |
| Read the conceptual synthesis | 20–21: discussion and conclusion. |

## Research agenda

The [master roadmap](STWIN_Master_Research_Roadmap_EN.md) develops the paper's agenda into 30 domains. The table summarizes their scope; individual question statuses and dependencies are recorded in the full document.

| Domains | Scope |
| --- | --- |
| SRP-0–2 | Foundations, minimal assumptions, temporal architecture, causality, and chronology. |
| SRP-3–4 | Wormhole geometry and moving-mouth dynamics. |
| SRP-5–6 | Deployment missions, trajectories, effective mass, and propulsion energy. |
| SRP-7–8 | Exotic energy, stress-energy, stability, and traffic backreaction. |
| SRP-9–10 | Communication, channel capacity, and quantum information. |
| SRP-11–13 | Network theory, causal graphs, and distributed time. |
| SRP-14–16 | Autonomous control, AI, safety, and security. |
| SRP-17–18 | Matter transport and additional requirements for biological transport. |
| SRP-19–20 | Recursive expansion and implications for a connected civilization. |
| SRP-21–22 | No-go conditions and alternative architectures. |
| SRP-23–27 | Simulations, mathematical formalization, falsifiability, observation, and experimental analogues. |
| SRP-28–29 | Incremental publications, research records, assumptions, decisions, and versioning. |

The immediate sequence starts with **SRP-2.1**, proceeds to Minkowski diagrams and temporal mappings (**SRP-2.2/2.3**), and then addresses chronology margins and closed-timelike-curve conditions (**SRP-2.4/2.5**). The next planned publication target is **Paper II — Temporal Architecture and Two-Mouth Causality**.

The program's method is to address one central question at a time, seek refutations, and record the conclusion, confidence level, objections, and open questions. Claims should distinguish established physics, known theoretical results, conditional extrapolations, STWIN hypotheses, and engineering speculation.

## Contributing

Useful contributions include mathematical corrections, identification of implicit assumptions, terminology review, relevant references, translations, and improvements to the presentation of the argument.

To propose a change:

1. Open an issue or prepare a pull request identifying the affected section and proposed change.
2. Explain the problem and your reasoning; for scientific changes, include sources and state the assumptions used.
3. Preserve the distinction between established results, theoretical results with restricted domains, and STWIN assumptions.
4. Check equations, units, references, links, and Markdown rendering.
5. When changing the manuscript, keep its `.md` and `.docx` versions consistent or state which version still needs updating.
6. For research advances, specify the corresponding SRP identifier, dependencies, and what has been concluded or remains open. Update the roadmap when a status changes.

This repository has no automated document synchronization or scientific validation process. Changes undergo documentary and conceptual review.

## Publication and versioning

The project uses two complementary spaces:

| Platform | Purpose |
| --- | --- |
| [Zenodo](https://zenodo.org/records/22676356) | Archived academic publication, identified by DOI and used as the citation reference. |
| [GitHub](https://github.com/gustavotenshi/STWIN) | Evolving documentation, Markdown manuscript, change history, issues, and technical discussion. It may also host future figures, simulations, and calculations. |

The roadmap and conclusion notes track research progress in the repository. Their presence does not imply a new version of the archived paper; the manuscript badge remains at `v1.0` until a corresponding formal update.

For future paper versions, such as `v1.1` or `v2.0`, the proposed publication workflow is:

1. Update and review the manuscript files, recording changes in a changelog.
2. Create a corresponding GitHub release with the version and release notes.
3. Publish the new version on Zenodo and record its DOI in the release notes.
4. Update this README's links and version badge to keep the materials aligned.

The Zenodo metadata should list `https://github.com/gustavotenshi/STWIN` as a related repository. This README already provides the link from GitHub to the academic publication.

## References and citation

The bibliography at the end of the [Markdown paper](STWIN_Paper_EN.md) includes works on traversable wormholes, chronology protection, quantum energy constraints, ER=EPR, and multi-mouth geometries, alongside the source used for the distance to Proxima Centauri.

To cite the academic publication, consult the metadata and citation export options in the [Zenodo record](https://zenodo.org/records/22676356). The DOI provided for the project is **[10.5281/zenodo.22676355](https://doi.org/10.5281/zenodo.22676355)**.

The manuscript is titled *STWIN: Subluminally Transported Wormhole Infrastructure Networks — A Conditional Framework for Persistent Interstellar Communication, Transport, and Topological Infrastructure*, version **1.0 (September 2026)**. When citing a specific version, use its corresponding DOI as displayed on Zenodo. When discussing changes available only on GitHub, also include the commit hash or a file permalink.

The repository does not currently include a `CITATION.cff` file.

## License

The paper and project documentation are made available under **[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)**.

See the linked license text for the applicable reuse terms. When reusing the material, credit the authorship, identify the license, and indicate any changes.
