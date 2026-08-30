Steel Industrial Warehouse --- STAAD.Pro Structural Design

A structural analysis and steel design project for an industrial
warehouse developed and checked using STAAD.Pro and IS 800 steel
design provisions.

Project Overview

This project covers the structural modelling, analysis, and steel member
design of an industrial warehouse structure in STAAD.Pro.

The model was iteratively refined based on the steel design utilization
ratios reported by STAAD.Pro. Failed members were identified,
appropriate member sections were redefined, and the model was re-run
until the final steel design check passed.

Software & Standards

STAAD.Pro --- Structural analysis and steel design

Design standard: IS 800

Section database: Indian steel sections

Analysis type: 3D structural analysis

Design check: Steel member strength/slenderness and utilization
ratio

Key Work Performed

Developed and reviewed the STAAD.Pro structural model.

Verified the analysis model before steel design refinement.

Reviewed steel design output and identified members with utilization
ratios greater than 1.0.

Investigated member failures, including slenderness-controlled
design checks.

Revised member sections for the critical members.

Corrected STAAD.Pro member-property assignments and section-database
issues.

Re-ran the steel design after each revision.

Achieved a final model in which the reported steel design checks
passed.

Design Refinement Process

The project followed an iterative engineering workflow:

Structural analysis

Reviewed the analysis results and model behaviour.

Initial steel design

Checked member utilization ratios against the allowable ratio.

Failure identification

Located members with RATIO (ACT./ALLOW.) > 1.000.

Section optimization

Increased/redefined sections for the governing members.

Model correction

Removed duplicate property assignments and corrected unavailable
section-table definitions.

Final verification

Re-ran STAAD.Pro steel design and confirmed the final design
checks passed.

Representative Design Issue

The critical members initially exceeded the allowable utilization ratio,
with several failures governed by the SLENDERNESS check.

The final refinement focused on the governing pillar/column members
while avoiding unnecessary changes to the entire structural model.

Repository Contents

Suggested repository structure:

steel-industrial-warehouse-staad/
├── README.md
├── STAAD_FINAL_PILLAR_REDESIGN.std
└── screenshots/
    ├── analysis-results.png
    └── final-steel-design.png

Result

The final STAAD.Pro model was successfully re-run after member-section
refinement, and the steel design checks passed.

Resume Description

Steel Industrial Warehouse Structural Design --- STAAD.Pro

Designed and analyzed an industrial warehouse structure using
STAAD.Pro and IS 800.

Evaluated steel member utilization ratios and identified governing
slenderness failures.

Iteratively redefined critical member sections and corrected
STAAD.Pro property/database issues.

Verified the final model through repeated analysis and steel design
checks, achieving passing utilization ratios.

Note

This repository is intended as a portfolio/academic engineering
project demonstrating structural modelling, steel design verification,
troubleshooting, and iterative section refinement in STAAD.Pro. Final
structural adequacy for construction should be independently reviewed
and approved by the responsible structural engineer.
