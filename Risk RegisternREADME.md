# Sample IT Risk Register

A mock IT/security risk register covering 10 representative assets across a typical
tech company's environment (IAM, application code, databases, payroll, endpoints,
vendors, backups, cloud infrastructure, support tooling, and an in-flight system
migration).

Built to demonstrate practical GRC risk assessment methodology: writing risk
statements in cause → event → impact form, scoring inherent vs. residual risk,
mapping existing controls, and documenting a treatment decision with an owner and
target date — the same structure used in real enterprise risk registers.

## Methodology

- **Risk scoring:** Likelihood × Impact, each rated 1–5.
  - 1–6 = Low, 7–14 = Medium, 15–25 = High
- **Inherent risk:** the risk level assuming no controls existed at all.
- **Residual risk:** the risk level after accounting for controls currently in place.
- **Treatment decision:** Mitigate, Accept, Transfer, or Avoid (see column
  `Treatment_Decision`) — chosen based on whether residual risk is within the
  organization's tolerance.
- **Risk categories used:** Access Management, Change Management, Data Protection,
  Segregation of Duties, Endpoint Security, Vendor/Third-Party Risk, Backup &
  Recovery, Privileged Access Management, Logging & Monitoring, SDLC/Program
  Development — deliberately spread across the ITGC domains plus adjacent GRC risk
  areas, rather than clustering in one area.

## Columns

| Column | Meaning |
|---|---|
| `Risk_ID` | Unique identifier |
| `Asset` | The system/asset the risk relates to |
| `Risk_Category` | Risk domain (maps to ITGC/framework areas) |
| `Risk_Description` | Full cause → event → impact risk statement |
| `Likelihood_Inherent` / `Impact_Inherent` | 1–5 scoring with no controls applied |
| `Inherent_Risk_Score` / `Inherent_Risk_Rating` | Likelihood × Impact, and its Low/Medium/High banding |
| `Existing_Controls` | Controls currently mitigating the risk |
| `Likelihood_Residual` / `Impact_Residual` | 1–5 scoring after existing controls |
| `Residual_Risk_Score` / `Residual_Risk_Rating` | Likelihood × Impact after controls, and banding |
| `Risk_Owner` | Person/role accountable for the risk |
| `Treatment_Decision` | Mitigate / Accept / Transfer / Avoid |
| `Target_Date` | Date by which further remediation is expected |
| `Status` | Open / In Progress / Closed |

## Note

This is a fictional dataset built for portfolio/demonstration purposes — it does not
represent any real company's actual risk posture.
