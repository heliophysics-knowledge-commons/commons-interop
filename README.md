
# Purpose
The ```commons-interop``` repository is to steward, document, and maintain semantic and structural alignments between Heliophysics knowledge resources and those of other communities, standards bodies, and domains.

Interoperability work is inherently relational, evolving, and negotiated. This repository provides for that work to live. When an interoperability artifact becomes sufficiently mature and broadly accepted, it may be proposed for promotion into ```commons-foundations```, following the review processes defined in ```commons-governance```.

```commons-interop``` exists to ensure that heliophysics knowledge:
- can circulate beyond disciplinary boundaries,
- can be integrated into broader scientific cyberinfrastructure, and
- can participate meaningfully in emerging data- and ML-driven research ecosystems.

# Scope

This repository includes:
- Semantic crosswalks and mappings between Heliophysics vocabularies, ontologies, and data models and those used by other communities
- Documentation of alignment decisions, assumptions, and known limitations
- Interoperability design patterns and best practices
- Lightweight coordination artifacts for collaboration with external semantic and data initiatives

This repository does not host:
- Authoritative ontologies or data models (see [```commons-foundations```](https://github.com/heliophysics-knowledge-commons/commons-foundations))
- Project-specific experimentation or prototypes (see individual project-* repositories)
- General governance or policy (see [```commons-governance```](https://github.com/heliophysics-knowledge-commons/commons-governance))


# Types of Artifacts
1. Semantic Crosswalks
- Machine-readable mappings, such as:
    - Helio-KNOW ↔ SPASE
    - Heliophysics phenomena ontology ↔ Unified Astronomy Thesaurus (UAT)
    - Region-based taxonomies ↔ ADS / SciX concepts
    - Coordinate system representations ↔ external standards

Crosswalks may be expressed using SKOS, OWL axioms, JSON-LD, or other community-appropriate formats, and must be accompanied by human-readable documentation.

2. Interoperability Design Patterns
- Reusable guidance addressing questions such as:
    - When to use equivalence vs. subsumption
    - How to represent partial or context-dependent overlap
    - How to document non-alignment or irreducible differences
    - How to manage version drift across evolving standards

These patterns are intended to support consistency across mappings and to transfer hard-earned experience to new contributors.


3. External Alignment Spaces
- Subdirectories may be organized by external system or community, for example:
```
/ads
/scix
/uat
/spase
/earth-science
```

Each alignment space should include:
- Scope and intent of the alignment
- Current status and maturity
- Points of contact (individuals or organizations)
- Open issues and unresolved questions

# Maturity and Stability
Artifacts in commons-interop are expected to evolve.
- Provisional mappings are explicitly allowed
- Versioning should be used to track changes
- Stability is not required for inclusion

# Contributing

Contributions are welcome from across heliophysics and allied domains.

Contributors are encouraged to:
- Open GitHub Issues to propose new mappings or alignment efforts
- Use Pull Requests for concrete artifacts and documentation
- Explicitly state assumptions, scope, and intended use
- Propose changes to repository structure when needed
- Structural changes to this repository—or to the broader Knowledge Commons—should be discussed via GitHub Issues and, when appropriate, escalated to commons-governance.

See the organization-wide ```CONTRIBUTING.md``` for general contribution guidelines.
