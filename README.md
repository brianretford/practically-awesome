# Awesome Structured Thinking, Ontology, and Constraint-Based Systems [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of projects, datasets, ontologies, and tools that aim to make the structure of thought, knowledge, and constraints explicit — across science, software, simulation, and everyday domains.

Structured thinking, ontologies, and constraint-based systems provide frameworks for organizing knowledge, reasoning about the world, and solving problems systematically. This list brings together resources that help make implicit knowledge explicit, enable automated reasoning, and support principled decision-making.

## Contents

- [Ontologies and Knowledge Representation](#ontologies-and-knowledge-representation)
- [Constraint-Based Systems](#constraint-based-systems)
- [Structured Thinking Tools](#structured-thinking-tools)
- [Knowledge Graphs](#knowledge-graphs)
- [Semantic Web Technologies](#semantic-web-technologies)
- [Logic Programming and Reasoning](#logic-programming-and-reasoning)
- [Planning and Scheduling](#planning-and-scheduling)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Libraries and Frameworks](#libraries-and-frameworks)
- [Research Papers and Books](#research-papers-and-books)
- [Learning Resources](#learning-resources)

## Ontologies and Knowledge Representation

### General Purpose Ontologies

- [Schema.org](https://schema.org/) - Collaborative effort to create, maintain, and promote schemas for structured data on the Internet, on web pages, in email messages, and beyond.
- [Dublin Core](https://www.dublincore.org/) - Metadata standard for describing digital and physical resources.
- [FOAF (Friend of a Friend)](http://www.foaf-project.org/) - Machine-readable ontology describing persons, their activities, and relations to other people and objects.
- [SKOS (Simple Knowledge Organization System)](https://www.w3.org/2004/02/skos/) - W3C recommendation for representing knowledge organization systems.
- [WordNet](https://wordnet.princeton.edu/) - Large lexical database of English, grouping words into sets of cognitive synonyms (synsets).

### Domain-Specific Ontologies

- [Gene Ontology](http://geneontology.org/) - World's largest source of information on the functions of genes, providing computational representation of biological knowledge.
- [ChEBI (Chemical Entities of Biological Interest)](https://www.ebi.ac.uk/chebi/) - Dictionary of molecular entities focused on 'small' chemical compounds.
- [SNOMED CT](https://www.snomed.org/) - Comprehensive clinical healthcare terminology providing codes, terms, synonyms, and definitions.
- [GeoNames](https://www.geonames.org/) - Geographical database covering all countries and containing over eleven million placenames.
- [Music Ontology](http://musicontology.com/) - Vocabulary for describing music-related information.

### Ontology Tools

- [Protégé](https://protege.stanford.edu/) - Free, open-source ontology editor and framework for building intelligent systems.
- [WebProtégé](https://webprotege.stanford.edu/) - Web-based ontology development environment for creating, uploading, modifying, and sharing ontologies.
- [Ontop](https://ontop-vkg.org/) - Virtual knowledge graph system for accessing relational databases as knowledge graphs.
- [TopBraid Composer](https://www.topquadrant.com/products/topbraid-composer/) - Enterprise-level modeling environment for developing semantic models and ontologies.

## Constraint-Based Systems

### Constraint Satisfaction

- [Choco Solver](https://choco-solver.org/) - Open-source Java library for constraint satisfaction problems (CSP), constraint programming (CP), and explanation-based constraint solving.
- [OR-Tools](https://developers.google.com/optimization) - Google's software suite for combinatorial optimization, including constraint programming.
- [Gecode](https://www.gecode.org/) - Toolkit for developing constraint-based systems and applications in C++.
- [JaCoP](https://github.com/radsz/jacop) - Java Constraint Programming solver with finite domain constraints.
- [MiniZinc](https://www.minizinc.org/) - High-level constraint modeling language that allows expressing constraint problems independent of specific solvers.

### Constraint Programming Languages

- [Prolog](https://www.swi-prolog.org/) - Logic programming language associated with artificial intelligence and computational linguistics.
- [ASP (Answer Set Programming)](https://potassco.org/) - Form of declarative programming oriented towards difficult search problems.
- [Mercury](https://mercurylang.org/) - Logic/functional programming language designed for large, reliable, efficient programs.
- [Picat](http://picat-lang.org/) - Multi-paradigm programming language that combines logic programming, functional programming, constraint programming, and imperative programming.

### Configuration and Product Modeling

- [CKMS (Configuration Knowledge Management System)](https://github.com/topics/configuration-management) - Systems for managing complex product configurations using constraints.
- [VariCAD](https://www.varicad.com/) - Software for constraint-based parametric CAD design.

## Structured Thinking Tools

### Mind Mapping and Concept Mapping

- [CmapTools](https://cmap.ihmc.us/) - Software for constructing, navigating, sharing, and criticizing knowledge models represented as concept maps.
- [FreeMind](http://freemind.sourceforge.net/) - Free mind mapping software written in Java.
- [XMind](https://www.xmind.net/) - Mind mapping and brainstorming software.
- [Obsidian](https://obsidian.md/) - Knowledge base that works on local Markdown files with powerful linking capabilities.
- [Roam Research](https://roamresearch.com/) - Note-taking tool for networked thought with bidirectional linking.

### Argument Mapping

- [Rationale](https://www.rationaleonline.com/) - Visual argument mapping software for critical thinking.
- [Argdown](https://argdown.org/) - Simple syntax for defining argumentative structures, inspired by Markdown.
- [Argunet](http://www.argunet.org/) - Software for creating, analyzing, and visualizing complex debates and arguments.

### Formal Methods

- [Alloy](http://alloytools.org/) - Language and tool for software modeling and verification using first-order relational logic.
- [TLA+](https://lamport.azurewebsites.net/tla/tla.html) - High-level language for modeling programs and systems, especially concurrent and distributed ones.
- [Z Notation](https://en.wikipedia.org/wiki/Z_notation) - Formal specification language used for describing and modeling computing systems.
- [Event-B](http://www.event-b.org/) - Formal method for system-level modeling and analysis.

## Knowledge Graphs

### Knowledge Graph Platforms

- [Neo4j](https://neo4j.com/) - Graph database management system for storing and querying connected data.
- [Amazon Neptune](https://aws.amazon.com/neptune/) - Fully managed graph database service supporting property graphs and RDF.
- [Apache Jena](https://jena.apache.org/) - Free and open-source Java framework for building semantic web and linked data applications.
- [GraphDB](https://www.ontotext.com/products/graphdb/) - RDF database with reasoning capabilities for knowledge graphs.
- [Stardog](https://www.stardog.com/) - Enterprise knowledge graph platform with reasoning and analytics.

### Knowledge Graph Construction

- [OpenKE](https://github.com/thunlp/OpenKE) - Open toolkit for knowledge embedding.
- [PyKEEN](https://github.com/pykeen/pykeen) - Python library for learning and evaluating knowledge graph embeddings.
- [DGL-KE](https://github.com/awslabs/dgl-ke) - High-performance library for knowledge graph embeddings.
- [Ampligraph](https://github.com/Accenture/AmpliGraph) - Python library for representation learning on knowledge graphs.

### Public Knowledge Graphs

- [Wikidata](https://www.wikidata.org/) - Free and open knowledge base that can be read and edited by both humans and machines.
- [DBpedia](https://www.dbpedia.org/) - Crowd-sourced community effort to extract structured information from Wikipedia.
- [YAGO](https://yago-knowledge.org/) - Huge semantic knowledge base derived from Wikipedia, WordNet, and GeoNames.
- [Freebase](https://developers.google.com/freebase) - Large collaborative knowledge base (now archived, data available).
- [ConceptNet](https://conceptnet.io/) - Multilingual knowledge graph connecting words and phrases with labeled edges.

## Semantic Web Technologies

### RDF and SPARQL Tools

- [RDF4J](https://rdf4j.org/) - Open-source Java framework for processing RDF data.
- [rdflib](https://github.com/RDFLib/rdflib) - Python library for working with RDF.
- [Jena Fuseki](https://jena.apache.org/documentation/fuseki2/) - SPARQL server providing REST-style SPARQL HTTP Update, SPARQL Query, and SPARQL Update.
- [Virtuoso](https://virtuoso.openlinksw.com/) - Multi-model database engine supporting relational, graph, and document data models.

### Linked Data

- [Linked Open Data Cloud](https://lod-cloud.net/) - Collection of interlinked datasets published in RDF.
- [JSON-LD](https://json-ld.org/) - JSON-based format for serializing Linked Data.
- [Hydra](https://www.hydra-cg.com/) - Vocabulary for hypermedia-driven Web APIs using linked data.

### OWL (Web Ontology Language)

- [OWL API](https://github.com/owlcs/owlapi) - Java API for creating, manipulating, and serializing OWL ontologies.
- [Owlready2](https://pypi.org/project/Owlready2/) - Python module for ontology-oriented programming with OWL ontologies.
- [HermiT](http://www.hermit-reasoner.com/) - OWL reasoner based on hypertableau calculus.
- [Pellet](https://github.com/stardog-union/pellet) - Open-source OWL DL reasoner in Java.

## Logic Programming and Reasoning

### Theorem Provers

- [Coq](https://coq.inria.fr/) - Formal proof management system providing a formal language to write mathematical definitions, executable algorithms, and theorems.
- [Isabelle](https://isabelle.in.tum.de/) - Generic proof assistant supporting various logics for mathematical reasoning.
- [Lean](https://leanprover.github.io/) - Theorem prover and programming language with powerful automation features.
- [Z3](https://github.com/Z3Prover/z3) - High-performance theorem prover from Microsoft Research.

### Logic Solvers

- [SAT4J](https://www.sat4j.org/) - Library of SAT solvers in Java.
- [CryptoMiniSat](https://github.com/msoos/cryptominisat) - Advanced SAT solver with various optimizations.
- [PicoSAT](http://fmv.jku.at/picosat/) - Compact SAT solver with good performance.

### Description Logic Reasoners

- [FaCT++](https://github.com/ethz-asl/libfactplusplus) - OWL-DL reasoner implemented in C++.
- [RACER](https://www.ifis.uni-luebeck.de/~moeller/racer/) - Renamed ABox and Concept Expression Reasoner for description logics.
- [ELK](https://github.com/liveontologies/elk-reasoner) - Ontology reasoner optimized for large biomedical ontologies.

## Planning and Scheduling

### Planning Systems

- [Fast Downward](https://www.fast-downward.org/) - Classical planning system using heuristic search.
- [PDDL](https://planning.wiki/) - Planning Domain Definition Language for describing planning problems.
- [STRIPS](https://en.wikipedia.org/wiki/STRIPS) - Classic automated planning technique.
- [HTN (Hierarchical Task Network)](http://www.cs.umd.edu/projects/shop/) - Planning approach using task decomposition.

### Scheduling Tools

- [OptaPlanner](https://www.optaplanner.org/) - AI constraint solver optimizing planning and scheduling problems.
- [Timefold](https://timefold.ai/) - Open-source AI solver for optimization problems like scheduling and routing.
- [CP-SAT](https://developers.google.com/optimization/cp/cp_solver) - Constraint programming solver from Google OR-Tools.

## Datasets and Benchmarks

### Ontology Benchmarks

- [OAEI (Ontology Alignment Evaluation Initiative)](http://oaei.ontologymatching.org/) - Coordinated international initiative for evaluating ontology matching technologies.
- [BioPortal](https://bioportal.bioontology.org/) - Repository of biomedical ontologies.
- [Ontology Design Patterns](http://ontologydesignpatterns.org/) - Repository of reusable ontology design patterns.

### Knowledge Graph Benchmarks

- [FB15k-237](https://paperswithcode.com/dataset/fb15k-237) - Link prediction dataset derived from Freebase.
- [WN18RR](https://paperswithcode.com/dataset/wn18rr) - Link prediction dataset derived from WordNet.
- [YAGO3-10](https://github.com/TimDettmers/ConvE) - Subset of YAGO3 for knowledge graph embedding evaluation.

### Constraint Satisfaction Benchmarks

- [MiniZinc Challenge](https://www.minizinc.org/challenge.html) - Annual competition comparing constraint solving systems.
- [CSPLib](https://www.csplib.org/) - Library of test problems for constraint solvers.
- [XCSP3](https://xcsp.org/) - Format for representing constraint satisfaction and optimization problems.

## Libraries and Frameworks

### Python

- [owlready2](https://pypi.org/project/Owlready2/) - Package for ontology-oriented programming in Python.
- [rdflib](https://github.com/RDFLib/rdflib) - Python library for working with RDF.
- [python-constraint](https://pypi.org/project/python-constraint/) - Module for constraint satisfaction problems.
- [NetworkX](https://networkx.org/) - Package for complex networks and graph analysis.
- [PySAT](https://pysathq.github.io/) - Toolkit providing Python interfaces for SAT solvers.

### Java

- [OWL API](https://github.com/owlcs/owlapi) - Java API for OWL ontologies.
- [Apache Jena](https://jena.apache.org/) - Framework for semantic web applications.
- [Choco Solver](https://choco-solver.org/) - Constraint programming library.
- [JGraphT](https://jgrapht.org/) - Java library for graph data structures and algorithms.

### JavaScript/TypeScript

- [rdf-ext](https://github.com/rdf-ext/rdf-ext) - RDF library for JavaScript.
- [N3.js](https://github.com/rdfjs/N3.js) - Lightning fast, spec-compatible RDF library for JavaScript.
- [constraint.js](https://github.com/d4hines/constraint.js) - Constraint programming library for JavaScript.
- [Cytoscape.js](https://js.cytoscape.org/) - Graph theory / network library for analysis and visualization.

### Other Languages

- [RDF.rb](https://github.com/ruby-rdf/rdf) - Ruby library for working with Resource Description Framework data.
- [Gecode](https://www.gecode.org/) - C++ toolkit for constraint programming.
- [Clingo](https://potassco.org/clingo/) - Answer set programming system in C++.

## Research Papers and Books

### Foundational Papers

- [A Semantic Web Primer](https://www.w3.org/2009/pdf/web-services/A_Semantic_Web_Primer.pdf) - Introduction to semantic web technologies.
- [Description Logics](https://www.cambridge.org/core/books/description-logic-handbook/E8C2D3161AEE5D2B2B5D6C39F1A1B1D1) - Comprehensive handbook on description logics.
- [Constraint Processing](https://www.elsevier.com/books/constraint-processing/dechter/978-1-55860-890-0) - Rina Dechter's comprehensive book on constraint satisfaction.

### Key Research Areas

- Knowledge Representation and Reasoning (KRR)
- Semantic Web and Linked Data
- Ontology Engineering and Alignment
- Constraint Programming and Optimization
- Formal Methods and Verification
- Knowledge Graph Completion and Embedding
- Automated Planning and Scheduling

## Learning Resources

### Online Courses

- [Stanford CS 520: Knowledge Graphs](https://web.stanford.edu/class/cs520/) - Course on knowledge graph construction and reasoning.
- [Semantic Web Technologies](https://open.hpi.de/courses/semanticweb2015) - Free online course on semantic web.
- [Constraint Programming](https://www.coursera.org/learn/modeling-discrete-optimization) - Coursera course on discrete optimization with constraint programming.

### Tutorials and Documentation

- [RDF Primer](https://www.w3.org/TR/rdf11-primer/) - Introduction to RDF from W3C.
- [SPARQL Tutorial](https://www.w3.org/TR/sparql11-overview/) - W3C guide to SPARQL query language.
- [Protégé Tutorial](https://protege.stanford.edu/publications/ontology_development/ontology101.pdf) - Guide to ontology development using Protégé.
- [MiniZinc Tutorial](https://www.minizinc.org/doc-2.5.5/en/index.html) - Comprehensive guide to constraint modeling with MiniZinc.

### Communities and Forums

- [Semantic Web Community Group](https://www.w3.org/community/semweb/) - W3C community for semantic web discussions.
- [Constraint Programming Group](https://www.a4cp.org/) - Association for Constraint Programming.
- [Stack Overflow - Ontology Tag](https://stackoverflow.com/questions/tagged/ontology) - Q&A for ontology-related questions.
- [Stack Overflow - SPARQL Tag](https://stackoverflow.com/questions/tagged/sparql) - Q&A for SPARQL queries.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

If you'd like to add a resource:
1. Fork this repository
2. Add your resource to the appropriate section
3. Ensure it follows the format: `[Name](URL) - Description.`
4. Submit a pull request

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
