# Eventities-Stories
This repository contains the cases and marketing for Eventities as a best practice for interoperable data. The strong suggestion being made here is that as a concept, this format can serve as a sort of polyfill for interoperable data.

# nv:Principles
1. Anything with an identity requires at least one discrete and unambiguous URI;
2. Description is annotation, requiring evidence and attribution; and
3. Resources of any kind must be respected when encoding for DH use.

# nv:Structures
The most basic `nv:Entity` has only an `@id` (one), `@type` (one or more), and `label` (none or more), with only mechanical information stored beyond that. Within the graph, annotations (`oa:Annotation`) confer descriptive properties or relationships onto an Entity as the `outcome` of another Entity. An Outcome
asserts that an Entity ought to be described in some way and provides both Evidence and Attribution for that assertion.

# Stories
The [stories](https://github.com/CenterForDigitalHumanities/Eventities-Stories/tree/master/stories) directory contains the cases for various perspectives on Eventities, including use cases, technical and non-technical explanations, and links to relevant notes and presentations. Feel free to add an issue describing your own case to petition for its inclusion.