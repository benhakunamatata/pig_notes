# pig_notes
notes for pig scripts

## UNION [ONSCHEMA]

UNION
Computes the union of two or more relations.

Syntax
alias = UNION [ONSCHEMA] alias, alias [, alias …];

Terms
alias

The name of a relation.

ONSCHEMA

Use the ONSCHEMA clause to base the union on named fields (rather than positional notation). All inputs to the union must have a non-unknown (non-null) schema.


