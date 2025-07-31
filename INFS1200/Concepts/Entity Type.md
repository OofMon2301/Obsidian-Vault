---
tags:
  - INFS1200
---
# Entity Type
An entity type **provides a format for the data** which needs to be recorded and to represent a particular [[Entity]]. The **entity type** is described by its *name* and *attributes*.

In the [[Entity-Relationship Model (ER Model)|ER Model]]:
- An Entity Type is represented as a rectangular box.
- Attribute Names are represented by ovals attached to their entity type.
## Key Attributes
All entity types have at least one **key** (or uniqueness) constraint.
- The value of a key attribute are *distinct (unique)* for each individual entity in the entity set.

In the [[Entity-Relationship Model (ER Model)]]:
- A key attribute has it names *underlined* inside the oval
- Key must hold for **every** possible extension of the entity type (see super/subclasses in later slides)
- Multiple Keys are possible

## Multivalued Attributes
Simple attributes can either be single-valued or multi-valued:
- Single-valued attributes can only have one value
- Multivalued attributes are shown to double-lined ovals and can have multiple values (e.g. one person can hold multiple degrees)

## Derived Attributes
In some cases, attribute values can be derived from related attribute values (e.g. age can be derived from Birth Dates).

In the ER Model, derived attributes are shown with an oval with a dotted line.
