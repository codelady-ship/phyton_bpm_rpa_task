# Login Validation Automation (BPM + RPA)
Bu layihə **BPM və RPA inteqrasiyasını** sadə və real nümunə üzərində göstərir.
- Excel-dən istifadəçi məlumatları oxunur
- Selenium ilə login avtomatlaşdırılır
- Biznes qaydasına görə SUCCESS / FAIL / SYSTEM_ERROR verilir
- Nəticələr tarix və saatla Excel-ə yazılır
- Proses Camunda BPMN ilə modelləşdirilir
Layihə CV və müsahibələr üçün nəzərdə tutulub.
# Login Validation Automation (BPM + RPA)

A sample automation project demonstrating **BPM and RPA integration** using Python and Camunda BPMN.

---

## What this project does
- Reads allowed users from Excel
- Automates login via Selenium (RPA)
- Applies business rules to decide:
  - SUCCESS
  - FAIL (highlighted in red)
  - SYSTEM_ERROR
- Writes execution results with timestamp to Excel
- Models the process visually using BPMN (Camunda)

---

## Why BPM + RPA
- **RPA** handles UI automation
- **BPM** controls decision logic and process flow
- Clear separation between execution and business rules

---

## Tech Stack
- Python
- Selenium
- Pandas
- OpenPyXL
- Camunda Modeler (BPMN)
- Excel

---

## Challenges solved
- Browser closing too fast → execution flow controlled
- External system downtime → SYSTEM_ERROR path added
- Excel permission error → file state handling
- Backend credential limitation → business rule mock

---

## BPM Perspective
- Exclusive Gateway for decision making
- Separate SUCCESS / FAIL / SYSTEM_ERROR paths
- RPA used only as execution layer

---

## Goal
Provide a **realistic, interview-ready BPM + RPA automation example**.
