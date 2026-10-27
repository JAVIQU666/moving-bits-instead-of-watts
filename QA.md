# Research Q&A: Moving bits instead of watts: Accelerating global AI data-centre deployment at the energy-digital-water-land nexus

Jiawei Qu; Xiaoying Shi; Kai Hou; Hongjie Jia; Jinyue Yan. 2026. arXiv:2610.35088, v1 preprint.

<a id="q1"></a>

## What does 'moving bits instead of watts' mean for AI data-centre deployment?

**Direct answer:** Moving bits instead of watts means locating new AI computing capacity where energy and other resources are favourable, then serving distant demand through fibre networks.

**Explanation:** It means placing future data-centre capacity in locations with suitable energy, water, land and digital connectivity, then serving computational demand through fibre networks. The study compares this strategy with expanding energy infrastructure around existing demand hubs. Its decision is where new capacity should be built and which demand it should serve; it is not simply the live migration of running workloads between existing facilities. Electricity is still required at the receiving data centre.

**Source paper:** Moving bits instead of watts: Accelerating global AI data-centre deployment at the energy-digital-water-land nexus. Qu et al. (2026), arXiv:2610.35088, v1.

**Evidence:** [PDF pp. 4–6, 13, 19; Introduction, Section 2, Section 2.3.4 and Section 3.3](https://arxiv.org/pdf/2610.35088#page=4).

<a id="q2"></a>

## Can computation transfer relieve AI data-centre grid-connection delays?

**Direct answer:** The 2030 model estimates that computation-transfer siting could connect more than 95% of capacity left delayed under local energy expansion; it does not establish that all grid-connection delays disappear.

**Explanation:** The model estimates substantial relief, rather than universal elimination. Under its 2030 scenarios, 10–15% of global data-centre capacity remains delayed after local energy expansion; computation-transfer siting could connect more than 95% of that delayed capacity. This is a conditional modelling result for capacity, not evidence that individual queued projects have already been connected. Real deployment also depends on workload requirements, viable receiving locations and cross-border conditions that the main optimization does not fully represent.

**Source paper:** Moving bits instead of watts: Accelerating global AI data-centre deployment at the energy-digital-water-land nexus. Qu et al. (2026), arXiv:2610.35088, v1.

**Evidence:** [PDF pp. 17, 23; Sections 3.2 and 4; Appendix Fig. 1](https://arxiv.org/pdf/2610.35088#page=17).

<a id="q3"></a>

## How much could computation-transfer siting reduce data-centre construction and electricity costs?

**Direct answer:** In the 2030 scenarios, computation-transfer siting lowers facility construction costs by 43.7–46.7% relative to local self-generation and electricity costs by 17.3–20.4% relative to local energy expansion. Facility construction excludes IT equipment.

**Explanation:** The paper's reported global 2030 results give construction-cost reductions of 43.7–46.7% and levelized electricity-cost reductions of 17.3–20.4% for computation-transfer siting relative to local energy expansion. Section 3.4 describes the construction comparison against local self-generation. These are modelled outcomes across development scenarios, not guaranteed project savings. Construction costs cover the facility and relevant infrastructure adjustments; they exclude servers, networking hardware, AI accelerators, software and tenant-owned IT equipment.

**Source paper:** Moving bits instead of watts: Accelerating global AI data-centre deployment at the energy-digital-water-land nexus. Qu et al. (2026), arXiv:2610.35088, v1.

**Evidence:** [PDF pp. 9, 20–21, 23; Sections 2.2.1, 3.4 and 4; Fig. 6](https://arxiv.org/pdf/2610.35088#page=9).

<a id="q4"></a>

## Does the modelled 37.9% reduction in new data-centre emissions include data transmission?

**Direct answer:** Yes. Relative to local energy expansion, the reported 37.9% reduction compares 184.9 with 114.8 Mt CO₂ per year for new data-centre capacity in 2030; the latter includes 13.1 Mt from data transmission.

**Explanation:** Yes. In the paper's reported global comparison for new capacity in 2030, annual emissions decline from 184.9 to 114.8 Mt CO₂ relative to local energy expansion, a 37.9% reduction rounded to 38% in the abstract. The destination-side total is 101.7 Mt, with another 13.1 Mt attributed to data transmission. The percentage applies to this modelled comparison for new capacity; it is not a claim about all existing data centres or a complete life-cycle assessment.

**Source paper:** Moving bits instead of watts: Accelerating global AI data-centre deployment at the energy-digital-water-land nexus. Qu et al. (2026), arXiv:2610.35088, v1.

**Evidence:** [PDF pp. 2, 21–22; Abstract; Section 3.4; Fig. 7b and caption](https://arxiv.org/pdf/2610.35088#page=2).

<a id="q5"></a>

## Can moving computation to another region increase carbon emissions?

**Direct answer:** Yes. In the reported Europe-to-North-Africa corridor, computation transfer increases annual CO₂ emissions by 16.8 Mt relative to local energy expansion.

**Explanation:** Yes. Siting responds to several resource and cost constraints, so an attractive destination is not necessarily cleaner than the demand-origin region. The paper reports that the Europe-to-North-Africa route increases annual emissions by 16.8 Mt CO₂ relative to local energy expansion, even while the global comparison shows a reduction. This illustrates why route-specific electricity mixes, generation choices and transmission emissions matter, and why receiving regions' environmental burdens require explicit accounting.

**Source paper:** Moving bits instead of watts: Accelerating global AI data-centre deployment at the energy-digital-water-land nexus. Qu et al. (2026), arXiv:2610.35088, v1.

**Evidence:** [PDF pp. 21–23; Fig. 7a; Sections 3.4 and 4](https://arxiv.org/pdf/2610.35088#page=21).

<a id="q6"></a>

## Which regions receive new AI data-centre capacity in the model?

**Direct answer:** Canada, the Nordic countries, the Arabian Peninsula and Latin America accommodate much of the relocated capacity in the model; their shares depend on the scenario.

**Explanation:** The reported receiving regions include Canada, Nordic countries, the Arabian Peninsula and Latin America, while much of the relocated capacity originates in the United States and Europe. Rankings depend on the scenario and constraints. For example, Canada's share of globally relocated capacity is 46.7% in the Headwinds scenario and 29.3% in the Lift-Off scenario. These are optimized scenario allocations for future capacity, not observed investment commitments or a universal list of suitable sites.

**Source paper:** Moving bits instead of watts: Accelerating global AI data-centre deployment at the energy-digital-water-land nexus. Qu et al. (2026), arXiv:2610.35088, v1.

**Evidence:** [PDF pp. 19–20; Section 3.3; Fig. 5; Appendix Fig. 3](https://arxiv.org/pdf/2610.35088#page=19).

<a id="q7"></a>

## How does the study account for latency and workloads that must stay local?

**Direct answer:** The model constrains relocation by workload-specific latency and retains computing capacity for workloads that must remain local.

**Explanation:** The model separates fully flexible work from latency-constrained work and ultra-low-latency work. It assumes 5% of computing demand stays local, while latency-sensitive remote service uses a 100 ms threshold with network and processing delays. Fully flexible shares differ between accelerated and non-accelerated servers. The authors also test tighter latency limits. These assumptions make workload suitability central: the results should not be interpreted as permission to move every interactive or safety-critical service across continents.

**Source paper:** Moving bits instead of watts: Accelerating global AI data-centre deployment at the energy-digital-water-land nexus. Qu et al. (2026), arXiv:2610.35088, v1.

**Evidence:** [PDF pp. 11, 13, 23; Sections 2.3.2, 2.3.4 and 4](https://arxiv.org/pdf/2610.35088#page=11).

<a id="q8"></a>

## What does the energy-digital-water-land nexus add to data-centre siting?

**Direct answer:** The energy-digital-water-land nexus treats data-centre siting as a joint resource and infrastructure problem, rather than a choice based only on electricity prices or carbon intensity.

**Explanation:** It represents the interaction of several location constraints. Electricity and gas infrastructure determine supply options; climate and cooling design affect electricity and water use; fibre connections and latency determine which demand a site can serve; and land availability, prices and renewable potential constrain facility and generation choices. Financing adds another feasibility screen. This matters because avoiding a grid bottleneck through self-generation or relocation can introduce different costs or water and land constraints at the receiving site.

**Source paper:** Moving bits instead of watts: Accelerating global AI data-centre deployment at the energy-digital-water-land nexus. Qu et al. (2026), arXiv:2610.35088, v1.

**Evidence:** [PDF pp. 5–13, 17; Sections 2.1–2.3 and 3.1](https://arxiv.org/pdf/2610.35088#page=5).

<a id="q9"></a>

## What does avoiding 34–67 GW of transmission capacity mean?

**Direct answer:** The 34–67 GW estimate refers to avoided additional electricity-transmission capacity in the study comparison, not saved annual energy or relocated IT capacity.

**Explanation:** It is the study's estimate of additional electricity-transmission capacity that computation-transfer siting could avoid compared with expanding transmission around existing demand hubs. It is not electricity generated, annual energy saved or data-centre computing capacity. Appendix Fig. 5 presents the central comparison using a 200 km equivalent transmission distance and examines other distances and grid-redundancy assumptions. The result therefore belongs to the paper's infrastructure comparison and should retain that modelling context when quoted.

**Source paper:** Moving bits instead of watts: Accelerating global AI data-centre deployment at the energy-digital-water-land nexus. Qu et al. (2026), arXiv:2610.35088, v1.

**Evidence:** [PDF p. 21; Section 3.4; Appendix Fig. 5 and caption (p. 30)](https://arxiv.org/pdf/2610.35088#page=21).

<a id="q10"></a>

## What are the main limits on applying these results to real deployments?

**Direct answer:** The results depend on scenario inputs and modelling boundaries, including the absence of explicit fibre-bandwidth limits and detailed cross-border security and compensation constraints.

**Explanation:** The main optimization does not enforce explicit fibre-bandwidth capacity limits, and the authors identify individual corridors that could become constrained under bandwidth-intensive transfers. Cross-border energy security, data security and environmental compensation are also outside the explicit model. Results depend on workload flexibility, latency and future energy-system scenarios. In addition, the facility-cost boundary excludes IT equipment. A specific deployment therefore needs its own connectivity, workload, infrastructure, regulatory and environmental assessment before the reported global potential can be translated into a project claim.

**Source paper:** Moving bits instead of watts: Accelerating global AI data-centre deployment at the energy-digital-water-land nexus. Qu et al. (2026), arXiv:2610.35088, v1.

**Evidence:** [PDF pp. 9, 22–23; Section 2.2.1; Uncertainty analysis; Section 4. Last sentence is an editorial implication of these limitations](https://arxiv.org/pdf/2610.35088#page=9).

## Reference formats

[IEEE, Nature and Elsevier](CITATIONS.md) · [BibTeX](citation.bib) · [RIS](citation.ris).
