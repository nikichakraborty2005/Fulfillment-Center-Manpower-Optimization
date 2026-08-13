🏭 Fulfillment Center Manpower & Network Optimization

Workforce Planning | Excel Solver | Cost Optimization | SLA Management | Operations Analytics

📌 Project Overview

This project develops a data-driven workforce planning and optimization model for a fulfillment center.

The model uses Microsoft Excel Solver to determine the optimal allocation of Full-Time Employees (FTEs) and contract staff across different shifts, with the objective of minimizing workforce cost while satisfying operational demand and SLA requirements.

In addition to manpower optimization, the project maps the cross-functional handoffs between Operations, Finance, HRBP, and Facilities to identify bottlenecks, reduce coordination delays, and improve overall fulfillment-center efficiency.

🎯 Business Objective

A fulfillment center must maintain enough manpower to handle demand without unnecessarily increasing labor costs.

The project therefore solves the following business problem:

How can a fulfillment center allocate FTE and contract manpower across shifts at minimum cost while maintaining required capacity and SLA performance?

The analysis focuses on two connected areas:

1. Workforce Optimization

Match staffing levels with shift-wise workload

Determine the optimal FTE vs. contract workforce mix

Minimize total workforce cost

Maintain required operational capacity

Support SLA targets

2. Network & Process Optimization

Map cross-functional handoffs

Identify process bottlenecks

Improve coordination between Operations, HRBP, Finance and Facilities

Reduce delays caused by approvals, staffing readiness and resource availability

🔍 Business Questions

The project answers key operational questions such as:

How many employees are required in each shift?

What combination of FTE and contract staff is most cost-effective?

What is the minimum workforce cost required to satisfy demand?

Which shifts are at risk of understaffing?

Can the optimized staffing plan meet SLA requirements?

Where do cross-functional handoffs create bottlenecks?

How can workforce planning become more responsive to changing demand?

🛠️ Tools & Methodologies

Tool / Method

Application

Microsoft Excel

Workforce planning and operational analysis

Excel Solver

Optimization of FTE and contract staff allocation

Optimization Modeling

Cost minimization under operational constraints

SQL

Supporting data analysis and validation

SLA Analysis

Service-level and capacity evaluation

Process Mapping

Cross-functional handoff analysis

Bottleneck Analysis

Identification of operational delays

🔄 Project Workflow

                 OPERATIONAL DEMAND
                         │
                         ▼
                  DATA PREPARATION
                         │
                         ▼
               SHIFT-WISE REQUIREMENT
                         │
                         ▼
              DEFINE DECISION VARIABLES
                         │
                         ▼
             DEFINE COST & CONSTRAINTS
                         │
                         ▼
                EXCEL SOLVER MODEL
                         │
                         ▼
              MINIMIZE WORKFORCE COST
                         │
                         ▼
             CHECK CAPACITY & SLA
                         │
                         ▼
              OPTIMAL STAFF ALLOCATION
                         │
                         ▼
             BOTTLENECK IDENTIFICATION
                         │
                         ▼
              PROCESS IMPROVEMENTS

📊 Optimization Model

Decision Variables

The model determines the number of:

FTEs assigned to each shift

Contract employees assigned to each shift

These variables are changed by Excel Solver to find the most cost-effective feasible workforce plan.

💰 Objective Function

The primary objective is to minimize total workforce cost.

Conceptually:

Minimize Total Cost

= Σ (FTE Allocation × FTE Cost)
+ Σ (Contract Allocation × Contract Cost)

The goal is not simply to reduce manpower.

Instead, the model finds the lowest-cost staffing combination that can still meet operational requirements and SLA targets.

🔒 Model Constraints

The Solver model incorporates practical workforce constraints.

1. Demand Constraint

Each shift must have sufficient workforce to handle its expected workload.

Allocated Workforce ≥ Required Workforce

2. SLA Constraint

The available workforce must provide enough operational capacity to support the required SLA.

Available Capacity ≥ Required SLA Capacity

3. Workforce Availability

Staff allocation must remain within the available workforce pool.

4. Integer Constraint

Employees cannot be allocated as fractions.

FTEs = Integer
Contract Staff = Integer

5. Non-Negativity

FTEs ≥ 0
Contract Staff ≥ 0

🧮 Excel Solver Implementation

The optimization model is implemented using Microsoft Excel Solver.

Solver Configuration

Solver Component

Model Setup

Objective Cell

Total Workforce Cost

Goal

Minimize

Changing Cells

FTE & Contract Staff Allocation

