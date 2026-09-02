# Steel Industrial Warehouse Structural Design — STAAD.Pro

## Project Overview

This project presents the structural analysis and steel design of an industrial warehouse structure developed using **STAAD.Pro** in accordance with **IS 800** steel design provisions.

The project involved structural modelling, analysis verification, steel member design, identification of critical members, section refinement, and final design verification.
## design
<img width="1243" height="688" alt="image" src="https://github.com/user-attachments/assets/aa081cc5-2bd7-4838-83ab-1f92da431c13" />
<img width="877" height="717" alt="image" src="https://github.com/user-attachments/assets/25cd7273-a86a-490f-b1ef-f4db8bafb38b" />
<img width="881" height="732" alt="image" src="https://github.com/user-attachments/assets/2f7d2c60-a2f4-4a4e-9197-7dc87e520f32" />
<img width="887" height="725" alt="image" src="https://github.com/user-attachments/assets/67ef78a0-e9fe-4a5c-80b7-70baede6ebd8" />
<img width="887" height="760" alt="image" src="https://github.com/user-attachments/assets/557deebb-60ad-4a44-8b00-422637b7d50e" />

<img width="787" height="717" alt="image" src="https://github.com/user-attachments/assets/6d4ab0d5-79db-4f69-ba4b-f0aad5fe70a0" />



## Software & Standards

- **Software:** STAAD.Pro
- **Design Code:** IS 800
- **Structural System:** Steel Industrial Warehouse
- **Analysis:** 3D Structural Analysis
- **Design:** Steel Member Design
- **Section Database:** Indian Steel Sections

## Key Responsibilities

- Developed and reviewed the 3D structural model in STAAD.Pro.
- Defined member properties, supports, loading conditions, and load combinations.
- Performed structural analysis and reviewed analysis results.
- Conducted steel design checks according to IS 800.
- Evaluated member utilization ratios using `RATIO (ACT./ALLOW.)`.
- Identified members exceeding the allowable utilization ratio.
- Investigated failures governed by member slenderness.
- Revised critical member sections based on the design results.
- Corrected STAAD.Pro member-property assignments and section database issues.
- Re-ran analysis and steel design after each modification.
- Verified the final model with all reported steel design checks passing.

## Design Optimization Process

The structural design was completed through an iterative design-verification process:

1. Created the initial STAAD.Pro structural model.
2. Performed structural analysis.
3. Reviewed the steel design output.
4. Identified members with utilization ratios greater than `1.000`.
5. Investigated the governing design clauses and slenderness failures.
6. Revised the sections of critical members.
7. Corrected duplicate member-property assignments and unavailable section definitions.
8. Re-ran the analysis and steel design.
9. Verified the final design results.
10. Achieved passing steel design checks for the final model.

## Critical Design Considerations

The initial design contained several members with utilization ratios greater than the allowable value of `1.000`.

The major governing issue was **member slenderness**, particularly for critical pillar/column members.

The member sections were progressively refined based on the STAAD.Pro design output until the final design satisfied the required steel design checks.

## Final Result

The final STAAD.Pro model was successfully analyzed and checked for steel design.

**Final result: All reported steel member design checks passed with utilization ratios within the allowable limit.**

## Project Files

```text
steel-industrial-warehouse-staad/
│
├── README.md
├── STAAD_FINAL_PILLAR_REDESIGN.std
│
└── screenshots/
    ├── staad-model.png
    ├── analysis-results.png
    └── final-steel-design.png
