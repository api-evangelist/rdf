# RDF (rdf)
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
