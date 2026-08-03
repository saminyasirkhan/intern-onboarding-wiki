# 📈 Labour Planning

Planning is rarely the same from one day to the next. This section documents common scenarios you may encounter as a Labour Capacity Planning Intern.

---

<details>
<summary>📚 Basic Theory</summary>

<details>
<summary>📦 Volume</summary>

**Volume** is the forecasted number of packages expected to be processed during a planning period.

</details>

<details>
<summary>🔄 Rolled Volume</summary>

**Rolled Volume** is package volume carried over from a previous planning period because it was not processed.

</details>

<details>
<summary>⚠️ Volume Beyond Mechanical Capacity</summary>

**Volume Beyond Mechanical Capacity** is the amount of forecasted volume that exceeds what the site's equipment can physically process.

</details>

<details>
<summary>🏭 Max Capacity</summary>

**Max Capacity** is the maximum volume the site can process under normal operating conditions.

</details>

<details>
<summary>📊 Max Capacity UC</summary>

**Max Capacity UC** is the site's maximum processing capacity expressed as a unit count.

</details>

<details>
<summary>📈 TPH (Throughput Per Hour)</summary>

**TPH** is the average number of packages processed per labour hour.

It is one of the main drivers used to calculate labour requirements.

</details>

<details>
<summary>🎯 TPH QxG</summary>

**TPH QxG** is the target Throughput Per Hour that the labour plan is measured against.

</details>

<details>
<summary>📉 TPH QxG Delta</summary>

**TPH QxG Delta** is the difference between the actual TPH achieved and the planned TPH target.

</details>

<details>
<summary>🔄 Transfer by Type</summary>

**Transfer by Type** shows labour hours transferred into or out of a site, grouped by transfer category.

</details>

<details>
<summary>🚫 Absence %</summary>

**Absence Percentage** is the percentage of scheduled associates expected to be absent during the shift.

</details>

<details>
<summary>👋 Attrition</summary>

**Attrition** is the number of associates leaving the workforce.

</details>

<details>
<summary>📉 Attrition %</summary>

**Attrition Percentage** expresses workforce attrition as a percentage of the total workforce.

</details>

<details>
<summary>👥 Roster HC</summary>

**Roster Headcount (HC)** is the number of associates currently rostered on the schedule.

</details>

<details>
<summary>📝 Labour Order</summary>

**Labour Order** is the staffing request that specifies how many associates are required.

</details>

<details>
<summary>⏰ Scheduled Hours</summary>

**Scheduled Hours** are the total labour hours currently scheduled.

</details>

<details>
<summary>✅ Needed Hours</summary>

**Needed Hours** are the total labour hours required to meet forecasted demand.

</details>

<details>
<summary>🙋 Show Hours</summary>

**Show Hours** are the labour hours actually worked by associates who attend their scheduled shifts.

</details>

<details>
<summary>➕ VET Hours Required</summary>

**VET Hours Required** are the additional voluntary extra-time hours needed to satisfy demand.

</details>

<details>
<summary>📈 VET Hours Achievable</summary>

**VET Hours Achievable** are the number of VET hours that can realistically be filled.

</details>

<details>
<summary>✔️ VET Hours Accepted</summary>

**VET Hours Accepted** are the VET hours associates have accepted.

</details>

<details>
<summary>❗ Deficit Hours</summary>

**Deficit Hours** represent the shortfall between available labour hours and required labour hours.

</details>

<details>
<summary>➖ VTO Hours Required</summary>

**VTO Hours Required** are the voluntary time-off hours needed to reduce excess labour.

</details>

<details>
<summary>📉 VTO Hours Achievable</summary>

**VTO Hours Achievable** are the number of VTO hours that can realistically be offered.

</details>

<details>
<summary>✔️ VTO Hours Accepted</summary>

**VTO Hours Accepted** are the VTO hours associates have chosen to take.

</details>

<details>
<summary>💤 Idle Hours</summary>

**Idle Hours** are paid labour hours where associates are not performing productive work.

</details>

