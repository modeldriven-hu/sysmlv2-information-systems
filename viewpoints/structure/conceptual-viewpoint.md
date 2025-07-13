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