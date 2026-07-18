# PC3 --- Published Computational Capability Console

PC3 (Published Computational Capability Console) is a reference
application for exploring, exercising, and observing **published
computational capabilities** organized according to the **SISD-KOPM
(Specify--Implement--Serve--Deploy Knowledge Object Publication
Model)**.

PC3 operates on **one published computational capability at a time**,
creating a single active **Publication Context** for the user's session.

## Purpose

PC3 enables users to:

-   Load a published computational capability.
-   Discover every available realization pathway.
-   Explore the publication structure through progressive disclosure.
-   Execute supported realizations using external execution
    environments.
-   Supply publication-defined input objects.
-   Observe and compare computational outputs.
-   Produce optional execution evidence without modifying the
    publication.

## Architectural Principles

-   Publication-driven operation.
-   One active publication context per session.
-   Read-only interaction with published artifacts.
-   External execution environments.
-   Progressive disclosure of publication complexity.
-   Support for multiple realization pathways (IR, IR→SR, IR→SR→DP).

## Relationship to UKO

PC3 is **not** part of a UKO publication.

A UKO publishes computational capabilities.

PC3 consumes published UKOs to demonstrate and observe their executable
realizations while preserving publication integrity.

## Status

This repository contains the reference implementation of PC3.

The implementation follows the PC3 Architecture Blueprint and PC3
Specification and is intended to evolve alongside the SISD-KOPM
publication architecture.
