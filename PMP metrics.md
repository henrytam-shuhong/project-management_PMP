

Let's use an example to clearly illustrate the difference between **Earned Value (EV)** and **Planned Value (PV)**.

### Project Overview:

- **Total Budget (BAC)**: $100,000 (This is the total budget allocated for the project.)
    
- **Total Duration**: 10 months
    
- **Work Completed by End of Month 5**: 40% of the project work is completed.
    
- **Planned Progress by End of Month 5**: 50% of the work was planned to be completed by this time.
    

### Step-by-Step Calculation:

---

### 1. **Planned Value (PV)**

Planned Value represents the value of the work that was **planned** to be completed by a certain point in time.
**PV = How much money had you planned to spend by**

- **Planned Percent of Work by Month 5** = 50% (This is the planned progress according to the project schedule.)
    
- **Total Budget (BAC)** = $100,000
    

$$\text{Planned Value (PV)} = \text{Planned Percent of Work Completed} \times \text{Total Budget} $$$$\text{PV} = 50\% \times 100,000 = 50,000$$

- So, **Planned Value (PV)** at the end of Month 5 is **$50,000**.
    

---

### 2. **Earned Value (EV)**

Earned Value represents the value of the work that has been **actually completed** by a certain point in time.
**EV= PV  times   % of work completed**

- **Percent of Work Completed by Month 5** = 40% (This is the actual progress made on the project.)
    
- **Total Budget (BAC)** = $100,000
    

$$\text{Earned Value (EV)} = \text{Percent of Work Completed} \times \text{Total Budget}$$$$\text{EV} = 40\% \times 100,000 = 40,000$$

- So, **Earned Value (EV)** at the end of Month 5 is **$40,000**.
    

---

### Summary of Results:

- **Planned Value (PV)** at the end of Month 5: **$50,000**
    
- **Earned Value (EV)** at the end of Month 5: **$40,000**
    

### What Does This Mean?

- The **Planned Value (PV)** tells us that by Month 5, the project was **planned to have completed work worth $50,000**.
    
- The **Earned Value (EV)** tells us that the project has **actually completed work worth $40,000** by Month 5.
    

This means the project is behind schedule in terms of work completed, as the actual work is valued at $40,000 (instead of the planned $50,000).

---

### Key Takeaways:

- **Planned Value (PV)** is based on the **project schedule** (what should have been done by a certain date).
    
- **Earned Value (EV)** is based on the **actual progress** (what has been completed by that date).
    

This allows you to assess the project's **schedule performance** by comparing the planned work with the actual work done.

Would you like to calculate additional metrics, such as **Cost Performance Index (CPI)** or **Schedule Performance Index (SPI)**, to assess project performance further?


Let’s expand on the original example by calculating additional performance metrics commonly used in Earned Value Management (EVM). These metrics help assess the project’s cost and schedule performance.

### Recap of the Example Data:

- **Total Budget (BAC)** = $100,000
    
- **Planned Value (PV)** at the end of Month 5 = **$50,000**
    
- **Earned Value (EV)** at the end of Month 5 = **$40,000**
    
- **Actual Cost (AC)** by the end of Month 5 = **$45,000** (this is the actual money spent so far)
    

---

### 1. **Cost Variance (CV)**

**Cost Variance (CV)** tells us if the project is under or over budget at a specific point in time.

$$\text{CV} = \text{EV} - \text{AC}$$$$\text{CV} = 40,000 - 45,000 = -5,000$$

- **Interpretation**: The project is **over budget** by **$5,000**.
    

---

### 2. **Schedule Variance (SV)**

**Schedule Variance (SV)** measures how much ahead or behind the project is compared to the schedule.

$$\text{SV} = \text{EV} - \text{PV}$$$$\text{SV} = 40,000 - 50,000 = -10,000$$

- **Interpretation**: The project is **behind schedule** by **$10,000** worth of work.
    

---

### 3. **Estimate at Completion (EAC)**

The **Estimate at Completion (EAC)** predicts the total cost of the project based on its performance so far. It is calculated differently depending on the situation. Here are two common formulas for EAC:

- **If future performance is expected to be similar to current performance:**
    
    $$\text{EAC} = \frac{\text{BAC}}{\text{CPI}}$$
- **If future performance is expected to be similar to past performance:**
    
     $$\text{EAC} = \text{AC} + (\text{BAC} - \text{EV})$$

First, let's calculate **EAC based on CPI**:

- **CPI (Cost Performance Index)**:
    
    $$\text{CPI} = \frac{\text{EV}}{\text{AC}} = \frac{40,000}{45,000} = 0.89$$

