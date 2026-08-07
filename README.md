# South African Grid Flexibility Explorer

**An interactive systems-mapping tool for understanding South Africa's electricity network as an interconnected whole — not a collection of isolated problems.**

🔗 [Live Project](https://tadia-siwisa.github.io/energy-flow-dash/)
📄 Companion reflection: *Commentary Note 001 — From Problems to Systems*

---

## Overview

This project began as an attempt to visualize the challenges identified in the paper *Reimagining Grid Flexibility in a Constrained Power System*. During development, it became clear that treating generation, transmission, storage, and demand as separate, isolated categories didn't explain the system's actual behavior — each component's significance depended entirely on its relationship to the others.

The project shifted accordingly: from **visualizing problems** to **mapping a system**. The result is an interactive dashboard exploring how South Africa's generation assets, transmission infrastructure, storage (BESS), and demand centres interact — and what that interaction reveals about flexibility as an emergent, system-level property rather than a feature of any single technology.

## Key Findings

- **The system is more interconnected than expected.** A decision or constraint in one component (e.g. generation) reliably influences outcomes elsewhere (e.g. transmission value, storage significance).
- **Flexibility is emergent, not located.** It cannot be attributed to a single asset or technology — it arises from how generation, transmission, storage, and demand interact under changing conditions.
- **Geography is an active constraint, not background context.** South Africa's coal generation (Mpumalanga, Limpopo), renewable resources (Northern Cape, Eastern Cape), and demand centres (Gauteng, Durban, Cape Town) are spatially separated in ways that shape system behavior directly.
- **Energy movement may matter as much as energy production.** The central question shifted from "how much can we generate" to "how effectively can energy move through the system to where and when it's needed."

## Methodology

Development followed seven stages: interpreting the source research, identifying core challenges, generating preliminary solution concepts, recognizing gaps in system understanding, building an infrastructure map, exploring relationships through visualization, and — deliberately — separating mapping from solution development to avoid premature conclusions. Version 1 focuses exclusively on understanding current system structure.

## Data Sources

- **Global Energy Monitor (GEM)** — power station coordinates (WGS 84)
- **Eskom public records** — BESS Phase 1 locations
- **REIPPPP records** — renewable energy project data
- **Public geographic data** — demand node city centres

## Limitations

This is an exploratory systems-mapping tool, not an operational grid model. Congestion analysis and storage dispatch are not yet modelled; energy flows are represented conceptually rather than simulated; some BESS locations are approximate. The purpose is to support understanding and generate better questions — not to predict or simulate grid operations.

## Tech Stack

HTML, JavaScript, interactive data visualization, GitHub Pages

## Skills Demonstrated

Systems thinking · Data visualization · Geographic/spatial analysis · Research translation (paper → interactive tool) · Technical writing · Independent research methodology

---

*Version 1.0 · June 2026 · Companion piece: Commentary Note 001 — From Problems to Systems. Critique, correction, and discussion welcome.*

