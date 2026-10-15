# Collocation Processing Profile (CPP)

**CPP** is an OWL application profile for representing the methodological provenance of corpus-based collocation extraction.

It links **OntoLex-FrAC collocation observations** to both:
- the **planned extraction procedure**; and
- the **concrete execution context** in which the observations were produced.

CPP reuses **P-Plan** for the planned workflow, **PROV-O** for execution provenance, and **OntoLex-FrAC** for collocation observations.

![Overview of the Collocation Processing Profile (CPP)](cpp-overview-en.png)

## Main characteristics

- models the **planned process**, the **runtime execution**, and the **resulting observation**;
- distinguishes **abstract extraction parameters** from **runtime parameter bindings**;
- represents corpus, index, software, and optional human involvement;
- connects each collocation observation to the run that generated it;
- reuses existing vocabularies rather than introducing a new property system.

## Ontology metadata

- **Title:** Collocation Processing Profile (CPP)
- **Version:** 0.1.0
- **Ontology IRI:** `https://example.org/cpp`
- **Main reused vocabularies:** P-Plan, PROV-O, OntoLex-FrAC, LexInfo

## Files

- `cpp.owl` — the ontology file
- `cpp-overview-en.png` — overview diagram in English
- `STRUCTURE.md` — concise description of the profile structure

## Download

Once published in the repository, the ontology can be downloaded directly from:

`https://raw.githubusercontent.com/giuliabenotto/collocation-processing-profile/main/cpp.owl`
