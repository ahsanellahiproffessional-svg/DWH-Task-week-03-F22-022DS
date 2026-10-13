PakFreight: Week 3 Star Schema Assignment
This repository contains the complete dimensional modeling and star schema implementation for PakFreight Week 3, transforming the flat Shipments_Unified table into a robust, production-ready data warehouse structure.

📂 Summary of Tasks
T1 · Column Classification: Categorized 12 candidate columns into facts, dimensions, degenerate dimensions (DD), or drops (X).

T2 · Grain Declaration: Declared the atomic grain ("One row represents a single completed or in-transit cargo movement billed under an individual waybill") and analyzed 4 new warehouse processes.

T3 · Additivity Audit: Classified measures into additive, semi-additive, and non-additive, resolving the ratio aggregation fallacy.

T4 · DimCity: Conformed 23 raw location strings into clean city master data with province, region, port flags, and a mandatory -1 Unknown row.

T5 · Supporting Dimensions: Built DimRoute, DimMode, DimStatus, and a continuous daily calendar (DimDate for Feb 2026).

T6 · FactShipment: Assembled the fact table using six integer surrogate keys, metrics, and degenerate shipment IDs—keeping all descriptive text out of the fact table.

T7 · Reconciliation: Passed all 13 integrity checks, ensuring the reshaping process preserved every single kilogram and rupee without data loss.