<details>
<summary>☕ Paid Break Hours</summary>

**Paid Break Hours** are paid break periods included within scheduled shifts.

</details>

<details>
<summary>🆕 New Hire Non-Productive Hours</summary>

**New Hire Non-Productive Hours** are labour hours allocated to onboarding and ramp-up activities where new associates are not yet fully productive.

</details>

<details>
<summary>🎓 Ambassador Hours</summary>

**Ambassador Hours** are labour hours allocated to ambassadors responsible for training and supporting new associates.

</details>

<details>
<summary>📚 Dilution Hours</summary>

**Dilution Hours** are labour hours spent on non-productive activities such as meetings, training, or administrative work.

</details>

<details>
<summary>➕ Hours Reallocation (+)</summary>

**Hours Reallocation (+)** represents labour hours reassigned into an activity.

</details>

<details>
<summary>➖ Hours Reallocation (-)</summary>

**Hours Reallocation (-)** represents labour hours reassigned away from an activity.

</details>

<details>
<summary>📈 New Hire TPH Impact</summary>

**New Hire TPH Impact** measures the reduction in expected throughput caused by associates who are still learning.

</details>

<details>
<summary>📊 Gross Excess %</summary>

**Gross Excess Percentage** is the percentage of labour available above the initial requirement before any adjustments.

</details>

<details>
<summary>📉 Net Excess %</summary>

**Net Excess Percentage** is the remaining labour excess after reallocations and adjustments have been made.

</details>

<details>
<summary>🛤️ ADTA FPP %</summary>

**ADTA Flow Path Percentage (FPP)** is the proportion of volume processed through the Automated Direct-to-Aisle flow path.

</details>

<details>
<summary>🧭 Flow Path Percentage</summary>

**Flow Path Percentage** is the percentage of total package volume routed through each operational flow path.

</details>

<details>
<summary>📦 Volume Processed</summary>

**Volume Processed** is the actual number of packages successfully processed during the planning period.

</details>

</details>

<details>
<summary>🖥️ Example Horizon Dashboard</summary>

This section provides an overview of the Horizon dashboard and explains the purpose of each key area used during Labour Planning.

### 📊 Dashboard Overview

<img src="images/dashboard.png" alt="Horizon Dashboard" width="100%">

### 📌 Key Sections

- 📦 **Forecast Volume** – Displays the expected package volume.
- 📈 **TPH** – Current and target throughput per hour.
- 👥 **Headcount (HC)** – Planned workforce.
- ⏰ **Scheduled Hours** – Total labour hours currently rostered.
- ✅ **Needed Hours** – Labour hours required to meet demand.
- ➕ **VET** – Additional hours required.
- ➖ **VTO** – Hours that can be reduced.
- 📊 **Capacity Metrics** – Site capacity and utilisation.

### 💡 Tip

Hover over most metrics within Horizon to view additional information or calculation details.

</details>

---

<details>
<summary>⚙️ Setting Up Your Environment</summary>

<details>
<summary>💻 Setting Up EU AMZL RDS ODBC</summary>

Follow the steps in this guide:

https://w.amazon.com/bin/view/AMZL-EU-PANDA/BI/NewJoinee/SA_Planning/Setting_RDS

</details>

</details>

---

<details>
<summary>👷🏼 Practical Labour Planning</summary>

<details>
<summary>👷🏼‍♂️ First Step: Roster Validation</summary>

1. Open ALPS on your desktop and make sure you are using the most recent version.
2. Download the latest input file for your station.
3. Go to:

   `\\ant\dept\LMA\EU Capacity Planning\ALPS\Roster Changes\UK\[Station Name]`

   This folder contains the roster changes file.
4. Open the input file and go to the **Transfers** tab (`Transfer_Type`).
5. Copy the employee ID.
6. Go to the **Roster** tab, which contains the current live roster.
7. Paste the employee ID and use:

   ```excel
   =XLOOKUP()
   
</details>
</details>

<details>
<summary>👷🏼‍♂️ Second Step: Running the input files into ALPS</summary>

