# Agents in Construction (AiC) Ontology

This repository hosts the published documentation and machine-readable serializations of the **Agents in Construction (AiC)** ontology.  

The canonical namespace for AiC terms is `https://w3id.org/aic#` and the suggested prefix is `aic`.

---

## Purpose

The **Agents in Construction (AiC)** ontology is a lightweight semantic model for coordinating on-site production in construction projects. It:

- Represents **construction agents** (human workers, robots, and other autonomous hardware) and their **capabilities**, **locations**, and **operational modes**.
- Describes **processes** (work packages, activities, tasks), and **elements** that agents work on, as well as related **zones** and **resources** (materials and equipment).
- Captures **operation modes**, **process states** and **metrics**, enabling monitoring and analysis of how work is executed over time.
- Provides a **temporal and contextual layer** via `aic:InformationID`, allowing statements to be annotated with validity intervals, information dimensions (e.g., *planned*, *simulated*, *performed*), provenance, and other metadata.
- Emphasizes **generic, trade-agnostic concepts** so that it can be applied across different project types, delivery methods, and technology stacks.

The ontology is intended to support data integration, reasoning, and analytics for digital twins, production control, and robotics in construction.

---

## Repository Contents

```text
AiC-Ontology/
├── index-en.html        # Main WIDOCO-generated HTML page (English)
├── index.html           # Main WIDOCO-generated HTML page
├── LICENSE              # License information
├── ontology.jsonld      # Latest JSON-LD serialization
├── ontology.nt          # Latest N-Triples serialization
├── ontology.owl         # Latest RDF/XML serialization
├── ontology.rdf         # Latest RDF/XML serialization
├── ontology.ttl         # Latest Turtle serialization
├── OOPSevaluation/      # Results and HTML page of the OntOlogy Pitfall Scanner! (OOPS!)
├── alignments/          # Alignment modules
    ├── versions/        # Published alignment versions
├── provenance/          # Provenance metadata about how the page was generated
├── resources/           # Images, CSS, JS used by documentation
├── versions/            # Published ontology versions
├── webvowl/             # HTML, CSS and JS for WebVOWL visualisation
├── README.md            # This file
```

---

## Citation

If you use the AiC ontology in academic or commercial work and software, please cite as:

```text
Čustović, I., Cao, J., Soman, R. (2026). Agents in Construction (AiC) Ontology – Version 1.1.0
```

BibTeX:

```bibtex
@misc{Custovic2026AiC,
  author       = {Irfan {\v{C}}ustovi{\'c} and Jianpeng Cao and Ranjith Soman},
  title        = {Agents in Construction (AiC) Ontology -- Version 1.1.0},
  year         = {2026},
  howpublished = {\url{https://w3id.org/aic}},
  note         = {Ontology specification and documentation. Licensed under CC BY 4.0.}
}
```

## Developed with

- [WIDOCO](https://github.com/dgarijo/Widoco)
- [OOPS!](https://oops.linkeddata.es/)