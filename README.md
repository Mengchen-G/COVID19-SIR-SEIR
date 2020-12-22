# COVID-19 SIR&SEIR Simulation
## Team Members
- Mengchen Gong (SEIR)
- Qinglu Sun (Data & Math Model)
- Tianli Wu (SIR)

## Overview
- Data and code are all in the 'Codes" folder
- Math model
- Data Plot
- SIR Model
  - The recovered people will not get reinfected again.
  - An infected patient will continuously spread COVID-19 until the patient is recovered.
  - Patients will recover at night, so the patients can still spread COVID-19 on that day.
  - Patients will stay at home when they need to be isolated.
- SEIR Model (on top of SIR Model)
  - Exposure duration: 6 days
  - 0.6 exposure probability, 0.125 infected probability, 0.143 recovery probability
  - An exposed person has ability to spread during its incubation time 
  - 0.5 chance an exposed person will be isolated with  2 days default delay
  - All infected people will be isolated without delay
  - Isolation simulation used a separated grid network with maximum 4 edges.
