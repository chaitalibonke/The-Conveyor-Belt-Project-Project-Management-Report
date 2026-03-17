
# The Conveyor Belt Project — Project Management Report

## Overview
This project applies project management principles to plan, execute, and
close a computer-controlled conveyor belt system. The project was managed
using Microsoft Project and evaluated across four quarterly status reports
using Earned Value Management (EVM) techniques. This project demonstrates
the application of EVM for tracking cost and schedule performance in a
large-scale engineering system. The initial proposed budget was $1.6
million with a target completion time of 530 days.

---

## Full Report
The complete project report is available here:
[View Full Report](Conveyor_Belt_Project_Report.pdf)

---

## Team — Group 32

| Name                   | Role               |
|------------------------|--------------------|
| Bonke Chaitali         | Business Analyst   |
| Chavan Kartik          | Technical Lead     |
| Murali Sathyendrasaran | Project Manager    |
| Thapliyal Vikalp       | Solution Architect |

Course: INSY-5373-001 — Project Management
Project Sponsor: Dr. Michel E. Whittenberg — VP of Operations

> Note: This repository represents my personal documentation
> of our group project and is shared for portfolio purposes only.

---

## Project Objective
To develop a computer-controlled conveyor belt that moves and positions
items within less than 1 millimeter of precision, within a budget of
$1.6 million and a timeline of 2 years. The system must be updatable
with future technologies and is intended to replace existing systems
in 30% of factories currently installed.

---

## Technical Specifications

- Positioning accuracy: less than 1 mm
- Operating temperature: 10°C to 80°C
- Belt width: 1,200 mm
- Belt speed: 100 m/min to 300 m/min
- Must pass ISO 703:2017 standard test
- Interchangeable and market-available parts
- Designed for future technology upgrades

---

## Project Priority Matrix

| Criterion | Time | Scope | Cost |
|-----------|------|-------|------|
| Constrain | X    |       |      |
| Enhance   |      | X     |      |
| Accept    |      |       | X    |

Time is the primary constraint for this project.

---

## Work Breakdown Structure

| Hardware                      | Operating System      | Utilities                | System Integration          |
|-------------------------------|-----------------------|--------------------------|-----------------------------|
| Hardware Specifications       | Kernel Specifications | Utilities Specifications | Architectural Decisions     |
| Hardware Design               | Disk Drivers          | Routine Utilities        | Integration First Phase     |
| Hardware Documentation        | Serial I/O Drivers    | Complex Utilities        | System Hard/Software Test   |
| Prototypes                    | Memory Management     | Utilities Documentation  | Project Documentation       |
| Order Circuit Boards          | OS Documentation      | Shell                    | Integration Acceptance Test |
| Assemble Preproduction Models | Network Interface     |                          |                             |

---

## Critical Path

```
Architectural Decisions → Hardware Specifications → Hardware Design →
Hardware Documentation → Integration First Phase → Serial I/O Drivers →
System Hard/Software Test → Network Interface → Integration Acceptance Testing
```

---

## Budget Summary

> The initial proposed budget was $1.6M. The finalized Budget at Completion
> (BAC) after planning adjustments was $1,210,713.08.

| Item                     | Amount          |
|--------------------------|-----------------|
| Total Project Cost       | $1,051,200.00   |
| Total Budget Reserve     | $49,448.25      |
| Management Reserve (10%) | $110,064.83     |
| Total Budget (BAC)       | $1,210,713.08   |

### Budget Reserve Contingency

| Risk                       | Probability | Cost Impact | Reserve        |
|----------------------------|-------------|-------------|----------------|
| Equipment Failures         | 40%         | $22,530     | $9,012.00      |
| Delay in Circuit Board     | 25%         | $20,945     | $5,236.25      |
| Increase of Material Cost  | 35%         | $36,220     | $12,677.00     |
| Operational Complexity     | 20%         | $8,500      | $1,700.00      |
| System Integration Failure | 55%         | $37,860     | $20,823.00     |
| **Total Budget Reserve**   |             |             | **$49,448.25** |

---

## Risk Assessment

| Risk Event                 | Likelihood | Impact | Response | Contingency Plan                     |
|----------------------------|------------|--------|----------|--------------------------------------|
| Equipment Failures         | 2          | 3      | Mitigate | Pick extra equipment from inventory  |
| Delay in Circuit Board     | 1          | 4      | Avoid    | Order from reliable vendor           |
| Increase of Material Cost  | 1          | 2      | Transfer | Contract to a supplier               |
| Operational Complexity     | 2          | 3      | Mitigate | Detailed training manual and support |
| System Integration Failure | 2          | 4      | Avoid    | Continually revise the design        |

---

## Resources

| Team          | Group                | Cost per Hour |
|---------------|----------------------|---------------|
| Design        | R&D (2 Teams)        | $100/hr       |
| Development   | R&D (2 Teams)        | $70/hr        |
| Documentation | R&D (1 Team)         | $60/hr        |
| Assembly/Test | R&D (1 Team)         | $70/hr        |
| Purchasing    | Procurement (1 Team) | $40/hr        |

Overallocated resources (Design, Documentation, Development) were
resolved by levelling outside slack, which increased project duration
from 530 to 560 days.

---

## Earned Value Management — Quarterly Status Reports

### Quarter 1 (April 1, 2016)

