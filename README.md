
# Integration of Value Stream Mapping and System Dynamics for Process Waste Improvement

## Project Overview

This project focuses on identifying and improving process waste in a complex production line by integrating **Value Stream Mapping (VSM)** with **System Dynamics (SD)** modeling. Value Stream Mapping is a Lean Manufacturing tool used to identify bottlenecks, inventory delays, non-value-added activities, and process waste. However, traditional VSM mainly provides a static snapshot of the production system.

To overcome this limitation, this project combines VSM with System Dynamics simulation using **Vensim**. The study was applied to a **hot water generator production line** in a manufacturing environment. The main objective was to analyze the current production flow, identify bottlenecks, evaluate operational and financial performance, and recommend practical Kaizen improvements for better productivity, reliability, and resource utilization.

The project demonstrates how a static lean manufacturing map can be converted into a dynamic decision-support model for production improvement.

---

## Objectives

- Identify waste and bottlenecks in the production line.
- Develop the current-state Value Stream Map for the hot water generator process.
- Convert the VSM into a System Dynamics model using Vensim.
- Evaluate operational, financial, and resource performance using Lean Box Score.
- Propose Kaizen improvements for quality, reliability, manpower, and cost reduction.
- Develop a future-state improvement plan for the production system.

---

## Tools and Techniques Used

- Value Stream Mapping (VSM)
- System Dynamics Modeling
- Vensim Simulation Software
- Lean Box Score
- Kaizen Improvement Analysis
- Takt Time Analysis
- Manpower Optimization
- Cost and Resource Capacity Evaluation
- Production Flow Analysis

---

## Methodology and Project Execution

The project was completed through a structured lean manufacturing and simulation-based improvement approach. The execution focused on understanding the existing production system, converting the static process map into a dynamic model, evaluating operational and financial performance, and developing improvement recommendations based on Lean principles.

### 1. Defined Improvement Priorities

The first step was to identify the key improvement areas within the production system. The project focused on internally controlled performance factors such as process quality, resource utilization, machine reliability, manpower efficiency, and cost reduction.

These priorities helped define the direction of the VSM and System Dynamics analysis.

### 2. Developed the Current-State Value Stream Map

A current-state Value Stream Map was developed for the hot water generator production line. The complete process flow was studied from customer order placement to finished goods inventory.

The production process included:

1. Customer order
2. Product design
3. Production control
4. Supplier material supply
5. Angle cutting
6. Arrangement of base
7. Outer shell layers
8. Shell layering
9. Initial assembly
10. Final connections
11. Painting
12. Testing
13. Finished goods inventory

Production data such as cycle time, changeover time, uptime, quality level, inventory, and lead time were collected for each workstation. This helped visualize the complete material and information flow across the production system.

### 3. Converted the VSM into a System Dynamics Model

After developing the current-state VSM, the production flow was translated into a System Dynamics model using **Vensim**.

The model represented the production system using:

- Stocks for inventory and accumulation points
- Flows for production movement between stages
- Variables for process time, quality, rework, and resource usage
- Feedback relationships between different production activities

This step helped move the analysis beyond a static process map and provided a dynamic view of how production delays, rework, resource availability, and process interactions affect overall value stream performance.

### 4. Evaluated the Current Production System

The existing production system was evaluated using Lean Box Score methodology. The analysis included operational, resource capacity, and financial performance indicators.

Key metrics evaluated included:

- Dock-to-dock time
- First Time Through quality
- On-Time Delivery
- Sales per person
- Conversion cost
- Average cost per unit
- Value stream profit
- Productive and non-productive resource capacity

This evaluation created a baseline for identifying improvement opportunities.

### 5. Identified Bottlenecks and Improvement Opportunities

Based on the VSM, System Dynamics model, and Lean Box Score evaluation, several improvement areas were identified:

- Painting defects
- Rust formation
- Assembly line delays
- Equipment malfunction
- Poor worker training
- Manpower underutilization

Each issue was analyzed from a Lean Manufacturing perspective to understand its effect on rework, cost, production delay, and process reliability.

### 6. Proposed Kaizen Improvements

Kaizen improvement actions were proposed for the identified problem areas. These actions included:

- Surface cleaning before painting
- Rust removal and rust-inhibiting primer application
- Preventive maintenance scheduling
- Supplier coordination and inventory control
- Instructor-led and on-the-job worker training
- Takt time-based manpower balancing

The improvement actions were selected based on feasibility and expected impact on quality, cost, productivity, and process flow.

### 7. Performed Manpower Optimization Using Takt Time

Takt time analysis was used to compare customer demand with available production time.