$$\text{EAC} = \frac{100,000}{0.89} = 112,359.55$$

So, **EAC based on current performance** is **$112,360**.

---

### 4. **Variance at Completion (VAC)**

**Variance at Completion (VAC)** measures the difference between the Budget at Completion (BAC) and the Estimate at Completion (EAC).

$$\text{VAC} = \text{BAC} - \text{EAC}$$$$\text{VAC} = 100,000 - 112,360 = -12,360$$

- **Interpretation**: The project is expected to be over budget by **$12,360** by the time it is completed.
    

---

### 5. **Cost Performance Index (CPI)**

**CPI (Cost Performance Index)** is a measure of cost efficiency and financial effectiveness.

$$\text{CPI} = \frac{\text{EV}}{\text{AC}} $$$$\text{CPI} = \frac{40,000}{45,000} = 0.89$$

- **Interpretation**: For every dollar spent, only **89 cents** worth of work has been completed, indicating the project is over budget.
    

---

### 6. **Schedule Performance Index (SPI)**

**SPI (Schedule Performance Index)** is a measure of schedule efficiency.

$$\text{SPI} = \frac{\text{EV}}{\text{PV}}$$$$\text{SPI} = \frac{40,000}{50,000} = 0.80$$

- **Interpretation**: The project is performing at **80%** of the planned schedule. This means the project is behind schedule.
    

---

### 7. **To-Complete Performance Index (TCPI)**

**TCPI (To-Complete Performance Index)** is a measure of the efficiency needed for the remaining work to stay within the budget.

- **TCPI based on BAC**:
    
    $$\text{TCPI} = \frac{\text{BAC} - \text{EV}}{\text{BAC} - \text{AC}}$$

$$\text{TCPI} = \frac{100,000 - 40,000}{100,000 - 45,000} = \frac{60,000}{55,000} = 1.09$$

- **Interpretation**: The project needs to perform at a **1.09** efficiency level for the remaining work in order to complete within the original budget. This is higher than the CPI (0.89), indicating that the project will need to improve performance significantly to stay within budget.
    

---

### Summary of Metrics:

|**Metric**|**Value**|
|---|---|
|**Cost Variance (CV)**|-$5,000|
|**Schedule Variance (SV)**|-$10,000|
|**Estimate at Completion (EAC)**|$112,360|
|**Variance at Completion (VAC)**|-$12,360|
|**Cost Performance Index (CPI)**|0.89|
|**Schedule Performance Index (SPI)**|0.80|
|**To-Complete Performance Index (TCPI)**|1.09|

---

### Conclusion:

- The project is behind schedule and over budget.
    
- The **CPI** indicates cost inefficiency, and the **SPI** shows schedule delays.
    
- The **EAC** suggests the project will end up over budget unless performance improves.
    
- The **TCPI** indicates the level of efficiency required for the remaining work to bring the project in on budget.
    

This analysis gives a comprehensive view of the project's performance and can guide decisions on corrective actions.

Would you like further clarification on any of these metrics?

---

Using **Earned Value Management (EVM)** to predict delays involves analyzing key performance indicators that assess whether a project is on track with its timeline. Here’s how you can do it:  

### **1. Monitor the Schedule Performance Index (SPI)**  
\[
$$SPI = \frac{Earned Value (EV)}{Planned Value (PV)}$$
\]  
- **SPI < 1.0** → The project is behind schedule.  
- **SPI = 1.0** → The project is on track.  
- **SPI > 1.0** → The project is ahead of schedule.  

### **2. Evaluate Earned Schedule (ES) vs. Actual Time (AT)**  
- If the **Earned Schedule (ES)** (how much work should have been completed) is **less than** the **Actual Time (AT)** (time spent so far), it indicates potential delays.  

### **3. Forecast Completion Time Using Schedule Variance (SV)**  
\[
$$SV = EV - PV$$
\]  
- If **SV is negative**, the project is behind schedule and may require corrective action.  

### **4. Estimate Time to Complete Using the Time Estimate at Completion (EACt)**  
\[
$$EACt = \frac{Original Duration}{SPI}$$
\]  
- If SPI **is low**, the estimated completion time **increases**, predicting delays.  

### **5. Identify Trends in Weekly SPI Values**  
- If SPI remains below **1.0** consistently, delays are likely to **continue** or **worsen** without intervention.  

### **6. Take Corrective Actions**  
- Increase resource allocation.  
- Optimize workflows.  
- Adjust schedules and critical path tasks.  

Would you like help interpreting EVM metrics for a specific project scenario?  
