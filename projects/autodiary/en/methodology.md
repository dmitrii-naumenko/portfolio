[Русская версия](../docs/methodology.md)

# Analytics core methodology

[Home](README.md) · [Product vision](vision.md)

This document describes one component of Autodiary: the analytics core, covering metric calculation, data quality, and analytical findings. Other components and workflows are described in the [product vision](vision.md).

The analytics core separates observations, calculated indicators, interpretation and decisions. This makes it possible to inspect the basis of a finding and revisit it when new data appears.

## Metric calculation

**Domains and dependencies.** Metrics belong to nine domains: sleep, activity, health, body, mentality, family, emotions, diary and system. Composite indicators depend on components; configuration defines their meaning and relationships.

**Periods.** Each metric has an aggregation period: day, week, month or quarter. Comparisons consider the indicator’s meaning and the observed period.

**Direction.** A higher value may be better, worse, optimal only within a range, or have no evaluative direction. Interpretation belongs to the particular metric.

**Incomplete periods.** Current periods use the elapsed portion when supported by the indicator. A partial value remains distinct from a complete-period result.

**Coverage.** Zero and missing data are different states. Values carry calculation statuses: success, no observations, insufficient observations, no valid observations, or an initial data-collection period.

**Versions.** Values are associated with a version of the calculation methodology. Changes to the definition or calculator make outdated results detectable and historical recalculation possible.

## From an observation to a finding

1. Identify a change and inspect the available data, period and observation quality.
2. Connect it with relevant events, diary context and other indicators.
3. Separate an established observation from interpretation and a hypothesis about its cause.
4. State the basis, limits and a next step that can be checked.

Events occurring together do not establish causality. New evidence can strengthen, weaken or change a conclusion. Missing information is not replaced with invented data.

## Accumulating experience

Insights retain links to sources and assessments of confidence and usefulness. New findings are compared with existing ones to reduce repetition and enrich prior observations.

The lifecycle distinguishes an active finding, an accepted and implemented idea, and a declined one. The owner’s comment helps explain the outcome and informs the next recommendation. Understanding an idea does not mean it has been tested in practice.

Knowledge from books and other materials may support interpretation and the choice of an exercise. It does not replace personal evidence or turn an individual hypothesis into a demonstrated effect.

## Quality and boundaries

Calculation checks, data quality and analytical discipline serve different purposes. A passing calculation test does not establish a recommendation’s causal effect. Detailed personal context stays inside the private system; the public showcase contains selected materials and clearly identified demonstrations.

Health and training workflows help interpret available data and prepare questions while preserving the limits of the source information. They do not provide a medical diagnosis.
