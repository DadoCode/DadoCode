# Tenancy Document Automation

**Document workflow · Python, DOCX templates, structured validation**

[Public project](https://github.com/DadoCode/tenancy-contract-generator)

## The problem

Preparing repetitive property agreements from Word templates involves copying tenant, landlord, property, rent and deposit details into the right fields. Missing placeholders and inconsistent formatting can cause rework.

## What I built

A Python tool that accepts structured inputs, checks required template fields and generates a populated Word agreement while preserving formatting.

The published version is a limited proof of concept, not a legal compliance product or a substitute for legal review.

## Productisation direction

A future hosted product could add:

- Organisation-specific templates and configuration
- Browser-based data entry and pre-generation checks
- Approval and version history
- Document extraction and structured review
- Integrations with property-management workflows

These future capabilities are **proposed**, not claims about the current generator.

## Demonstration and disclosure

The public project uses fictional names and example agreement details. Any commercial workflow, template licensing, customer data handling and current tenancy-law compliance would require separate assessment.

## My contribution

I designed the field-validation workflow and generated DOCX output, with missing-field checks that fail explicitly rather than silently producing incomplete documents.