```text
Takt Time = Available Production Time / Customer Demand

Takt Time = 36 hours / 4 units

Takt Time = 9 hours per product
````

The manpower allocation across workstations was reviewed based on process cycle times and workload requirements. Workers were reassigned more effectively to reduce underutilization and improve labor productivity.

### 8. Developed the Future-State Value Stream Map

Finally, a future-state VSM was developed to represent the improved production system. The future-state map reflected the proposed Kaizen improvements, optimized manpower allocation, reduced repair cases, and improved production flow.

---

## Results and Outcomes

The project achieved the following major outcomes:

* Integrated **Value Stream Mapping and System Dynamics** to create a dynamic Lean Manufacturing analysis framework.
* Identified major bottlenecks in painting, rust formation, assembly, equipment reliability, and manpower utilization.
* Reduced manpower requirement from **18 workers to 10 workers**.
* Improved sales per person from approximately **$1,376 to $2,477**.
* Reduced failure/repair cases from **13 to 7**.
* Estimated weekly manpower cost saving of approximately **$1,101**.
* Proposed Kaizen actions to reduce rework caused by painting and rust-related defects.
* Developed a future-state value stream map for improved production performance.
* Demonstrated how Vensim-based System Dynamics can improve decision-making beyond traditional static VSM.

---

## Lean Box Score Summary

Approximate USD values were calculated using:

```text
1 USD = ₹94.46
```

| Category    |                  Metric |   Result |
| ----------- | ----------------------: | -------: |
| Operational |       Dock-to-Dock Time | 58 hours |
| Operational |      First Time Through |      75% |
| Operational |        On-Time Delivery |     100% |
| Operational | Sales per Person Before |  ~$1,376 |
| Operational |  Sales per Person After |  ~$2,477 |
| Financial   |                 Revenue | ~$24,772 |
| Financial   |           Material Cost | ~$11,645 |
| Financial   |         Conversion Cost |    ~$930 |
| Financial   |     Value Stream Profit | ~$21,628 |
| Manpower    |          Workers Before |       18 |
| Manpower    |           Workers After |       10 |
| Reliability |   Failure/Repair Before |       13 |
| Reliability |    Failure/Repair After |        7 |

---

## Key Calculations

### Takt Time

```text
Takt Time = Available Production Time / Customer Demand

Takt Time = 36 hours / 4 units

Takt Time = 9 hours per product
```

### Sales per Person Before Optimization

```text
Sales per Person = (208 × 585000) / (52 × 18)

Sales per Person = ₹130,000

Sales per Person ≈ $1,376
```

### Sales per Person After Optimization

```text
Sales per Person = (208 × 585000) / (52 × 10)

Sales per Person = ₹234,000

Sales per Person ≈ $2,477
```

### Manpower Improvement

```text
Before Optimization = 18 workers

After Optimization = 10 workers

Reduction = 8 workers
```

### Weekly Manpower Cost Saving

```text
Weekly Saving = ₹104,000

Weekly Saving ≈ $1,101
```

### Value Stream Profit

```text
Value Stream Profit = Revenue - Total Cost

Value Stream Profit ≈ ₹2,043,018

Value Stream Profit ≈ $21,628
```

---

## Project Workflow

```text
Define Organizational Priorities
        ↓
Create Current-State Value Stream Map
        ↓
Collect Production and Process Data
        ↓
Build System Dynamics Model in Vensim
        ↓
Evaluate Using Lean Box Score
        ↓
Identify Bottlenecks and Waste
        ↓
Propose Kaizen Improvements
        ↓
Optimize Manpower Using Takt Time
        ↓
Create Future-State Value Stream Map
```

---

## Kaizen Improvement Summary

| Problem Area          | Issue Identified            | Proposed Improvement                                 | Expected Benefit             |
| --------------------- | --------------------------- | ---------------------------------------------------- | ---------------------------- |
| Painting              | Poor paint adhesion         | Clean metal surface using sandpaper and wire brush   | Reduced rework               |
| Rust Formation        | Rust under painted surface  | Remove rust and apply rust-inhibiting primer         | Improved surface quality     |
| Assembly Line         | Supply chain delays         | Improve supplier coordination and inventory planning | Reduced production stoppage  |
| Equipment Malfunction | Machine breakdowns          | Apply preventive maintenance and root-cause analysis | Improved machine reliability |
| Worker Training       | Errors due to poor training | Use instructor-led and on-the-job training           | Reduced mistakes and rework  |
| Manpower Utilization  | Underutilized workers       | Use takt time-based worker allocation                | Improved labor productivity  |

---

## Major Learnings

Through this project, I gained practical understanding of:

* Lean Manufacturing implementation in a real production environment
* Value Stream Mapping for identifying process waste
* System Dynamics modeling using Vensim
* Lean Box Score evaluation for operational and financial performance
* Takt time-based manpower optimization
* Kaizen-based continuous improvement
* Production bottleneck analysis
* Cost reduction and resource utilization improvement

---

## Authors

* **Dr. Shyamal Samant**
  Department of Mechanical Engineering
  Amity School of Engineering and Technology

* **Abhay Tyagi**
  Department of Mechatronics Engineering
  Amity School of Engineering and Technology

* **Naman Narula**
  Department of Mechatronics Engineering
  Amity School of Engineering and Technology

---

## Conclusion

This project demonstrates that integrating **Value Stream Mapping with System Dynamics** provides a stronger and more practical Lean Manufacturing improvement approach than using VSM alone.

VSM helped identify waste, bottlenecks, and non-value-added activities, while System Dynamics helped understand the behavior of the production system more dynamically. The Lean Box Score provided a structured way to evaluate operational, financial, and resource performance.

The proposed improvements reduced manpower requirements, improved sales per person, reduced repair cases, and provided a future-state production roadmap. This framework can be applied to other manufacturing systems where production waste, resource utilization, quality issues, and bottlenecks need to be analyzed and improved.

```
```
