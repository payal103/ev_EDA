# ev_EDA
**5,000 electric vehicle charging stations**:

---

### 📄 **Basic Dataset Info**

* **Rows × Columns**: `5000 × 17`
* **No missing values or duplicates**
* **All columns are clean and complete**

---

### 📋 **Key Columns Overview**

* **Categorical**:
  `Charger Type`, `Availability`, `Station Operator`, `Connector Types`, `Renewable Energy Source`, `Maintenance Frequency`

* **Numerical**:
  `Cost (USD/kWh)`, `Distance to City (km)`, `Usage Stats (avg users/day)`, `Charging Capacity (kW)`, `Reviews (Rating)`, `Parking Spots`

* **Location Info**:
  `Latitude`, `Longitude`, `Address`

* **Time Info**:
  `Installation Year`

---

### 📊 **Numerical Summary (Selected Columns)**

| Feature                         | Min  | Mean   | Max  |
| ------------------------------- | ---- | ------ | ---- |
| **Cost (USD/kWh)**              | 0.10 | 0.30   | 0.50 |
| **Usage Stats (avg users/day)** | 10   | 55.45  | 100  |
| **Charging Capacity (kW)**      | 22   | 144.27 | 350  |
| **Distance to City (km)**       | 0.5  | 10.2   | 20   |
| **Reviews (Rating)**            | 3.0  | 3.99   | 5.0  |
| **Parking Spots**               | 1    | 5.52   | 10   |

---


1. **Charger Type Distribution**
2. **Usage Stats vs Charging Capacity**
3. **Correlation Heatmap**
4. **Geographic Distribution (Map)**
5. **Peak Installation Years**
6. **Renewable Source Usage**
7. **Availability and Maintenance Patterns**

![image](https://github.com/user-attachments/assets/4e7ad6da-3883-4c90-a108-93cf10e66d94)


The chart above shows the **distribution of charger types** in the dataset:

* **AC Level 2** is the most common.
* **DC Fast Chargers** are widely used but less than Level 2.
* **AC Level 1** chargers are the least common.

This reflects real-world trends where Level 2 chargers are most popular for public and residential use, while DC Fast Chargers are typically used on highways or high-traffic areas.

**Usage Stats vs Charging Capacity**.
![image](https://github.com/user-attachments/assets/31bb9790-334f-4164-b530-6a7c3cea1a8e)


The scatter plot reveals the following:

* **Higher charging capacities (e.g., 350 kW)** generally attract **more users per day**, especially for **DC Fast Chargers**.
* **AC Level 1 and Level 2** chargers typically serve fewer users, consistent with their lower power output.
* There's a positive trend: **more capacity → more usage**, but with some overlap.




