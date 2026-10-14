# Occupational Therapy Activity Analysis — Portfolio Report

## Business question
How can hospital management monitor therapeutic activity engagement, understand declined sessions and identify where activity planning may benefit from review?

## Approach
1. Organise session-level data into consistent fields (date, activity, anonymised synthetic patient ID, outcome, duration and time of day).
2. Distinguish **Accepted**, **Declined**, **Cancelled**, and **Not Recorded**. Do not treat cancellation or missing records as patient refusal.
3. Calculate total offered sessions, acceptance rate, decline rate, attended minutes and average accepted session duration.
4. Compare outcomes by month, activity and time of day.
5. Add interactive filters so managers can examine patterns without changing raw records.

## KPI definitions
- **Total sessions:** number of recorded session offers.
- **Accepted sessions:** count of Outcome = Accepted.
- **Declined sessions:** count of Outcome = Declined.
- **Acceptance rate:** Accepted / Total sessions (includes cancellations and not-recorded in denominator; clearly stated).
- **Decline rate:** Declined / Total sessions.
- **Engagement minutes:** sum of Minutes_Attended (zero for non-attended outcomes).
- **Average accepted session duration:** Engagement minutes / Accepted sessions.

## Interpretation
The interactive charts illustrate how a manager might review activity uptake, identify activities with relatively lower participation, and investigate changes across time. This is descriptive analysis; it does not establish why a patient declined or whether a treatment was effective.

## Limitations
- Fabricated records are for demonstration only; results are not workplace findings.
- A single session may not represent a unique patient; session counts are not patient counts.
- Scheduling, staffing, patient preference and clinical context could affect participation.
- A cancelled session is not equivalent to a patient decline.

## Confidentiality
The original project used confidential workplace data and Excel. This public version uses fully synthetic records and a separately recreated dashboard. **All uploaded figures and visualisations differ from the actual confidential analysis.**
