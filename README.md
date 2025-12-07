# Awesome Structured Thinking, Ontology, and Constraint-Based Systems

> Interesting projects exploring the realm on structured thinking, ontology, and constraint-based systems.

A curated collection of projects, datasets, ontologies, and tools that aim to make the structure of thought, knowledge, and constraints explicit — across science, software, simulation, and everyday domains.

---

## Table of Contents

- [Motivation](#motivation)
- [Core Ideas](#core-ideas)
- [Cross-Domain Knowledge Graphs & Ontologies](#cross-domain-knowledge-graphs--ontologies)
- [Biomedical & Protein-Centric Systems](#biomedical--protein-centric-systems)
- [Food, Cooking, and Material Transformation](#food-cooking-and-material-transformation)
- [Game Engines, Simulation, and Environments](#game-engines-simulation-and-environments)
- [Constraint-Based & Logic Systems](#constraint-based--logic-systems)
- [Structured Knowledge Management](#structured-knowledge-management)
- [Process / Provenance / Causality Models](#process--provenance--causality-models)
- [Core Abstractions and Meta-Schemas](#core-abstractions-and-meta-schemas)
- [Contributing](#contributing)
- [License](#license)

---

## Motivation

Most “knowledge systems” either:
- focus on *static facts* (triples, entities, taxonomies), or  
- focus on *runtime behavior* (code, simulations, games),

but relatively few projects try to **integrate**:

- explicit **structure of domains** (ontology, types, graphs)
- explicit **constraints** (logical, physical, economic, social)
- explicit **process and state-change** (transforms, environments, signals)

This list tracks projects that are interesting precisely because they move in that direction.

---

## Core Ideas

This list loosely favors projects that touch some combination of:

- **Structured Thinking**  
  Formal or semi-formal ways to externalize reasoning: typed models, state machines, decision structures, compositional schemas.

- **Ontology / Knowledge Graphs**  
  Typed entities, relations, and often domain-specific constraints.

- **Constraint-Based Systems**  
  Logic programming, solvers, synthesis frameworks, and tools that treat “what must be true” as a first-class object.

- **Process & State**  
  Systems that care about transitions: from biochemistry pathways to simulation environments to provenance models.

---

## Cross-Domain Knowledge Graphs & Ontologies

General-purpose or multi-domain knowledge systems.

- [totogo/awesome-knowledge-graph](https://github.com/totogo/awesome-knowledge-graph)  
  Curated list of knowledge-graph databases, tools, and datasets.

- [ozekik/awesome-ontology](https://github.com/ozekik/awesome-ontology)  
  Wide-ranging collection of ontology languages, editors, libraries, and upper/domain ontologies.

- [brettkromkamp/awesome-knowledge-management](https://github.com/brettkromkamp/awesome-knowledge-management)  
  Resources on knowledge representation, conceptual modeling, and semantic systems.

- **Wikidata**  
  Large-scale, community-maintained knowledge graph with a rich property and qualifier system.

- **Schema.org / Bioschemas / related profiles**  
  Lightweight schemas for structured data on the web, extended into scientific domains.

---

## Biomedical & Protein-Centric Systems

Knowledge systems where *state*, *transform*, and *constraints* are first-class.

- [robert-haas/awesome-biomedical-knowledge-graphs](https://github.com/robert-haas/awesome-biomedical-knowledge-graphs)  
  High-quality curated list of biomedical KGs, ontologies, and tools.

- **BioPAX**  
  Standard language for representing biological pathways: reactions, participants, control, and context.

- **Reactome**  
  Curated pathway database with explicit reaction, state, and process semantics.

- **UniProt / OBO Foundry ontologies**  
  Protein and biological ontologies (GO, CHEBI, etc.) with rich, typed relationships.

---

## Food, Cooking, and Material Transformation

Projects that model ingredients, processes, and transformations.

- **FoodKG**  
  Knowledge graph linking ingredients, recipes, and nutritional information; explicit process steps.

- **FoodOn**  
  An ontology for food products, ingredients, and related processes.

- **Recipe Ontology / related efforts**  
  Structured representations of recipes as sequences of constrained transformations (prep, cook, combine).

---

## Game Engines, Simulation, and Environments

Systems where structured state, actions, and constraints are explicit.

- [dgarijo/VideoGameOntology](https://github.com/dgarijo/VideoGameOntology)  
  Ontology aiming to describe video games, mechanics, and related entities.

- **OpenAI Gym / RL environment APIs**  
  Simple but powerful abstraction: `state → action → new state + reward`, with explicit environment interfaces.

- **Unity ML-Agents / RL in Unity**  
  Bridges game engines with formalized observation/action spaces and reward structures.

- **Unreal / Unity data schemas** (non-ontological but structurally rich)  
  Scene graphs, component systems, and blueprints as de-facto ontologies of interactive worlds.

---

## Constraint-Based & Logic Systems

Tools that treat constraints, logic, and relations as primary modeling devices.

- **Prolog and modern descendants (e.g., SWI-Prolog, Logtalk)**  
  Declarative logic programming: facts, rules, queries.

- **Z3 / SMT solvers**  
  Satisfiability modulo theories engines used for verification, synthesis, configuration, and scheduling.

- **Alloy**  
  Relational modeling language and analyzer for expressing structures and constraints, then checking them.

- **Answer Set Programming (Clingo, etc.)**  
  Declarative problem specification + solver-based model generation.

- **MiniZinc**  
  High-level constraint modeling language targeting multiple solvers.

---

## Structured Knowledge Management

Systems that blur the line between notes, models, and graphs.

- **Roam Research / Logseq / Obsidian plugins (graph views, typed links)**  
  Personal knowledge tools that introduce structure, typed links, and emergent graphs.

- **TiddlyWiki + plugins for typed fields and semantics**  
  Hypertext wiki system where fields and links can approximate a lightweight ontology.

- **Concept mapping tools** (CmapTools, etc.)  
  Visual structuring of concepts and relations; often exportable as graphs.

---

## Process / Provenance / Causality Models

Standards and projects modeling how things came to be: activities, agents, entities, and their relations.

- **W3C PROV-O (Provenance Ontology)**  
  Ontology for describing entities, activities, and agents, and how they influence each other.

- **Open Provenance Model (OPM)**  
  Earlier model for provenance; influences PROV-O and related efforts.

- **Workflow and pipeline ontologies**  
  Systems describing scientific workflows, data pipelines, and their causal graphs.

---

## Core Abstractions and Meta-Schemas

Projects and ideas that explicitly try to provide “unifying” abstractions across domains.

- **Upper Ontologies** (BFO, DOLCE, etc.)  
  Attempts to formalize very general categories (object, process, quality, role, etc.) for reuse.

- **Category-Theoretic Approaches to Systems**  
  Monoidal categories, lenses, open systems modeling, and compositionality for networked dynamics.

- **State-Transition / Actor Models**  
  XState, TLA+, Petri nets, process calculi — all ways to describe discrete state and change under constraints.

- **Relational & Graphical Modeling Frameworks**  
  Factor graphs, probabilistic graphical models, PGMs-as-structure.

_This section is intentionally meta: it collects projects and frameworks that help you think about structure, constraints, and processes in a reusable way._

---

## Contributing

Contributions are welcome.

- Add projects that:
  - make **structure** of a domain explicit (ontology, schema, typed graph, state space),  
  - embrace **constraints** (logical, physical, economic, social), or  
  - model **process and state change** (transforms, environments, signals).

- Prefer:
  - open licenses,  
  - clear documentation,  
  - explicit schemas or conceptual models (not just code blobs).

Please open a PR with:
- a one-line description,
- why it’s structurally interesting,
- and a link.

---

## License

Unless otherwise noted, this list is licensed under **CC BY 4.0**.

You are free to share and adapt it, with attribution.
