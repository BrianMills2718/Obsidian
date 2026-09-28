---
tags: [ontology-engineering, competency-questions, methodology]
---
# Ontology Engineering

Ontology engineering systematically constructs, evaluates, evolves, and reuses formal ontologies.

```text
motivating scenario -> competency questions -> concepts/distinctions -> relations/constraints -> formalization -> fixtures/tests/counterexamples -> revision
```

A **competency question** is effectively a semantic acceptance test. Example: can the ontology distinguish temporal precedence from causation?

Software-engineering analogy: competency question ↔ requirement/use case; axiom ↔ invariant/contract; ontology implementation ↔ implementation; reasoner/query test ↔ acceptance test; counterexample ↔ negative test; ontology revision ↔ schema evolution/refactoring.

This suggests **test-driven conceptual engineering**, including positive/negative fixtures, invariant tests, migration tests, semantic versioning, compatibility tests, and explicit deprecation rules.