# Conceptual Viewpoint 

## Goal

The goal of the conceptual - we might call it also ontological viewpoint - viewpoint is to present high-level business concepts, their relationships and the rules governing those relationships.

## Stakeholders 

- Business stakeholders
- Business analysts
- Engineers
- Testers
- Architects

## Description

When discussing any kind of business problem a common language has to be used among the participants otherwise they will not speak a common language resulting in misunderstandings and solving the wrong problem in a later phase.

## Examples 

- In retail domain we use the terms Product Assortment, Point of Sale, Inventory, Product, etc.
- In finance domain we use the terms Account, Loan, Interest, Liability, etc.
- In cybersecurity domain we use the terms Asset, Threat, Vulnerability, Attack, Risk, Control, etc.

When the terms are defined we can ask questions like how many Threats might relate to an Asset, what 
the connection between an Account and a Loan is, and how many Loans can be associated to the same Account?

# Requirements

- Describe concepts
  - Concept have a name
  - Concept have a description
- Describe relationship between concepts 
  - A relationship connects two concepts
  - Type of relationship: association, subtype
- Describe rules governing the instances of the concepts and relationships
  - Constraint on multiplicities
  - Constraint on subtypes (coveringness, distjointness)

# Viewpoint definition in SysML V2

| Requirement | Solution |
| ----------- | -------  |
| Define a concept | item def |
| Define an association relationship | TODO |
| Define a subtype relationship | TODO |
| Constraint on multiplicities | TODO |
| Constraint on subtypes | TODO | 

# Explanation of the decisions for SysML V2

TODO

# Example in SysML V2

```
 item def Threat {

 }

 item def Asset {

 }

 // TODO

```

# Open questions

TODO

# Additional material

## OntoUML

OntoUML is an ontologically well-founded language for Ontology-driven Conceptual Modeling. It provides base elements like `kind`, `subkind`, `phase`, `role`, etc. also both a pattern and anti-pattern catalog that helps evaluating the goodness of a model.

### Ideas

Although OntoUML seems also to have a textual syntax, the SysML V2 metadata capability could be used to define concepts above enabling seamless integration in the SysML V2 world. Alternatively a model to model transformation could be implemented to convert from OntoUML textual format to SysML V2 textual format.

### Links

- https://ontouml.readthedocs.io
- https://ontouml.org/
- https://research.utwente.nl/en/publications/
- https://www.youtube.com/channel/UCuTDQnqa9EBTkH508NDIBHg

## Alloy Analyzer

Alloy is an open source language and analyzer for software modeling. It can be used to describe ontological structures and generate examples of it that can be used to validate the ontological model. The language itself can be used for both structured and behavior modeling.

### Ideas

The conceptual views based on SysML V2 could be transformed to AlloyTools models and executed using the AlloyTools engine in order to validate the model.

### Links

- https://alloytools.org/
- https://practicalalloy.github.io/