# Property Analytics & Operations Platform

**Full-stack business application · Python, Flask, SQLite, HTMX, Chart.js**

[Explore the synthetic-data demo](https://fernhill-property-dashboard.onrender.com)

## The problem

Property operators often collect bookings, expenses and financial performance across booking platforms, invoices and spreadsheets. Producing reliable portfolio-level reports requires reconciling records and handling multiple business models.

## What I built

A property operations application with:

- Portfolio and property-level analytics: revenue, profit, occupancy, ADR and RevPAR
- Booking, expense and vendor records with period comparisons
- Spreadsheet and reservation imports with reviewable differences
- PDF/image document extraction with AI-assisted interpretation and human confirmation
- Traceable reporting to PDF, CSV and Excel
- Distinction between operated and managed properties
- Data-completeness indicators and correction workflows

## Engineering decisions

- Normalised records are used to derive metrics instead of storing disconnected totals.
- Missing periods are not misrepresented as zero revenue or occupancy.
- Financial import steps can be reviewed, confirmed and, where supported, reversed.
- AI-assisted extraction is separated from approval; unreviewed output does not automatically become accounting truth.
- The application includes authentication and automated regression tests.

## Demonstration and disclosure

The linked demonstration is read-only and uses fictional properties and synthetic records. No private client financial data or production credentials are included in this case study.

This page documents product capabilities and engineering decisions. New commercial development is maintained separately; source-code availability and licensing are governed by the relevant repository.

## My contribution

I defined the operational problem, data model, accounting rules, UX requirements and testing approach, and used AI-assisted coding during implementation.
