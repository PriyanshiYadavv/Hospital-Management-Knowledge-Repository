# Decision Making

The knowledge repository supports basic
rule-based decision-making.

| Input Condition | Decision |
|---|---|
| Doctor available | Confirm appointment |
| Doctor unavailable | Reject appointment request |
| Room available | Allocate room |
| Room occupied | Do not allocate room |
| Patient has high fever | Recommend medical evaluation |
| Charges are provided | Calculate total bill |

Example:

IF Doctor Availability = Yes
THEN Appointment Status = Confirmed
