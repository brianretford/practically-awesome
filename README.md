# Awesome Structured Thinking, Ontology, and Constraint-Based Systems

> Interesting projects exploring the realm on structured thinking, ontology, and constraint-based systems.

A semi-curated [LLM-aided] collection of projects, datasets, ontologies, and tools that aim to make the structure of thought, knowledge, and constraints explicit — across science, software, simulation, and everyday domains.

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
  Typed entities, relations, and domain-specific constraints.

- **Constraint-Based Systems**  
  Logic programming, solvers, synthesis frameworks, and tools that treat “what must be true” as a first-class object.

- **Process & State**  
  Systems that care about transitions: biochemistry pathways, simulation environments, provenance models, games.

---

## Cross-Domain Knowledge Graphs & Ontologies

General-purpose or multi-domain knowledge systems.

- **Awesome Knowledge Graph** — https://github.com/totogo/awesome-knowledge-graph  
  Curated list of KG databases, tools, and datasets.

- **Awesome Ontology** — https://github.com/ozekik/awesome-ontology  
  Broad list of ontology languages, editors, libraries, and foundational/domain ontologies.

- **Awesome Knowledge Management** — https://github.com/brettkromkamp/awesome-knowledge-management  
  Representation, conceptual modeling, semantic systems, and related tools.

- **Wikidata** — https://www.wikidata.org  
  Massive collaborative KG with rich qualifiers, references, and typed relations.

- **Schema.org** — https://schema.org  
  Lightweight structured-data schemas used across the Web.

- **Bioschemas** — https://bioschemas.org  
  Schema.org-style structured-data extensions for biological entities.

---

## Biomedical & Protein-Centric Systems

Knowledge systems where *state*, *transform*, or *constraints* are explicit.

- **Awesome Biomedical Knowledge Graphs (Robert Haas)** — https://github.com/robert-haas/awesome-biomedical-knowledge-graphs  
  High-quality curation of biomedical KGs, ontologies, standards, tools.

- **BioPAX** — https://biopax.github.io  
  Standard language for representing biological pathways (reactions, states, controls).

- **Reactome** — https://reactome.org  
  Expert-curated biological pathway database with explicit reaction/state models.

- **UniProt** — https://www.uniprot.org  
  Comprehensive protein knowledgebase with structured metadata.

- **OBO Foundry Ontologies** — https://obofoundry.org  
  Collection of interoperable biological and biomedical ontologies (GO, CHEBI, etc.).

---

## Food, Cooking, and Material Transformation

Projects that model ingredients, processes, cooking steps, and transformations.

- **FoodKG** — https://github.com/foodkg/foodkg  
  KG linking recipes, ingredients, substitutions, nutrition.

- **FoodOn Ontology** — https://foodon.org  
  Ontology for food products, ingredients, processes, and food systems.

- **RecipeKG / Recipe Ontology** — https://github.com/varunhari/RecipeKG  
  Structured representation of cooking instructions and culinary transformations.

---

## Game Engines, Simulation, and Environments

Systems where structured state, action, and constraints are explicit.

- **Video Game Ontology (VGO)** — https://github.com/dgarijo/VideoGameOntology  
  Ontology describing games, mechanics, assets, and interactions.

- **OpenAI Gym** — https://github.com/openai/gym  
  Standard API for RL environments: `state → action → new state + reward`.

- **Unity ML-Agents** — https://github.com/Unity-Technologies/ml-agents  
  Unity engine agents with explicit observation/action/reward schema.

- **Unreal Engine Documentation (Data Models)** — https://dev.epicgames.com/documentation/en-us/unreal-engine  
  Component model, scene graphs, Blueprints as de facto ontological structures.

- **Unity Data Model Docs** — https://docs.unity3d.com  
  Entity-component models and typed scene structures.

---

## Constraint-Based & Logic Systems

Tools based on logical structure, constraints, and rule-based modeling.

- **SWI-Prolog** — https://www.swi-prolog.org  
  Prolog engine for logic programming and symbolic reasoning.

- **Logtalk** — https://logtalk.org  
  Object-oriented extension to Prolog for modular entities and relations.

- **Z3 SMT Solver** — https://github.com/Z3Prover/z3  
  Solver for logical theories; widely used for verification and synthesis.

- **Alloy Analyzer** — https://alloytools.org  
  Relational modeling language + analyzer for structure/constraint checking.

- **Clingo (Answer Set Programming)** — https://potassco.org/clingo  
  Declarative problem modeling with constraint solving semantics.

- **MiniZinc** — https://www.minizinc.org  
  High-level constraint modeling language supporting many solvers.

---

## Structured Knowledge Management

Tools that blur the line between notes, graphs, and structured models.

- **Roam Research** — https://roamresearch.com  
  Bidirectional linking + graph view for structured ideas.

- **Logseq** — https://logseq.com  
  Open-source outliner with typed links, properties, and graph queries.

- **Obsidian** — https://obsidian.md  
  Markdown knowledge base with community plugins for ontologies and typed fields.

- **TiddlyWiki** — https://tiddlywiki.com  
  Structured fields + hypertext for building typed knowledge systems.

- **CmapTools** — https://cmap.ihmc.us  
  Concept-mapping software with exportable structured graphs.

---

## Process / Provenance / Causality Models

Models of activity, entities, agents, and causal relationships.

- **W3C PROV-O** — https://www.w3.org/TR/prov-o  
  Provenance ontology describing entities, activities, agents, and derivations.

- **Open Provenance Model (OPM)** — https://openprovenance.org/opm  
  Earlier provenance model; precursor to many workflow semantics.

- **CWL (Common Workflow Language)** — https://www.commonwl.org  
  Structured representation of computational workflows and their dependencies.

- **Nextflow Schema / Workflow DSL** — https://www.nextflow.io  
  Workflow semantics and provenance modeling.

---

## Core Abstractions and Meta-Schemas

Projects exploring universal or cross-domain structural abstractions.

- **Basic Formal Ontology (BFO)** — https://basic-formal-ontology.org  
  Foundational ontology for representing universal categories.

- **DOLCE Ontology** — http://www.loa.istc.cnr.it/old/DOLCE.html  
  Upper ontology focused on cognitive and linguistic grounding.

- **Process Calculi (π-calculus, CSP)**  
  Formal models for composable concurrent processes.  
  π-calculus overview: https://pi-calculus.net

- **Petri Nets (PNML Standard)** — https://pnml.org  
  Graphical and formal notation for state-transition nets with concurrency.

- **TLA+** — https://lamport.azurewebsites.net/tla/tla.html  
  Specification language for state transitions and temporal constraints.

- **Category-Theory for Open Systems (Applied Category Theory)**  
  Research group: https://topos.institute  
  Tutorials: https://github.com/ekmett/category-theory

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

Open a PR with:
- a one-line description,  
- why it's structurally interesting,  
- and a link.

---

## License

This list is licensed under **CC BY 4.0**.

You are free to share and adapt it, with attribution.