| Metric | Value         |
|--------|---------------|
| PV     | $140,800.00   |
| EV     | $155,980.72   |
| AC     | $151,680.00   |
| SV     | +$15,180.72   |
| CV     | +$4,300.72    |
| CPI    | 1.03          |
| SPI    | 1.11          |
| EACf   | $1,177,335.04 |
| PCIB   | 12.88%        |

> Status: Under budget and ahead of schedule.

---

### Quarter 2 (July 1, 2016)

| Metric | Value         |
|--------|---------------|
| PV     | $448,560.00   |
| EV     | $454,431.13   |
| AC     | $470,720.00   |
| SV     | +$5,871.13    |
| CV     | -$16,288.87   |
| CPI    | 0.97          |
| SPI    | 1.01          |
| EACf   | $1,254,115.26 |
| PCIB   | 37.53%        |

> Status: Over budget but ahead of schedule.

---

### Quarter 3 (October 1, 2016)

| Metric | Value         |
|--------|---------------|
| PV     | $599,440.00   |
| EV     | $609,520.00   |
| AC     | $631,600.00   |
| SV     | +$10,080.00   |
| CV     | -$22,080.00   |
| CPI    | 0.97          |
| SPI    | 1.02          |
| EACf   | $1,254,572.19 |
| PCIB   | 50.34%        |

> Status: Over budget but ahead of schedule.

---

### Quarter 4 (January 1, 2017)

| Metric | Value         |
|--------|---------------|
| PV     | $685,120.00   |
| EV     | $690,009.50   |
| AC     | $719,520.00   |
| SV     | +$4,889.50    |
| CV     | -$29,510.50   |
| CPI    | 0.96          |
| SPI    | 1.01          |
| EACf   | $1,262,496.48 |
| VAC    | -$51,783.40   |
| TCPI   | 1.06          |
| PCIB   | 56.99%        |

> Status: Over budget but ahead of schedule.
> TCPI of 1.06 means $1.06 of work must be earned for every dollar
> spent in the future to complete within budget.

---

### Revised Quarter 4

| Metric | Value         |
|--------|---------------|
| PV     | $685,120.00   |
| EV     | $688,281.67   |
| AC     | $719,520.00   |
| SV     | +$3,161.67    |
| CV     | -$31,238.33   |
| CPI    | 0.96          |
| SPI    | 1.00          |
| EACf   | $1,265,665.03 |
| VAC    | -$54,951.95   |
| TCPI   | 1.06          |
| PCIB   | 56.85%        |

> Status: On schedule but over budget.

---

## Project Changes

Two key changes were implemented to maintain the 530-day time constraint:

1. **Added 2 extra Development Teams** — increased resource allocation
   from 200% to 400%, reducing completion time to 550 days
2. **Assigned External Development Team** to Routine Utilities —
   a 60-day task with minimal dependencies, chosen to minimize
   communication risk and cost impact

---

## Key Findings
- Time was the primary project constraint throughout all phases
- The project moved from under budget in Q1 to progressively over
  budget by Q4 with a final Cost Variance of -$29,510.50
- Despite cost overruns, the project remained ahead of or on schedule
  across all four quarters
- EACf consistently exceeded BAC from Q2 onward indicating sustained
  cost pressure throughout the project
- Adding external development resources was the most effective
  intervention for maintaining the time constraint
- A TCPI of 1.06 at Q4 indicates the project requires above-normal
  cost efficiency to close within original budget
- System Integration Failure carried the highest risk score and
  budget reserve of $20,823 among all identified risks

---

## Lessons Learned
- Duration estimating methods need continuous improvement
- Effective communication within the team is essential
- Weekly meetings are critical for tracking priorities and progress
- Cost control methods need continuous monitoring and improvement
- Project Manager must closely monitor all tasks and activities
- Multi-tasking reduces productivity and should be minimized
- Training for increasing productivity should be provided early

---

## Project Closure Highlights
- Customer training provided on hardware operation, maintenance,
  assembly of spare parts, and trial runs
- All project resources released and reassigned after closure
- Performance evaluations conducted for all team members and vendors
- Project audit conducted focusing on lessons learned and process
  improvement for future projects

---

## Tools Used
- Microsoft Project — scheduling, resource leveling, Gantt charts
- Earned Value Management (EVM) — quarterly performance tracking
- Network Diagrams — critical path analysis
- Responsibility Matrix — task and role assignment
- Risk Assessment Matrix — risk identification and response planning

---

## Reproducibility
This project was conducted using Microsoft Project and document-based
deliverables. To reproduce the analysis:
- Load the Work Breakdown Structure into Microsoft Project
- Assign resources and costs as per the Organization Matrix
- Apply resource leveling outside slack to resolve overallocations
- Use Microsoft Project to track schedules, resource allocation,
  and Earned Value metrics at each quarterly checkpoint
- Generate EVM reports (PV, EV, AC, CPI, SPI, EACf, TCPI) at
  defined checkpoints to monitor cost and schedule performance

---

## Limitations
- Project estimates were based on assumptions provided by the sponsor
  and may not reflect real-world complexity
- Resource availability assumptions may differ in actual deployment
- External development team communication gaps were not fully quantified
- The model does not account for inflation or supply chain disruptions
  beyond the identified risk events

---

## Disclaimer
This project was completed as a group term paper for INSY-5373-001
at the University of Texas Arlington. No software code is
included in this repository as the project was conducted using
Microsoft Project and document-based deliverables.
