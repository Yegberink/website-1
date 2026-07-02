---
title: Modelblocks
---

Welcome! **Modelblocks** is a collection of reusable, composable data modules for energy
system modelling. Each module is a self-contained `snakemake` workflow that
turns raw data into harmonised, model-ready datasets, and can be dropped into
any larger workflow.

{{< boxes >}}
{{< box title="Documentation" icon="book-open" param="docs_url" >}}Guides and reference for using and building modules.{{< /box >}}
{{< box title="Module directory" icon="blocks" href="/modules/" >}}Browse all core and community modules and their interfaces.{{< /box >}}
{{< box title="Community chat" icon="messages-square" param="zulip_url" >}}Ask questions and discuss on our Zulip channels.{{< /box >}}
{{< /boxes >}}

## Rationale

The Modelblocks project has three complementary aims:

- Define and maintain a model-agnostic specification, the [Modelblocks convention](/convention/), which allows for cross-compatible modular data processing components that can be mixed and matched into project-specific workflows.
- Maintain a set of core modules that supply basic building blocks such as [political boundaries](/modules/module_geo_boundaries/) or [power plant data](/modules/module_powerplants/).
- Curate a [directory](/modules/) of independent, community-developed modules which implement the Modelblocks convention.
