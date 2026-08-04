# RDF (rdf)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The Resource Description Framework (RDF) is a W3C standard for representing information about resources on the web. RDF is the foundation for linked data and the semantic web, providing a graph-based data model where statements are expressed as subject-predicate-object triples. It enables interoperability between systems by using IRIs to identify resources and relationships, supporting multiple serialization formats including RDF/XML, Turtle, N-Triples, N-Quads, TriG, and JSON-LD.

RDF 1.1 is a W3C Recommendation (2014). RDF 1.2 is a Candidate Recommendation (2026) adding triple terms (RDF-star) and directional language-tagged strings.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/rdf/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

JSON-LD, Knowledge Graph, Linked Data, Ontology, RDF, Semantic Web, SPARQL, W3C

## JSON Schemas

| Schema | Description |
|--------|-------------|
| [RDF Triple Schema](json-schema/rdf-triple.json) | JSON Schema for an RDF triple |
| [RDF Graph Schema](json-schema/rdf-graph.json) | JSON Schema for an RDF graph in RDF/JSON format |
| [RDF Dataset Schema](json-schema/rdf-dataset.json) | JSON Schema for an RDF dataset |

## JSON Structures

| Structure | Description |
|-----------|-------------|
| [RDF Triple Structure](json-structure/rdf-triple-structure.json) | Field-level documentation for the RDF triple |
| [RDF Graph Structure](json-structure/rdf-graph-structure.json) | Field-level documentation for the RDF graph serialization |

## JSON-LD Context

| Context | Description |
|---------|-------------|
| [RDF Context](json-ld/rdf-context.jsonld) | JSON-LD context defining core RDF, RDFS, OWL, and related vocabularies |

## Examples

| Example | Description |
|---------|-------------|
| [RDF Triple Example](examples/rdf-triple-example.json) | Example triple using foaf:name for Tim Berners-Lee |
| [RDF Graph Example](examples/rdf-graph-example.json) | Example RDF graph in RDF/JSON serialization |

## Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [RDF Vocabulary](vocabulary/rdf-vocabulary.yml) | Normative vocabulary for RDF concepts, serialization formats, and related W3C standards |

## Specifications

- [RDF 1.1 Concepts (W3C Recommendation)](https://www.w3.org/TR/rdf11-concepts/)
- [RDF 1.2 Concepts (W3C Candidate Recommendation, 2026)](https://www.w3.org/TR/rdf12-concepts/)
- [SPARQL 1.1 Query Language](https://www.w3.org/TR/sparql11-query/)
- [JSON-LD 1.1](https://www.w3.org/TR/json-ld11/)
- [W3C RDF Working Group](https://www.w3.org/groups/wg/rdf-star/)

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
