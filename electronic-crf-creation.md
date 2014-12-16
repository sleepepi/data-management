Electronic CRF Creation
=======================

Purpose
-------
To describe the process of creating an electronic case report form (CRF) by adding variables, units, ranges, and branching logic when appropriate.

Scope
-----
This SOP is intended for use by any clinical research staff who may be involved in the creation of CRFs.

Responsibilities
----------------
#### Data Manager
- To provide guidance to Research Assistant(s) working on a CRF
- To designate the electronic data capture software that will be used to house the CRF

#### Research Assistant
- To create and maintain CRF(s) for any given study

Procedure
---------
1. Determine which CRF(s) will be created
  * Data Manager will provide Research Assistant with paper or electronic copies of the CRF that is being created
    - If possible, the CRF should be annotated with desired variable names
2. Create variables
  * Research Assistant will create electronic versions of each individual variable found the CRF
    - Variables should be given easy to reference variable names (such as ess_1 rather than would_you_every_fall_asleep)
    - Variables should be designated the correct type (numeric, date, scale, etc.) prior to the start of data collection<sup>1</sup>
    - If possible, date and numeric variables should have established minimums and maximums to flag improbable or impossible values<sup>1</sup>
    - Variables should be given consistent units<sup>1</sup>
  * For variables that contain option choices, these conventions should be followed whenever possible
    - For yes/no variables, yes should be coded as `1` and no should be coded as `0`
    - For checked/unchecked variables, checked should be coded as `1` and unchecked should be coded as `0`
    - The following missing codes have been established for use in all projects: `-10: Confusion`, `-9: Missing`, `-8: Not Applicable`, `-2: Don't Know`
  * Branching logic should be used judiciously to ensure that the flow of electronic form completion mimics that of the paper copy

References
----------
<sup>1</sup> [Spout Style Guide](https://www.github.com/sleepepi/spout)

===============
[Back to README](README.md)