Constraints

Demand, Capacity, SLA & Workforce Limits

Variable Type

Integer

Final Output

Optimal Workforce Allocation

Model Logic

FTE Allocation ───────┐
                      │
                      ▼
                Total Workforce
                      │
Contract Allocation ──┘
                      │
                      ▼
             Capacity Requirement
                      │
                      ▼
                SLA Requirement
                      │
                      ▼
             Minimum Feasible Cost

⏰ Shift-Level Workforce Planning

The model evaluates staffing requirements separately across operating shifts.

Shift

Required Staff

FTEs

Contract Staff

Total Staff

Total Cost

Morning

Input

Solver

Solver

Calculated

Calculated

Afternoon

Input

Solver

Solver

Calculated

Calculated

Evening

Input

Solver

Solver

Calculated

Calculated

Night

Input

Solver

Solver

Calculated

Calculated

The final allocation is generated automatically by Solver based on the project's input data and constraints.

📈 Workforce Capacity Analysis

The model compares the required workforce with the optimized workforce allocation.

                Required Workforce
                        │
             ┌──────────┴──────────┐
             ▼                     ▼
     Allocated < Required    Allocated ≥ Required
             │                     │
             ▼                     ▼
       ⚠ Staffing Gap          ✓ Requirement Met
             │                     │
             ▼                     ▼
          SLA Risk             Feasible Plan

This allows managers to identify shifts where staffing shortages could create operational or SLA risks.

👥 FTE vs. Contract Workforce

A major component of the model is determining the appropriate balance between permanent and flexible labor.

FTE Workforce

Provides:

Workforce stability

Process familiarity

Consistent operational capability

Stronger suitability for predictable base demand

Contract Workforce

Provides:

Workforce flexibility

Support during demand fluctuations

Additional capacity during peak periods

Ability to scale manpower without permanently increasing fixed staffing

The Solver model evaluates the cost and operational trade-off between the two workforce types.

🏢 Cross-Functional Network Analysis

Workforce planning does not operate independently.

The project maps the flow of information and responsibilities across:

Operations → HRBP → Finance → Facilities → Operations

Typical Handoff Flow

                 OPERATIONS
                     │
                     ▼
            Workforce Requirement
                     │
                     ▼
                    HRBP
                     │
          Hiring / Availability
                     │
                     ▼
                  FINANCE
                     │
            Budget / Approval
                     │
                     ▼
                FACILITIES
                     │
          Resource Readiness
                     │
                     ▼
                 OPERATIONS
                     │
                     ▼
                 EXECUTION

🔎 Bottleneck Analysis

The project identifies potential delays across the end-to-end workforce process.

Potential Bottlenecks

Delayed workforce approvals

Hiring or onboarding delays

Budget approval dependencies

Workforce availability constraints

Facility/resource readiness issues

Poor communication between functions

Manual handoffs between teams

These bottlenecks can ultimately affect shift readiness, productivity and SLA performance.

⚙️ Process Improvement Strategy

1. Demand-Based Staffing

Use historical demand patterns to estimate manpower requirements for every shift.

2. Dynamic Workforce Mix

Adjust the FTE and contract workforce mix according to workload and cost.

3. Peak-Demand Planning

Maintain flexible staffing capacity for periods of unusually high demand.

4. Standardized Handoffs

Define clear ownership, approval timelines and escalation paths between Operations, HRBP, Finance and Facilities.

5. Shift-Level Monitoring

Monitor staffing, demand, capacity and SLA performance at the shift level.

6. Exception-Based Management

Prioritize management attention when:

Staffing < Requirement
        OR
SLA Performance ↓
        OR
Cost > Target
        OR
Handoff Delay ↑

📊 Project Outputs

The model produces operational outputs such as:

Optimal FTE allocation

Optimal contract workforce allocation

Total workforce cost

Required vs. allocated manpower

Shift-wise staffing gaps

FTE vs. contract workforce mix

Cost comparison

Capacity feasibility

SLA feasibility

Cross-functional bottleneck analysis

The outputs_viz/ folder contains the project's charts and visualization outputs.

📁 Repository Structure

Fulfillment-Center-Manpower-Optimization/
│
├── 📄 README.md
│
├── 📁 data/
│   └── Input datasets
│
├── 📁 docs/
│   └── Project documentation
│
├── 📁 excel_model/
│   └── Excel Solver optimization model
│
├── 📁 outputs_viz/
│   └── Charts and model outputs
│
└── 📁 sql/
    └── Supporting SQL queries
