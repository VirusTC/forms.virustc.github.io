# EDI 837 Professional / Institutional Claims Transmission Mapping Guide
## Format Standard: ASC X12N 837 (Version 005010X222A1)

This loop profile defines data segments required for automated batch billing transmissions from Pacific Health Medical Centers Telehealth HQ to commercial clearinghouses and payers.

### Loop 2000A — Billing Provider Hierarchical Level
* **HL*1** -> Hierarchical Level Segment (Billing Provider)
* **PRV*BI*PXC*1223X0400X~** -> Provider Taxonomy (Telehealth / Clinical Logistics)

### Loop 2010AA — Billing Provider Name & NPI
* **NM1*85*2*PACIFIC HEALTH MEDICAL CENTERS*****XX*1234567890~** -> Entity ID (85), NPI Identifier
* **N3*YESLER TOWERS*****~** -> Facility Address
* **N4*SEATTLE*WA*98104~** -> Geographic Location

### Loop 2300 — Claim Information
* **CLM*CLAIMID10023*325.00***11:B:1*Y*A*Y*Y~** -> Total Claim Charge, Facility Code (11 = Telehealth)
* **HI*BK:N200*BF:E872~** -> Principal Diagnosis Code (ICD-10-CM Indexing)

### Loop 2400 — Service Line Details
* **LX*1~** -> Line Number
* **SV1*HC:S5190*85.00*UN*1***1:2~** -> Healthcare Common Procedure Coding System (HCPCS)
* **REF*XZ*71450045001~** -> National Drug Code (NDC) / Botanical Compound Lot Tracker
